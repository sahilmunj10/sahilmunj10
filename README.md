<!-- ═══════════════════════════════════════════════════════════════════════
     Sahil Munj · GitHub Profile README
     Repo: github.com/sahilmunj10/sahilmunj10
     Assets live in ./assets — keep paths relative so forks still render.
     ═══════════════════════════════════════════════════════════════════════ -->

<a id="top"></a>

<!-- Hero banner (custom animated SVG, local asset) -->
<p align="center">
  <img src="assets/header.svg" alt="Sahil Munj — Computer Engineering Student · Software Developer · AI & Data Enthusiast" width="100%" />
</p>

<!-- Typing animation (external service; text below keeps the hero readable if it fails) -->
<p align="center">
  <a href="https://github.com/sahilmunj10">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2800&pause=900&color=22D3EE&center=true&vCenter=true&multiline=false&repeat=true&width=520&height=42&lines=Computer+Engineering+Student;Software+Developer;AI+%26+Machine+Learning+Enthusiast;Full-Stack+Developer;Problem+Solver" alt="Computer Engineering Student · Software Developer · AI & Machine Learning Enthusiast · Full-Stack Developer · Problem Solver" />
  </a>
</p>

<p align="center">
  <em>I build practical software and explore intelligent systems — from healthcare platforms and gamified learning tools to gesture-controlled games and data dashboards.</em>
</p>

<!-- Section navigation -->
<p align="center">
  <a href="#projects"><img src="https://img.shields.io/badge/Projects-0b1220?style=for-the-badge&logo=github&logoColor=22d3ee" alt="Projects" /></a>&nbsp;
  <a href="#tech-stack"><img src="https://img.shields.io/badge/Tech_Stack-0b1220?style=for-the-badge&logo=stackblitz&logoColor=60a5fa" alt="Tech Stack" /></a>&nbsp;
  <a href="#github-activity"><img src="https://img.shields.io/badge/GitHub_Activity-0b1220?style=for-the-badge&logo=githubactions&logoColor=a78bfa" alt="GitHub Activity" /></a>&nbsp;
  <a href="#connect"><img src="https://img.shields.io/badge/Connect-0b1220?style=for-the-badge&logo=minutemailer&logoColor=22d3ee" alt="Connect" /></a>
</p>

<!-- Primary links -->
<p align="center">
  <a href="https://github.com/sahilmunj10"><img src="https://img.shields.io/badge/GitHub-sahilmunj10-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://www.linkedin.com/in/sahil-munj-1075s/"><img src="https://img.shields.io/badge/LinkedIn-Sahil_Munj-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:sahilmunj10@gmail.com"><img src="https://img.shields.io/badge/Email-sahilmunj10%40gmail.com-1e293b?style=flat-square&logo=gmail&logoColor=ea4335" alt="Email" /></a>
</p>

<p align="center"><img src="assets/divider.svg" alt="" width="100%" /></p>

## About Me

<table>
  <tr>
    <td width="55%" valign="top">
      <p>I'm a <strong>Computer Engineering student</strong> who learns by shipping. Most of my time goes into building full-stack web applications — React/TypeScript on the front, Node.js and Express on the back — and wiring them to real data stores like MongoDB, SQLite (via Prisma) and Firebase.</p>
      <p>I'm increasingly drawn to <strong>AI-powered applications and data-driven systems</strong>: integrating LLM APIs into products, real-time computer vision in the browser, rule-based decision engines, and turning raw datasets into interactive dashboards.</p>
      <p>I prefer projects that solve a concrete problem — placement workflows for a college, care continuity for rural patients, a more engaging way to learn to code — and I use each one to pick up a new technology hands-on.</p>
      <p>
        <img src="https://img.shields.io/badge/Based_in-Maharashtra,_India-0b1220?style=flat-square&logo=googlemaps&logoColor=22d3ee" alt="Based in Maharashtra, India" />
        <img src="https://img.shields.io/badge/Open_to-Internships_%26_Collaboration-0b1220?style=flat-square&logo=handshake&logoColor=a78bfa" alt="Open to internships and collaboration" />
      </p>
    </td>
    <td width="45%" valign="top" align="center">
      <img src="assets/terminal.svg" alt="Terminal card: role — Computer Engineering Student; builds — web apps, AI tools, dashboards; stack — JavaScript, TypeScript, Python" width="100%" />
    </td>
  </tr>
</table>

<p align="center"><img src="assets/divider.svg" alt="" width="100%" /></p>

<a id="projects"></a>
## Featured Projects

<p align="center"><sub>Seven projects spanning healthcare technology, education, AI, computer vision, data analytics and web applications. Every description below is based on the repository source.</sub></p>

<table>
  <!-- ─────────── Row 1: SwastyaSetu · CodeQuest ─────────── -->
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🩺 SwastyaSetu</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Healthcare_Tech-0b1220?style=flat-square&logoColor=22d3ee" alt="Healthcare Tech" />
        <img src="https://img.shields.io/badge/SIH_Prototype-0b1220?style=flat-square&logoColor=a78bfa" alt="Smart India Hackathon Prototype" />
      </p>
      <p>A care-continuity platform for rural public health in India, linking patients, ASHA frontline workers, PHC doctors, labs, pharmacies and district officers into <em>one continuous healthcare journey</em>. Built as a Smart India Hackathon software prototype (Problem Statement 26133, Govt. of Maharashtra).</p>
      <p><strong>Implemented:</strong> seven role-based dashboards, guided triage engine (ROUTINE → EMERGENCY), 8-stage referral tracking, patient EHR timeline with vitals charts, medicine-availability finder, diagnostics coordination, teleconsultation page with low-bandwidth mode, offline-first PWA sync via IndexedDB, and English/Marathi/Hindi localisation.</p>
      <p><strong>Technical highlight:</strong> a rule-based follow-up risk scorer and triage engine on the backend, with JWT auth, audit middleware and a Prisma/SQLite schema — zero-config to run locally.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/React_18-20232a?style=flat-square&logo=react&logoColor=61dafb" alt="React" />
        <img src="https://img.shields.io/badge/TypeScript-1e293b?style=flat-square&logo=typescript&logoColor=3178c6" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Vite-1e293b?style=flat-square&logo=vite&logoColor=a78bfa" alt="Vite" />
        <img src="https://img.shields.io/badge/Tailwind-1e293b?style=flat-square&logo=tailwindcss&logoColor=38bdf8" alt="Tailwind CSS" />
        <img src="https://img.shields.io/badge/Express-1e293b?style=flat-square&logo=express&logoColor=white" alt="Express" />
        <img src="https://img.shields.io/badge/Prisma-1e293b?style=flat-square&logo=prisma&logoColor=white" alt="Prisma" />
        <img src="https://img.shields.io/badge/SQLite-1e293b?style=flat-square&logo=sqlite&logoColor=0ea5e9" alt="SQLite" />
        <img src="https://img.shields.io/badge/Leaflet-1e293b?style=flat-square&logo=leaflet&logoColor=199900" alt="Leaflet" />
        <img src="https://img.shields.io/badge/Recharts-1e293b?style=flat-square&logoColor=white" alt="Recharts" />
      </p>
      <p align="center">
        <a href="https://github.com/sahilmunj10/SwastyaSetu"><img src="https://img.shields.io/badge/View_Repository-2563eb?style=for-the-badge&logo=github&logoColor=white" alt="View SwastyaSetu repository" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🎮 CodeQuest</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Gamified_Learning-0b1220?style=flat-square&logoColor=22d3ee" alt="Gamified Learning" />
        <img src="https://img.shields.io/badge/MERN_%2B_Socket.IO-0b1220?style=flat-square&logoColor=a78bfa" alt="MERN and Socket.IO" />
      </p>
      <p>A full-stack gamified coding platform that teaches programming through structured courses, hands-on challenges and project-based learning — with XP, levels, streaks, badges, ranks and a leaderboard to keep learners moving.</p>
      <p><strong>Implemented:</strong> multi-course level progression with theory and quizzes, Monaco-based in-browser editor with JavaScript/Python/HTML execution routes, step-by-step project tutorials with draft saving, a custom project builder, community feed with likes/comments and automated achievement posts, real-time chat rooms, daily challenges, a "30 Nites of Coding" path, and an AI assistant.</p>
      <p><strong>Technical highlight:</strong> an LLM-powered chatbot (Groq SDK) plus a server-side Python executor, backed by 15 Mongoose models covering courses, progress, posts, projects and chat.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/React_19-20232a?style=flat-square&logo=react&logoColor=61dafb" alt="React" />
        <img src="https://img.shields.io/badge/Vite_7-1e293b?style=flat-square&logo=vite&logoColor=a78bfa" alt="Vite" />
        <img src="https://img.shields.io/badge/Tailwind_v4-1e293b?style=flat-square&logo=tailwindcss&logoColor=38bdf8" alt="Tailwind CSS" />
        <img src="https://img.shields.io/badge/Node.js-1e293b?style=flat-square&logo=nodedotjs&logoColor=5fa04e" alt="Node.js" />
        <img src="https://img.shields.io/badge/Express-1e293b?style=flat-square&logo=express&logoColor=white" alt="Express" />
        <img src="https://img.shields.io/badge/MongoDB-1e293b?style=flat-square&logo=mongodb&logoColor=47a248" alt="MongoDB" />
        <img src="https://img.shields.io/badge/Socket.IO-1e293b?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" />
        <img src="https://img.shields.io/badge/Monaco_Editor-1e293b?style=flat-square&logoColor=white" alt="Monaco Editor" />
        <img src="https://img.shields.io/badge/Groq_API-1e293b?style=flat-square&logoColor=f55036" alt="Groq API" />
      </p>
      <p align="center">
        <a href="https://github.com/sahilmunj10/codequest"><img src="https://img.shields.io/badge/View_Repository-2563eb?style=for-the-badge&logo=github&logoColor=white" alt="View CodeQuest repository" /></a>
      </p>
    </td>
  </tr>

  <!-- ─────────── Row 2: ResearchIQ · Hand Gesture Game ─────────── -->
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">🔬 ResearchIQ</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/AI_%2F_Research-0b1220?style=flat-square&logoColor=22d3ee" alt="AI / Research" />
      </p>
      <p>A research-oriented project focused on making academic research workflows faster and more intelligent.</p>
      <!-- PLACEHOLDER: the ResearchIQ repository was not publicly accessible when this README was written.
           Replace the paragraph below with a verified description, feature list and tech badges once the repo is public. -->
      <p><strong>Status:</strong> repository is currently private / being prepared for public release. A detailed description, feature list and tech stack will be added once it is published.</p>
      <p align="center">
        <a href="https://github.com/sahilmunj10/ResearchIQ"><img src="https://img.shields.io/badge/View_Repository-2563eb?style=for-the-badge&logo=github&logoColor=white" alt="View ResearchIQ repository" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">✋ Hand Gesture Game — <em>Catch the Stars</em></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Computer_Vision-0b1220?style=flat-square&logoColor=22d3ee" alt="Computer Vision" />
        <img src="https://img.shields.io/badge/Browser_Game-0b1220?style=flat-square&logoColor=a78bfa" alt="Browser Game" />
      </p>
      <p>A webcam-controlled arcade game: move your hand to steer a basket and catch falling stars, coins and diamonds while dodging bombs. All tracking runs client-side — no video leaves the device.</p>
      <p><strong>Implemented:</strong> 21-point hand tracking with MediaPipe Hands, exponential smoothing to remove jitter, a rule-based gesture classifier (open palm, thumbs-up, peace, fist) that triggers power-ups like shield, 2× score, slow-motion and magnet, combo multipliers, dynamic difficulty, procedural Web Audio sound synthesis, localStorage high scores, and a mouse/touch fallback when camera access is denied.</p>
      <p><strong>Technical highlight:</strong> gesture detection is written from scratch on raw landmark geometry with hold-frame confirmation and per-gesture cooldowns — no ML training step required.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/JavaScript_(ES_Modules)-1e293b?style=flat-square&logo=javascript&logoColor=f7df1e" alt="JavaScript" />
        <img src="https://img.shields.io/badge/MediaPipe_Hands-1e293b?style=flat-square&logo=google&logoColor=4285f4" alt="MediaPipe Hands" />
        <img src="https://img.shields.io/badge/HTML5_Canvas-1e293b?style=flat-square&logo=html5&logoColor=e34f26" alt="HTML5 Canvas" />
        <img src="https://img.shields.io/badge/Web_Audio_API-1e293b?style=flat-square&logoColor=white" alt="Web Audio API" />
        <img src="https://img.shields.io/badge/Vite-1e293b?style=flat-square&logo=vite&logoColor=a78bfa" alt="Vite" />
      </p>
      <p align="center">
        <a href="https://github.com/sahilmunj10/hand-gesture-game"><img src="https://img.shields.io/badge/View_Repository-2563eb?style=for-the-badge&logo=github&logoColor=white" alt="View Hand Gesture Game repository" /></a>
        <a href="https://hand-gesture-game-rust.vercel.app"><img src="https://img.shields.io/badge/Live_Demo-0f172a?style=for-the-badge&logo=vercel&logoColor=white" alt="Play the live demo" /></a>
      </p>
    </td>
  </tr>

  <!-- ─────────── Row 3: Retail Sales Dashboard · E-Placement ─────────── -->
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📊 Retail Sales Analysis Dashboard</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Business_Intelligence-0b1220?style=flat-square&logoColor=22d3ee" alt="Business Intelligence" />
      </p>
      <p>An interactive Power BI dashboard built on the Superstore retail dataset that turns raw order records into an executive view of sales, profit, orders and product performance.</p>
      <p><strong>Implemented:</strong> KPI cards for Total Sales, Total Profit, Total Orders, Average Sales and Profit Margin %; monthly sales trend; sales by category and region; Top-10 products; and slicer-driven interactive filtering. Data shaping is done in Power Query with custom DAX measures.</p>
      <p><strong>Technical highlight:</strong> a reusable <code>.pbit</code> template is shipped alongside the <code>.pbix</code> report so the model can be re-pointed at new data.</p>
      <p align="center">
        <a href="https://github.com/sahilmunj10/Retail-Sales-Analysis-Dashboard"><img src="https://github.com/user-attachments/assets/b9232d23-a17a-4091-bc84-cbc9c787d7e5" alt="Retail Sales Analysis Dashboard preview — Power BI executive summary page" width="92%" /></a>
      </p>
      <p align="center">
        <img src="https://img.shields.io/badge/Power_BI-1e293b?style=flat-square&logo=powerbi&logoColor=f2c811" alt="Power BI" />
        <img src="https://img.shields.io/badge/DAX-1e293b?style=flat-square&logoColor=white" alt="DAX" />
        <img src="https://img.shields.io/badge/Power_Query-1e293b?style=flat-square&logoColor=white" alt="Power Query" />
      </p>
      <p align="center">
        <a href="https://github.com/sahilmunj10/Retail-Sales-Analysis-Dashboard"><img src="https://img.shields.io/badge/View_Repository-2563eb?style=for-the-badge&logo=github&logoColor=white" alt="View Retail Sales Analysis Dashboard repository" /></a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🎓 E-Placement Portal</h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Placement_Management-0b1220?style=flat-square&logoColor=22d3ee" alt="Placement Management" />
        <img src="https://img.shields.io/badge/Serverless-0b1220?style=flat-square&logoColor=a78bfa" alt="Serverless" />
      </p>
      <p>A web portal for managing college placement activities, with separate student and faculty workflows and no custom server to maintain.</p>
      <p><strong>Implemented:</strong> role-based auth for students and faculty, placement posting with deadlines and automatic expiry, application forms with status tracking, student profile management, an in-browser resume generator with PDF download (html2pdf.js), resume upload to Firebase Storage, faculty views to manage students and applications, dark mode, and email notifications to students when new placements are posted.</p>
      <p><strong>Technical highlight:</strong> Firebase Cloud Functions with Nodemailer handle notification emails, while Firestore security rules and indexes are version-controlled in the repo.</p>
      <p align="center">
        <a href="https://benevolent-chebakia-c10d0f.netlify.app/"><img src="https://raw.githubusercontent.com/sahilmunj10/E-placement/main/image.png" alt="E-Placement Portal preview" width="92%" /></a>
      </p>
      <p align="center">
        <img src="https://img.shields.io/badge/HTML5-1e293b?style=flat-square&logo=html5&logoColor=e34f26" alt="HTML5" />
        <img src="https://img.shields.io/badge/Tailwind-1e293b?style=flat-square&logo=tailwindcss&logoColor=38bdf8" alt="Tailwind CSS" />
        <img src="https://img.shields.io/badge/JavaScript-1e293b?style=flat-square&logo=javascript&logoColor=f7df1e" alt="JavaScript" />
        <img src="https://img.shields.io/badge/Firebase-1e293b?style=flat-square&logo=firebase&logoColor=ffca28" alt="Firebase Auth, Firestore, Storage, Functions" />
        <img src="https://img.shields.io/badge/Nodemailer-1e293b?style=flat-square&logoColor=white" alt="Nodemailer" />
      </p>
      <p align="center">
        <a href="https://github.com/sahilmunj10/E-placement"><img src="https://img.shields.io/badge/View_Repository-2563eb?style=for-the-badge&logo=github&logoColor=white" alt="View E-Placement repository" /></a>
        <a href="https://benevolent-chebakia-c10d0f.netlify.app/"><img src="https://img.shields.io/badge/Live_Demo-0f172a?style=for-the-badge&logo=netlify&logoColor=00c7b7" alt="Open the live demo" /></a>
      </p>
    </td>
  </tr>

  <!-- ─────────── Row 4: Foodora ─────────── -->
  <tr>
    <td colspan="2" valign="top">
      <table width="100%">
        <tr>
          <td width="38%" valign="middle" align="center">
            <a href="https://foodora-theta.vercel.app/"><img src="https://raw.githubusercontent.com/sahilmunj10/foodora/main/Screenshot%202025-08-08%20150713.png" alt="Foodora home page preview" width="100%" /></a>
          </td>
          <td width="62%" valign="top">
            <h3>🍽️ Foodora</h3>
            <p>
              <img src="https://img.shields.io/badge/Restaurant_Web_App-0b1220?style=flat-square&logoColor=22d3ee" alt="Restaurant Web App" />
              <img src="https://img.shields.io/badge/Frontend_%2B_Integrations-0b1220?style=flat-square&logoColor=a78bfa" alt="Frontend plus integrations" />
            </p>
            <p>A responsive restaurant web app covering the whole dining flow: browse and search the menu, build a cart with a live bill, place an order, and book a table.</p>
            <p><strong>Implemented:</strong> email OTP login (OTP sent via Google Apps Script MailApp), menu and cart persisted in <code>localStorage</code>, order-summary popup on checkout, table booking form, and instant <strong>Telegram Bot</strong> notifications to the restaurant for every order and booking. Login events are logged to Google Sheets through Apps Script.</p>
            <p><strong>Technical highlight:</strong> a working order-and-booking pipeline with zero backend servers — the browser talks directly to Apps Script and the Telegram Bot API.</p>
            <p>
              <img src="https://img.shields.io/badge/HTML5-1e293b?style=flat-square&logo=html5&logoColor=e34f26" alt="HTML5" />
              <img src="https://img.shields.io/badge/CSS3-1e293b?style=flat-square&logo=css&logoColor=1572b6" alt="CSS3" />
              <img src="https://img.shields.io/badge/JavaScript-1e293b?style=flat-square&logo=javascript&logoColor=f7df1e" alt="JavaScript" />
              <img src="https://img.shields.io/badge/Google_Apps_Script-1e293b?style=flat-square&logo=googleappsscript&logoColor=4285f4" alt="Google Apps Script" />
              <img src="https://img.shields.io/badge/Telegram_Bot_API-1e293b?style=flat-square&logo=telegram&logoColor=26a5e4" alt="Telegram Bot API" />
              <img src="https://img.shields.io/badge/Vercel-1e293b?style=flat-square&logo=vercel&logoColor=white" alt="Vercel" />
            </p>
            <p>
              <a href="https://github.com/sahilmunj10/foodora"><img src="https://img.shields.io/badge/View_Repository-2563eb?style=for-the-badge&logo=github&logoColor=white" alt="View Foodora repository" /></a>
              <a href="https://foodora-theta.vercel.app/"><img src="https://img.shields.io/badge/Live_Demo-0f172a?style=for-the-badge&logo=vercel&logoColor=white" alt="Open the live demo" /></a>
            </p>
          </td>
        </tr>
      </table>
    </td>
  </tr>
</table>

<p align="center"><sub>More on my profile: a real-time <a href="https://github.com/sahilmunj10/chatapp">chat app</a> (Socket.IO), a <a href="https://github.com/sahilmunj10/Python-Analysis-Page">Python analysis page</a> (Streamlit) and <a href="https://github.com/sahilmunj10/X-GEO">X-GEO</a>, an explainable GEO optimisation tool.</sub></p>

<p align="center"><img src="assets/divider.svg" alt="" width="100%" /></p>

<a id="tech-stack"></a>
## Tech Stack

<p align="center"><sub>Only technologies that appear in my public repositories.</sub></p>

<table align="center">
  <tr>
    <td align="right"><strong>Languages</strong></td>
    <td><img src="https://skillicons.dev/icons?i=js,ts,python,html,css&theme=dark" alt="JavaScript, TypeScript, Python, HTML, CSS" height="44" /></td>
  </tr>
  <tr>
    <td align="right"><strong>Frontend</strong></td>
    <td><img src="https://skillicons.dev/icons?i=react,vite,tailwind&theme=dark" alt="React, Vite, Tailwind CSS" height="44" /></td>
  </tr>
  <tr>
    <td align="right"><strong>Backend</strong></td>
    <td><img src="https://skillicons.dev/icons?i=nodejs,express,prisma,firebase&theme=dark" alt="Node.js, Express, Prisma, Firebase" height="44" />&nbsp;<img src="https://img.shields.io/badge/Socket.IO-0b1220?style=flat-square&logo=socketdotio&logoColor=white" alt="Socket.IO" /></td>
  </tr>
  <tr>
    <td align="right"><strong>Databases</strong></td>
    <td><img src="https://skillicons.dev/icons?i=mongodb,sqlite&theme=dark" alt="MongoDB, SQLite" height="44" />&nbsp;<img src="https://img.shields.io/badge/Cloud_Firestore-0b1220?style=flat-square&logo=firebase&logoColor=ffca28" alt="Cloud Firestore" /></td>
  </tr>
  <tr>
    <td align="right"><strong>AI · ML · Data</strong></td>
    <td>
      <img src="https://img.shields.io/badge/Power_BI-0b1220?style=flat-square&logo=powerbi&logoColor=f2c811" alt="Power BI" />
      <img src="https://img.shields.io/badge/DAX_%2F_Power_Query-0b1220?style=flat-square&logoColor=f2c811" alt="DAX and Power Query" />
      <img src="https://img.shields.io/badge/MediaPipe-0b1220?style=flat-square&logo=google&logoColor=4285f4" alt="MediaPipe Hands" />
      <img src="https://img.shields.io/badge/Groq_LLM_API-0b1220?style=flat-square&logoColor=f55036" alt="Groq LLM API" />
      <img src="https://img.shields.io/badge/Streamlit-0b1220?style=flat-square&logo=streamlit&logoColor=ff4b4b" alt="Streamlit" />
      <img src="https://img.shields.io/badge/Recharts-0b1220?style=flat-square&logoColor=22d3ee" alt="Recharts" />
    </td>
  </tr>
  <tr>
    <td align="right"><strong>Tools &amp; Platforms</strong></td>
    <td><img src="https://skillicons.dev/icons?i=git,github,vercel,netlify&theme=dark" alt="Git, GitHub, Vercel, Netlify" height="44" />&nbsp;<img src="https://img.shields.io/badge/GitHub_Actions-0b1220?style=flat-square&logo=githubactions&logoColor=2088ff" alt="GitHub Actions" /></td>
  </tr>
</table>

<p align="center"><img src="assets/divider.svg" alt="" width="100%" /></p>

## What I Like Building

<table>
  <tr>
    <td width="25%" valign="top" align="center">
      <h4>Practical software</h4>
      <sub>Applications with a clear user and a job to do — placement portals, restaurant ordering, chat. <br/><em>E-Placement · Foodora</em></sub>
    </td>
    <td width="25%" valign="top" align="center">
      <h4>AI-enabled &amp; research systems</h4>
      <sub>Products where an LLM, a decision engine or a model adds real leverage. <br/><em>CodeQuest · SwastyaSetu · ResearchIQ</em></sub>
    </td>
    <td width="25%" valign="top" align="center">
      <h4>Interactive experiences</h4>
      <sub>Real-time, playful interfaces — computer vision input, gamified progression, live chat. <br/><em>Hand Gesture Game · CodeQuest</em></sub>
    </td>
    <td width="25%" valign="top" align="center">
      <h4>Data-driven problem solving</h4>
      <sub>Turning raw data into KPIs, trends and decisions people can act on. <br/><em>Retail Sales Dashboard · Python Analysis Page</em></sub>
    </td>
  </tr>
</table>

<p align="center"><img src="assets/divider.svg" alt="" width="100%" /></p>

<a id="github-activity"></a>
## GitHub Activity

<p align="center"><sub>Statistics reflect public repositories only.</sub></p>

<p align="center">
  <a href="https://github.com/sahilmunj10">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=sahilmunj10&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0b1220&title_color=22d3ee&icon_color=a78bfa&text_color=cbd5e1&rank_icon=github" alt="Sahil Munj's GitHub stats" />
  </a>
  <a href="https://github.com/sahilmunj10">
    <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=sahilmunj10&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&bg_color=0b1220&title_color=22d3ee&text_color=cbd5e1" alt="Most used languages" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/sahilmunj10">
    <img src="https://streak-stats.demolab.com?user=sahilmunj10&theme=tokyonight&hide_border=true&background=0b1220&ring=22d3ee&fire=a78bfa&currStreakLabel=22d3ee&sideLabels=cbd5e1&dates=64748b" alt="GitHub contribution streak" />
  </a>
</p>

<!-- Contribution snake — generated by .github/workflows/snake.yml into the `output` branch -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/sahilmunj10/sahilmunj10/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/sahilmunj10/sahilmunj10/output/github-snake.svg" />
  <img alt="Contribution graph snake animation" src="https://raw.githubusercontent.com/sahilmunj10/sahilmunj10/output/github-snake-dark.svg" width="100%" />
</picture>

<p align="center"><img src="assets/divider.svg" alt="" width="100%" /></p>

<a id="connect"></a>
## Connect

<p align="center">
  <a href="https://github.com/sahilmunj10"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>&nbsp;
  <a href="https://www.linkedin.com/in/sahil-munj-1075s/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>&nbsp;
  <a href="mailto:sahilmunj10@gmail.com"><img src="https://img.shields.io/badge/Email-ea4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  Open to internships, collaborations and conversations about software, AI and data.<br/>
  <sub>If one of the projects above is useful to you, a ⭐ on the repo is always appreciated.</sub>
</p>

<p align="center"><a href="#top"><img src="https://img.shields.io/badge/↑_Back_to_top-0b1220?style=flat-square&logoColor=22d3ee" alt="Back to top" /></a></p>
