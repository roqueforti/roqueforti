<svg width="1200" height="380" viewBox="0 0 1200 380" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#0A0A0A"/>
      <stop offset="55%" stop-color="#141414"/>
      <stop offset="100%" stop-color="#1A1310"/>
    </linearGradient>
    <radialGradient id="glow" cx="82%" cy="12%" r="55%">
      <stop offset="0%" stop-color="#FF7A00" stop-opacity="0.16"/>
      <stop offset="100%" stop-color="#FF7A00" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="sweep" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#FF7A00" stop-opacity="0"/>
      <stop offset="50%" stop-color="#FF7A00" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#FF7A00" stop-opacity="0"/>
      <animateTransform attributeName="gradientTransform" type="translate"
        values="-1200 0; 1200 0; -1200 0" dur="7s" repeatCount="indefinite"/>
    </linearGradient>
    <filter id="soft" x="-20%" y="-20%" width="140%" height="140%">
      <feGaussianBlur stdDeviation="1.1"/>
    </filter>
  </defs>

  <!-- window -->
  <rect x="0" y="0" width="1200" height="380" rx="18" fill="url(#bg)"/>
  <rect x="0" y="0" width="1200" height="380" rx="18" fill="url(#glow)"/>
  <rect x="0.75" y="0.75" width="1198.5" height="378.5" rx="17.25" fill="none" stroke="#2D2D2D" stroke-width="1.5"/>

  <!-- background network (AI motif) -->
  <g stroke="#FF7A00" stroke-width="1" opacity="0.18">
    <line x1="880" y1="60" x2="990" y2="110"/>
    <line x1="990" y1="110" x2="1080" y2="70"/>
    <line x1="990" y1="110" x2="960" y2="190"/>
    <line x1="1080" y1="70" x2="1150" y2="130"/>
    <line x1="960" y1="190" x2="1060" y2="230"/>
  </g>
  <g fill="#FF7A00">
    <circle cx="880" cy="60" r="3.2">
      <animate attributeName="cy" values="60;52;60" dur="5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="990" cy="110" r="4" opacity="0.9">
      <animate attributeName="cy" values="110;100;110" dur="6.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1080" cy="70" r="3">
      <animate attributeName="cy" values="70;80;70" dur="4.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1150" cy="130" r="2.6" opacity="0.8">
      <animate attributeName="cy" values="130;120;130" dur="5.5s" repeatCount="indefinite"/>
    </circle>
    <circle cx="960" cy="190" r="3.4">
      <animate attributeName="cy" values="190;180;190" dur="6s" repeatCount="indefinite"/>
    </circle>
    <circle cx="1060" cy="230" r="2.8" opacity="0.85">
      <animate attributeName="cy" values="230;222;230" dur="5.2s" repeatCount="indefinite"/>
    </circle>
  </g>

  <!-- traffic dots -->
  <g transform="translate(28,26)">
    <circle cx="0" cy="0" r="6" fill="#2D2D2D"/>
    <circle cx="22" cy="0" r="6" fill="#2D2D2D"/>
    <circle cx="44" cy="0" r="6" fill="#FF7A00"/>
  </g>
  <text x="600" y="31" text-anchor="middle" font-family="SFMono-Regular, Consolas, 'JetBrains Mono', monospace"
        font-size="13" fill="#B3B3B3" letter-spacing="0.5">~/hilman-zahrawa/profile.ts</text>
  <line x1="0" y1="52" x2="1200" y2="52" stroke="#2D2D2D" stroke-width="1"/>

  <!-- typed code block -->
  <g font-family="SFMono-Regular, Consolas, 'JetBrains Mono', monospace" font-size="27">

    <g opacity="1">
      <animate attributeName="opacity" from="0" to="1" begin="0.2s" dur="0.5s" fill="freeze"/>
      <text x="60" y="120">
        <tspan fill="#FF7A00">const</tspan>
        <tspan fill="#FFFFFF"> hilman </tspan>
        <tspan fill="#B3B3B3">= {</tspan>
      </text>
    </g>

    <g opacity="1">
      <animate attributeName="opacity" from="0" to="1" begin="0.9s" dur="0.5s" fill="freeze"/>
      <text x="60" y="168">
        <tspan fill="#B3B3B3">  name: </tspan>
        <tspan fill="#FFFFFF">"Hilman Zahrawa Budiarto"</tspan><tspan fill="#B3B3B3">,</tspan>
      </text>
    </g>

    <g opacity="1">
      <animate attributeName="opacity" from="0" to="1" begin="1.6s" dur="0.5s" fill="freeze"/>
      <text x="60" y="216">
        <tspan fill="#B3B3B3">  roles: [</tspan>
        <tspan fill="#FF7A00">"Software Engineer"</tspan><tspan fill="#B3B3B3">, </tspan>
        <tspan fill="#FF7A00">"AI Engineer"</tspan><tspan fill="#B3B3B3">, </tspan>
        <tspan fill="#FF7A00">"Full-Stack Dev"</tspan><tspan fill="#B3B3B3">],</tspan>
      </text>
    </g>

    <g opacity="1">
      <animate attributeName="opacity" from="0" to="1" begin="2.3s" dur="0.5s" fill="freeze"/>
      <text x="60" y="264">
        <tspan fill="#B3B3B3">  builds: </tspan>
        <tspan fill="#FFFFFF">"intelligent systems &amp; scalable apps"</tspan><tspan fill="#B3B3B3">,</tspan>
      </text>
    </g>

    <g opacity="1">
      <animate attributeName="opacity" from="0" to="1" begin="3.0s" dur="0.5s" fill="freeze"/>
      <text x="60" y="312" fill="#B3B3B3">};</text>
      <rect x="88" y="292" width="14" height="27" fill="#FF7A00">
        <animate attributeName="opacity" values="1;0;1" dur="1s" begin="3.0s" repeatCount="indefinite"/>
      </rect>
    </g>
  </g>

  <text x="60" y="350" font-family="SFMono-Regular, Consolas, 'JetBrains Mono', monospace" font-size="15"
        fill="#6B6B6B" font-style="italic" opacity="1">
    // turning ideas into shipped code
    <animate attributeName="opacity" from="0" to="1" begin="3.6s" dur="0.8s" fill="freeze"/>
  </text>

  <!-- scanning accent line -->
  <rect x="0" y="377" width="1200" height="2.5" fill="url(#sweep)"/>
</svg>
