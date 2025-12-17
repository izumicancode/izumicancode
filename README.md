<p align="center">
<svg width="100%" height="220" viewBox="0 0 1200 220" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0F2027"/>
      <stop offset="50%" stop-color="#203A43"/>
      <stop offset="100%" stop-color="#2C5364"/>
    </linearGradient>

    <linearGradient id="wave" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#6C63FF" stop-opacity="0.6"/>
      <stop offset="100%" stop-color="#00F5A0" stop-opacity="0.6"/>
    </linearGradient>

    <filter id="glow">
      <feGaussianBlur stdDeviation="8" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect width="1200" height="220" fill="url(#bg)" />

  <path d="M0 140 Q300 100 600 140 T1200 140 V220 H0 Z"
        fill="url(#wave)" filter="url(#glow)"/>

  <text x="50%" y="90" text-anchor="middle"
        font-size="42"
        fill="#FFFFFF"
        font-family="Segoe UI, sans-serif"
        font-weight="700">
    Your Name
  </text>

  <text x="50%" y="130" text-anchor="middle"
        font-size="18"
        fill="#E0E0E0"
        font-family="Segoe UI, sans-serif">
    Full-Stack Developer • Design-Driven Builder
  </text>
</svg>
</p>
