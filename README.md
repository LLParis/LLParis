<!-- LLParis Profile README — v2 (aesthetic + stable) -->
<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="220" viewBox="0 0 1200 220">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#0b1220"/>
      <stop offset="0.55" stop-color="#111827"/>
      <stop offset="1" stop-color="#0b1220"/>
    </linearGradient>

    <linearGradient id="fg" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#00E5FF"/>
      <stop offset="0.5" stop-color="#7C3AED"/>
      <stop offset="1" stop-color="#22C55E"/>
    </linearGradient>
  </defs>

  <rect x="18" y="18" width="1164" height="184" rx="22" fill="url(#bg)" stroke="#1f2937" stroke-width="2"/>

  <text x="60" y="110"
        font-family="ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial"
        font-size="64" font-weight="800" fill="url(#fg)" letter-spacing="2">
    LLPARIS
  </text>

  <text x="62" y="152"
        font-family="ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial"
        font-size="18" fill="#cbd5e1">
    Graphics × Generative AI × Simulation / Benchmarks × Long-horizon Agents
  </text>

  <text x="62" y="178"
        font-family="ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, 'Liberation Mono', 'Courier New', monospace"
        font-size="13" fill="#94a3b8">
    status: building foundations → shipping weekly artifacts (not claiming affiliations)
  </text>
</svg>

<div align="center">

<!-- Self-contained animated header (no external banner service needed) -->
<svg viewBox="0 0 900 140" width="900" height="140" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="LLParis header">
  <defs>
    <linearGradient id="g" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#00E5FF">
        <animate attributeName="stop-color" values="#00E5FF;#7C3AED;#00E5FF" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="50%" stop-color="#7C3AED">
        <animate attributeName="stop-color" values="#7C3AED;#22C55E;#7C3AED" dur="6s" repeatCount="indefinite"/>
      </stop>
      <stop offset="100%" stop-color="#22C55E">
        <animate attributeName="stop-color" values="#22C55E;#00E5FF;#22C55E" dur="6s" repeatCount="indefinite"/>
      </stop>
    </linearGradient>

    <filter id="softGlow">
      <feGaussianBlur stdDeviation="2.5" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>

  <rect x="0" y="0" width="900" height="140" rx="18" fill="#0b1220"/>
  <text x="50%" y="58%" text-anchor="middle" dominant-baseline="middle"
        font-family="ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial"
        font-size="56" fill="url(#g)" filter="url(#softGlow)" letter-spacing="2">
    LLPARIS
  </text>
  <text x="50%" y="82%" text-anchor="middle" dominant-baseline="middle"
        font-family="ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial"
        font-size="14" fill="#cbd5e1" opacity="0.95">
    UW / GRAIL lane — Graphics × Generative AI × Real-Time Anime Pipeline
  </text>
</svg>

<br/>

<a href="https://github.com/LLParis">
  <img src="https://img.shields.io/badge/github-LLParis-0b1220?style=for-the-badge&logo=github" />
</a>
<!-- Add these later if you want -->
<!--
<a href="https://www.linkedin.com/in/YOUR_LINKEDIN/">
  <img src="https://img.shields.io/badge/linkedin-connect-0b1220?style=for-the-badge&logo=linkedin" />
</a>
<a href="https://twitter.com/YOUR_HANDLE">
  <img src="https://img.shields.io/badge/x-updates-0b1220?style=for-the-badge&logo=x" />
</a>
<a href="https://www.youtube.com/@YOUR_CHANNEL">
  <img src="https://img.shields.io/badge/youtube-channel-0b1220?style=for-the-badge&logo=youtube" />
</a>
-->

</div>

---

```text
STATUS  : building foundations → shipping weekly artifacts
FOCUS   : Python → tools → vision/graphics experiments
RULE    : every week = demo clip + commits + 1-page log
