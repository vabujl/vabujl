<p align="center">
<svg width="620" height="220" viewBox="0 0 620 220" xmlns="http://www.w3.org/2000/svg">

  <!-- Background -->

  <rect width="620" height="220" fill="#0a0a0f"/>

  <!-- Left Eye (Human - white) -->

  <ellipse cx="250" cy="110" rx="60" ry="28" fill="#ffffff" opacity="0.9"/>
  <circle cx="250" cy="110" r="10" fill="#0a0a0f"/>

  <!-- Blink Animation -->

  <ellipse cx="250" cy="110" rx="60" ry="28" fill="#0a0a0f">
    <animate attributeName="ry" values="28;2;28" dur="4s" repeatCount="indefinite"/>
  </ellipse>

  <!-- Right Eye (Kakugan - purple) -->

  <ellipse cx="370" cy="110" rx="60" ry="28" fill="#a855f7" opacity="0.15"/>

  <!-- Outer Glow -->

  <ellipse cx="370" cy="110" rx="65" ry="32" fill="none" stroke="#a855f7" stroke-width="2">
    <animate attributeName="opacity" values="0.4;1;0.4" dur="2s" repeatCount="indefinite"/>
  </ellipse>

  <!-- Inner Eye -->

  <circle cx="370" cy="110" r="12" fill="#ffffff">
    <animate attributeName="r" values="10;14;10" dur="2s" repeatCount="indefinite"/>
  </circle>

  <!-- Dark Core -->

  <circle cx="370" cy="110" r="5" fill="#0a0a0f"/>

  <!-- Vein Lines (minimal kagune vibe) -->

  <line x1="400" y1="95" x2="430" y2="75" stroke="#a855f7" stroke-width="1" opacity="0.6">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="2s" repeatCount="indefinite"/>
  </line>
  <line x1="395" y1="125" x2="430" y2="145" stroke="#a855f7" stroke-width="1" opacity="0.6">
    <animate attributeName="opacity" values="0.2;0.8;0.2" dur="2s" begin="0.5s" repeatCount="indefinite"/>
  </line>

  <!-- Title -->

  <text x="50%" y="185" text-anchor="middle" fill="#ffffff" font-size="18" font-family="monospace">
    KANEKI MODE
    <animate attributeName="opacity" values="1;0.3;1" dur="1.5s" repeatCount="indefinite"/>
  </text>

</svg>
</p>
