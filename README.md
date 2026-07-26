<svg width="1180" height="610" viewBox="0 0 1180 610" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" role="img" aria-label="Rohan Tarke profile header">
  <defs>
    <clipPath id="roundedCanvas"><rect x="0" y="0" width="1180" height="610" rx="28"/></clipPath>
    <clipPath id="leftPanelClip"><rect x="24" y="24" width="420" height="562" rx="20"/></clipPath>
    <clipPath id="rightPanelClip"><rect x="468" y="24" width="688" height="562" rx="20"/></clipPath>

    <linearGradient id="bgWash" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#030712"/>
      <stop offset="55%" stop-color="#050B18"/>
      <stop offset="100%" stop-color="#030712"/>
    </linearGradient>

    <radialGradient id="glowA" cx="15%" cy="10%" r="55%">
      <stop offset="0%" stop-color="#7C3AED" stop-opacity="0.30"/>
      <stop offset="100%" stop-color="#7C3AED" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowB" cx="90%" cy="15%" r="55%">
      <stop offset="0%" stop-color="#22D3EE" stop-opacity="0.30"/>
      <stop offset="100%" stop-color="#22D3EE" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowC" cx="60%" cy="95%" r="60%">
      <stop offset="0%" stop-color="#10B981" stop-opacity="0.30"/>
      <stop offset="100%" stop-color="#10B981" stop-opacity="0"/>
    </radialGradient>

    <linearGradient id="asciiGrad" x1="0%" y1="0%" x2="100%" y2="0%" gradientUnits="objectBoundingBox">
      <stop offset="0%" stop-color="#22D3EE"/>
      <stop offset="50%" stop-color="#7C3AED"/>
      <stop offset="100%" stop-color="#22D3EE"/>
      <animateTransform attributeName="gradientTransform" type="translate" values="-1 0;1 0;-1 0" dur="7s" repeatCount="indefinite"/>
    </linearGradient>

    <linearGradient id="titleGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7C3AED"/>
      <stop offset="50%" stop-color="#22D3EE"/>
      <stop offset="100%" stop-color="#10B981"/>
    </linearGradient>

    <linearGradient id="borderShimmer" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#7C3AED" stop-opacity="0.9"/>
      <stop offset="30%" stop-color="#22D3EE" stop-opacity="0.9"/>
      <stop offset="60%" stop-color="#10B981" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#7C3AED" stop-opacity="0.9"/>
    </linearGradient>

    <linearGradient id="pillStroke" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#7C3AED"/>
      <stop offset="100%" stop-color="#22D3EE"/>
    </linearGradient>

    <linearGradient id="scanGrad" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" stop-color="#22D3EE" stop-opacity="0"/>
      <stop offset="50%" stop-color="#22D3EE" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#22D3EE" stop-opacity="0"/>
    </linearGradient>

    <linearGradient id="reflect" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="rgba(255,255,255,0.06)" stop-opacity="0.5"/>
      <stop offset="40%" stop-color="rgba(255,255,255,0.06)" stop-opacity="0"/>
      <stop offset="100%" stop-color="rgba(255,255,255,0.06)" stop-opacity="0"/>
    </linearGradient>

    <filter id="softGlow" x="-60%" y="-60%" width="220%" height="220%">
      <feGaussianBlur stdDeviation="10"/>
    </filter>
    <filter id="textGlow" x="-40%" y="-40%" width="180%" height="180%">
      <feGaussianBlur stdDeviation="1.4" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="noiseFilter">
      <feTurbulence type="fractalNoise" baseFrequency="0.9" numOctaves="2" stitchTiles="stitch" result="n"/>
      <feColorMatrix in="n" type="matrix" values="0 0 0 0 0  0 0 0 0 0  0 0 0 0 0  0.9 0.9 0.9 0 0"/>
    </filter>
  </defs>

  <g clip-path="url(#roundedCanvas)">
    <rect x="0" y="0" width="1180" height="610" fill="url(#bgWash)"/>

    <g>
      <circle cx="170" cy="60" r="260" fill="url(#glowA)">
        <animate attributeName="cx" values="170;230;170" dur="10s" repeatCount="indefinite"/>
      </circle>
      <circle cx="1060" cy="90" r="280" fill="url(#glowB)">
        <animate attributeName="cy" values="90;150;90" dur="12s" repeatCount="indefinite"/>
      </circle>
      <circle cx="700" cy="580" r="300" fill="url(#glowC)">
        <animate attributeName="cx" values="700;600;700" dur="14s" repeatCount="indefinite"/>
      </circle>
    </g>

    <rect x="0" y="0" width="1180" height="610" filter="url(#noiseFilter)" opacity="0.035"/>

    
        <circle cx="60" cy="560" r="1.6" fill="#7C3AED" opacity="0.55">
          <animate attributeName="cy" values="560;520;560" dur="5.2s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.15;0.65;0.15" dur="5.2s" repeatCount="indefinite"/>
        </circle>
        <circle cx="150" cy="520" r="2.1" fill="#22D3EE" opacity="0.55">
          <animate attributeName="cy" values="520;480;520" dur="6.7s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.15;0.65;0.15" dur="6.7s" repeatCount="indefinite"/>
        </circle>
        <circle cx="330" cy="570" r="2.6" fill="#10B981" opacity="0.55">
          <animate attributeName="cy" values="570;530;570" dur="4.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.15;0.65;0.15" dur="4.1s" repeatCount="indefinite"/>
        </circle>
        <circle cx="860" cy="60" r="1.6" fill="#7C3AED" opacity="0.55">
          <animate attributeName="cy" values="60;20;60" dur="5.8s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.15;0.65;0.15" dur="5.8s" repeatCount="indefinite"/>
        </circle>
        <circle cx="1000" cy="100" r="2.1" fill="#22D3EE" opacity="0.55">
          <animate attributeName="cy" values="100;60;100" dur="4.4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.15;0.65;0.15" dur="4.4s" repeatCount="indefinite"/>
        </circle>
        <circle cx="1100" cy="500" r="2.6" fill="#10B981" opacity="0.55">
          <animate attributeName="cy" values="500;460;500" dur="6.1s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.15;0.65;0.15" dur="6.1s" repeatCount="indefinite"/>
        </circle>
        <circle cx="700" cy="40" r="1.6" fill="#7C3AED" opacity="0.55">
          <animate attributeName="cy" values="40;0;40" dur="4.8s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.15;0.65;0.15" dur="4.8s" repeatCount="indefinite"/>
        </circle>
        <circle cx="980" cy="560" r="2.1" fill="#22D3EE" opacity="0.55">
          <animate attributeName="cy" values="560;520;560" dur="5.4s" repeatCount="indefinite"/>
          <animate attributeName="opacity" values="0.15;0.65;0.15" dur="5.4s" repeatCount="indefinite"/>
        </circle>

    <!-- LEFT PANEL -->
    <g>
      <rect x="24" y="24" width="420" height="562" rx="20" fill="#0F172A" fill-opacity="0.55" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>
      <rect x="24" y="24" width="420" height="562" rx="20" fill="url(#reflect)"/>
      <g clip-path="url(#leftPanelClip)">
        
      <circle cx="54" cy="52" r="6" fill="#FF5F56"/>
      <circle cx="72" cy="52" r="6" fill="#FFBD2E"/>
      <circle cx="90" cy="52" r="6" fill="#27C93F"/>
        <text x="118" y="57" font-family="'Fira Code','Consolas',monospace" font-size="12" fill="#94A3B8">portrait.ascii</text>
        <line x1="54" y1="72" x2="414" y2="72" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>

        <g>
          <animateTransform attributeName="transform" type="translate" values="0 0;0 -6;0 0" dur="5s" repeatCount="indefinite"/>
          
      <text x="54" y="108" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">        .-&quot;&quot;&quot;&quot;-.        <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.5s" fill="freeze"/></text>
      <text x="54" y="131" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">      .&#x27;        &#x27;.      <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.68s" fill="freeze"/></text>
      <text x="54" y="154" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">     /   O    O   \     <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="0.86s" fill="freeze"/></text>
      <text x="54" y="177" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">    :      __      :    <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="1.04s" fill="freeze"/></text>
      <text x="54" y="200" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">    :    &#x27;----&#x27;    :    <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="1.22s" fill="freeze"/></text>
      <text x="54" y="223" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">     \            /     <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="1.4s" fill="freeze"/></text>
      <text x="54" y="246" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">      &#x27;.        .&#x27;      <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="1.58s" fill="freeze"/></text>
      <text x="54" y="269" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">        &#x27;-....-&#x27;        <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="1.76s" fill="freeze"/></text>
      <text x="54" y="292" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">       /|      |\       <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="1.94s" fill="freeze"/></text>
      <text x="54" y="315" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">      / |      | \      <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="2.12s" fill="freeze"/></text>
      <text x="54" y="338" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">     /__|______|__\     <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="2.3s" fill="freeze"/></text>
      <text x="54" y="361" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">    /_____/\_____\      <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="2.48s" fill="freeze"/></text>
      <text x="54" y="384" font-family="'Fira Code','Consolas',monospace" font-size="15"
            fill="url(#asciiGrad)" opacity="0" xml:space="preserve">   [ ROHAN.TARKE ]      <animate attributeName="opacity" from="0" to="1" dur="0.35s" begin="2.66s" fill="freeze"/></text>
          <rect x="54" y="411" width="9" height="16" fill="#22D3EE">
            <animate attributeName="opacity" values="1;1;0;0" keyTimes="0;0.5;0.51;1" dur="1s" begin="2.84s" repeatCount="indefinite"/>
          </rect>
        </g>

        <rect x="54" y="0" width="360" height="46" fill="url(#scanGrad)">
          <animate attributeName="y" values="72;540;72" dur="4.5s" repeatCount="indefinite"/>
        </rect>

        <text x="54" y="560" font-family="'Fira Code','Consolas',monospace" font-size="12" fill="#94A3B8" font-style="italic">// building things, one commit at a time</text>
      </g>
      <rect x="24" y="24" width="420" height="562" rx="20" fill="none" stroke="url(#borderShimmer)" stroke-width="1.4" stroke-dasharray="60 900" opacity="0.9">
        <animate attributeName="stroke-dashoffset" values="0;-1920" dur="9s" repeatCount="indefinite"/>
      </rect>
    </g>

    <!-- RIGHT PANEL -->
    <g>
      <rect x="468" y="24" width="688" height="562" rx="20" fill="#0F172A" fill-opacity="0.55" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>
      <rect x="468" y="24" width="688" height="562" rx="20" fill="url(#reflect)"/>
      <g clip-path="url(#rightPanelClip)">
        
      <circle cx="500" cy="52" r="6" fill="#FF5F56"/>
      <circle cx="518" cy="52" r="6" fill="#FFBD2E"/>
      <circle cx="536" cy="52" r="6" fill="#27C93F"/>
        <text x="564" y="57" font-family="'Fira Code','Consolas',monospace" font-size="12" fill="#94A3B8">rohan@dev:~</text>
        <line x1="500" y1="72" x2="1124" y2="72" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>

        <text x="502" y="108" font-family="'Fira Code','Consolas',monospace" font-size="16" fill="#94A3B8" opacity="0">Hi 👋<animate attributeName="opacity" from="0" to="1" dur="0.5s" begin="0.3s" fill="freeze"/></text>

        <text x="502" y="150" font-family="'Fira Code','Consolas',monospace" font-size="32" font-weight="700" fill="url(#titleGrad)" filter="url(#textGlow)" opacity="0">I&#8217;m Rohan Tarke<animate attributeName="opacity" from="0" to="1" dur="0.7s" begin="0.9s" fill="freeze"/></text>

        
        <text x="502" y="192" font-family="'Fira Code','Consolas',monospace" font-size="19" fill="#22D3EE" opacity="0">&gt; Frontend Engineer<animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.0001;0.028;0.172;0.2;1.0" dur="10.0s" begin="0s" repeatCount="indefinite"/></text>
        <text x="502" y="192" font-family="'Fira Code','Consolas',monospace" font-size="19" fill="#22D3EE" opacity="0">&gt; Full Stack Developer<animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.2;0.228;0.372;0.4;1.0" dur="10.0s" begin="0s" repeatCount="indefinite"/></text>
        <text x="502" y="192" font-family="'Fira Code','Consolas',monospace" font-size="19" fill="#22D3EE" opacity="0">&gt; Open Source Contributor<animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.4;0.428;0.572;0.6;1.0" dur="10.0s" begin="0s" repeatCount="indefinite"/></text>
        <text x="502" y="192" font-family="'Fira Code','Consolas',monospace" font-size="19" fill="#22D3EE" opacity="0">&gt; UI Engineer<animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.6;0.628;0.772;0.8;1.0" dur="10.0s" begin="0s" repeatCount="indefinite"/></text>
        <text x="502" y="192" font-family="'Fira Code','Consolas',monospace" font-size="19" fill="#22D3EE" opacity="0">&gt; AI Enthusiast<animate attributeName="opacity" values="0;0;1;1;0;0" keyTimes="0;0.8;0.828;0.972;1.0;1.0" dur="10.0s" begin="0s" repeatCount="indefinite"/></text>

        <line x1="502" y1="215" x2="1122" y2="215" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>

        
        <g opacity="0" transform="translate(-14,0)">
          <animate attributeName="opacity" from="0" to="1" dur="0.5s" begin="2.1s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="-14 0" to="0 0" dur="0.5s" begin="2.1s" fill="freeze"/>
          <text x="502" y="250" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#10B981">◎</text>
          <text x="524" y="250" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#94A3B8">Location:</text>
          <text x="618" y="250" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#F8FAFC">India</text>
        </g>
        <g opacity="0" transform="translate(-14,0)">
          <animate attributeName="opacity" from="0" to="1" dur="0.5s" begin="2.45s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="-14 0" to="0 0" dur="0.5s" begin="2.45s" fill="freeze"/>
          <text x="502" y="284" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#10B981">■</text>
          <text x="524" y="284" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#94A3B8">Education:</text>
          <text x="618" y="284" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#F8FAFC">B.Tech, Computer Science Engineering</text>
        </g>
        <g opacity="0" transform="translate(-14,0)">
          <animate attributeName="opacity" from="0" to="1" dur="0.5s" begin="2.8s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="-14 0" to="0 0" dur="0.5s" begin="2.8s" fill="freeze"/>
          <text x="502" y="318" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#10B981">◆</text>
          <text x="524" y="318" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#94A3B8">Focus:</text>
          <text x="618" y="318" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#F8FAFC">Data Science • AI • Cloud • MERN</text>
        </g>
        <g opacity="0" transform="translate(-14,0)">
          <animate attributeName="opacity" from="0" to="1" dur="0.5s" begin="3.15s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="-14 0" to="0 0" dur="0.5s" begin="3.15s" fill="freeze"/>
          <text x="502" y="352" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#10B981">▸</text>
          <text x="524" y="352" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#94A3B8">Portfolio:</text>
          <text x="618" y="352" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#F8FAFC">rohantarke-portfolio.vercel.app</text>
        </g>
        <g opacity="0" transform="translate(-14,0)">
          <animate attributeName="opacity" from="0" to="1" dur="0.5s" begin="3.5s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="-14 0" to="0 0" dur="0.5s" begin="3.5s" fill="freeze"/>
          <text x="502" y="386" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#10B981">✉</text>
          <text x="524" y="386" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#94A3B8">Email:</text>
          <text x="618" y="386" font-family="'Fira Code','Consolas',monospace" font-size="14" fill="#F8FAFC">rohantarke07@gmail.com</text>
        </g>

        <text x="502" y="426" font-family="'Fira Code','Consolas',monospace" font-size="13" fill="#94A3B8" letter-spacing="2" opacity="0">SKILLS<animate attributeName="opacity" from="0" to="1" dur="0.5s" begin="2.4s" fill="freeze"/></text>

        
        <g opacity="0" transform="translate(0,8)">
          <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="2.6s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="0 8" to="0 0" dur="0.45s" begin="2.6s" fill="freeze"/>
          <rect x="502.0" y="433" width="72.0" height="27" rx="13.5" fill="#0F172A" fill-opacity="0.6" stroke="url(#pillStroke)" stroke-width="1.1">
            <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="2.6s" begin="3.5s" repeatCount="indefinite"/>
          </rect>
          <text x="538.0" y="452" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="12.5" fill="#F8FAFC">React</text>
        </g>
        <g opacity="0" transform="translate(0,8)">
          <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="2.72s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="0 8" to="0 0" dur="0.45s" begin="2.72s" fill="freeze"/>
          <rect x="586.0" y="433" width="87.2" height="27" rx="13.5" fill="#0F172A" fill-opacity="0.6" stroke="url(#pillStroke)" stroke-width="1.1">
            <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="2.6s" begin="3.75s" repeatCount="indefinite"/>
          </rect>
          <text x="629.6" y="452" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="12.5" fill="#F8FAFC">Node.js</text>
        </g>
        <g opacity="0" transform="translate(0,8)">
          <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="2.84s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="0 8" to="0 0" dur="0.45s" begin="2.84s" fill="freeze"/>
          <rect x="685.2" y="433" width="110.0" height="27" rx="13.5" fill="#0F172A" fill-opacity="0.6" stroke="url(#pillStroke)" stroke-width="1.1">
            <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="2.6s" begin="4.0s" repeatCount="indefinite"/>
          </rect>
          <text x="740.2" y="452" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="12.5" fill="#F8FAFC">TypeScript</text>
        </g>
        <g opacity="0" transform="translate(0,8)">
          <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="2.96s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="0 8" to="0 0" dur="0.45s" begin="2.96s" fill="freeze"/>
          <rect x="807.2" y="433" width="94.8" height="27" rx="13.5" fill="#0F172A" fill-opacity="0.6" stroke="url(#pillStroke)" stroke-width="1.1">
            <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="2.6s" begin="4.25s" repeatCount="indefinite"/>
          </rect>
          <text x="854.6" y="452" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="12.5" fill="#F8FAFC">Tailwind</text>
        </g>
        <g opacity="0" transform="translate(0,8)">
          <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.08s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="0 8" to="0 0" dur="0.45s" begin="3.08s" fill="freeze"/>
          <rect x="914.0" y="433" width="79.6" height="27" rx="13.5" fill="#0F172A" fill-opacity="0.6" stroke="url(#pillStroke)" stroke-width="1.1">
            <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="2.6s" begin="4.5s" repeatCount="indefinite"/>
          </rect>
          <text x="953.8" y="452" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="12.5" fill="#F8FAFC">Python</text>
        </g>
        <g opacity="0" transform="translate(0,8)">
          <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.3s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="0 8" to="0 0" dur="0.45s" begin="3.3s" fill="freeze"/>
          <rect x="502.0" y="475" width="87.2" height="27" rx="13.5" fill="#0F172A" fill-opacity="0.6" stroke="url(#pillStroke)" stroke-width="1.1">
            <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="2.6s" begin="3.5s" repeatCount="indefinite"/>
          </rect>
          <text x="545.6" y="494" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="12.5" fill="#F8FAFC">MongoDB</text>
        </g>
        <g opacity="0" transform="translate(0,8)">
          <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.42s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="0 8" to="0 0" dur="0.45s" begin="3.42s" fill="freeze"/>
          <rect x="601.2" y="475" width="87.2" height="27" rx="13.5" fill="#0F172A" fill-opacity="0.6" stroke="url(#pillStroke)" stroke-width="1.1">
            <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="2.6s" begin="3.75s" repeatCount="indefinite"/>
          </rect>
          <text x="644.8" y="494" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="12.5" fill="#F8FAFC">Express</text>
        </g>
        <g opacity="0" transform="translate(0,8)">
          <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.54s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="0 8" to="0 0" dur="0.45s" begin="3.54s" fill="freeze"/>
          <rect x="700.4" y="475" width="72.0" height="27" rx="13.5" fill="#0F172A" fill-opacity="0.6" stroke="url(#pillStroke)" stroke-width="1.1">
            <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="2.6s" begin="4.0s" repeatCount="indefinite"/>
          </rect>
          <text x="736.4" y="494" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="12.5" fill="#F8FAFC">MySQL</text>
        </g>
        <g opacity="0" transform="translate(0,8)">
          <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.66s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="0 8" to="0 0" dur="0.45s" begin="3.66s" fill="freeze"/>
          <rect x="784.4" y="475" width="56.8" height="27" rx="13.5" fill="#0F172A" fill-opacity="0.6" stroke="url(#pillStroke)" stroke-width="1.1">
            <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="2.6s" begin="4.25s" repeatCount="indefinite"/>
          </rect>
          <text x="812.8" y="494" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="12.5" fill="#F8FAFC">Git</text>
        </g>
        <g opacity="0" transform="translate(0,8)">
          <animate attributeName="opacity" from="0" to="1" dur="0.45s" begin="3.78s" fill="freeze"/>
          <animateTransform attributeName="transform" type="translate" from="0 8" to="0 0" dur="0.45s" begin="3.78s" fill="freeze"/>
          <rect x="853.2" y="475" width="56.8" height="27" rx="13.5" fill="#0F172A" fill-opacity="0.6" stroke="url(#pillStroke)" stroke-width="1.1">
            <animate attributeName="stroke-opacity" values="0.4;1;0.4" dur="2.6s" begin="4.5s" repeatCount="indefinite"/>
          </rect>
          <text x="881.6" y="494" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="12.5" fill="#F8FAFC">C++</text>
        </g>

        <line x1="502" y1="524" x2="1122" y2="524" stroke="rgba(255,255,255,0.08)" stroke-width="1"/>

        
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" dur="0.5s" begin="4.0s" fill="freeze"/>
          <circle cx="520" cy="552" r="18" fill="#0F172A" fill-opacity="0.6" stroke="rgba(255,255,255,0.16)" stroke-width="1">
            <animate attributeName="stroke" values="#7C3AED;#22D3EE;#10B981;#7C3AED" dur="6s" repeatCount="indefinite"/>
          </circle>
          <text x="520" y="556" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="10.5" font-weight="600" fill="#94A3B8">GH</text>
        </g>
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" dur="0.5s" begin="4.15s" fill="freeze"/>
          <circle cx="572" cy="552" r="18" fill="#0F172A" fill-opacity="0.6" stroke="rgba(255,255,255,0.16)" stroke-width="1">
            <animate attributeName="stroke" values="#7C3AED;#22D3EE;#10B981;#7C3AED" dur="6s" repeatCount="indefinite"/>
          </circle>
          <text x="572" y="556" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="10.5" font-weight="600" fill="#94A3B8">in</text>
        </g>
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" dur="0.5s" begin="4.3s" fill="freeze"/>
          <circle cx="624" cy="552" r="18" fill="#0F172A" fill-opacity="0.6" stroke="rgba(255,255,255,0.16)" stroke-width="1">
            <animate attributeName="stroke" values="#7C3AED;#22D3EE;#10B981;#7C3AED" dur="6s" repeatCount="indefinite"/>
          </circle>
          <text x="624" y="556" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="10.5" font-weight="600" fill="#94A3B8">LC</text>
        </g>
        <g opacity="0">
          <animate attributeName="opacity" from="0" to="1" dur="0.5s" begin="4.45s" fill="freeze"/>
          <circle cx="676" cy="552" r="18" fill="#0F172A" fill-opacity="0.6" stroke="rgba(255,255,255,0.16)" stroke-width="1">
            <animate attributeName="stroke" values="#7C3AED;#22D3EE;#10B981;#7C3AED" dur="6s" repeatCount="indefinite"/>
          </circle>
          <text x="676" y="556" text-anchor="middle" font-family="'Fira Code','Consolas',monospace" font-size="10.5" font-weight="600" fill="#94A3B8">PF</text>
        </g>
      </g>
      <rect x="468" y="24" width="688" height="562" rx="20" fill="none" stroke="url(#borderShimmer)" stroke-width="1.4" stroke-dasharray="70 1400" opacity="0.9">
        <animate attributeName="stroke-dashoffset" values="0;-2940" dur="11s" repeatCount="indefinite"/>
      </rect>
    </g>

    <rect x="1.5" y="1.5" width="1177" height="607" rx="27" fill="none" stroke="url(#borderShimmer)" stroke-width="1.6" stroke-dasharray="140 3400" opacity="0.85">
      <animate attributeName="stroke-dashoffset" values="0;-7080" dur="16s" repeatCount="indefinite"/>
    </rect>
  </g>
</svg>
