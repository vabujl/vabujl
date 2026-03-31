<div align="center">

<!-- TYPING HEADER -->
<img src="https://readme-typing-svg.demolab.com?font=Space+Mono&weight=700&size=28&pause=1000&color=000000&center=true&vCenter=true&width=600&lines=Hey%2C+I+build+things.+%F0%9F%A4%A0;Full-Stack+Developer.;No+bug+survives.+%F0%9F%90%9B" alt="Typing SVG" />

<br/>

<!-- COWBOY BUG HUNT SCENE (animated SVG) -->
<img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" style="display:none"/>

<!-- Animated Badge Row -->
<img src="https://img.shields.io/badge/🤠-Bug%20Hunter-000000?style=for-the-badge&labelColor=000000&color=111111" />
<img src="https://img.shields.io/badge/⚡-Full--Stack-000000?style=for-the-badge&labelColor=111111&color=222222" />
<img src="https://img.shields.io/badge/☕-Powered%20by%20Coffee-000000?style=for-the-badge&labelColor=222222&color=333333" />

<br/><br/>

<!-- ANIMATED COWBOY SVG SCENE -->
<svg width="700" height="130" viewBox="0 0 700 130" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <style>
      /* Ground */
      .ground { fill: #f5f5f5; }
      .ground-line { stroke: #e0e0e0; stroke-width: 0.5; }

      /* Cowboy walk */
      .cowboy-group { animation: walk 0.5s steps(2) infinite; }
      @keyframes walk {
        0%   { transform: translateY(0px); }
        50%  { transform: translateY(-2px); }
        100% { transform: translateY(0px); }
      }

      /* Lasso spin */
      .lasso { animation: lasso 3s ease-in-out infinite; transform-origin: 155px 55px; }
      @keyframes lasso {
        0%, 30%  { opacity: 0; r: 0; }
        40%      { opacity: 0.5; r: 14; }
        55%      { opacity: 0.8; r: 18; }
        65%      { opacity: 0; r: 0; }
        100%     { opacity: 0; r: 0; }
      }

      /* Bugs running left */
      .bug1 { animation: bugRun 5s linear infinite; }
      .bug2 { animation: bugRun 7s linear 1.5s infinite; }
      .bug3 { animation: bugRun 4.5s linear 3s infinite; }
      @keyframes bugRun {
        0%   { transform: translateX(550px); opacity: 1; }
        60%  { transform: translateX(30px);  opacity: 1; }
        62%  { transform: translateX(30px) scale(0) rotate(360deg); opacity: 0; }
        63%  { transform: translateX(700px); opacity: 0; }
        65%  { opacity: 0; }
        100% { transform: translateX(550px); opacity: 0; }
      }

      /* Caught stars pop */
      .caught { animation: caughtPop 5s ease-out infinite; }
      @keyframes caughtPop {
        0%, 59%  { opacity: 0; transform: translate(0,0) scale(0); }
        63%      { opacity: 1; transform: translate(-5px, -8px) scale(1.3); }
        75%      { opacity: 0.5; transform: translate(-8px, -16px) scale(1); }
        85%      { opacity: 0; }
        100%     { opacity: 0; }
      }

      /* Dust puffs */
      .dust { animation: dustFloat 0.6s ease-out infinite alternate; }
      @keyframes dustFloat {
        from { opacity: 0.3; transform: translateY(0) scale(1); }
        to   { opacity: 0;   transform: translateY(-6px) scale(0.4); }
      }
    </style>
  </defs>

  <!-- Ground -->
  <rect class="ground" x="0" y="105" width="700" height="25" rx="0"/>
  <line class="ground-line" x1="0" y1="105" x2="700" y2="105"/>

  <!-- Dust puffs under cowboy -->
  <circle class="dust" cx="108" cy="104" r="4" fill="#bbb"/>
  <circle class="dust" cx="116" cy="102" r="3" fill="#ccc" style="animation-delay:0.2s"/>
  <circle class="dust" cx="100" cy="103" r="2.5" fill="#bbb" style="animation-delay:0.4s"/>

  <!-- COWBOY (pixel art style) -->
  <g class="cowboy-group">
    <!-- Hat brim -->
    <rect x="100" y="22" width="36" height="5" rx="2.5" fill="#222"/>
    <!-- Hat top -->
    <rect x="106" y="10" width="24" height="16" rx="4" fill="#111"/>
    <!-- Hat band -->
    <rect x="106" y="22" width="24" height="3" rx="1" fill="#444"/>
    <!-- Head -->
    <ellipse cx="118" cy="38" rx="12" ry="11" fill="#f5c6a0"/>
    <!-- Eyes -->
    <circle cx="113" cy="36" r="2" fill="#222"/>
    <circle cx="123" cy="36" r="2" fill="#222"/>
    <!-- Eye shine -->
    <circle cx="114" cy="35" r="0.8" fill="#fff"/>
    <circle cx="124" cy="35" r="0.8" fill="#fff"/>
    <!-- Smile -->
    <path d="M113 43 Q118 47 123 43" stroke="#a0522d" stroke-width="1.5" fill="none" stroke-linecap="round"/>
    <!-- Body -->
    <rect x="107" y="50" width="22" height="26" rx="4" fill="#111"/>
    <!-- Sheriff star -->
    <text x="115" y="66" font-size="10" fill="#f5c6a0" font-family="serif">★</text>
    <!-- Belt -->
    <rect x="107" y="72" width="22" height="4" rx="1" fill="#333"/>
    <!-- Left arm -->
    <rect x="90" y="52" width="18" height="6" rx="3" fill="#222"/>
    <!-- Right arm (raised for lasso) -->
    <rect x="128" y="46" width="16" height="6" rx="3" fill="#222" transform="rotate(-30 136 49)"/>
    <!-- Legs -->
    <rect x="108" y="75" width="9" height="22" rx="3" fill="#333"/>
    <rect x="119" y="75" width="9" height="22" rx="3" fill="#333"/>
    <!-- Boots -->
    <rect x="104" y="93" width="14" height="7" rx="3" fill="#111"/>
    <rect x="118" y="93" width="14" height="7" rx="3" fill="#111"/>
  </g>

  <!-- Lasso circle (animated) -->
  <circle class="lasso" cx="155" cy="55" r="0" stroke="#888" stroke-width="1.5" fill="none" stroke-dasharray="4 2"/>

  <!-- BUGS running across the scene -->
  <text class="bug1" y="101" font-size="18">🐛</text>
  <text class="bug2" y="101" font-size="16">🦟</text>
  <text class="bug3" y="101" font-size="17">🐞</text>

  <!-- Caught explosion -->
  <text class="caught" x="140" y="90" font-size="14">✨💥✨</text>

  <!-- Comment label -->
  <text x="560" y="20" font-size="11" fill="#aaa" font-family="monospace">// no bug survives</text>
</svg>

</div>

---

## 👨‍💻 About Me

```kotlin
val developer = Developer(
    name    = "Your Name",
    role    = "Full-Stack Developer",
    motto   = "Clean code. Real impact. Zero bugs. (almost)",
    loves   = listOf("Building products", "Fixing things", "Strong coffee")
)
```

---

## 🛠 Tech Stack

<div align="center">

[![My Skills](https://skillicons.dev/icons?i=java,kotlin,nodejs,figma&theme=light)](https://skillicons.dev)

</div>

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=DEIN_USERNAME&show_icons=true&theme=default&hide_border=true&count_private=true&title_color=000000&icon_color=000000&text_color=333333" />
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=DEIN_USERNAME&layout=compact&hide_border=true&theme=default&title_color=000000&text_color=333333" />

</div>

---

## 🔥 Streak

<div align="center">

<img src="https://streak-stats.demolab.com?user=DEIN_USERNAME&theme=default&hide_border=true&date_format=j%20M%5B%20Y%5D&stroke=000000&ring=000000&fire=000000&currStreakLabel=000000" />

</div>

---

## 📡 Status

<div align="center">

![Open to Work](https://img.shields.io/badge/Status-Open%20to%20Opportunities-22c55e?style=flat-square&labelColor=166534)
![Building](https://img.shields.io/badge/Mode-Building%20in%20Public-555?style=flat-square)
![Learning](https://img.shields.io/badge/Always-Learning-555?style=flat-square)

</div>

---

<!-- SCROLLING MARQUEE -->
<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Space+Mono&size=12&pause=0&color=999999&center=true&vCenter=true&multiline=false&repeat=true&width=700&lines=🤠+bug+hunter+·+⚡+full-stack+·+☕+java+dev+·+🤖+kotlin+·+🎨+figma+·+⬡+node.js+·+🐛+no+bug+survives+·" alt="Marquee" />

</div>
