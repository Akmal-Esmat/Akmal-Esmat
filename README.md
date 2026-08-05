<!-- 
  ╔══════════════════════════════════════════════════════════════════════════════╗
  ║  NEXT-GENERATION GITHUB PROFILE README                                       ║
  ║  ─────────────────────────────────────                                       ║
  ║  Author: Akmal Esmat (Template)                                              ║
  ║  Style: Futuristic · Terminal-Inspired · Premium · Dark-First                ║
  ║                                                                              ║
  ║  CUSTOMIZATION GUIDE:                                                        ║
  ║  ────────────────────                                                        ║
  ║  1. Replace "YOUR_USERNAME" with your actual GitHub username everywhere      ║
  ║  2. Replace "Akmal Esmat" with your name                                     ║
  ║  3. Update social links, email, and location                                 ║
  ║  4. Configure WakaTime API key for coding stats                              ║
  ║  5. Set up the Snake GitHub Action (see Section 4)                           ║
  ║  6. Replace project cards with your actual repositories                      ║
  ║  7. Adjust skill badges to match your stack                                  ║
  ║                                                                              ║
  ║  NOTE: GitHub sanitizes most HTML/CSS. All animations use SVG with inline    ║
  ║  CSS keyframes, which GitHub renders reliably. External image services       ║
  ║  (readme-typing-svg, github-readme-stats, etc.) generate dynamic SVGs.       ║
  ╚══════════════════════════════════════════════════════════════════════════════╝
-->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 0: HIDDEN EASTER EGG (Konami Code Trigger)                         -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Easter Egg: Try pressing ↑↑↓↓←→←→BA on your keyboard while viewing this README
  (Works in browsers that support keyboard events on markdown-rendered pages)
-->
<div align="center">
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 2: ANIMATED HERO BANNER                                            -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  This SVG banner creates a cyber-grid background with flowing gradients.
  It is self-contained — no external dependencies.

  CUSTOMIZE: Change the text "AKMAL ESMAT" to your name.
  The gradient colors can be adjusted in the <linearGradient> definitions.
-->
<svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <!-- Animated gradient background -->
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0d1117">
        <animate attributeName="stop-color" values="#0d1117;#161b22;#0d1117" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#161b22">
        <animate attributeName="stop-color" values="#161b22;#21262d;#161b22" dur="8s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#0d1117">
        <animate attributeName="stop-color" values="#0d1117;#161b22;#0d1117" dur="8s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>
plain
<!-- Glowing line gradient -->
<linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
  <stop offset="0%" stop-color="#00d4aa" stop-opacity="0"/>
  <stop offset="50%" stop-color="#00d4aa" stop-opacity="1"/>
  <stop offset="100%" stop-color="#00d4aa" stop-opacity="0"/>
</linearGradient>

<!-- Cyber grid pattern -->
<pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
  <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#21262d" stroke-width="0.5" opacity="0.3"/>
</pattern>

<!-- Glow filter -->
<filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
  <feGaussianBlur stdDeviation="3" result="coloredBlur"/>
  <feMerge>
    <feMergeNode in="coloredBlur"/>
    <feMergeNode in="SourceGraphic"/>
  </feMerge>
</filter>
  </defs>
  <!-- Background -->
  <rect width="100%" height="100%" fill="url(#bgGrad)"/>
  <rect width="100%" height="100%" fill="url(#grid)"/>
  <!-- Animated horizontal scan lines -->
  <line x1="0" y1="30" x2="1200" y2="30" stroke="url(#lineGrad)" stroke-width="1" opacity="0.4">
    <animate attributeName="y1" values="30;190;30" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="30;190;30" dur="6s" repeatCount="indefinite"/>
  </line>
  <line x1="0" y1="80" x2="1200" y2="80" stroke="url(#lineGrad)" stroke-width="1" opacity="0.2">
    <animate attributeName="y1" values="80;150;80" dur="8s" repeatCount="indefinite"/>
    <animate attributeName="y2" values="80;150;80" dur="8s" repeatCount="indefinite"/>
  </line>
  <!-- Floating particles -->
  <circle cx="200" cy="50" r="2" fill="#00d4aa" opacity="0.6">
    <animate attributeName="cy" values="50;170;50" dur="5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.6;0;0.6" dur="5s" repeatCount="indefinite"/>
  </circle>
  <circle cx="900" cy="120" r="1.5" fill="#58a6ff" opacity="0.5">
    <animate attributeName="cy" values="120;40;120" dur="7s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.5;0;0.5" dur="7s" repeatCount="indefinite"/>
  </circle>
  <circle cx="600" cy="180" r="2" fill="#f0883e" opacity="0.4">
    <animate attributeName="cy" values="180;60;180" dur="6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.4;0;0.4" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1100" cy="70" r="1" fill="#00d4aa" opacity="0.7">
    <animate attributeName="cy" values="70;160;70" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.7;0;0.7" dur="4s" repeatCount="indefinite"/>
  </circle>
  <!-- Main title text -->
<text x="50%" y="45%" dominant-baseline="middle" text-anchor="middle" 
     font-family="'Segoe UI', 'SF Mono', monospace" font-size="52" font-weight="700" 
     fill="#f0f6fc" letter-spacing="8" filter="url(#glow)"><animate attributeName="opacity" values="0.9;1;0.9" dur="3s" repeatCount="indefinite"/>
  <!-- Subtitle -->
<text x="50%" y="65%" dominant-baseline="middle" text-anchor="middle"
     font-family="'Segoe UI', 'SF Mono', monospace" font-size="16" font-weight="400"
     fill="#8b949e" letter-spacing="6">
  <!-- Decorative bottom line -->
  <line x1="35%" y1="80%" x2="65%" y2="80%" stroke="#21262d" stroke-width="1"/>
  <line x1="45%" y1="80%" x2="55%" y2="80%" stroke="#00d4aa" stroke-width="2">
    <animate attributeName="x1" values="45%;35%;45%" dur="4s" repeatCount="indefinite"/>
    <animate attributeName="x2" values="55%;65%;55%" dur="4s" repeatCount="indefinite"/>
  </line>
</svg>

<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 3: DYNAMIC TYPING ANIMATION                                        -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Powered by readme-typing-svg (DenverCoder1).
  Generates an animated SVG that cycles through text with a typing effect.

  CUSTOMIZE: 
  - Change the "lines=" parameter to your own roles/identities
  - Adjust "color=" for different text colors (hex without #)
  - Adjust "pause=" for typing speed
  - Adjust "width=" to fit your longest line

  Demo & Configurator: https://readme-typing-svg.demolab.com/demo/
-->
https://git.io/typing-svg


<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 1: INTERACTIVE TERMINAL HERO                                       -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Self-contained terminal SVG with character-by-character typing animation.
  No external dependencies — pure SVG + CSS keyframes.

  CUSTOMIZE:
  - Change the text content in the <tspan> elements
  - Adjust colors in the gradient and text fill
  - Modify typing speed by changing the animation durations
-->
<svg width="700" height="320" viewBox="0 0 700 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="termBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#161b22"/>
    </linearGradient>
    <filter id="termGlow">
      <feGaussianBlur stdDeviation="1.5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <!-- Terminal window -->
  <rect x="10" y="10" width="680" height="300" rx="12" fill="url(#termBg)" stroke="#30363d" stroke-width="2"/>
  <!-- Title bar -->
  <rect x="10" y="10" width="680" height="36" rx="12" fill="#21262d"/>
  <rect x="10" y="22" width="680" height="24" fill="#21262d"/>
  <!-- Window controls -->
  <circle cx="38" cy="28" r="6" fill="#ff5f56"/>
  <circle cx="60" cy="28" r="6" fill="#ffbd2e"/>
  <circle cx="82" cy="28" r="6" fill="#27c93f"/>
  <!-- Terminal title -->
<text x="350" y="32" text-anchor="middle" font-family="'SF Mono', monospace" font-size="12" fill="#8b949e">
  <!-- Terminal content -->
  <text x="30" y="70" font-family="'Fira Code', 'SF Mono', monospace" font-size="14" fill="#00d4aa" filter="url(#termGlow)">
    <tspan x="30" dy="0">$ whoami</tspan>
  </text>
  <text x="30" y="95" font-family="'Fira Code', 'SF Mono', monospace" font-size="14" fill="#f0f6fc">
    <tspan x="30" dy="0" opacity="0">
      Akmal Esmat
      <animate attributeName="opacity" values="0;1" dur="0.5s" begin="0.8s" fill="freeze"/>
    </tspan>
  </text>
  <text x="30" y="120" font-family="'Fira Code', 'SF Mono', monospace" font-size="14" fill="#f0f6fc">
    <tspan x="30" dy="0" opacity="0">
      Computer & Communications Engineer
      <animate attributeName="opacity" values="0;1" dur="0.5s" begin="1.3s" fill="freeze"/>
    </tspan>
  </text>
  <text x="30" y="155" font-family="'Fira Code', 'SF Mono', monospace" font-size="14" fill="#58a6ff" filter="url(#termGlow)">
    <tspan x="30" dy="0" opacity="0">
      &gt; Full Stack Developer
      <animate attributeName="opacity" values="0;1" dur="0.4s" begin="1.8s" fill="freeze"/>
    </tspan>
  </text>
  <text x="30" y="180" font-family="'Fira Code', 'SF Mono', monospace" font-size="14" fill="#58a6ff">
    <tspan x="30" dy="0" opacity="0">
      &gt; DevOps Engineer
      <animate attributeName="opacity" values="0;1" dur="0.4s" begin="2.2s" fill="freeze"/>
    </tspan>
  </text>
  <text x="30" y="205" font-family="'Fira Code', 'SF Mono', monospace" font-size="14" fill="#58a6ff">
    <tspan x="30" dy="0" opacity="0">
      &gt; Linux Enthusiast
      <animate attributeName="opacity" values="0;1" dur="0.4s" begin="2.6s" fill="freeze"/>
    </tspan>
  </text>
  <text x="30" y="230" font-family="'Fira Code', 'SF Mono', monospace" font-size="14" fill="#58a6ff">
    <tspan x="30" dy="0" opacity="0">
      &gt; AI Systems Builder
      <animate attributeName="opacity" values="0;1" dur="0.4s" begin="3.0s" fill="freeze"/>
    </tspan>
  </text>
  <text x="30" y="255" font-family="'Fira Code', 'SF Mono', monospace" font-size="14" fill="#58a6ff">
    <tspan x="30" dy="0" opacity="0">
      &gt; Automation Addict
      <animate attributeName="opacity" values="0;1" dur="0.4s" begin="3.4s" fill="freeze"/>
    </tspan>
  </text>
  <!-- Blinking cursor -->
  <rect x="30" y="275" width="10" height="18" fill="#00d4aa" opacity="0">
    <animate attributeName="opacity" values="0;1;0" dur="1s" begin="4s" repeatCount="indefinite"/>
  </rect>
</svg>


<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 8: CUSTOM SVG WIDGETS (Status Dashboard)                           -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  A row of premium glassmorphism-style status widgets.
  Each widget is a self-contained SVG with subtle animations.

  CUSTOMIZE: Update the text values, colors, and icons to match your status.
-->
<table align="center">
  <tr>
    <td>
      <!-- Current Focus Widget -->
      <svg width="200" height="80" viewBox="0 0 200 80" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="cardBg1" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#161b22"/>
            <stop offset="100%" stop-color="#0d1117"/>
          </linearGradient>
        </defs>
        <rect width="200" height="80" rx="12" fill="url(#cardBg1)" stroke="#30363d" stroke-width="1.5"/>
        <text x="20" y="28" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e" letter-spacing="1">CURRENT FOCUS</text>
        <text x="20" y="55" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">Building AI Knowledge</text>
        <text x="20" y="72" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">Systems</text>
        <circle cx="175" cy="25" r="4" fill="#00d4aa">
          <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
        </circle>
      </svg>
    </td>
    <td width="12"></td>
    <td>
      <!-- Learning Widget -->
      <svg width="200" height="80" viewBox="0 0 200 80" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="cardBg2" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#161b22"/>
            <stop offset="100%" stop-color="#0d1117"/>
          </linearGradient>
        </defs>
        <rect width="200" height="80" rx="12" fill="url(#cardBg2)" stroke="#30363d" stroke-width="1.5"/>
        <text x="20" y="28" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e" letter-spacing="1">LEARNING</text>
        <text x="20" y="55" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">Kubernetes</text>
        <text x="20" y="72" font-family="'Segoe UI', sans-serif" font-size="14" fill="#58a6ff" font-weight="600">Distributed Systems</text>
      </svg>
    </td>
    <td width="12"></td>
    <td>
      <!-- Location Widget -->
      <svg width="200" height="80" viewBox="0 0 200 80" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="cardBg3" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#161b22"/>
            <stop offset="100%" stop-color="#0d1117"/>
          </linearGradient>
        </defs>
        <rect width="200" height="80" rx="12" fill="url(#cardBg3)" stroke="#30363d" stroke-width="1.5"/>
        <text x="20" y="28" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e" letter-spacing="1">LOCATION</text>
        <text x="20" y="58" font-family="'Segoe UI', sans-serif" font-size="16" fill="#f0f6fc" font-weight="600">Cairo, Egypt</text>
        <circle cx="175" cy="40" r="8" fill="none" stroke="#f0883e" stroke-width="2"/>
        <circle cx="175" cy="40" r="3" fill="#f0883e"/>
      </svg>
    </td>
  </tr>
  <tr><td height="12"></td></tr>
  <tr>
    <td>
      <!-- Status Widget -->
      <svg width="200" height="80" viewBox="0 0 200 80" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="cardBg4" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#161b22"/>
            <stop offset="100%" stop-color="#0d1117"/>
          </linearGradient>
        </defs>
        <rect width="200" height="80" rx="12" fill="url(#cardBg4)" stroke="#30363d" stroke-width="1.5"/>
        <text x="20" y="28" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e" letter-spacing="1">STATUS</text>
        <text x="20" y="55" font-family="'Segoe UI', sans-serif" font-size="14" fill="#00d4aa" font-weight="600">● Online</text>
        <text x="20" y="72" font-family="'Segoe UI', sans-serif" font-size="12" fill="#8b949e">Building · Learning</text>
      </svg>
    </td>
    <td width="12"></td>
    <td>
      <!-- Coffee Counter Widget -->
      <svg width="200" height="80" viewBox="0 0 200 80" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="cardBg5" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#161b22"/>
            <stop offset="100%" stop-color="#0d1117"/>
          </linearGradient>
        </defs>
        <rect width="200" height="80" rx="12" fill="url(#cardBg5)" stroke="#30363d" stroke-width="1.5"/>
        <text x="20" y="28" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e" letter-spacing="1">COFFEE COUNTER</text>
        <text x="20" y="58" font-family="'Segoe UI', sans-serif" font-size="28" fill="#f0883e" font-weight="700">☕ 235</text>
      </svg>
    </td>
    <td width="12"></td>
    <td>
      <!-- Projects Widget -->
      <svg width="200" height="80" viewBox="0 0 200 80" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="cardBg6" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#161b22"/>
            <stop offset="100%" stop-color="#0d1117"/>
          </linearGradient>
        </defs>
        <rect width="200" height="80" rx="12" fill="url(#cardBg6)" stroke="#30363d" stroke-width="1.5"/>
        <text x="20" y="28" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e" letter-spacing="1">PROJECTS</text>
        <text x="20" y="55" font-family="'Segoe UI', sans-serif" font-size="22" fill="#58a6ff" font-weight="700">12 Active</text>
        <text x="20" y="72" font-family="'Segoe UI', sans-serif" font-size="12" fill="#8b949e">Repositories Growing...</text>
      </svg>
    </td>
  </tr>
</table>


</div>
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 5: 3D SKILLS SECTION                                               -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Premium skill showcase using custom SVG cards with depth, shadows, and lighting.
  Grouped by category with floating animation effects.

  CUSTOMIZE: Add/remove skills, change colors, adjust category names.
  Each skill is an SVG card — no external badge services used.
-->
<div align="center">
⚡ Tech Stack

<!-- LANGUAGES -->
<svg width="800" height="130" viewBox="0 0 800 130" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <filter id="shadow" x="-10%" y="-10%" width="130%" height="130%">
      <feDropShadow dx="0" dy="4" stdDeviation="6" flood-color="#000" flood-opacity="0.4"/>
    </filter>
    <linearGradient id="langGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#21262d"/>
      <stop offset="100%" stop-color="#161b22"/>
    </linearGradient>
  </defs>
  <!-- Category label -->
<text x="20" y="25" font-family="'SF Mono', monospace" font-size="11" fill="#8b949e" letter-spacing="3">
  <!-- Python -->
  <g transform="translate(20, 45)" filter="url(#shadow)">
    <rect width="100" height="40" rx="8" fill="url(#langGrad)" stroke="#3776ab" stroke-width="1.5"/>
    <text x="50" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Python</text>
  </g>
  <!-- C++ -->
  <g transform="translate(132, 45)" filter="url(#shadow)">
    <rect width="70" height="40" rx="8" fill="url(#langGrad)" stroke="#00599c" stroke-width="1.5"/>
    <text x="35" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">C++</text>
  </g>
  <!-- C# -->
  <g transform="translate(214, 45)" filter="url(#shadow)">
    <rect width="70" height="40" rx="8" fill="url(#langGrad)" stroke="#512bd4" stroke-width="1.5"/>
    <text x="35" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">C#</text>
  </g>
  <!-- TypeScript -->
  <g transform="translate(296, 45)" filter="url(#shadow)">
    <rect width="110" height="40" rx="8" fill="url(#langGrad)" stroke="#3178c6" stroke-width="1.5"/>
    <text x="55" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">TypeScript</text>
  </g>
  <!-- JavaScript -->
  <g transform="translate(418, 45)" filter="url(#shadow)">
    <rect width="110" height="40" rx="8" fill="url(#langGrad)" stroke="#f7df1e" stroke-width="1.5"/>
    <text x="55" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">JavaScript</text>
  </g>
  <!-- SQL -->
  <g transform="translate(540, 45)" filter="url(#shadow)">
    <rect width="70" height="40" rx="8" fill="url(#langGrad)" stroke="#e535ab" stroke-width="1.5"/>
    <text x="35" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">SQL</text>
  </g>
  <!-- Bash -->
  <g transform="translate(622, 45)" filter="url(#shadow)">
    <rect width="80" height="40" rx="8" fill="url(#langGrad)" stroke="#4eaa25" stroke-width="1.5"/>
    <text x="40" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Bash</text>
  </g>
</svg>

<!-- FRONTEND -->
<svg width="600" height="130" viewBox="0 0 600 130" xmlns="http://www.w3.org/2000/svg">
  <text x="20" y="25" font-family="'SF Mono', monospace" font-size="11" fill="#8b949e" letter-spacing="3">FRONTEND</text>
  <g transform="translate(20, 45)" filter="url(#shadow)">
    <rect width="100" height="40" rx="8" fill="url(#langGrad)" stroke="#f0f6fc" stroke-width="1.5"/>
    <text x="50" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Next.js</text>
  </g>
  <g transform="translate(132, 45)" filter="url(#shadow)">
    <rect width="80" height="40" rx="8" fill="url(#langGrad)" stroke="#61dafb" stroke-width="1.5"/>
    <text x="40" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">React</text>
  </g>
  <g transform="translate(224, 45)" filter="url(#shadow)">
    <rect width="110" height="40" rx="8" fill="url(#langGrad)" stroke="#06b6d4" stroke-width="1.5"/>
    <text x="55" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Tailwind</text>
  </g>
  <g transform="translate(346, 45)" filter="url(#shadow)">
    <rect width="70" height="40" rx="8" fill="url(#langGrad)" stroke="#e34c26" stroke-width="1.5"/>
    <text x="35" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">HTML</text>
  </g>
  <g transform="translate(428, 45)" filter="url(#shadow)">
    <rect width="60" height="40" rx="8" fill="url(#langGrad)" stroke="#264de4" stroke-width="1.5"/>
    <text x="30" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">CSS</text>
  </g>
</svg>

<!-- BACKEND -->
<svg width="500" height="130" viewBox="0 0 500 130" xmlns="http://www.w3.org/2000/svg">
  <text x="20" y="25" font-family="'SF Mono', monospace" font-size="11" fill="#8b949e" letter-spacing="3">BACKEND</text>
  <g transform="translate(20, 45)" filter="url(#shadow)">
    <rect width="100" height="40" rx="8" fill="url(#langGrad)" stroke="#009688" stroke-width="1.5"/>
    <text x="50" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">FastAPI</text>
  </g>
  <g transform="translate(132, 45)" filter="url(#shadow)">
    <rect width="80" height="40" rx="8" fill="url(#langGrad)" stroke="#512bd4" stroke-width="1.5"/>
    <text x="40" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">.NET</text>
  </g>
  <g transform="translate(224, 45)" filter="url(#shadow)">
    <rect width="110" height="40" rx="8" fill="url(#langGrad)" stroke="#00d4aa" stroke-width="1.5"/>
    <text x="55" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">REST APIs</text>
  </g>
</svg>

<!-- DEVOPS -->
<svg width="900" height="180" viewBox="0 0 900 180" xmlns="http://www.w3.org/2000/svg">
  <text x="20" y="25" font-family="'SF Mono', monospace" font-size="11" fill="#8b949e" letter-spacing="3">DEVOPS</text>
  <g transform="translate(20, 45)" filter="url(#shadow)">
    <rect width="90" height="40" rx="8" fill="url(#langGrad)" stroke="#2496ed" stroke-width="1.5"/>
    <text x="45" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Docker</text>
  </g>
  <g transform="translate(122, 45)" filter="url(#shadow)">
    <rect width="140" height="40" rx="8" fill="url(#langGrad)" stroke="#2496ed" stroke-width="1.5"/>
    <text x="70" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Docker Compose</text>
  </g>
  <g transform="translate(274, 45)" filter="url(#shadow)">
    <rect width="110" height="40" rx="8" fill="url(#langGrad)" stroke="#326ce5" stroke-width="1.5"/>
    <text x="55" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Kubernetes</text>
  </g>
  <g transform="translate(396, 45)" filter="url(#shadow)">
    <rect width="110" height="40" rx="8" fill="url(#langGrad)" stroke="#7b42bc" stroke-width="1.5"/>
    <text x="55" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Terraform</text>
  </g>
  <g transform="translate(518, 45)" filter="url(#shadow)">
    <rect width="150" height="40" rx="8" fill="url(#langGrad)" stroke="#2088ff" stroke-width="1.5"/>
    <text x="75" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">GitHub Actions</text>
  </g>
  <g transform="translate(680, 45)" filter="url(#shadow)">
    <rect width="80" height="40" rx="8" fill="url(#langGrad)" stroke="#0078d4" stroke-width="1.5"/>
    <text x="40" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Azure</text>
  </g>
  <!-- Second row -->
  <g transform="translate(20, 100)" filter="url(#shadow)">
    <rect width="80" height="40" rx="8" fill="url(#langGrad)" stroke="#fcc624" stroke-width="1.5"/>
    <text x="40" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Linux</text>
  </g>
  <g transform="translate(112, 100)" filter="url(#shadow)">
    <rect width="80" height="40" rx="8" fill="url(#langGrad)" stroke="#009639" stroke-width="1.5"/>
    <text x="40" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Nginx</text>
  </g>
  <g transform="translate(204, 100)" filter="url(#shadow)">
    <rect width="110" height="40" rx="8" fill="url(#langGrad)" stroke="#e6522c" stroke-width="1.5"/>
    <text x="55" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Prometheus</text>
  </g>
  <g transform="translate(326, 100)" filter="url(#shadow)">
    <rect width="90" height="40" rx="8" fill="url(#langGrad)" stroke="#f46800" stroke-width="1.5"/>
    <text x="45" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Grafana</text>
  </g>
</svg>

<!-- DATABASE -->
<svg width="500" height="130" viewBox="0 0 500 130" xmlns="http://www.w3.org/2000/svg">
  <text x="20" y="25" font-family="'SF Mono', monospace" font-size="11" fill="#8b949e" letter-spacing="3">DATABASE</text>
  <g transform="translate(20, 45)" filter="url(#shadow)">
    <rect width="110" height="40" rx="8" fill="url(#langGrad)" stroke="#336791" stroke-width="1.5"/>
    <text x="55" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">PostgreSQL</text>
  </g>
  <g transform="translate(142, 45)" filter="url(#shadow)">
    <rect width="110" height="40" rx="8" fill="url(#langGrad)" stroke="#cc2927" stroke-width="1.5"/>
    <text x="55" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">SQL Server</text>
  </g>
  <g transform="translate(264, 45)" filter="url(#shadow)">
    <rect width="80" height="40" rx="8" fill="url(#langGrad)" stroke="#003b57" stroke-width="1.5"/>
    <text x="40" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">SQLite</text>
  </g>
</svg>

<!-- AI -->
<svg width="800" height="130" viewBox="0 0 800 130" xmlns="http://www.w3.org/2000/svg">
  <text x="20" y="25" font-family="'SF Mono', monospace" font-size="11" fill="#8b949e" letter-spacing="3">AI & MACHINE LEARNING</text>
  <g transform="translate(20, 45)" filter="url(#shadow)">
    <rect width="100" height="40" rx="8" fill="url(#langGrad)" stroke="#00d4aa" stroke-width="1.5"/>
    <text x="50" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">LangGraph</text>
  </g>
  <g transform="translate(132, 45)" filter="url(#shadow)">
    <rect width="100" height="40" rx="8" fill="url(#langGrad)" stroke="#1c3c3c" stroke-width="1.5"/>
    <text x="50" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">LangChain</text>
  </g>
  <g transform="translate(244, 45)" filter="url(#shadow)">
    <rect width="70" height="40" rx="8" fill="url(#langGrad)" stroke="#f0f6fc" stroke-width="1.5"/>
    <text x="35" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">MCP</text>
  </g>
  <g transform="translate(326, 45)" filter="url(#shadow)">
    <rect width="60" height="40" rx="8" fill="url(#langGrad)" stroke="#ff6b6b" stroke-width="1.5"/>
    <text x="30" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">RAG</text>
  </g>
  <g transform="translate(398, 45)" filter="url(#shadow)">
    <rect width="80" height="40" rx="8" fill="url(#langGrad)" stroke="#10a37f" stroke-width="1.5"/>
    <text x="40" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">OpenAI</text>
  </g>
  <g transform="translate(490, 45)" filter="url(#shadow)">
    <rect width="70" height="40" rx="8" fill="url(#langGrad)" stroke="#cc785c" stroke-width="1.5"/>
    <text x="35" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Claude</text>
  </g>
  <g transform="translate(572, 45)" filter="url(#shadow)">
    <rect width="140" height="40" rx="8" fill="url(#langGrad)" stroke="#8b5cf6" stroke-width="1.5"/>
    <text x="70" y="25" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Vector Databases</text>
  </g>
</svg>
</div>
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 6: ANIMATED ARCHITECTURE SECTION                                   -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Animated system architecture diagram showing data flow.
  Uses SVG animations for packet movement and arrow pulsing.

  CUSTOMIZE: Add/remove layers, change labels, adjust colors.
-->
<div align="center">
🏗️ System Architecture

<svg width="500" height="600" viewBox="0 0 500 600" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="archBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#161b22"/>
    </linearGradient>
    <filter id="archGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
    <marker id="arrowhead" markerWidth="10" markerHeight="7" refX="9" refY="3.5" orient="auto">
      <polygon points="0 0, 10 3.5, 0 7" fill="#00d4aa"/>
    </marker>
  </defs>
  <!-- Background -->
  <rect width="500" height="600" rx="16" fill="url(#archBg)" stroke="#30363d" stroke-width="2"/>
  <!-- Browser Layer -->
  <rect x="150" y="30" width="200" height="50" rx="10" fill="#21262d" stroke="#58a6ff" stroke-width="2" filter="url(#archGlow)"/>
  <text x="250" y="60" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">🌐 Browser</text>
  <!-- Arrow 1 -->
  <line x1="250" y1="80" x2="250" y2="120" stroke="#00d4aa" stroke-width="2" marker-end="url(#arrowhead)" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" repeatCount="indefinite"/>
  </line>
  <!-- Packet animation -->
  <circle cx="250" cy="80" r="4" fill="#00d4aa">
    <animate attributeName="cy" values="80;120;80" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0;1" dur="2s" repeatCount="indefinite"/>
  </circle>
  <!-- Frontend Layer -->
  <rect x="150" y="130" width="200" height="50" rx="10" fill="#21262d" stroke="#f0883e" stroke-width="2" filter="url(#archGlow)"/>
  <text x="250" y="160" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">⚡ Frontend</text>
  <!-- Arrow 2 -->
  <line x1="250" y1="180" x2="250" y2="220" stroke="#00d4aa" stroke-width="2" marker-end="url(#arrowhead)" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" begin="0.3s" repeatCount="indefinite"/>
  </line>
  <circle cx="250" cy="180" r="4" fill="#00d4aa">
    <animate attributeName="cy" values="180;220;180" dur="2s" begin="0.3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0;1" dur="2s" begin="0.3s" repeatCount="indefinite"/>
  </circle>
  <!-- API Gateway Layer -->
  <rect x="150" y="230" width="200" height="50" rx="10" fill="#21262d" stroke="#a371f7" stroke-width="2" filter="url(#archGlow)"/>
  <text x="250" y="260" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">🔀 API Gateway</text>
  <!-- Arrow 3 -->
  <line x1="250" y1="280" x2="250" y2="320" stroke="#00d4aa" stroke-width="2" marker-end="url(#arrowhead)" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" begin="0.6s" repeatCount="indefinite"/>
  </line>
  <circle cx="250" cy="280" r="4" fill="#00d4aa">
    <animate attributeName="cy" values="280;320;280" dur="2s" begin="0.6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0;1" dur="2s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
  <!-- Backend Layer -->
  <rect x="150" y="330" width="200" height="50" rx="10" fill="#21262d" stroke="#3fb950" stroke-width="2" filter="url(#archGlow)"/>
  <text x="250" y="360" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">🔧 Backend</text>
  <!-- Arrow 4 -->
  <line x1="250" y1="380" x2="250" y2="420" stroke="#00d4aa" stroke-width="2" marker-end="url(#arrowhead)" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" begin="0.9s" repeatCount="indefinite"/>
  </line>
  <circle cx="250" cy="380" r="4" fill="#00d4aa">
    <animate attributeName="cy" values="380;420;380" dur="2s" begin="0.9s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0;1" dur="2s" begin="0.9s" repeatCount="indefinite"/>
  </circle>
  <!-- AI Agents Layer -->
  <rect x="150" y="430" width="200" height="50" rx="10" fill="#21262d" stroke="#ff6b6b" stroke-width="2" filter="url(#archGlow)"/>
  <text x="250" y="460" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">🤖 AI Agents</text>
  <!-- Arrow 5 -->
  <line x1="250" y1="480" x2="250" y2="520" stroke="#00d4aa" stroke-width="2" marker-end="url(#arrowhead)" opacity="0.6">
    <animate attributeName="opacity" values="0.6;1;0.6" dur="2s" begin="1.2s" repeatCount="indefinite"/>
  </line>
  <circle cx="250" cy="480" r="4" fill="#00d4aa">
    <animate attributeName="cy" values="480;520;480" dur="2s" begin="1.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="1;0;1" dur="2s" begin="1.2s" repeatCount="indefinite"/>
  </circle>
  <!-- Vector Database Layer -->
  <rect x="150" y="530" width="200" height="50" rx="10" fill="#21262d" stroke="#8b5cf6" stroke-width="2" filter="url(#archGlow)"/>
  <text x="250" y="560" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">🧠 Vector Database</text>
  <!-- Side connection to Cloud -->
  <path d="M 350 555 L 420 555 L 420 350 L 350 350" fill="none" stroke="#f0883e" stroke-width="2" stroke-dasharray="5,5" opacity="0.5">
    <animate attributeName="stroke-dashoffset" values="0;10" dur="1s" repeatCount="indefinite"/>
  </path>
  <!-- Cloud Infrastructure -->
  <rect x="360" y="320" width="120" height="50" rx="10" fill="#21262d" stroke="#f0883e" stroke-width="2" filter="url(#archGlow)"/>
  <text x="420" y="350" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="12" fill="#f0f6fc" font-weight="600">☁️ Cloud</text>
</svg>
</div>
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 4: CONTRIBUTION SNAKE                                              -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Animated GitHub contribution snake.

  SETUP REQUIRED:
  1. Create .github/workflows/snake.yml in your profile repo
  2. Use the Platane/snk GitHub Action (see below)
  3. The snake SVG will be generated in the output branch

  WORKFLOW FILE (.github/workflows/snake.yml):
  ───────────────────────────────────────────
  name: Generate Snake
  on:
    schedule: [cron: "0 0 * * *"]
    workflow_dispatch:
  jobs:
    build:
      runs-on: ubuntu-latest
      steps:
        - uses: Platane/snk@v3
          with:
            github_user_name: ${{ github.repository_owner }}
            outputs: |
              dist/github-snake-dark.svg?palette=github-dark
        - uses: crazy-max/ghaction-github-pages@v3
          with:
            target_branch: output
            build_dir: dist
          env:
            GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  ───────────────────────────────────────────

  CUSTOMIZE: Replace "YOUR_USERNAME" with your GitHub username.
-->
<div align="center">
🐍 Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-snake.svg"/>
  <img alt="github-snake" src="https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_USERNAME/output/github-snake.svg"/>
</picture>
</div>
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 7: WAKATIME CODING DASHBOARD                                       -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  WakaTime coding statistics dashboard.

  SETUP REQUIRED:
  1. Create a WakaTime account at https://wakatime.com
  2. Install the WakaTime plugin in your IDE
  3. Get your API key from https://wakatime.com/settings/account
  4. Use the WakaTime README Stats service or self-host

  Alternative: Use github-readme-stats with WakaTime integration:
  https://github.com/anuraghazra/github-readme-stats#wakatime-week-stats

  CUSTOMIZE: Replace "YOUR_USERNAME" and configure your WakaTime API key.
-->
<div align="center">
📊 Coding Dashboard

<!-- WakaTime Weekly Stats -->
<!-- 
  To enable: Visit https://github.com/anuraghazra/github-readme-stats 
  and follow the WakaTime setup instructions.

  Replace the URL below with your actual WakaTime stats endpoint.
-->
<img src="https://github-readme-stats.vercel.app/api/wakatime?username=YOUR_USERNAME&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00d4aa&text_color=f0f6fc&icon_color=58a6ff&layout=compact" alt="WakaTime Stats" width="60%"/>


<!-- Coding Activity Graph -->
<img src="https://github-readme-activity-graph.vercel.app/graph?username=YOUR_USERNAME&theme=github-dark&hide_border=true&bg_color=0d1117&color=00d4aa&line=58a6ff&point=f0883e" alt="Activity Graph" width="95%"/>
</div>
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 9: CURRENTLY BUILDING                                              -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Premium project cards with animated borders and glowing effects.
  Each card shows progress, tech stack, and status.

  CUSTOMIZE: Replace project names, descriptions, progress values, and tech stacks.
-->
<div align="center">
🚀 Currently Building

<table>
  <tr>
    <td>
      <svg width="380" height="200" viewBox="0 0 380 200" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="cardGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#161b22"/>
            <stop offset="100%" stop-color="#0d1117"/>
          </linearGradient>
          <linearGradient id="borderGrad1" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#00d4aa"/>
            <stop offset="50%" stop-color="#58a6ff"/>
            <stop offset="100%" stop-color="#00d4aa"/>
          </linearGradient>
        </defs>
plain
    <!-- Animated border -->
    <rect x="2" y="2" width="376" height="196" rx="14" fill="none" stroke="url(#borderGrad1)" stroke-width="2">
      <animate attributeName="stroke-dasharray" values="0,1200;1200,0;0,1200" dur="6s" repeatCount="indefinite"/>
    </rect>

    <rect x="4" y="4" width="372" height="192" rx="12" fill="url(#cardGrad1)"/>

    <!-- Icon -->
    <text x="30" y="45" font-size="24">🚀</text>
    <text x="60" y="42" font-family="'Segoe UI', sans-serif" font-size="16" fill="#f0f6fc" font-weight="700">AI Knowledge OS</text>

    <!-- Status badge -->
    <rect x="280" y="28" width="80" height="22" rx="11" fill="#238636"/>
    <text x="320" y="43" text-anchor="middle" font-family="'SF Mono', monospace" font-size="10" fill="#fff">ACTIVE</text>

    <!-- Description -->
    <text x="30" y="75" font-family="'Segoe UI', sans-serif" font-size="12" fill="#8b949e">Autonomous knowledge management</text>
    <text x="30" y="92" font-family="'Segoe UI', sans-serif" font-size="12" fill="#8b949e">system with AI agents and RAG</text>

    <!-- Tech stack -->
    <rect x="30" y="110" width="60" height="20" rx="4" fill="#21262d" stroke="#00d4aa" stroke-width="1"/>
    <text x="60" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#00d4aa">Python</text>

    <rect x="96" y="110" width="80" height="20" rx="4" fill="#21262d" stroke="#58a6ff" stroke-width="1"/>
    <text x="136" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#58a6ff">LangGraph</text>

    <rect x="182" y="110" width="70" height="20" rx="4" fill="#21262d" stroke="#8b5cf6" stroke-width="1"/>
    <text x="217" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#8b5cf6">Vector DB</text>

    <!-- Progress bar -->
    <text x="30" y="155" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">PROGRESS</text>
    <text x="340" y="155" font-family="'SF Mono', monospace" font-size="10" fill="#00d4aa">78%</text>
    <rect x="30" y="165" width="320" height="6" rx="3" fill="#21262d"/>
    <rect x="30" y="165" width="250" height="6" rx="3" fill="#00d4aa">
      <animate attributeName="width" values="240;260;240" dur="3s" repeatCount="indefinite"/>
    </rect>

    <!-- Glow effect -->
    <circle cx="190" cy="100" r="80" fill="url(#borderGrad1)" opacity="0.03">
      <animate attributeName="r" values="80;90;80" dur="4s" repeatCount="indefinite"/>
    </circle>
  </svg>
</td>
<td width="20"></td>
<td>
  <svg width="380" height="200" viewBox="0 0 380 200" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="cardGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#161b22"/>
        <stop offset="100%" stop-color="#0d1117"/>
      </linearGradient>
      <linearGradient id="borderGrad2" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#f0883e"/>
        <stop offset="50%" stop-color="#ff6b6b"/>
        <stop offset="100%" stop-color="#f0883e"/>
      </linearGradient>
    </defs>

    <rect x="2" y="2" width="376" height="196" rx="14" fill="none" stroke="url(#borderGrad2)" stroke-width="2">
      <animate attributeName="stroke-dasharray" values="0,1200;1200,0;0,1200" dur="6s" begin="1s" repeatCount="indefinite"/>
    </rect>

    <rect x="4" y="4" width="372" height="192" rx="12" fill="url(#cardGrad2)"/>

    <text x="30" y="45" font-size="24">⚡</text>
    <text x="60" y="42" font-family="'Segoe UI', sans-serif" font-size="16" fill="#f0f6fc" font-weight="700">Agent Framework</text>

    <rect x="280" y="28" width="80" height="22" rx="11" fill="#1f6feb"/>
    <text x="320" y="43" text-anchor="middle" font-family="'SF Mono', monospace" font-size="10" fill="#fff">BETA</text>

    <text x="30" y="75" font-family="'Segoe UI', sans-serif" font-size="12" fill="#8b949e">Modular AI agent orchestration</text>
    <text x="30" y="92" font-family="'Segoe UI', sans-serif" font-size="12" fill="#8b949e">platform with tool calling</text>

    <rect x="30" y="110" width="70" height="20" rx="4" fill="#21262d" stroke="#f0883e" stroke-width="1"/>
    <text x="65" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#f0883e">LangChain</text>

    <rect x="106" y="110" width="60" height="20" rx="4" fill="#21262d" stroke="#ff6b6b" stroke-width="1"/>
    <text x="136" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#ff6b6b">MCP</text>

    <rect x="172" y="110" width="70" height="20" rx="4" fill="#21262d" stroke="#00d4aa" stroke-width="1"/>
    <text x="207" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#00d4aa">FastAPI</text>

    <text x="30" y="155" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">PROGRESS</text>
    <text x="340" y="155" font-family="'SF Mono', monospace" font-size="10" fill="#f0883e">62%</text>
    <rect x="30" y="165" width="320" height="6" rx="3" fill="#21262d"/>
    <rect x="30" y="165" width="198" height="6" rx="3" fill="#f0883e">
      <animate attributeName="width" values="190;210;190" dur="3s" repeatCount="indefinite"/>
    </rect>

    <circle cx="190" cy="100" r="80" fill="url(#borderGrad2)" opacity="0.03">
      <animate attributeName="r" values="80;90;80" dur="4s" begin="1s" repeatCount="indefinite"/>
    </circle>
  </svg>
</td>
  </tr>
  <tr><td height="20"></td></tr>
  <tr>
    <td>
      <svg width="380" height="200" viewBox="0 0 380 200" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="cardGrad3" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#161b22"/>
            <stop offset="100%" stop-color="#0d1117"/>
          </linearGradient>
          <linearGradient id="borderGrad3" x1="0%" y1="0%" x2="100%" y2="100%">
            <stop offset="0%" stop-color="#8b5cf6"/>
            <stop offset="50%" stop-color="#a371f7"/>
            <stop offset="100%" stop-color="#8b5cf6"/>
          </linearGradient>
        </defs>
plain
    <rect x="2" y="2" width="376" height="196" rx="14" fill="none" stroke="url(#borderGrad3)" stroke-width="2">
      <animate attributeName="stroke-dasharray" values="0,1200;1200,0;0,1200" dur="6s" begin="2s" repeatCount="indefinite"/>
    </rect>

    <rect x="4" y="4" width="372" height="192" rx="12" fill="url(#cardGrad3)"/>

    <text x="30" y="45" font-size="24">🧠</text>
    <text x="60" y="42" font-family="'Segoe UI', sans-serif" font-size="16" fill="#f0f6fc" font-weight="700">Knowledge Graph</text>

    <rect x="280" y="28" width="80" height="22" rx="11" fill="#8957e5"/>
    <text x="320" y="43" text-anchor="middle" font-family="'SF Mono', monospace" font-size="10" fill="#fff">ALPHA</text>

    <text x="30" y="75" font-family="'Segoe UI', sans-serif" font-size="12" fill="#8b949e">Graph-based knowledge representation</text>
    <text x="30" y="92" font-family="'Segoe UI', sans-serif" font-size="12" fill="#8b949e">with semantic search capabilities</text>

    <rect x="30" y="110" width="70" height="20" rx="4" fill="#21262d" stroke="#8b5cf6" stroke-width="1"/>
    <text x="65" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#8b5cf6">Neo4j</text>

    <rect x="106" y="110" width="60" height="20" rx="4" fill="#21262d" stroke="#a371f7" stroke-width="1"/>
    <text x="136" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#a371f7">RAG</text>

    <rect x="172" y="110" width="80" height="20" rx="4" fill="#21262d" stroke="#00d4aa" stroke-width="1"/>
    <text x="212" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#00d4aa">Python</text>

    <text x="30" y="155" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">PROGRESS</text>
    <text x="340" y="155" font-family="'SF Mono', monospace" font-size="10" fill="#8b5cf6">45%</text>
    <rect x="30" y="165" width="320" height="6" rx="3" fill="#21262d"/>
    <rect x="30" y="165" width="144" height="6" rx="3" fill="#8b5cf6">
      <animate attributeName="width" values="140;150;140" dur="3s" repeatCount="indefinite"/>
    </rect>

    <circle cx="190" cy="100" r="80" fill="url(#borderGrad3)" opacity="0.03">
      <animate attributeName="r" values="80;90;80" dur="4s" begin="2s" repeatCount="indefinite"/>
    </circle>
  </svg>
</td>
<td width="20"></td>
<td>
  <svg width="380" height="200" viewBox="0 0 380 200" xmlns="http://www.w3.org/2000/svg">
    <defs>
      <linearGradient id="cardGrad4" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#161b22"/>
        <stop offset="100%" stop-color="#0d1117"/>
      </linearGradient>
      <linearGradient id="borderGrad4" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" stop-color="#2496ed"/>
        <stop offset="50%" stop-color="#58a6ff"/>
        <stop offset="100%" stop-color="#2496ed"/>
      </linearGradient>
    </defs>

    <rect x="2" y="2" width="376" height="196" rx="14" fill="none" stroke="url(#borderGrad4)" stroke-width="2">
      <animate attributeName="stroke-dasharray" values="0,1200;1200,0;0,1200" dur="6s" begin="3s" repeatCount="indefinite"/>
    </rect>

    <rect x="4" y="4" width="372" height="192" rx="12" fill="url(#cardGrad4)"/>

    <text x="30" y="45" font-size="24">🐳</text>
    <text x="60" y="42" font-family="'Segoe UI', sans-serif" font-size="16" fill="#f0f6fc" font-weight="700">DevOps Handbook</text>

    <rect x="280" y="28" width="80" height="22" rx="11" fill="#238636"/>
    <text x="320" y="43" text-anchor="middle" font-family="'SF Mono', monospace" font-size="10" fill="#fff">ACTIVE</text>

    <text x="30" y="75" font-family="'Segoe UI', sans-serif" font-size="12" fill="#8b949e">Infrastructure as code templates</text>
    <text x="30" y="92" font-family="'Segoe UI', sans-serif" font-size="12" fill="#8b949e">and deployment playbooks</text>

    <rect x="30" y="110" width="70" height="20" rx="4" fill="#21262d" stroke="#2496ed" stroke-width="1"/>
    <text x="65" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#2496ed">Docker</text>

    <rect x="106" y="110" width="80" height="20" rx="4" fill="#21262d" stroke="#326ce5" stroke-width="1"/>
    <text x="146" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#326ce5">K8s</text>

    <rect x="192" y="110" width="80" height="20" rx="4" fill="#21262d" stroke="#7b42bc" stroke-width="1"/>
    <text x="232" y="124" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#7b42bc">Terraform</text>

    <text x="30" y="155" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">PROGRESS</text>
    <text x="340" y="155" font-family="'SF Mono', monospace" font-size="10" fill="#2496ed">91%</text>
    <rect x="30" y="165" width="320" height="6" rx="3" fill="#21262d"/>
    <rect x="30" y="165" width="291" height="6" rx="3" fill="#2496ed">
      <animate attributeName="width" values="285;295;285" dur="3s" repeatCount="indefinite"/>
    </rect>

    <circle cx="190" cy="100" r="80" fill="url(#borderGrad4)" opacity="0.03">
      <animate attributeName="r" values="80;90;80" dur="4s" begin="3s" repeatCount="indefinite"/>
    </circle>
  </svg>
</td>
  </tr>
</table>
</div>
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 10: FEATURED PROJECTS                                              -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Large project cards with animated previews, architecture, technologies, 
  metrics, and links.

  CUSTOMIZE: Replace with your actual repositories. Update:
  - Project names and descriptions
  - Tech stack badges
  - GitHub repo links
  - Live demo links
  - Star counts and fork counts
-->
<div align="center">
🎯 Featured Projects

<table>
  <tr>
    <td width="50%">
      <a href="https://github.com/YOUR_USERNAME/ai-knowledge-os">
        <svg width="100%" height="280" viewBox="0 0 500 280" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="projBg1" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" stop-color="#161b22"/>
              <stop offset="100%" stop-color="#0d1117"/>
            </linearGradient>
            <linearGradient id="projBorder1" x1="0%" y1="0%" x2="100%" y2="0%">
              <stop offset="0%" stop-color="#00d4aa"/>
              <stop offset="100%" stop-color="#58a6ff"/>
            </linearGradient>
          </defs>
plain
      <rect width="500" height="280" rx="16" fill="url(#projBg1)" stroke="#30363d" stroke-width="1"/>

      <!-- Top accent line -->
      <rect x="0" y="0" width="500" height="3" rx="1.5" fill="url(#projBorder1)"/>

      <!-- Project icon -->
      <text x="30" y="55" font-size="32">🚀</text>
      <text x="75" y="50" font-family="'Segoe UI', sans-serif" font-size="20" fill="#f0f6fc" font-weight="700">AI Knowledge OS</text>

      <!-- Stars & Forks -->
      <text x="380" y="45" font-family="'SF Mono', monospace" font-size="12" fill="#f0883e">⭐ 128</text>
      <text x="440" y="45" font-family="'SF Mono', monospace" font-size="12" fill="#8b949e">🍴 24</text>

      <!-- Description -->
      <text x="30" y="90" font-family="'Segoe UI', sans-serif" font-size="13" fill="#8b949e">Autonomous knowledge management platform</text>
      <text x="30" y="110" font-family="'Segoe UI', sans-serif" font-size="13" fill="#8b949e">powered by AI agents, RAG, and vector databases.</text>

      <!-- Architecture mini-diagram -->
      <rect x="30" y="130" width="440" height="60" rx="8" fill="#0d1117" stroke="#21262d" stroke-width="1"/>
      <text x="45" y="150" font-family="'SF Mono', monospace" font-size="9" fill="#8b949e">ARCHITECTURE</text>
      <rect x="45" y="160" width="60" height="18" rx="4" fill="#21262d" stroke="#58a6ff" stroke-width="1"/>
      <text x="75" y="173" text-anchor="middle" font-family="'SF Mono', monospace" font-size="8" fill="#58a6ff">Next.js</text>
      <text x="110" y="170" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">→</text>
      <rect x="125" y="160" width="60" height="18" rx="4" fill="#21262d" stroke="#00d4aa" stroke-width="1"/>
      <text x="155" y="173" text-anchor="middle" font-family="'SF Mono', monospace" font-size="8" fill="#00d4aa">FastAPI</text>
      <text x="190" y="170" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">→</text>
      <rect x="205" y="160" width="70" height="18" rx="4" fill="#21262d" stroke="#8b5cf6" stroke-width="1"/>
      <text x="240" y="173" text-anchor="middle" font-family="'SF Mono', monospace" font-size="8" fill="#8b5cf6">LangGraph</text>
      <text x="280" y="170" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">→</text>
      <rect x="295" y="160" width="70" height="18" rx="4" fill="#21262d" stroke="#f0883e" stroke-width="1"/>
      <text x="330" y="173" text-anchor="middle" font-family="'SF Mono', monospace" font-size="8" fill="#f0883e">Vector DB</text>

      <!-- Tech tags -->
      <rect x="30" y="210" width="50" height="20" rx="4" fill="#21262d"/>
      <text x="55" y="224" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#00d4aa">Python</text>

      <rect x="88" y="210" width="70" height="20" rx="4" fill="#21262d"/>
      <text x="123" y="224" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#58a6ff">LangGraph</text>

      <rect x="166" y="210" width="60" height="20" rx="4" fill="#21262d"/>
      <text x="196" y="224" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#8b5cf6">RAG</text>

      <rect x="234" y="210" width="70" height="20" rx="4" fill="#21262d"/>
      <text x="269" y="224" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#f0883e">Docker</text>

      <!-- Links -->
      <text x="30" y="260" font-family="'SF Mono', monospace" font-size="11" fill="#58a6ff">📎 github.com/YOUR_USERNAME/ai-knowledge-os</text>
    </svg>
  </a>
</td>
<td width="50%">
  <a href="https://github.com/YOUR_USERNAME/agent-framework">
    <svg width="100%" height="280" viewBox="0 0 500 280" xmlns="http://www.w3.org/2000/svg">
      <defs>
        <linearGradient id="projBg2" x1="0%" y1="0%" x2="100%" y2="100%">
          <stop offset="0%" stop-color="#161b22"/>
          <stop offset="100%" stop-color="#0d1117"/>
        </linearGradient>
        <linearGradient id="projBorder2" x1="0%" y1="0%" x2="100%" y2="0%">
          <stop offset="0%" stop-color="#f0883e"/>
          <stop offset="100%" stop-color="#ff6b6b"/>
        </linearGradient>
      </defs>

      <rect width="500" height="280" rx="16" fill="url(#projBg2)" stroke="#30363d" stroke-width="1"/>
      <rect x="0" y="0" width="500" height="3" rx="1.5" fill="url(#projBorder2)"/>

      <text x="30" y="55" font-size="32">⚡</text>
      <text x="75" y="50" font-family="'Segoe UI', sans-serif" font-size="20" fill="#f0f6fc" font-weight="700">Agent Framework</text>

      <text x="380" y="45" font-family="'SF Mono', monospace" font-size="12" fill="#f0883e">⭐ 86</text>
      <text x="440" y="45" font-family="'SF Mono', monospace" font-size="12" fill="#8b949e">🍴 18</text>

      <text x="30" y="90" font-family="'Segoe UI', sans-serif" font-size="13" fill="#8b949e">Modular AI agent orchestration platform</text>
      <text x="30" y="110" font-family="'Segoe UI', sans-serif" font-size="13" fill="#8b949e">with tool calling and state management.</text>

      <rect x="30" y="130" width="440" height="60" rx="8" fill="#0d1117" stroke="#21262d" stroke-width="1"/>
      <text x="45" y="150" font-family="'SF Mono', monospace" font-size="9" fill="#8b949e">ARCHITECTURE</text>
      <rect x="45" y="160" width="70" height="18" rx="4" fill="#21262d" stroke="#f0883e" stroke-width="1"/>
      <text x="80" y="173" text-anchor="middle" font-family="'SF Mono', monospace" font-size="8" fill="#f0883e">LangChain</text>
      <text x="120" y="170" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">→</text>
      <rect x="135" y="160" width="60" height="18" rx="4" fill="#21262d" stroke="#ff6b6b" stroke-width="1"/>
      <text x="165" y="173" text-anchor="middle" font-family="'SF Mono', monospace" font-size="8" fill="#ff6b6b">MCP</text>
      <text x="200" y="170" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">→</text>
      <rect x="215" y="160" width="70" height="18" rx="4" fill="#21262d" stroke="#00d4aa" stroke-width="1"/>
      <text x="250" y="173" text-anchor="middle" font-family="'SF Mono', monospace" font-size="8" fill="#00d4aa">FastAPI</text>
      <text x="290" y="170" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">→</text>
      <rect x="305" y="160" width="70" height="18" rx="4" fill="#21262d" stroke="#58a6ff" stroke-width="1"/>
      <text x="340" y="173" text-anchor="middle" font-family="'SF Mono', monospace" font-size="8" fill="#58a6ff">Redis</text>

      <rect x="30" y="210" width="60" height="20" rx="4" fill="#21262d"/>
      <text x="60" y="224" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#f0883e">Python</text>

      <rect x="98" y="210" width="70" height="20" rx="4" fill="#21262d"/>
      <text x="133" y="224" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#ff6b6b">LangChain</text>

      <rect x="176" y="210" width="50" height="20" rx="4" fill="#21262d"/>
      <text x="201" y="224" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#00d4aa">MCP</text>

      <rect x="234" y="210" width="70" height="20" rx="4" fill="#21262d"/>
      <text x="269" y="224" text-anchor="middle" font-family="'SF Mono', monospace" font-size="9" fill="#58a6ff">Docker</text>

      <text x="30" y="260" font-family="'SF Mono', monospace" font-size="11" fill="#58a6ff">📎 github.com/YOUR_USERNAME/agent-framework</text>
    </svg>
  </a>
</td>
  </tr>
</table>
</div>
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 11: GITHUB ANALYTICS                                               -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Beautiful statistics dashboard using github-readme-stats and streak-stats.

  SETUP: These are dynamic images that update automatically.
  Just replace "YOUR_USERNAME" with your GitHub username.

  CUSTOMIZE: 
  - Change theme parameter (github_dark, radical, tokyonight, etc.)
  - Adjust bg_color, title_color, text_color
  - Add/remove stats with hide/show parameters

  Available themes: https://github.com/anuraghazra/github-readme-stats/blob/master/themes/README.md
-->
<div align="center">
📈 GitHub Analytics

<table width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00d4aa&text_color=f0f6fc&icon_color=58a6ff&ring_color=00d4aa&include_all_commits=true&count_private=true" alt="GitHub Stats" width="100%"/>
    </td>
    <td width="50%" align="center">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=github-dark-blue&hide_border=true&background=0d1117&stroke=30363d&ring=00d4aa&fire=f0883e&currStreakLabel=00d4aa&sideLabels=8b949e&currStreakNum=f0f6fc&sideNums=f0f6fc" alt="GitHub Streak" width="100%"/>
    </td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <br>
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=00d4aa&text_color=f0f6fc&layout=compact&langs_count=10&hide=html,css" alt="Top Languages" width="50%"/>
    </td>
  </tr>
</table>

<!-- GitHub Trophies -->
<img src="https://github-profile-trophy.vercel.app/?username=YOUR_USERNAME&theme=onestar&no-frame=true&no-bg=true&margin-w=15&margin-h=15&column=7" alt="GitHub Trophies" width="100%"/>
</div>
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 12: TIMELINE                                                       -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Animated journey timeline showing career progression.
  Uses SVG with staggered fade-in animations.

  CUSTOMIZE: Update milestones, dates, and descriptions to match your journey.
-->
<div align="center">
🛤️ Journey

<svg width="600" height="500" viewBox="0 0 600 500" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="timeBg" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#0d1117"/>
      <stop offset="100%" stop-color="#161b22"/>
    </linearGradient>
    <filter id="timeGlow">
      <feGaussianBlur stdDeviation="2" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <rect width="600" height="500" rx="16" fill="url(#timeBg)" stroke="#30363d" stroke-width="2"/>
  <!-- Central timeline line -->
  <line x1="300" y1="50" x2="300" y2="460" stroke="#21262d" stroke-width="3"/>
  <!-- Animated progress line -->
  <line x1="300" y1="50" x2="300" y2="460" stroke="#00d4aa" stroke-width="3" stroke-dasharray="5,5" opacity="0.6">
    <animate attributeName="stroke-dashoffset" values="0;20" dur="2s" repeatCount="indefinite"/>
  </line>
  <!-- Milestone 1: Started Programming -->
  <circle cx="300" cy="70" r="8" fill="#00d4aa" filter="url(#timeGlow)"/>
  <circle cx="300" cy="70" r="12" fill="none" stroke="#00d4aa" stroke-width="2" opacity="0.3">
    <animate attributeName="r" values="12;16;12" dur="2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0;0.3" dur="2s" repeatCount="indefinite"/>
  </circle>
  <text x="270" y="55" text-anchor="end" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">2018</text>
  <text x="320" y="65" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Started Programming</text>
  <text x="320" y="82" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8b949e">First line of code in C</text>
  <!-- Milestone 2: University -->
  <circle cx="300" cy="140" r="8" fill="#58a6ff" filter="url(#timeGlow)"/>
  <circle cx="300" cy="140" r="12" fill="none" stroke="#58a6ff" stroke-width="2" opacity="0.3">
    <animate attributeName="r" values="12;16;12" dur="2s" begin="0.3s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0;0.3" dur="2s" begin="0.3s" repeatCount="indefinite"/>
  </circle>
  <text x="270" y="125" text-anchor="end" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">2020</text>
  <text x="320" y="135" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">University</text>
  <text x="320" y="152" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8b949e">Computer & Communications Engineering</text>
  <!-- Milestone 3: First Internship -->
  <circle cx="300" cy="210" r="8" fill="#f0883e" filter="url(#timeGlow)"/>
  <circle cx="300" cy="210" r="12" fill="none" stroke="#f0883e" stroke-width="2" opacity="0.3">
    <animate attributeName="r" values="12;16;12" dur="2s" begin="0.6s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0;0.3" dur="2s" begin="0.6s" repeatCount="indefinite"/>
  </circle>
  <text x="270" y="195" text-anchor="end" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">2022</text>
  <text x="320" y="205" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">First Internship</text>
  <text x="320" y="222" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8b949e">Full Stack Development</text>
  <!-- Milestone 4: Open Source -->
  <circle cx="300" cy="280" r="8" fill="#a371f7" filter="url(#timeGlow)"/>
  <circle cx="300" cy="280" r="12" fill="none" stroke="#a371f7" stroke-width="2" opacity="0.3">
    <animate attributeName="r" values="12;16;12" dur="2s" begin="0.9s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0;0.3" dur="2s" begin="0.9s" repeatCount="indefinite"/>
  </circle>
  <text x="270" y="265" text-anchor="end" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">2023</text>
  <text x="320" y="275" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">Open Source</text>
  <text x="320" y="292" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8b949e">Contributing to the community</text>
  <!-- Milestone 5: DevOps -->
  <circle cx="300" cy="350" r="8" fill="#3fb950" filter="url(#timeGlow)"/>
  <circle cx="300" cy="350" r="12" fill="none" stroke="#3fb950" stroke-width="2" opacity="0.3">
    <animate attributeName="r" values="12;16;12" dur="2s" begin="1.2s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0;0.3" dur="2s" begin="1.2s" repeatCount="indefinite"/>
  </circle>
  <text x="270" y="335" text-anchor="end" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">2024</text>
  <text x="320" y="345" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">DevOps</text>
  <text x="320" y="362" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8b949e">Infrastructure & Automation</text>
  <!-- Milestone 6: AI Systems -->
  <circle cx="300" cy="420" r="8" fill="#ff6b6b" filter="url(#timeGlow)"/>
  <circle cx="300" cy="420" r="12" fill="none" stroke="#ff6b6b" stroke-width="2" opacity="0.3">
    <animate attributeName="r" values="12;16;12" dur="2s" begin="1.5s" repeatCount="indefinite"/>
    <animate attributeName="opacity" values="0.3;0;0.3" dur="2s" begin="1.5s" repeatCount="indefinite"/>
  </circle>
  <text x="270" y="405" text-anchor="end" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">2025</text>
  <text x="320" y="415" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">AI Systems</text>
  <text x="320" y="432" font-family="'Segoe UI', sans-serif" font-size="11" fill="#8b949e">Building intelligent agents</text>
  <!-- Future -->
  <circle cx="300" cy="480" r="6" fill="#21262d" stroke="#8b949e" stroke-width="2" stroke-dasharray="3,3"/>
  <text x="270" y="475" text-anchor="end" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e">NEXT</text>
  <text x="320" y="480" font-family="'Segoe UI', sans-serif" font-size="13" fill="#8b949e" font-weight="600" font-style="italic">Future Startup...</text>
</svg>
</div>
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 13: PHILOSOPHY                                                     -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Minimal, memorable quote section.

  CUSTOMIZE: Replace with your own philosophy or favorite quote.
-->
<div align="center">

<svg width="800" height="120" viewBox="0 0 800 120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="philGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00d4aa" stop-opacity="0"/>
      <stop offset="20%" stop-color="#00d4aa" stop-opacity="0.3"/>
      <stop offset="50%" stop-color="#00d4aa" stop-opacity="0.6"/>
      <stop offset="80%" stop-color="#00d4aa" stop-opacity="0.3"/>
      <stop offset="100%" stop-color="#00d4aa" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <rect width="800" height="120" rx="12" fill="#0d1117" stroke="#21262d" stroke-width="1"/>
  <!-- Decorative quote marks -->
<text x="40" y="50" font-family="'Georgia', serif" font-size="48" fill="#00d4aa" opacity="0.2">
<text x="750" y="100" font-family="'Georgia', serif" font-size="48" fill="#00d4aa" opacity="0.2">
  <!-- Quote text -->
  <text x="400" y="55" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="20" fill="#f0f6fc" font-weight="300" letter-spacing="1">
    Build systems that outlive your attention.
  </text>
  <!-- Subtle glow line -->
  <line x1="200" y1="80" x2="600" y2="80" stroke="url(#philGrad)" stroke-width="1"/>
</svg>


</div>
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 14: CONTACT SECTION                                                -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Premium glassmorphism contact cards.
  No ugly badges — clean, minimal design.

  CUSTOMIZE: Update all links, usernames, and email addresses.
-->
<div align="center">
📡 Connect

<table>
  <tr>
    <td>
      <a href="https://github.com/YOUR_USERNAME">
        <svg width="180" height="80" viewBox="0 0 180 80" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="contactBg1" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" stop-color="#161b22"/>
              <stop offset="100%" stop-color="#0d1117"/>
            </linearGradient>
          </defs>
          <rect width="180" height="80" rx="12" fill="url(#contactBg1)" stroke="#30363d" stroke-width="1.5"/>
          <text x="90" y="30" text-anchor="middle" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e" letter-spacing="2">GITHUB</text>
          <text x="90" y="55" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">@YOUR_USERNAME</text>
          <circle cx="20" cy="40" r="6" fill="#f0f6fc"/>
          <circle cx="20" cy="37" r="3" fill="#0d1117"/>
          <path d="M 17 43 Q 20 46 23 43" stroke="#0d1117" stroke-width="1.5" fill="none"/>
        </svg>
      </a>
    </td>
    <td width="12"></td>
    <td>
      <a href="https://linkedin.com/in/YOUR_LINKEDIN">
        <svg width="180" height="80" viewBox="0 0 180 80" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="contactBg2" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" stop-color="#161b22"/>
              <stop offset="100%" stop-color="#0d1117"/>
            </linearGradient>
          </defs>
          <rect width="180" height="80" rx="12" fill="url(#contactBg2)" stroke="#30363d" stroke-width="1.5"/>
          <text x="90" y="30" text-anchor="middle" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e" letter-spacing="2">LINKEDIN</text>
          <text x="90" y="55" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">/in/YOUR_NAME</text>
          <rect x="14" y="34" width="12" height="12" rx="2" fill="#0a66c2"/>
          <text x="20" y="44" text-anchor="middle" font-family="'Arial', sans-serif" font-size="10" fill="#fff" font-weight="700">in</text>
        </svg>
      </a>
    </td>
    <td width="12"></td>
    <td>
      <a href="https://YOUR_PORTFOLIO.com">
        <svg width="180" height="80" viewBox="0 0 180 80" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="contactBg3" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" stop-color="#161b22"/>
              <stop offset="100%" stop-color="#0d1117"/>
            </linearGradient>
          </defs>
          <rect width="180" height="80" rx="12" fill="url(#contactBg3)" stroke="#30363d" stroke-width="1.5"/>
          <text x="90" y="30" text-anchor="middle" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e" letter-spacing="2">PORTFOLIO</text>
          <text x="90" y="55" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="14" fill="#f0f6fc" font-weight="600">yourportfolio.com</text>
          <circle cx="20" cy="40" r="8" fill="none" stroke="#00d4aa" stroke-width="2"/>
          <text x="20" y="44" text-anchor="middle" font-family="'SF Mono', monospace" font-size="10" fill="#00d4aa">&lt;/&gt;</text>
        </svg>
      </a>
    </td>
    <td width="12"></td>
    <td>
      <a href="mailto:your.email@example.com">
        <svg width="180" height="80" viewBox="0 0 180 80" xmlns="http://www.w3.org/2000/svg">
          <defs>
            <linearGradient id="contactBg4" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" stop-color="#161b22"/>
              <stop offset="100%" stop-color="#0d1117"/>
            </linearGradient>
          </defs>
          <rect width="180" height="80" rx="12" fill="url(#contactBg4)" stroke="#30363d" stroke-width="1.5"/>
          <text x="90" y="30" text-anchor="middle" font-family="'SF Mono', monospace" font-size="10" fill="#8b949e" letter-spacing="2">EMAIL</text>
          <text x="90" y="55" text-anchor="middle" font-family="'Segoe UI', sans-serif" font-size="13" fill="#f0f6fc" font-weight="600">your@email.com</text>
          <rect x="14" y="36" width="14" height="10" rx="2" fill="none" stroke="#f0883e" stroke-width="1.5"/>
          <path d="M 14 36 L 21 42 L 28 36" stroke="#f0883e" stroke-width="1.5" fill="none"/>
        </svg>
      </a>
    </td>
  </tr>
</table>


<!-- Visitor Counter (Optional) -->
<!-- 
  Uncomment to enable visitor counting.
  Replace with your own counter service if preferred.
-->
<!-- <img src="https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=00d4aa&style=flat-square&label=PROFILE+VIEWS" alt="Profile Views"/> -->
</div>
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- SECTION 15: HIDDEN EASTER EGGS                                             -->
<!-- ════════════════════════════════════════════════════════════════════════════ -->
<!-- 
  Fun interactive surprises hidden throughout the README.

  EASTER EGG 1: Konami Code
  Try pressing ↑↑↓↓←→←→BA on your keyboard (in some browsers).

  EASTER EGG 2: Hidden Terminal Command
  Look for the secret command in the terminal section above.

  EASTER EGG 3: ASCII Art (Hidden below)

  EASTER EGG 4: Random Quote Generator (Commented out — enable if desired)
-->
<!-- 
  ╔══════════════════════════════════════════════════════════════════════════════╗
  ║  EASTER EGG: SECRET ASCII ART                                                ║
  ║  This section is invisible in normal rendering but visible in raw markdown   ║
  ╚══════════════════════════════════════════════════════════════════════════════╝
-->
<!--

    ███████╗██╗   ██╗███████╗████████╗███████╗███╗   ███╗
    ██╔════╝╚██╗ ██╔╝██╔════╝╚══██╔══╝██╔════╝████╗ ████║
    ███████╗ ╚████╔╝ ███████╗   ██║   █████╗  ██╔████╔██║
    ╚════██║  ╚██╔╝  ╚════██║   ██║   ██╔══╝  ██║╚██╔╝██║
    ███████║   ██║   ███████║   ██║   ███████╗██║ ╚═╝ ██║
    ╚══════╝   ╚═╝   ╚══════╝   ╚═╝   ╚══════╝╚═╝     ╚═╝

    You found the secret section! 

    Here is a hidden command for you:

    $ curl -s https://api.github.com/users/YOUR_USERNAME | jq '.bio'

    Keep exploring. The best developers are the most curious ones.

-->
<!-- 
  ╔══════════════════════════════════════════════════════════════════════════════╗
  ║  EASTER EGG: RANDOM QUOTE (Enable by uncommenting below)                     ║
  ║  This fetches a random programming quote on each load.                       ║
  ╚══════════════════════════════════════════════════════════════════════════════╝
-->
<!-- 
[![Random Quote](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)](https://github.com/piyushsuthar/github-readme-quotes)
-->

<div align="center">
<!-- Footer wave -->
<svg width="100%" height="60" viewBox="0 0 1200 60" xmlns="http://www.w3.org/2000/svg" preserveAspectRatio="none">
  <path d="M0,30 Q300,0 600,30 T1200,30 L1200,60 L0,60 Z" fill="#161b22" opacity="0.5">
    <animate attributeName="d" values="M0,30 Q300,0 600,30 T1200,30 L1200,60 L0,60 Z;M0,30 Q300,60 600,30 T1200,30 L1200,60 L0,60 Z;M0,30 Q300,0 600,30 T1200,30 L1200,60 L0,60 Z" dur="6s" repeatCount="indefinite"/>
  </path>
  <path d="M0,40 Q300,10 600,40 T1200,40 L1200,60 L0,60 Z" fill="#0d1117" opacity="0.3">
    <animate attributeName="d" values="M0,40 Q300,10 600,40 T1200,40 L1200,60 L0,60 Z;M0,40 Q300,70 600,40 T1200,40 L1200,60 L0,60 Z;M0,40 Q300,10 600,40 T1200,40 L1200,60 L0,60 Z" dur="8s" repeatCount="indefinite"/>
  </path>
</svg>

<!-- Final signature -->
<svg width="400" height="40" viewBox="0 0 400 40" xmlns="http://www.w3.org/2000/svg">
  <text x="200" y="25" text-anchor="middle" font-family="'SF Mono', monospace" font-size="11" fill="#30363d" letter-spacing="4">
    BUILT WITH CODE AND CAFFEINE
    <animate attributeName="opacity" values="0.3;0.6;0.3" dur="4s" repeatCount="indefinite"/>
  </text>
</svg>
</div>
<!-- 
  ╔══════════════════════════════════════════════════════════════════════════════╗
  ║  END OF README                                                               ║
  ║  Thank you for exploring!                                                    ║
  ╚══════════════════════════════════════════════════════════════════════════════╝
-->
