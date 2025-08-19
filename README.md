# 🎯 AI Resume Analyzer (Resumind)

**Resumind** is an intelligent resume analysis platform that helps job seekers optimize their resumes for better ATS (Applicant Tracking System) compatibility and overall effectiveness. Built with modern React Router architecture and powered by AI technology, this application provides comprehensive feedback to improve job application success rates.

[![React Router](https://img.shields.io/badge/React%20Router-7.0.0-blue.svg)](https://reactrouter.com/)
[![React](https://img.shields.io/badge/React-19.1.0-blue.svg)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-Latest-blue.svg)](https://www.typescriptlang.org/)
[![TailwindCSS](https://img.shields.io/badge/TailwindCSS-4.1.4-blue.svg)](https://tailwindcss.com/)

## ✨ Key Features

### 🔍 **AI-Powered Analysis**

Advanced artificial intelligence evaluates resumes across multiple dimensions including content quality, structure, tone & style, and skills alignment.

### 📊 **ATS Compatibility Scoring**

Specialized analysis for Applicant Tracking System optimization with actionable improvement recommendations.

### 🎯 **Job-Specific Feedback**

Tailored analysis based on target company and job description for personalized recommendations.

### 📈 **Multi-Category Scoring**

Comprehensive evaluation across:

- **Overall Resume Score** (0-100)
- **ATS Compatibility**
- **Content Quality**
- **Structure & Formatting**
- **Tone & Style**
- **Skills Assessment**

### 🔄 **Resume Portfolio Management**

Track multiple resumes and their performance scores across different job applications.

### 📱 **Modern UI/UX**

Responsive design with intuitive file upload, real-time processing status, and visual score displays using gauges, badges, and charts.

### 🔒 **Secure File Handling**

PDF processing with automatic image conversion for preview generation.

## 🛠️ Technical Stack

- **Frontend**: React 19 with React Router 7
- **Styling**: TailwindCSS 4.1.4 with custom components
- **File Processing**: PDF.js for document handling
- **File Upload**: React Dropzone for drag-and-drop functionality
- **Storage**: Puter cloud storage integration
- **AI Integration**: Custom AI feedback engine
- **State Management**: Zustand for global state
- **Build System**: Vite with TypeScript support
- **Type Safety**: Full TypeScript implementation

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm or pnpm
- Modern web browser

### Installation

#### Clone the repository

```bash
git clone https://github.com/aditya-2k23/ai-resume-analyzer.git
cd ai-resume-analyzer
```

#### Install dependencies

```bash
npm install
```

#### Start the development server

```bash
npm run dev
```

#### Open your browser and navigate to `http://localhost:5173`

### Environment Setup

Make sure you have the necessary environment variables configured for Puter integration and AI services.

## 📁 Project Structure

```plaintext
resume-analyzer/
├── app/
│   ├── components/          # Reusable React components
│   │   ├── ATS.tsx         # ATS score display
│   │   ├── Details.tsx     # Detailed feedback
│   │   ├── FileUploader.tsx # File upload component
│   │   ├── Navbar.tsx      # Navigation bar
│   │   ├── ResumeCard.tsx  # Resume preview card
│   │   ├── ScoreBadge.tsx  # Score status badge
│   │   ├── ScoreCircle.tsx # Circular score display
│   │   ├── ScoreGauge.tsx  # Score gauge component
│   │   └── Summary.tsx     # Score summary
│   ├── lib/                # Utility libraries
│   │   ├── pdf2img.ts      # PDF to image conversion
│   │   ├── puter.ts        # Puter integration
│   │   └── utils.ts        # Common utilities
│   ├── routes/             # Application routes
│   │   ├── auth.tsx        # Authentication
│   │   ├── home.tsx        # Home page
│   │   ├── resume.tsx      # Resume analysis view
│   │   └── upload.tsx      # Upload interface
│   ├── app.css            # Global styles
│   ├── root.tsx           # Root component
│   └── routes.ts          # Route configuration
├── constants/
│   └── index.ts           # Application constants
├── types/
│   ├── index.d.ts         # Type definitions
│   └── puter.d.ts         # Puter type definitions
├── public/                # Static assets
└── package.json
```

## 🎨 Key Components

### ScoreBadge

A reusable component that displays score-based badges:

- **Green "Strong"** for scores > 70
- **Yellow "Good Start"** for scores > 49
- **Red "Needs Work"** for lower scores

### ScoreGauge

Visual circular gauge displaying overall resume scores with color-coded indicators.

### ATS Component

Dedicated ATS analysis display with:

- ATS compatibility score
- Specific improvement suggestions
- Visual feedback indicators

## 📊 Scoring System

The application evaluates resumes across five key areas:

1. **Overall Score** - Comprehensive rating (0-100)
2. **ATS Compatibility** - How well the resume passes through automated systems
3. **Content Quality** - Relevance and quality of information
4. **Structure & Formatting** - Organization and visual appeal
5. **Skills Assessment** - Skill relevance and presentation

## 🔧 Development

### Available Scripts

```bash
# Development server with HMR
npm run dev

# Type checking
npm run typecheck

# Production build
npm run build

# Start production server
npm run start
```

### Code Quality

- **TypeScript** for type safety
- **ESLint** for code linting
- **Prettier** for code formatting
- **Tailwind CSS** for consistent styling

## 🚢 Production Deployment

### Building for Production

```bash
npm run build
```

### Docker Deployment

```bash
# Build Docker image
docker build -t ai-resume-analyzer .

# Run container
docker run -p 3000:3000 ai-resume-analyzer
```

### Deployment Platforms

This application can be deployed to:

- **Vercel** (Recommended for React Router apps)
- **Netlify**
- **AWS ECS**
- **Google Cloud Run**
- **Azure Container Apps**
- **Digital Ocean App Platform**
- **Fly.io**
- **Railway**

## 🎯 Use Cases

- **Job Seekers** - Optimize resumes for specific positions
- **Career Coaches** - Provide data-driven resume feedback
- **Recruitment Consultants** - Assess candidate resume quality
- **Students** - Prepare for job applications
- **Professionals** - Update resumes for career advancement

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- React Router team for the excellent framework
- Tailwind CSS for the utility-first styling approach
- PDF.js for robust PDF processing
- The open-source community for inspiration and tools

---

Built with ❤️ using React Router, TypeScript, and modern web technologies.
