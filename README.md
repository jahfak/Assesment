John's Tech Support Assessment

A retro-styled technical assessment application for a Technical Customer Support position, featuring a nostalgic terminal aesthetic with modern React/TypeScript architecture.

🌟 Live Demo

https://incredible-biscochitos-5b1083.netlify.app/

🎯 Features
Retro Terminal Aesthetic: Green-on-black color scheme with scan lines and CRT effects

Responsive Design: Works on all devices from mobile to desktop

Interactive Elements: Click sound effects, blinking cursor, and animated scan lines

Modern Architecture: Built with React 18, TypeScript, and TailwindCSS

Component-Based: Clean, reusable component structure

Type Safety: Full TypeScript support for better development experience

📁 Project Structure
text
assessment/
├── public/                 # Static assets
├── src/
│   ├── components/        # React components
│   │   ├── Header.tsx    # Site header with time display
│   │   ├── Footer.tsx    # Site footer
│   │   ├── ScanLine.tsx  # Animated scan line effect
│   │   ├── Cursor.tsx    # Blinking cursor
│   │   ├── CRTEffect.tsx # CRT screen effect
│   │   ├── QASection.tsx # Questions & Answers section
│   │   └── QuestionCard.tsx # Individual question card
│   ├── utils/            # Utility functions
│   │   ├── dateTime.ts   # Date/time formatting
│   │   ├── sounds.ts     # Audio effects
│   │   └── typewriter.ts # Typewriter animations
│   ├── data/             # Data files
│   │   └── questions.ts  # Q&A data
│   ├── types/            # TypeScript type definitions
│   ├── App.tsx          # Main application component
│   ├── main.tsx         # Application entry point
│   └── index.css        # Global styles
├── index.html           # HTML template
├── package.json         # Dependencies and scripts
├── tailwind.config.js   # Tailwind configuration
├── tsconfig.json        # TypeScript configuration
├── vite.config.ts       # Vite build configuration
└── README.md           # This file
🚀 Quick Start
Prerequisites
Node.js 16+ and npm/yarn/pnpm

Installation
Clone the repository

bash
git clone https://github.com/yourusername/tech-support-assessment.git
cd tech-support-assessment
Install dependencies

bash
npm install
# or
yarn install
# or
pnpm install
Start the development server

bash
npm run dev
# or
yarn dev
# or
pnpm dev
Open your browser
Navigate to http://localhost:5173

Build for Production
bash
npm run build
# or
yarn build
# or
pnpm build
The built files will be in the dist/ directory.

🛠️ Tech Stack
Frontend Framework: React 18 with TypeScript

Styling: TailwindCSS with custom animations

Build Tool: Vite

Fonts: VT323 (retro terminal font), Font Awesome icons

Hosting: Optimized for Netlify deployment

🎨 Design Features
Retro Effects
Scan Line: Animated line that scans from top to bottom

CRT Effect: Authentic cathode-ray tube screen overlay

Blinking Cursor: Classic terminal cursor animation

Typewriter Effect: Text appears as if being typed

Click Sounds: Retro terminal beep sounds on interaction

Responsive Design
Mobile-first approach

Adaptive layouts for all screen sizes

Maintains retro aesthetic across devices

📝 Assessment Questions Covered
The application includes comprehensive answers to 9 technical questions:

Technical Stack Explanation: Tools and challenges

Service Feedback: Netlify experience and suggestions

Activity Ranking: Favorite vs. least favorite tasks

Documentation Review: Analysis of well-done technical docs

DNS Challenges: Issues for non-technical users

Troubleshooting Scenario: "Site won't build" response

Redirect Configuration: 301 and proxy redirect rules

Serverless Function Deployment: Experience and process

Security Incident Response: Handling security reports

🔧 Customization
Add New Questions
Edit src/data/questions.ts:

typescript
export const questions = [
  {
    number: "Q10",
    question: "Your new question here?",
    answer: (
      <p>Your answer here</p>
    )
  },
  // ... existing questions
]
Modify Styling
Colors: Edit src/index.css for retro theme colors

Animations: Update tailwind.config.js for custom animations

Layout: Modify component styles in respective .tsx files

Change Content
Header: Edit src/components/Header.tsx

Footer: Edit src/components/Footer.tsx

Introduction: Edit the intro section in src/App.tsx

📦 Deployment
Netlify Deployment
Connect Git Repository

Push code to GitHub/GitLab/Bitbucket

Connect repository in Netlify dashboard

Configure Build Settings

text
Build Command: npm run build
Publish Directory: dist
Environment Variables (if needed)
Add in Netlify site settings > Environment variables

Custom Domain (optional)
Configure in Netlify domain settings

Other Hosting Platforms
Vercel: Similar to Netlify, optimized for Next.js/Vite

GitHub Pages: Use vite-plugin-gh-pages

AWS S3/CloudFront: Static site hosting

Firebase Hosting: Free tier available

🤝 Contributing
Fork the repository

Create a feature branch (git checkout -b feature/AmazingFeature)

Commit changes (git commit -m 'Add AmazingFeature')

Push to branch (git push origin feature/AmazingFeature)

Open a Pull Request

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
