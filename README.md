# 🛡️ Cortex Shield - AI-Powered Security Analysis Toolkit

**Making Cybersecurity Accessible to All**

Cortex Shield is an advanced, AI-powered security analysis platform that democratizes cybersecurity tools. Built with Google Gemini 2.5 Pro and featuring a modern glassmorphism UI, it provides instant threat detection, URL validation, code redaction, and more - all through an intuitive interface requiring zero technical expertise.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Node](https://img.shields.io/badge/node-%3E%3D18.0.0-brightgreen.svg)
![AI](https://img.shields.io/badge/AI-Gemini%202.5%20Pro-blueviolet.svg)

---

## 📋 Table of Contents
- [Problem Statement](#-problem-statement)
- [Solution Approach](#-solution-approach)
- [Technology Stack](#-technology-stack)
- [Features](#-features)
- [Setup Instructions](#-setup-instructions)
- [How to Run](#-how-to-run)
- [Architecture](#-architecture)
- [Team Members](#-team-members)
- [Demo & Screenshots](#-demo--screenshots)
- [Contributing](#-contributing)

---

## ⚠️ Problem Statement

**Current cybersecurity landscape faces critical barriers:**

1. **Complexity Crisis** 
   - Traditional security tools require deep technical expertise
   - Complex interfaces intimidate non-technical users
   - Steep learning curve prevents widespread adoption

2. **Fragmentation Issue**
   - Multiple specialized tools needed for different tasks
   - No unified platform for comprehensive security analysis
   - Time-consuming to switch between applications

3. **Accessibility Gap**
   - Enterprise security tools are prohibitively expensive
   - Small businesses and individuals lack affordable solutions
   - Real-time threat detection requires specialized knowledge

4. **Slow Response Times**
   - Manual analysis is time-intensive
   - Critical vulnerabilities may go unnoticed
   - Delayed threat detection increases risk exposure

**The Problem:** There is no single, user-friendly, AI-powered security platform that provides instant, comprehensive threat analysis accessible to everyone - from security professionals to everyday users.

---

## ✅ Solution Approach

**Cortex Shield solves these challenges through:**

### 🎯 **AI-First Architecture**
- Leverages Google Gemini 2.5 Pro for context-aware threat detection
- Natural language explanations in plain English
- Dual-mode analysis: text (NLP) + image (Vision AI)
- Continuous learning from latest AI model updates

### 🔧 **Unified Platform Design**
- **9 specialized security modules** in one interface
- Seamless workflow with consistent user experience
- Session-based history tracking
- Single click from landing page to analysis

### 👥 **User-Centric Approach**
- Zero technical knowledge required
- Visual severity indicators (🟢🟡🔴)
- Glassmorphism UI with 3D effects
- 3-theme system (Default/Light/Dark modes)
- Actionable recommendations, not just data

### 💰 **Open & Accessible**
- 100% free and open-source
- No subscriptions or hidden costs
- Community-driven development
- Transparent methodology

**Result:** A comprehensive security toolkit that empowers anyone to detect threats, analyze vulnerabilities, and protect their digital assets - instantly and effortlessly.

---

## 🛠️ Technology Stack

### **Frontend Technologies**

| Technology | Purpose | Version |
|------------|---------|---------|
| **HTML5/CSS3** | Structure & Modern Styling | Latest |
| **JavaScript (ES6+)** | Core Application Logic | ES2022 |
| **Tailwind CSS** | Utility-First CSS Framework | 3.x |
| **Three.js** | 3D Particle Background | 0.160.0 |
| **Lucide Icons** | Modern Icon Library | Latest |
| **Axios** | HTTP Client for API Calls | Latest |

### **Backend Technologies**

| Technology | Purpose | Version |
|------------|---------|---------|
| **Node.js** | JavaScript Runtime | 18.x+ |
| **Express.js** | Web Application Framework | 4.x |
| **Multer** | File Upload Middleware | Latest |
| **CORS** | Cross-Origin Resource Sharing | Latest |
| **Helmet** | Security Headers | Latest |
| **dotenv** | Environment Configuration | Latest |

### **AI & External Services**

| Service | Purpose | Integration |
|---------|---------|-------------|
| **Google Gemini 2.5 Pro** | AI-Powered Analysis (Text + Vision) | REST API |
| **VirusTotal API** | Multi-Engine Malware Detection | REST API |

### **Development Tools**

- **Git** - Version control
- **Nodemon** - Hot reload for development
- **VS Code** - IDE with Live Server extension
- **Postman** - API testing

---

## 🎨 Features

### **9 Specialized Security Modules**

1. **🔍 Universal Threat Analyzer**
   - Detects phishing attempts
   - Identifies social engineering tactics
   - Analyzes suspicious messages
   - Plain English threat assessment

2. **🌐 Web & URL Risk Assessor**
   - Validates website safety
   - VirusTotal integration (70+ AV engines)
   - Structural deception detection
   - Real-time malicious link identification

3. **💻 Code Redactor**
   - Finds exposed API keys in code
   - Detects hardcoded passwords
   - Identifies security tokens
   - Automated secret redaction

4. **📋 Log Anomaly Hunter**
   - Parses server logs
   - Detects unusual patterns
   - Identifies security events
   - Plain-English threat reports

5. **⚠️ Vulnerability Explainer**
   - Demystifies CVEs with analogies
   - Explains code vulnerabilities
   - Educational security content
   - Step-by-step mitigation guides

6. **📁 Secure File Autopsy**
   - Document malware detection
   - Image safety analysis
   - VirusTotal file scanning
   - Multi-format support (PDF, DOCX, images)

7. **🗑️ Data Sanitization Guide**
   - OS-specific secure deletion
   - Privacy protection procedures
   - Data wiping best practices
   - Step-by-step instructions

8. **🔑 Secure Password Explainer**
   - Strong password generation
   - Security best practices
   - Authentication guidance
   - Password strength analysis

9. **📰 Fake News Detector**
   - AI fact-checking
   - Multi-source verification suggestions
   - Credibility scoring
   - Red flag identification

### **Advanced UI/UX Features**

- **🎨 3-Theme System**: Default (vibrant), Light (clean), Dark (pure black)
- **✨ Glassmorphism Design**: Frosted glass effects with transparency
- **🌌 3D Particle Background**: Three.js animated particles
- **📱 Fully Responsive**: Works on desktop, tablet, and mobile
- **⚡ Real-Time Analysis**: 2-5 second average response time
- **💾 Session Storage**: Temporary history (clears on browser close)
- **🎭 Smooth Animations**: 60fps transitions and hover effects
- **📊 Visual Feedback**: Loading states, toast notifications, status indicators

---

## 🚀 Setup Instructions

### **Prerequisites**

Before you begin, ensure you have:
- ✅ **Node.js** v18.0.0 or higher ([Download](https://nodejs.org/))
- ✅ **npm** (comes with Node.js) or **yarn**
- ✅ **Git** ([Download](https://git-scm.com/))
- ✅ **Google Gemini API Key** ([Get Free Key](https://makersuite.google.com/app/apikey))
- ✅ **VirusTotal API Key** (Optional) ([Get Free Key](https://www.virustotal.com/gui/join-us))
- ✅ Modern web browser (Chrome 90+, Firefox 88+, Safari 14+, Edge 90+)

### **Installation Steps**

#### **1️⃣ Clone the Repository**

```bash
# Clone from GitHub
git clone https://github.com/N7Axlen/Cortex-Shield.git

# Navigate to project directory
cd Cortex-Shield
```

#### **2️⃣ Setup Backend**

```bash
# Navigate to backend directory
cd backend

# Install dependencies
npm install

# The following packages will be installed:
# - express (Web framework)
# - cors (Cross-origin resource sharing)
# - helmet (Security headers)
# - dotenv (Environment variables)
# - axios (HTTP client)
# - multer (File uploads)
# - form-data (Multipart forms)
```

#### **3️⃣ Configure Environment Variables**

Create a `.env` file in the `backend/` directory:

```bash
# Create .env file
cd backend
touch .env  # On Windows: type nul > .env
```

Add the following configuration:

```env
# Server Configuration
PORT=5000
NODE_ENV=development

# Frontend URL (for CORS)
FRONTEND_URL=http://localhost:3000

# API Keys
GEMINI_API_KEY=your_actual_gemini_api_key_here
VIRUSTOTAL_API_KEY=your_virustotal_api_key_here

# Optional Settings
MAX_FILE_SIZE=10485760
REQUEST_TIMEOUT=30000
```

**⚠️ Important:** 
- Replace `your_actual_gemini_api_key_here` with your real API key
- Never commit the `.env` file to version control
- The `.gitignore` file already excludes `.env`

#### **4️⃣ Setup Frontend**

```bash
# Navigate to frontend directory (from project root)
cd frontend

# No npm install needed - uses vanilla JavaScript
# All dependencies loaded via CDN in index.html
```

#### **5️⃣ Verify File Structure**

Ensure your directory structure looks like this:

```
Cortex-Shield/
├── frontend/
│   ├── index.html
│   ├── css/
│   │   ├── styles.css
│   │   └── themes/
│   │       ├── default.css
│   │       ├── light.css
│   │       └── dark.css
│   ├── js/
│   │   ├── app.js
│   │   ├── config.js
│   │   ├── ui-new.js
│   │   ├── api.js
│   │   ├── modules.js
│   │   ├── landing.js
│   │   └── three-scene.js
│   └── assets/
│       └── logo.png
├── backend/
│   ├── server.js
│   ├── package.json
│   ├── package-lock.json
│   ├── .env
│   └── uploads/ (created automatically)
├── .gitignore
├── README.md
└── Cortex_Shield_Presentation.Rmd
```

---

## ▶️ How to Run

### **Method 1: Using NPM Scripts (Recommended)**

#### **Start Backend Server**

Open Terminal/Command Prompt #1:

```bash
# Navigate to backend
cd backend

# Start development server with hot reload
npm run dev

# OR start production server
npm start
```

You should see:
```
🛡️  Cortex Shield Backend Server
🚀 Server running on http://localhost:5000
📝 Environment: development
✅ Gemini AI: Connected
⏰ Started at: [timestamp]
```

#### **Start Frontend Server**

Open Terminal/Command Prompt #2:

```bash
# Navigate to frontend
cd frontend

# Option A: Using Python (if installed)
python -m http.server 3000

# Option B: Using Node.js http-server
npx http-server -p 3000 -c-1

# Option C: Using PHP (if installed)
php -S localhost:3000

# Option D: VS Code Live Server Extension
# Right-click index.html → "Open with Live Server"
```

### **Method 2: Using VS Code Live Server (Easiest)**

1. Install **Live Server** extension in VS Code
2. Open `frontend/index.html`
3. Right-click and select "Open with Live Server"
4. Backend still needs to run separately (see above)

### **Method 3: Using Docker (Advanced)**

```bash
# Backend
cd backend
docker build -t cortex-shield-backend .
docker run -p 5000:5000 --env-file .env cortex-shield-backend

# Frontend
cd frontend
docker build -t cortex-shield-frontend .
docker run -p 3000:80 cortex-shield-frontend
```

### **Access the Application**

1. **Open your browser**
2. **Navigate to:** `http://localhost:3000`
3. **You should see:** The landing page with animated logo
4. **Click "Start Analyzing"** to access the dashboard

### **Verify Everything Works**

✅ **Backend Health Check:**
```bash
curl http://localhost:5000/health

# Expected response:
# {"status":"ok","timestamp":"...","environment":"development"}
```

✅ **Frontend Console Check:**
- Open browser DevTools (F12)
- Check Console for: "🛡️ Cortex Shield Initialized"
- No red errors should appear

---

## 🏗️ Architecture

### **High-Level System Design**

```
┌─────────────────────────────────────────────────────┐
│                   USER INTERFACE                    │
│                                                     │
│  Landing Page ──→ Dashboard ──→ Analysis Module    │
│  (Animated)      (9 Modules)    (Split Panel)      │
└─────────────────────┬───────────────────────────────┘
                      │
                      │ HTTP/HTTPS
                      │ Axios Requests
                      ↓
┌─────────────────────────────────────────────────────┐
│                FRONTEND LAYER                       │
│                                                     │
│  ┌──────────┐  ┌──────────┐  ┌────────────────┐   │
│  │ UI       │  │ State    │  │ Theme          │   │
│  │ Manager  │  │ Manager  │  │ Manager        │   │
│  └──────────┘  └──────────┘  └────────────────┘   │
│                                                     │
│  ┌──────────┐  ┌──────────┐  ┌────────────────┐   │
│  │ API      │  │ Module   │  │ Three.js       │   │
│  │ Client   │  │ Logic    │  │ Background     │   │
│  └──────────┘  └──────────┘  └────────────────┘   │
└─────────────────────┬───────────────────────────────┘
                      │
                      │ REST API
                      │ POST /api/analyze/:moduleId
                      ↓
┌─────────────────────────────────────────────────────┐
│                 BACKEND LAYER                       │
│                                                     │
│  ┌─────────────────────────────────────────────┐   │
│  │         Express.js Server (Port 5000)       │   │
│  │                                             │   │
│  │  • CORS Middleware                          │   │
│  │  • Helmet Security Headers                  │   │
│  │  • Body Parser                              │   │
│  │  • Multer File Upload                       │   │
│  │  • Error Handling                           │   │
│  └─────────────────────────────────────────────┘   │
│                                                     │
│  ┌──────────────┐         ┌──────────────────┐    │
│  │ API Routes   │         │ File Processing  │    │
│  │              │         │                  │    │
│  │ /analyze     │    ──→  │ Multer Handler   │    │
│  │ /analyze/    │         │ Base64 Convert   │    │
│  │  upload      │         │ Temp Storage     │    │
│  │ /virustotal  │         │ Cleanup          │    │
│  └──────────────┘         └──────────────────┘    │
└─────────────────────┬───────────────────────────────┘
                      │
        ┌─────────────┴─────────────┐
        │                           │
        ↓                           ↓
┌───────────────────┐     ┌─────────────────────┐
│  Google Gemini    │     │  VirusTotal API     │
│  2.5 Pro API      │     │                     │
│                   │     │  • URL Scanning     │
│  • Text Analysis  │     │  • File Scanning    │
│  • Vision AI      │     │  • 70+ AV Engines   │
│  • gemini-2.0-    │     │  • Threat Intel DB  │
│    flash-exp      │     │                     │
└───────────────────┘     └─────────────────────┘
```

### **Data Flow**

1. **User Input** → Frontend captures text or file
2. **Validation** → Client-side checks (size, format)
3. **API Request** → Axios sends to backend endpoint
4. **Processing** → Backend prepares prompt for AI
5. **AI Analysis** → Gemini processes and generates insights
6. **Response** → Backend formats and returns results
7. **Display** → Frontend renders with visual indicators
8. **History** → Session storage saves for current session

### **Component Architecture**

#### **Frontend Components:**
- **`app.js`** - Application bootstrap and initialization
- **`config.js`** - Configuration constants and module definitions
- **`ui-new.js`** - UI rendering, theme management, DOM manipulation
- **`api.js`** - HTTP client for backend communication
- **`modules.js`** - Module-specific logic and handlers
- **`landing.js`** - Landing page animations and interactions
- **`three-scene.js`** - 3D particle background rendering

#### **Backend Components:**
- **`server.js`** - Express server, routes, middleware, AI integration
- **`uploads/`** - Temporary storage for uploaded files (auto-cleanup)

---

## 👥 Team Members

**Project Team:**

1. **Mohd Anas** - Full Stack Developer & Project Lead
   - Role: Backend development, Gemini AI integration, architecture design, security modules implementation
   - GitHub: [N7Axlen](https://github.com/N7Axlen)

2. **Shivam Kashyap** - Frontend Developer & UI/UX Designer
   - Role: Frontend development, glassmorphism design, theme system, Three.js integration, responsive UI

---

---

## 📁 Complete Project Structure

```
cortex-shield/
├── frontend/
│   ├── index.html                 # Main HTML entry point
│   ├── css/
│   │   └── styles.css            # Custom CSS with animations
│   └── js/
│       ├── config.js             # App configuration
│       ├── particles.js          # Particle animation system
│       ├── api.js                # API integration layer
│       ├── modules.js            # Module management
│       ├── ui.js                 # UI components & rendering
│       └── app.js                # Main application logic
│
├── backend/
│   ├── server.js                 # Express server with Gemini API
│   ├── package.json              # Backend dependencies
│   └── .env                      # Environment variables (create this)
│
├── .gitignore
└── README.md                     # This file
```

---

## 🚀 Quick Start Guide

### Prerequisites

- **Node.js** v18+ ([Download](https://nodejs.org/))
- **npm** or **yarn**
- **Google Gemini API Key** ([Get one here](https://makersuite.google.com/app/apikey))
- **Git** ([Download](https://git-scm.com/))

### Installation Steps

#### 1️⃣ Clone or Create Project

```bash
# Create project directory
mkdir cortex-shield
cd cortex-shield

# Create subdirectories
mkdir frontend backend
mkdir frontend/css frontend/js
```

#### 2️⃣ Setup Backend

```bash
cd backend

# Initialize npm
npm init -y

# Install dependencies
npm install express cors helmet axios dotenv body-parser

# Install dev dependencies
npm install --save-dev nodemon
```

Create `package.json` scripts:
```json
{
  "scripts": {
    "start": "node server.js",
    "dev": "nodemon server.js"
  }
}
```

Create `.env` file:
```env
PORT=5000
GEMINI_API_KEY=your_actual_api_key_here
FRONTEND_URL=http://localhost:3000
NODE_ENV=development
```

Copy the `server.js` file I provided earlier into `backend/server.js`.

#### 3️⃣ Setup Frontend

```bash
cd ../frontend
```

1. Copy the `index.html` file into `frontend/`
2. Copy `styles.css` into `frontend/css/`
3. Copy all JavaScript files into `frontend/js/`:
   - config.js
   - particles.js
   - api.js
   - modules.js
   - ui.js
   - app.js

#### 4️⃣ Start the Application

**Terminal 1 - Backend:**
```bash
cd backend
npm run dev
```

**Terminal 2 - Frontend:**
```bash
cd frontend
# Option 1: Use Python
python -m http.server 3000

# Option 2: Use Node.js http-server
npx http-server -p 3000

# Option 3: Use VS Code Live Server extension
# Just right-click index.html and select "Open with Live Server"
```

#### 5️⃣ Access Application

Open your browser and navigate to:
```
http://localhost:3000
```

---

## 🎨 Features

### 8 Security Modules

1. **Universal Threat Analyzer** - Detect phishing and social engineering
2. **Web & URL Risk Assessor** - Validate websites for security risks
3. **Code Redactor** - Automatically redact API keys and secrets
4. **Log Anomaly Hunter** - Analyze server logs for threats
5. **Vulnerability Explainer** - Learn about security flaws
6. **Secure File Autopsy** - Analyze documents for malicious content
7. **Data Sanitization Guide** - OS-specific data wiping instructions
8. **Secure Password Explainer** - Generate and learn about passwords

### Visual Effects

- ✨ Floating particle animations
- 🌈 Dynamic gradient backgrounds
- 💫 Glassmorphism design
- 🎭 3D card tilt effects
- ⚡ Smooth page transitions
- 🔮 Hover glow effects
- 📊 Real-time statistics
- 🎪 Grid pattern overlays

---

## 🔧 Configuration

### Frontend Configuration (`js/config.js`)

```javascript
const CONFIG = {
    API: {
        BASE_URL: 'http://localhost:5000/api', // Change for production
        TIMEOUT: 30000
    },
    FEATURES: {
        DEMO_MODE: true, // Set to false when backend is ready
        ENABLE_LOCAL_STORAGE: true,
        ENABLE_ANALYTICS: false
    }
    // ... more settings
};
```

### Backend Configuration (`.env`)

```env
PORT=5000
GEMINI_API_KEY=your_key_here
FRONTEND_URL=http://localhost:3000
NODE_ENV=development
```

---

## 📡 API Endpoints

### Backend API

```
GET  /health
     Returns server status

POST /api/analyze/:moduleId
     Body: { "input": "text to analyze" }
     Returns: { "success": true, "result": "..." }

GET  /api/history
     Returns analysis history (future feature)
```

---

## 🎯 Usage Examples

### Analyzing Phishing Text

1. Open Cortex Shield
2. Select "Universal Threat Analyzer"
3. Paste suspicious text
4. Click "Analyze with AI"
5. Review threat assessment

### Redacting Code Secrets

1. Select "Code Redactor"
2. Paste code with secrets
3. Get redacted version + security tips

---

## 🌐 Deployment

### Frontend Deployment (Vercel)

```bash
cd frontend
vercel --prod
```

Set environment variable:
- `REACT_APP_API_URL` = your backend URL

### Backend Deployment (Render)

1. Push code to GitHub
2. Create new Web Service on Render
3. Set environment variables:
   - `GEMINI_API_KEY`
   - `FRONTEND_URL`
   - `NODE_ENV=production`
4. Deploy!

### Alternative: Railway

Deploy both frontend and backend on Railway.app:
```bash
railway login
railway init
railway up
```

---

## 🔐 Security Best Practices

1. **Never commit `.env` files**
   ```bash
   echo ".env" >> .gitignore
   ```

2. **Use HTTPS in production**
   - Enable SSL/TLS certificates
   - Update CORS settings

3. **Implement rate limiting**
   ```javascript
   npm install express-rate-limit
   ```

4. **Validate all inputs**
   - Already implemented in server.js

5. **Keep dependencies updated**
   ```bash
   npm audit
   npm update
   ```

---

## 🐛 Troubleshooting

### Backend won't start

```bash
# Check if port is in use
lsof -i :5000

# Kill process
kill -9 <PID>

# Or use different port in .env
PORT=5001
```

### CORS errors

Update `server.js`:
```javascript
app.use(cors({
    origin: 'http://localhost:3000', // Your frontend URL
    credentials: true
}));
```

### API key errors

1. Verify key in `.env` file
2. Check key is valid at [AI Studio](https://makersuite.google.com/)
3. Restart backend server

### Frontend not loading

1. Check console for errors (F12)
2. Verify all JS files are loaded
3. Check network tab for failed requests
4. Clear browser cache

---

## 📊 Performance Tips

1. **Lazy load modules** (future optimization)
2. **Implement caching** for repeated analyses
3. **Use CDN** for production assets
4. **Minimize bundle size** with webpack
5. **Enable gzip compression** on server

---

## 🎓 Development Tips

### Using Browser Console

```javascript
// Check app version
cortex.version()

// View configuration
cortex.config()

// Get statistics
cortex.stats()

// Clear history
cortex.clearHistory()

// Export history
cortex.exportHistory()

// Reset app
cortex.reset()

// Show help
cortex.help()
```

### Hot Reload Setup

Backend:
```bash
npm install -g nodemon
nodemon server.js
```

Frontend:
```bash
# Use Live Server extension in VS Code
# Or watch mode with any static server
```

---

## 📦 Building for Production

### Optimize Frontend

1. Minify CSS and JS
2. Compress images
3. Enable caching headers
4. Use CDN for libraries

### Optimize Backend

1. Use PM2 for process management
   ```bash
   npm install -g pm2
   pm2 start server.js
   ```

2. Enable clustering
3. Add Redis for caching
4. Implement load balancing

---

## 🤝 Contributing

1. Fork the repository
2. Create feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open Pull Request

---

## 📝 License

MIT License - feel free to use for personal or commercial projects

---

## 🙏 Acknowledgments

- **Google Gemini AI** - AI analysis engine
- **Tailwind CSS** - Styling framework
- **Lucide Icons** - Beautiful icons
- **Express.js** - Backend framework

---

## 📞 Support

Having issues? Check:

1. [GitHub Issues](https://github.com/yourusername/cortex-shield/issues)
2. [Documentation](https://github.com/yourusername/cortex-shield/wiki)
3. [Discord Community](https://discord.gg/yourserver)

---

## 🗺️ Roadmap

- [ ] User authentication (Firebase)
- [ ] Database integration (MongoDB)
- [ ] Export reports as PDF
- [ ] Real-time collaboration
- [ ] Mobile app version
- [ ] More AI models (GPT-4, Claude)
- [ ] Custom security rules
- [ ] API rate limiting
- [ ] Analytics dashboard
- [ ] Dark/Light theme toggle

---

## 📈 Version History

### v1.0.0 (Current)
- Initial release
- 9 security modules
- Gemini AI integration
- Beautiful UI with animations
- Demo mode support

---

**Built with ❤️ for security professionals and enthusiasts**


*Star ⭐ this repo if you find it helpful!*
