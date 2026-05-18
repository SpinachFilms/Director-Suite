Director Suite
A collection of AI-powered tools built for content creators. Each tool is a standalone web app — no installs, no accounts, works on desktop and mobile.

Tools
01 · Task Supervisor
Plan your day the night before. Set a task cap, mark up to three items as priority, check off completed tasks, and carry unfinished ones to the next day. Persists in the browser between sessions.
02 · Script Supervisor
Paste a script and get brutally honest feedback — hook strength, problem statement, solution payoff, CTA effectiveness, what to cut, and what's missing. Separate analysis modes for short-form (Reels/TikTok), long-form, UGC, and storytelling.
03 · Video Supervisor
Describe your available footage and target style. Get back a full shot sequence, cut pacing plan, music style recommendation, on-screen text suggestions, visual effects placement, and the three highest retention-risk moments with solutions.
04 · Idea Supervisor
Pitch any idea — video concept, app, business offer, content series, or book. Get a viability score, market reality check, effort-to-reward analysis, a phased execution roadmap, and a clear Go / Wait / No-Go recommendation grounded in current market conditions.
05 · Video Scriptwriter
Give your concept, mood, platform, and goal. Receive three complete, production-ready script options with distinct angles. Select one, review it broken down by component (hook, problem, solution, CTA), rewrite individual sections until they're right, and export the final script with estimated duration and tone.

Stack

Vanilla HTML, CSS, JavaScript — no frameworks, no build step
Anthropic Claude API (claude-sonnet-4-20250514) via streaming
Each tool is a single self-contained index.html file


Structure
director-suite/
├── task-supervisor/
│   └── index.html
├── script-supervisor/
│   └── index.html
├── video-supervisor/
│   └── index.html
├── idea-supervisor/
│   └── index.html
└── video-scriptwriter/
    └── index.html

Deployment
Hosted on Netlify via GitHub integration. Every push to main deploys automatically.
Each tool is accessible at its own path:
/task-supervisor/
/script-supervisor/
/video-supervisor/
/idea-supervisor/
/video-scriptwriter/

Local Development
No build process. Open any index.html directly in a browser or use a simple local server:
bashnpx serve .

Roadmap

 Shared navigation bar across all tools
 PWA manifest for mobile home screen install
 Google Drive export for scripts and plans
 Google Calendar integration for task scheduling
 Spanish language support


Built by Paulo — HO Studio