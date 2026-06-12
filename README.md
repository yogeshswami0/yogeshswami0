<!-- HEADER -->
<p align="center">
  <img src="https://capsule-render.github.io/api?type=waving&color=auto&height=250&section=header&text=YOGESH%20SWAMI&fontSize=55&fontColor=ffffff&animation=twinkling&theme=dark" width="100%" alt="Header Banner" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=9A6AFF&center=true&vCenter=true&width=500&lines=Computer+Science+Engineer;Full+Stack+Developer;3D+Web+UI+Explorer" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://github.com/yogeshswami0"><img src="https://img.shields.io/badge/Degree-B.Tech+CSE+%40+NIT+Jamshedpur-6f42c1?style=flat-square&logo=academia&logoColor=white" alt="Academic"></a>
  <a href="https://github.com/yogeshswami0"><img src="https://img.shields.io/badge/Location-Jamshedpur%2C+India-4c1?style=flat-square&logo=googlemaps&logoColor=white" alt="Location"></a>
  <a href="https://github.com/yogeshswami0"><img src="https://img.shields.io/badge/Portfolio-Live+Auction-8a2be2?style=flat-square&logo=webauthn&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/yogesh-swami-a3095b288/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:swamiyogesh670@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=yogeshswami0&label=Profile+Views&color=7928CA&style=flat-square" alt="Views" />
  <img src="https://img.shields.io/github/followers/yogeshswami0?label=Followers&style=flat-square&color=5854d6" alt="Followers" />
  <img src="https://img.shields.io/github/stars/yogeshswami0?label=Total+Stars&style=flat-square&color=4b0082" alt="Stars" />
</p>

---

<!-- ABOUT SECTION -->
## 📌 About Me

I am a Computer Science & Engineering undergraduate at NIT Jamshedpur, focusing on robust full-stack applications, interactive UI systems, and highly responsive user architectures. I combine backend stability with advanced frontend engineering, currently exploring real-time web state synchronization and immersive 3D user interfaces.

* **Computer Science & Engineering:** Deepening core fundamentals in operating systems, distributed database designs, algorithms, and microservices architecture.
* **Full Stack Development:** Creating high-concurrency systems featuring unified authentication, secure role-based permissions, and dynamic client routing layers.
* **3D Visual & Interactive UIs:** Specialized in converting traditional static web layouts into real-time interactive systems utilizing 3D motion graphs and hardware-accelerated rendering.

### ⚡ Current Openings & Collaboration
* Full-stack application engineering partnerships
* Interactive UI/UX and 3D web graphics design exploration
* Open-source infrastructure contributions

---

<!-- TECH STACK SECTION -->
## 🛠️ Tech Stack

### Languages
<p align="left">
  <img src="https://skillicons.dev/icons?i=js,ts,python,cpp,c,html,css" alt="Languages" />
</p>

### Frontend
<p align="left">
  <img src="https://skillicons.dev/icons?i=react,nextjs,redux,tailwind,threejs,sass" alt="Frontend" />
</p>

### Backend & Databases
<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,mysql,postgres,redis" alt="Backend and DB" />
</p>

### Cloud, DevOps & Tooling
<p align="left">
  <img src="https://skillicons.dev/icons?i=aws,docker,git,github,githubactions,postman,linux" alt="DevOps and Tooling" />
</p>

---

<!-- AI/ML & 3D GRAPHICS EXPERTISE SECTION -->
## 🤖 AI / ML & Visualization Expertise

| Domain | Proficiency | Details |
| :--- | :--- | :--- |
| **3D Web Graphics** | Advanced | Three.js canvas generation, custom shaders, camera path animation, Matter.js 2D environments |
| **Real-time Synchronization** | Advanced | Socket.io event architecture, persistent state pooling, transactional API synchronization |
| **State Engineering** | Advanced | Redux Toolkit state architectures, unified data layers, asynchronous query caching via Axios |
| **Data Orchestration** | Intermediate | Relational data integrity schemas, complex pipeline parsing, aggregations |

---

<!-- FEATURED PROJECTS SECTION -->
## 🚀 Featured Projects

<details open>
<summary><b>🔨 Live Auction Architecture Engine</b></summary>
<br />

### Project Description
An enterprise-grade live web socket auction ecosystem featuring granular tier permission handling (Admin, Owner, Player), synchronous live leaderboards, and real-time state calculation metrics.

| Metric | Target / Implementation |
| :--- | :--- |
| **Stack** | React.js, Express, Node.js, Axios, Redux, Three.js, CSS Animations |
| **Scale** | Multi-role routing environments mapping specific user privilege gates |
| **Performance** | Asynchronous action state updates under 15ms local lifecycle delay |
| **Security** | Encrypted token authentication with strict cross-origin CORS security layers |
| **Impact** | Fully automated transactional event loops dropping layout refresh needs to zero |
| **Repository** | [github.com/yogeshswami0/live-auction](https://github.com/yogeshswami0) |

### Architectural Deep-Dive
Engineered a centralized state management module resolving dual server-client actions efficiently. Integrates interactive, hardware-accelerated 3D elements that dynamically respond to bidding milestones and user actions, replacing conventional tabular dashboard structures with immersive data representations.

#### Real-time Visual Engine Preview
<!-- Floating Isometric Viewport Simulation with Ambient Occlusion Shadows -->
<p align="center">
  <svg width="680" height="340" viewBox="0 0 680 340" fill="none" xmlns="http://www.w3.org/2000/svg">
    <style>
      .bg { fill: #0d1117; }
      .grid-line { stroke: #30363d; stroke-width: 1; opacity: 0.3; }
      
      /* Pure CSS Isometric Float Animation */
      @keyframes float3d {
        0% { transform: translateY(0px) rotateX(60deg) rotateZ(-45deg); }
        50% { transform: translateY(-12px) rotateX(60deg) rotateZ(-45deg); }
        100% { transform: translateY(0px) rotateX(60deg) rotateZ(-45deg); }
      }
      
      /* Continuous Dynamic Shadow Scaling Animation */
      @keyframes shadowScale {
        0% { transform: scale(1) translate(0, 0); opacity: 0.35; filter: blur(12px); }
        50% { transform: scale(0.88) translate(6px, 6px); opacity: 0.18; filter: blur(18px); }
        100% { transform: scale(1) translate(0, 0); opacity: 0.35; filter: blur(12px); }
      }

      /* Glow effect for active canvas nodes */
      @keyframes cyberGlow {
        0%, 100% { stroke: #9A6AFF; stroke-width: 2; }
        50% { stroke: #bf9eff; stroke-width: 4; filter: drop-shadow(0 0 8px #9A6AFF); }
      }
      
      .view-container {
        transform-origin: 340px 150px;
        animation: float3d 4s ease-in-out infinite;
      }
      
      .shadow-layer {
        transform-origin: 340px 250px;
        mix-blend-mode: multiply;
        animation: shadowScale 4s ease-in-out infinite;
      }

      .pulse-node { animation: cyberGlow 3s ease-in-out infinite; }
    </style>

    <!-- Deep Space Canvas Background -->
    <rect width="100%" height="100%" class="bg" rx="8"/>
    
    <!-- Perspective Grid Floor -->
    <g opacity="0.25">
      <line x1="-100" y1="100" x2="800" y2="400" class="grid-line" />
      <line x1="-100" y1="160" x2="800" y2="460" class="grid-line" />
      <line x1="-100" y1="220" x2="800" y2="520" class="grid-line" />
      <line x1="-100" y1="40" x2="800" y2="340" class="grid-line" />
      <line x1="100" y1="-100" x2="-200" y2="500" class="grid-line" />
      <line x1="250" y1="-100" x2="-50" y2="500" class="grid-line" />
      <line x1="400" y1="-100" x2="100" y2="500" class="grid-line" />
      <line x1="550" y1="-100" x2="250" y2="500" class="grid-line" />
    </g>

    <!-- REAL-TIME AMBIENT OCCLUSION SHADOW LAYER -->
    <g class="shadow-layer">
      <!-- Dropped Projection Soft Shadow Blur -->
      <ellipse cx="340" cy="250" rx="140" ry="60" fill="#000000" />
      <ellipse cx="260" cy="220" rx="40" ry="20" fill="#040208" />
      <ellipse cx="420" cy="260" rx="50" ry="22" fill="#040208" />
    </g>

    <!-- FLOATING ISOMETRIC APPLICATION MESH -->
    <g class="view-container">
      <!-- Main Board Backplate Structure -->
      <rect x="190" y="50" width="300" height="200" rx="12" fill="#161b22" stroke="#30363d" stroke-width="2"/>
      <rect x="190" y="50" width="300" height="40" rx="12" fill="#21262d" />
      
      <!-- Top Window Controls Decoration -->
      <circle cx="215" cy="70" r="5" fill="#ff5f56" />
      <circle cx="230" cy="70" r="5" fill="#ffbd2e" />
      <circle cx="245" cy="70" r="5" fill="#27c93f" />
      <text x="270" y="76" fill="#8b949e" font-family="monospace" font-size="12" font-weight="bold">live-auction-mesh</text>

      <!-- Glassmorphic Data Visualization Node 1 (Leaderboard Matrix) -->
      <g transform="translate(210, 105)">
        <rect width="120" height="60" rx="6" fill="#21262d" fill-opacity="0.8" stroke="#8a2be2" stroke-width="1.5"/>
        <text x="10" y="22" fill="#9a6aff" font-family="sans-serif" font-size="11" font-weight="bold">LEADERBOARD</text>
        <rect x="10" y="32" width="100" height="6" rx="3" fill="#30363d" />
        <rect x="10" y="44" width="75" height="6" rx="3" fill="#5854d6" />
      </g>

      <!-- Glassmorphic Data Visualization Node 2 (Realtime Metric Engine) -->
      <g transform="translate(350, 125)">
        <rect width="120" height="85" rx="6" fill="#1f1b2e" fill-opacity="0.9" class="pulse-node" />
        <text x="12" y="22" fill="#ffffff" font-family="sans-serif" font-size="11" font-weight="bold">LIVE BIDDING</text>
        <!-- Volumetric Step Graph Lines inside Engine Box -->
        <path d="M15 65 L40 45 L65 55 L95 35 L110 40" stroke="#9A6AFF" stroke-width="2.5" fill="none" stroke-linecap="round"/>
        <circle cx="95" cy="35" r="3" fill="#ffffff" />
      </g>
      
      <!-- Inter-node Mesh Connection Edge Pipeline -->
      <path d="M 330 135 L 350 135" stroke="#9A6AFF" stroke-width="1.5" stroke-dasharray="4,3" />
      
      <!-- Sub-platform Base Boundary Profile Lines -->
      <line x1="190" y1="240" x2="490" y2="240" stroke="#30363d" stroke-width="1"/>
    </g>
  </svg>
</p>
</details>

<details>
<summary><b>🌐 Immersive 3D Animated Navigation Core</b></summary>
<br />

### Project Description
A modular UI subsystem transforming typical navigation workflows into volumetric, reactive 3D workspaces running at persistent high frame rates across devices.

| Metric | Target / Implementation |
| :--- | :--- |
| **Stack** | JavaScript, Next.js, Three.js WebGL Framework, CSS3D Vectors, Anime.js |
| **Scale** | Scalable component architecture designed for modern complex layout routing |
| **Performance** | Locked 60FPS visual thread loops by offloading physics tasks to Web Workers |
| **Security** | Sanitized coordinate state structures ensuring input validation safety |
| **Impact** | Drastically elevates visual interaction metrics, keeping user sessions fluid and engaging |
| **Repository** | [github.com/yogeshswami0/3d-navigation](https://github.com/yogeshswami0) |

### Architectural Deep-Dive
Uses low-overhead raycasting matrices to detect cursor focus changes, feeding state offsets directly into structural matrix transformations. Intercepts standard route changes to execute seamless 3D spatial translations before rendering destination page viewframes.

#### Ray-Casted Viewport Node Mapping Preview
<!-- Raycast Node Matrix Hover Space Simulation with Dynamic Shadow Casting -->
<p align="center">
  <svg width="680" height="340" viewBox="0 0 680 340" fill="none" xmlns="http://www.w3.org/2000/svg">
    <style>
      .space-bg { fill: #0d1117; }
      
      /* Dynamic Layer Floating Animations (Asynchronous Offsets) */
      @keyframes floatLayerA {
        0%, 100% { transform: translateY(0px) rotateX(55deg) rotateY(5deg) rotateZ(-20deg); }
        50% { transform: translateY(-16px) rotateX(52deg) rotateY(3deg) rotateZ(-18deg); }
      }
      @keyframes floatLayerB {
        0%, 100% { transform: translateY(-30px) rotateX(55deg) rotateY(5deg) rotateZ(-20deg); }
        50% { transform: translateY(-52px) rotateX(52deg) rotateY(3deg) rotateZ(-18deg); }
      }
      
      /* Cast Depth Blur-Shadow Matrix Scales inversely with Object Height */
      @keyframes groundShadow {
        0%, 100% { transform: scale(1); opacity: 0.4; filter: blur(14px); }
        50% { transform: scale(0.82); opacity: 0.15; filter: blur(22px); }
      }

      .layer-bottom {
        transform-origin: 340px 170px;
        animation: floatLayerA 5s ease-in-out infinite;
      }
      .layer-top {
        transform-origin: 340px 170px;
        animation: floatLayerB 5s ease-in-out infinite;
      }
      .floor-shadow {
        transform-origin: 340px 240px;
        animation: groundShadow 5s ease-in-out infinite;
      }
    </style>

    <!-- Canvas Frame -->
    <rect width="100%" height="100%" class="space-bg" rx="8"/>

    <!-- REAL SHADOW MAPPING LAYER -->
    <g class="floor-shadow">
      <ellipse cx="340" cy="250" rx="160" ry="45" fill="#000000" />
      <ellipse cx="310" cy="245" rx="80" ry="25" fill="#030105" />
    </g>

    <!-- LAYER CONTAINER 1: THE INPUT INTERACTION PLANE -->
    <g class="layer-bottom">
      <!-- Grid Mesh Base Grid Window -->
      <rect x="200" y="80" width="280" height="160" rx="8" fill="#161b22" fill-opacity="0.6" stroke="#30363d" stroke-width="1.5"/>
      <path d="M 200 120 L 480 120 M 200 160 L 480 160 M 200 200 L 480 200" stroke="#21262d" stroke-width="1"/>
      <path d="M 270 80 L 270 240 M 340 80 L 340 240 M 410 80 L 410 240" stroke="#21262d" stroke-width="1"/>
      
      <!-- Interactive Focus Matrix Tracking Points -->
      <circle cx="340" cy="160" r="6" fill="#9A6AFF" opacity="0.8"/>
      <circle cx="340" cy="160" r="14" stroke="#9A6AFF" stroke-width="1" opacity="0.4" stroke-dasharray="2,2"/>
    </g>

    <!-- RAYCAST VECTOR CONNECTOR LINES -->
    <!-- These lines connect the lower coordinate canvas plane to the top floating menu transform blocks -->
    <g opacity="0.35">
      <line x1="290" y1="140" x2="270" y2="70" stroke="#6f42c1" stroke-width="1.5" stroke-dasharray="3,3" />
      <line x1="390" y1="140" x2="410" y2="70" stroke="#6f42c1" stroke-width="1.5" stroke-dasharray="3,3" />
    </g>

    <!-- LAYER CONTAINER 2: THE FLOATING 3D VIEWPORT LAYER -->
    <g class="layer-top">
      <!-- Upraised Primary Navigation Cards Vector -->
      <g transform="translate(220, 90)">
        <!-- Dashboard Workspace 3D Tile Layer -->
        <rect width="240" height="130" rx="10" fill="#21262d" fill-opacity="0.85" stroke="#7928CA" stroke-width="2" style="filter: drop-shadow(0px 15px 20px rgba(0,0,0,0.7));"/>
        
        <!-- UI Structural Components Inside Tile -->
        <rect x="15" y="15" width="40" height="8" rx="4" fill="#9A6AFF" />
        <rect x="15" y="35" width="210" height="40" rx="6" fill="#0d1117" stroke="#30363d" />
        <circle cx="35" cy="55" r="10" fill="#30363d" />
        <rect x="55" y="52" width="120" height="6" rx="3" fill="#21262d" />
        
        <!-- Glowing Coordinate Vectors -->
        <path d="M15 100 L 225 100" stroke="#30363d" stroke-width="2"/>
        <circle cx="140" cy="55" r="4" fill="#6f42c1" />
        <line x1="35" y1="55" x2="140" y2="55" stroke="#6f42c1" stroke-width="1" />
      </g>
    </g>
  </svg>
</p>
</details>

---

<!-- EXPERIENCE SECTION -->
## 💼 Academic & Practical Experience

### **Full Stack Engineer - Student Developer** — *NIT Jamshedpur*  
**July 2023 — Present**  
* Designing real-time data sync patterns for distributed apps using advanced Web Socket integrations.
* Scaling state management pipelines on frontend clients using Redux architectures, eliminating rendering redundancies.
* Building modern user portals with distinct login security wrappers and reactive user role boundaries.
* `React.js` `Node.js` `Express` `MongoDB` `Axios` `Redux`

---

<!-- ACHIEVEMENTS SECTION -->
## 🏆 Key Achievements

<p align="center">
</p>

| Recognition | Details |
| :--- | :--- |
| **NIT Jamshedpur CSE** | Pursuing highly technical B.Tech roadmap maintaining competitive structural specialization paradigms |
| **3D UI Innovation** | Deployed custom WebGL modules to convert traditional text-only interfaces into real-time kinetic environments |

---

<!-- CERTIFICATIONS SECTION -->
## 📜 Certifications

### Advanced Web Development
<p align="left">
  <img src="https://img.shields.io/badge/Full_Stack_Development-MERN_Architecture_Expertise-6f42c1?style=for-the-badge&logo=react&logoColor=white" alt="MERN Certified">
</p>

### Computer Science Foundations
<p align="left">
  <img src="https://img.shields.io/badge/NIT_Jamshedpur-Data_Structures_And_Algorithms_Core-005EA6?style=for-the-badge&logo=education&logoColor=white" alt="NITJ Foundation">
</p>

---

<!-- CODING PROFILES SECTION -->
## 💻 Coding Profiles

<p align="left">
  <a href="https://leetcode.com"><img src="https://img.shields.io/badge/LeetCode-Problem_Solving-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
  <a href="https://hackerrank.com"><img src="https://img.shields.io/badge/HackerRank-Computer_Science-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white" alt="HackerRank"></a>
</p>

---

<!-- GITHUB ANALYTICS SECTION -->
## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=yogeshswami0&show_icons=true&theme=dark&bg_color=0d1117&title_color=9A6AFF&icon_color=9A6AFF&text_color=c9d1d9&border_color=21262d" width="48%" alt="GitHub Stats" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=yogeshswami0&theme=dark&background=0d1117&title=9A6AFF&ring=9A6AFF&fire=9A6AFF&text=c9d1d9&border=21262d" width="48%" alt="Streak Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yogeshswami0&layout=compact&theme=dark&bg_color=0d1117&title_color=9A6AFF&text_color=c9d1d9&border_color=21262d" width="48%" alt="Top Languages" />
</p>

---

<!-- GITHUB TROPHIES SECTION -->
## 🏆 GitHub Trophies

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=yogeshswami0&theme=midnight&column=7&margin-w=15&margin-h=15" width="100%" alt="Trophies" />
</p>

---

<!-- CONTRIBUTION ACTIVITY SECTION -->
## 📈 Contribution Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=yogeshswami0&theme=react-dark&bg_color=0d1117&color=9A6AFF&line=9A6AFF&point=ffffff&area=true&hide_border=false" width="100%" alt="Activity Graph" />
</p>

---

<!-- CONTRIBUTION SNAKE SECTION -->
## 🐍 Contribution Canvas

<p align="center">
  <img src="https://raw.githubusercontent.com/yogeshswami0/yogeshswami0/output/github-contribution-grid-snake-dark.svg" width="100%" alt="Snake Animation" />
</p>

---

<!-- CURRENT FOCUS SECTION -->
## 🎯 Current Status

```yaml
Focusing:
  Learning: "Advanced hardware accelerated Three.js shaders and WebGL camera matrices"
  Building: "Live Auction continuous state sync layer with complex multi-role workflows"
  Exploring: "Real-time client synchronization frames and high frame rate viewport physics"
  Open_To: "Collaborating on interactive product architectures and innovative web platforms"
