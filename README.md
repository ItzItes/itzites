<div align="center">

<!-- Animated Name with Star Background -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,14,18,20,24&height=200&section=header&text=ITES&fontSize=90&fontColor=fff&animation=twinkling&fontAlignY=35&desc=Software%20Developer&descAlignY=55&descSize=20" width="100%"/>

<br/>

<!-- Terminal Animation SVG -->
<svg width="600" height="120" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes typewriter1 {
        0% { width: 0; }
        50% { width: 0; }
        100% { width: 280px; }
      }
      @keyframes typewriter2 {
        0%, 50% { width: 0; }
        100% { width: 180px; }
      }
      @keyframes blink {
        0%, 100% { opacity: 1; }
        50% { opacity: 0; }
      }
      @keyframes glow {
        0%, 100% { filter: drop-shadow(0 0 5px #0ff) drop-shadow(0 0 10px #0ff); }
        50% { filter: drop-shadow(0 0 10px #0ff) drop-shadow(0 0 20px #0ff); }
      }
      .terminal-bg {
        fill: #0a0e27;
        stroke: #00ffff;
        stroke-width: 2;
        filter: drop-shadow(0 0 10px #00ffff);
      }
      .prompt {
        fill: #ff00ff;
        font-family: 'Courier New', monospace;
        font-size: 18px;
        font-weight: bold;
      }
      .code {
        fill: #00ff00;
        font-family: 'Courier New', monospace;
        font-size: 18px;
        overflow: hidden;
        white-space: nowrap;
      }
      .output {
        fill: #00ffff;
        font-family: 'Courier New', monospace;
        font-size: 18px;
        animation: glow 2s infinite;
      }
      .cursor {
        fill: #00ffff;
        animation: blink 1s infinite;
      }
      .line1 {
        animation: typewriter1 3s steps(30) forwards;
      }
      .line2 {
        animation: typewriter2 3s steps(20) forwards;
      }
    </style>
  </defs>
  
  <!-- Terminal Window -->
  <rect class="terminal-bg" x="10" y="10" width="580" height="100" rx="5"/>
  
  <!-- Terminal Header Dots -->
  <circle cx="30" cy="25" r="5" fill="#ff5f56"/>
  <circle cx="50" cy="25" r="5" fill="#ffbd2e"/>
  <circle cx="70" cy="25" r="5" fill="#27c93f"/>
  
  <!-- Command Line 1 -->
  <text class="prompt" x="25" y="55">&gt;</text>
  <clipPath id="clip1">
    <rect x="45" y="38" width="0" height="20" class="line1"/>
  </clipPath>
  <text class="code" x="45" y="55" clip-path="url(#clip1)">print("Hello, World!")</text>
  
  <!-- Command Line 2 -->
  <text class="prompt" x="25" y="85">&gt;</text>
  <clipPath id="clip2">
    <rect x="45" y="68" width="0" height="20" class="line2"/>
  </clipPath>
  <text class="output" x="45" y="85" clip-path="url(#clip2)">Hello, World!</text>
</svg>

<br/><br/>

<!-- Snake Game Animation -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/itzites/itzites/output/github-contribution-grid-snake-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/itzites/itzites/output/github-contribution-grid-snake.svg">
  <img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/itzites/itzites/output/github-contribution-grid-snake.svg">
</picture>

<br/><br/>

<!-- Cyberpunk Status Badge -->
<svg width="300" height="80" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      @keyframes neon-pulse {
        0%, 100% { 
          filter: drop-shadow(0 0 5px #ff00ff) drop-shadow(0 0 10px #ff00ff) drop-shadow(0 0 15px #ff00ff);
        }
        50% { 
          filter: drop-shadow(0 0 10px #ff00ff) drop-shadow(0 0 20px #ff00ff) drop-shadow(0 0 30px #ff00ff);
        }
      }
      @keyframes slide {
        0% { transform: translateX(-100%); }
        100% { transform: translateX(100%); }
      }
      .status-bg {
        fill: #0a0e27;
        stroke: #ff00ff;
        stroke-width: 3;
        animation: neon-pulse 2s infinite;
      }
      .status-text {
        fill: #00ffff;
        font-family: 'Courier New', monospace;
        font-size: 28px;
        font-weight: bold;
        text-transform: uppercase;
        letter-spacing: 3px;
      }
      .glitch {
        fill: #ff00ff;
        font-family: 'Courier New', monospace;
        font-size: 12px;
        opacity: 0.7;
      }
      .scan-line {
        fill: none;
        stroke: #00ffff;
        stroke-width: 1;
        opacity: 0.3;
        animation: slide 3s linear infinite;
      }
    </style>
    <linearGradient id="cyber-gradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#ff00ff;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#00ffff;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#ff00ff;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <!-- Status Box -->
  <rect class="status-bg" x="10" y="10" width="280" height="60" rx="8"/>
  
  <!-- Corner Decorations -->
  <line x1="10" y1="20" x2="30" y2="20" stroke="#00ffff" stroke-width="2"/>
  <line x1="10" y1="20" x2="10" y2="40" stroke="#00ffff" stroke-width="2"/>
  <line x1="280" y1="20" x2="260" y2="20" stroke="#00ffff" stroke-width="2"/>
  <line x1="290" y1="20" x2="290" y2="40" stroke="#00ffff" stroke-width="2"/>
  
  <!-- Status Text -->
  <text class="glitch" x="150" y="25" text-anchor="middle">STATUS://</text>
  <text class="status-text" x="150" y="55" text-anchor="middle">VIBECODER</text>
  
  <!-- Scanning Line Effect -->
  <line class="scan-line" x1="-100" y1="40" x2="-50" y2="40"/>
</svg>

<br/><br/>

<!-- Cyberpunk Divider -->
<img src="data:image/svg+xml,%3Csvg width='800' height='4' xmlns='http://www.w3.org/2000/svg'%3E%3Cdefs%3E%3ClinearGradient id='grad' x1='0%25' y1='0%25' x2='100%25' y2='0%25'%3E%3Cstop offset='0%25' style='stop-color:%23ff00ff;stop-opacity:0'/%3E%3Cstop offset='50%25' style='stop-color:%2300ffff;stop-opacity:1'/%3E%3Cstop offset='100%25' style='stop-color:%23ff00ff;stop-opacity:0'/%3E%3C/linearGradient%3E%3C/defs%3E%3Crect width='800' height='4' fill='url(%23grad)'/%3E%3C/svg%3E" width="100%"/>

</div>
