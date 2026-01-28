# TalentMap Connect Hub

A comprehensive talent acquisition and management platform that connects students with hiring opportunities through intelligent resume matching and ATS scoring.

## 📹 Video Demo

[Drive Video Demo - Add your link here]()

## 🎯 What It Does

TalentMap Connect Hub is a full-stack recruitment management system that streamlines the hiring process through:

- **Intelligent Resume Matching**: AI-powered candidate-job matching using resume analysis and job requirements
- **ATS Score Analysis**: Automated Applicant Tracking System compatibility scoring for resumes
- **Resume Builder**: Built-in resume creation tool with professional templates
- **Resume Scanner**: PDF resume parsing and information extraction
- **Hiring Sessions Management**: Create and manage recruitment campaigns with tracked applicants
- **Student Dashboard**: Personalized view for students to manage profiles and track applications
- **Admin Dashboard**: Comprehensive admin panel for managing students, sessions, and recruitment data
- **Real-time Search**: Fast student search and filtering capabilities
- **Authentication System**: Secure user authentication with role-based access control

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone <repository-url>
cd talentmap-connect-hub
```

### 2. Install Frontend Dependencies
```bash
bun install
# or
npm install
```

### 3. Install Python Dependencies
```bash
pip install -e .
# or
python -m pip install -e .
```

### 4. Environment Setup
Create a `.env` file in the root directory with:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
GROQ_API_KEY=your_groq_api_key
```

### 5. Database Setup
Run the Supabase migrations:
```bash
run-migration.bat
# or manually apply migrations from supabase/migrations/
```

### 6. Run the Application

**Frontend (Development):**
```bash
bun dev
# or
npm run dev
```

**Backend API:**
```bash
uvicorn main:app --reload
```

The frontend will be available at `http://localhost:5173`  
The backend API will be available at `http://localhost:8000`

## 📂 Project Structure

```
├── src/
│   ├── components/       # Reusable UI components
│   ├── pages/           # Page components (routes)
│   ├── hooks/           # Custom React hooks
│   ├── contexts/        # React context providers
│   ├── integrations/    # Third-party integrations
│   └── lib/             # Utility functions
├── supabase/
│   └── migrations/      # Database migrations
├── main.py              # FastAPI backend server
├── embed_resume.py      # Resume embedding utilities
└── public/              # Static assets
```

## 🔑 Key Features Details

### For Students
- Create and manage professional profiles
- Upload and scan resumes for ATS compatibility
- Build resumes with guided templates
- View matching scores for job opportunities
- Track application status

### For Admins
- Create and manage hiring sessions
- Search and filter candidate pool
- View detailed student profiles and resumes
- Analyze candidate-job fit with AI-powered matching
- Extract job requirements from descriptions
- Monitor recruitment statistics



