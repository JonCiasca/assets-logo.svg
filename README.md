<p align="center">
  <img src="assets/logo.svg" alt="BTC Copilot by JonFlow-MDQ" width="200"/>
</p>
<svg viewBox="0 0 512 512" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bgGrad" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0e1117"/>
      <stop offset="100%" stop-color="#1a1f2b"/>
    </linearGradient>
    <linearGradient id="flowGrad" x1="0%" y1="100%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#22c55e"/>
      <stop offset="50%" stop-color="#a855f7"/>
      <stop offset="100%" stop-color="#f59e0b"/>
    </linearGradient>
  </defs>

  <!-- Fondo circular -->
  <circle cx="256" cy="256" r="248" fill="url(#bgGrad)" stroke="#2d3340" stroke-width="6"/>

  <!-- Curva de flujo/gamma de fondo -->
  <path d="M 70 320 Q 160 260 200 300 T 300 220 T 442 180"
        fill="none" stroke="url(#flowGrad)" stroke-width="6" stroke-linecap="round" opacity="0.55"/>

  <!-- Velas tipo candlestick -->
  <g stroke="#e5e7eb" stroke-width="6" stroke-linecap="round">
    <line x1="150" y1="200" x2="150" y2="330"/>
    <line x1="220" y1="170" x2="220" y2="300"/>
    <line x1="290" y1="220" x2="290" y2="360"/>
    <line x1="360" y1="150" x2="360" y2="280"/>
  </g>
  <g>
    <rect x="135" y="240" width="30" height="55" fill="#22c55e" rx="3"/>
    <rect x="205" y="200" width="30" height="60" fill="#22c55e" rx="3"/>
    <rect x="275" y="260" width="30" height="70" fill="#ef4444" rx="3"/>
    <rect x="345" y="190" width="30" height="50" fill="#22c55e" rx="3"/>
  </g>

  <!-- Simbolo Bitcoin estilizado, integrado como "ojo" del flujo -->
  <g transform="translate(256,150)">
    <circle r="46" fill="#0e1117" stroke="#f59e0b" stroke-width="5"/>
    <text x="0" y="18" font-family="Arial Black, Arial, sans-serif" font-size="52"
          font-weight="900" fill="#f59e0b" text-anchor="middle">B</text>
  </g>

  <!-- Texto principal -->
  <text x="256" y="410" font-family="Arial Black, Arial, sans-serif" font-size="46"
        font-weight="900" fill="#f3f4f6" text-anchor="middle" letter-spacing="2">
    BTC COPILOT
  </text>
  <text x="256" y="448" font-family="Arial, sans-serif" font-size="24"
        fill="#9ca3af" text-anchor="middle" letter-spacing="3">
    by JONFLOW-MDQ
  </text>
</svg>
