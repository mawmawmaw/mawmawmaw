<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>maw.dev - GitHub Profile Card</title>
  <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&display=swap" rel="stylesheet">
  <style>
    * { margin: 0; padding: 0; box-sizing: border-box; }
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
      background: #1a1a2e;
      font-family: 'Press Start 2P', monospace;
    }
    .preview-note {
      position: fixed;
      top: 10px;
      left: 50%;
      transform: translateX(-50%);
      background: #000080;
      color: white;
      padding: 8px 16px;
      font-family: 'Press Start 2P', monospace;
      font-size: 8px;
      border: 2px solid;
      border-color: #ffffff #808080 #808080 #ffffff;
      z-index: 100;
    }
  </style>
</head>
<body>
  <div class="preview-note">PREVIEW - Copy the SVG below for your GitHub README</div>

  <!-- === SVG PROFILE CARD - Copy from here === -->
  <svg xmlns="http://www.w3.org/2000/svg" width="840" height="480" viewBox="0 0 840 480">
    <defs>
      <style>
        @import url('https://fonts.googleapis.com/css2?family=Press+Start+2P&amp;display=swap');
      </style>
      <!-- Sky gradient -->
      <linearGradient id="sky" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#87CEEB"/>
        <stop offset="60%" stop-color="#5BA3D9"/>
        <stop offset="100%" stop-color="#0056aa"/>
      </linearGradient>
      <!-- Water shimmer -->
      <linearGradient id="water" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#0056aa"/>
        <stop offset="25%" stop-color="#0068c4"/>
        <stop offset="50%" stop-color="#0056aa"/>
        <stop offset="75%" stop-color="#004a94"/>
        <stop offset="100%" stop-color="#0056aa"/>
      </linearGradient>
      <!-- Title bar gradient -->
      <linearGradient id="titlebar" x1="0" y1="0" x2="1" y2="0">
        <stop offset="0%" stop-color="#000080"/>
        <stop offset="100%" stop-color="#1084d0"/>
      </linearGradient>
      <!-- Grass gradient -->
      <linearGradient id="grass" x1="0" y1="0" x2="0" y2="1">
        <stop offset="0%" stop-color="#4a8c3f"/>
        <stop offset="50%" stop-color="#3d7a34"/>
        <stop offset="100%" stop-color="#2d5a24"/>
      </linearGradient>
    </defs>

    <!-- ====== BACKGROUND LAYERS ====== -->
    <!-- Sky -->
    <rect width="840" height="480" fill="url(#sky)"/>
    <!-- Clouds -->
    <ellipse cx="120" cy="60" rx="80" ry="25" fill="white" opacity="0.3"/>
    <ellipse cx="160" cy="50" rx="60" ry="20" fill="white" opacity="0.25"/>
    <ellipse cx="600" cy="80" rx="70" ry="22" fill="white" opacity="0.2"/>
    <ellipse cx="750" cy="45" rx="55" ry="18" fill="white" opacity="0.25"/>
    <!-- Water -->
    <rect y="320" width="840" height="100" fill="url(#water)" opacity="0.9"/>
    <!-- Water wave lines -->
    <path d="M0,340 Q70,332 140,340 Q210,348 280,340 Q350,332 420,340 Q490,348 560,340 Q630,332 700,340 Q770,348 840,340" fill="none" stroke="#ffffff" stroke-width="1" opacity="0.15"/>
    <path d="M0,360 Q70,352 140,360 Q210,368 280,360 Q350,352 420,360 Q490,368 560,360 Q630,352 700,360 Q770,368 840,360" fill="none" stroke="#ffffff" stroke-width="1" opacity="0.1"/>
    <path d="M0,380 Q70,374 140,380 Q210,386 280,380 Q350,374 420,380 Q490,386 560,380 Q630,374 700,380 Q770,386 840,380" fill="none" stroke="#ffffff" stroke-width="1" opacity="0.08"/>
    <!-- Grass -->
    <rect y="400" width="840" height="80" fill="url(#grass)"/>
    <!-- Grass blades detail -->
    <path d="M0,400 L10,390 L20,400 L30,388 L40,400 L50,392 L60,400 L70,386 L80,400 L90,390 L100,400 L110,388 L120,400 L130,392 L140,400 L150,386 L160,400 L170,390 L180,400 L190,388 L200,400 L210,392 L220,400 L230,386 L240,400 L250,390 L260,400 L270,388 L280,400 L290,392 L300,400 L310,386 L320,400 L330,390 L340,400 L350,388 L360,400 L370,392 L380,400 L390,386 L400,400 L410,390 L420,400 L430,388 L440,400 L450,392 L460,400 L470,386 L480,400 L490,390 L500,400 L510,388 L520,400 L530,392 L540,400 L550,386 L560,400 L570,390 L580,400 L590,388 L600,400 L610,392 L620,400 L630,386 L640,400 L650,390 L660,400 L670,388 L680,400 L690,392 L700,400 L710,386 L720,400 L730,390 L740,400 L750,388 L760,400 L770,392 L780,400 L790,386 L800,400 L810,390 L820,400 L830,388 L840,400" fill="url(#grass)"/>
    <!-- Grass shadow/depth -->
    <rect y="400" width="840" height="4" fill="#2d5a24" opacity="0.3"/>

    <!-- ====== AVATAR CHARACTER ====== -->
    <image
      href="https://maw.dev/static/media/maw_waving.c1f9aef73ce81b23a6b9.gif"
      x="40" y="230" width="120" height="180"
      preserveAspectRatio="xMidYMax meet"
    />
    <!-- Avatar shadow -->
    <ellipse cx="100" cy="418" rx="40" ry="8" fill="black" opacity="0.2"/>

    <!-- ====== DIALOG BOX ====== -->
    <!-- Dialog pointer (triangle) -->
    <polygon points="168,300 180,286 180,314" fill="#ffffffdf"/>
    <!-- Dialog box border (pixel style) -->
    <rect x="178" y="238" width="284" height="150" fill="#dfdfdf" rx="0"/>
    <rect x="182" y="242" width="280" height="146" fill="#808080" rx="0"/>
    <rect x="180" y="240" width="280" height="144" fill="#ffffffdf" rx="0"/>
    <!-- Dialog text -->
    <foreignObject x="190" y="250" width="260" height="126">
      <div xmlns="http://www.w3.org/1999/xhtml" style="font-family: 'Press Start 2P', monospace; color: #111; line-height: 1.8;">
        <p style="font-size: 7px; margin-bottom: 10px;">Hi! I'm <strong>Mauricio</strong>,</p>
        <p style="font-size: 6px; margin-bottom: 8px;">a Senior Full-Stack Developer with 15+ years of experience.</p>
        <p style="font-size: 6px; margin-bottom: 8px;">I build scalable apps with React, TypeScript, Node.js &amp; AWS.</p>
        <p style="font-size: 6px; color: #0056aa;">Visit maw.dev to explore!</p>
      </div>
    </foreignObject>

    <!-- ====== ACTION BUTTONS ====== -->
    <!-- Actions container border -->
    <rect x="40" y="424" width="422" height="48" fill="#dfdfdf" rx="0"/>
    <rect x="44" y="428" width="418" height="44" fill="#808080" rx="0"/>
    <rect x="42" y="426" width="418" height="44" fill="#ffffffdf" rx="0"/>
    <!-- Action items -->
    <foreignObject x="50" y="430" width="404" height="38">
      <div xmlns="http://www.w3.org/1999/xhtml" style="font-family: 'Press Start 2P', monospace; display: flex; height: 100%;">
        <div style="display: flex; align-items: center; gap: 16px; padding: 0 8px; width: 100%;">
          <span style="font-size: 6px; color: #111;"><span style="color: #0056aa;">&gt;</span> Portfolio</span>
          <span style="font-size: 6px; color: #111;"><span style="color: #0056aa;">&gt;</span> Contact</span>
          <span style="font-size: 6px; color: #111;"><span style="color: #0056aa;">&gt;</span> Resume</span>
          <span style="font-size: 6px; color: #111;"><span style="color: #0056aa;">&gt;</span> Games</span>
        </div>
      </div>
    </foreignObject>

    <!-- ====== BROWSER WINDOW ====== -->
    <!-- Window outer border (raised bevel) -->
    <rect x="480" y="60" width="340" height="410" fill="#ffffff" rx="0"/>
    <rect x="482" y="62" width="338" height="408" fill="#808080" rx="0"/>
    <!-- Window background -->
    <rect x="481" y="61" width="338" height="408" fill="#c0c0c0" rx="0"/>

    <!-- Title bar -->
    <rect x="484" y="64" width="332" height="20" fill="url(#titlebar)" rx="0"/>
    <!-- Title bar text -->
    <text x="494" y="78" fill="white" font-family="'Press Start 2P', monospace" font-size="6" font-weight="bold">maw.dev - Mauricio's Portfolio</text>
    <!-- Title bar buttons -->
    <!-- Minimize -->
    <rect x="774" y="67" width="14" height="13" fill="#c0c0c0" stroke="#ffffff" stroke-width="1"/>
    <rect x="774" y="67" width="14" height="13" fill="#c0c0c0" style="outline: 1px solid #808080; outline-offset: -1px;"/>
    <line x1="777" y1="76" x2="785" y2="76" stroke="#000" stroke-width="1.5"/>
    <!-- Maximize -->
    <rect x="790" y="67" width="14" height="13" fill="#c0c0c0"/>
    <rect x="792" y="69" width="10" height="9" fill="none" stroke="#000" stroke-width="1.5"/>
    <!-- Close -->
    <rect x="806" y="67" width="14" height="13" fill="#c0c0c0"/>
    <line x1="809" y1="70" x2="817" y2="77" stroke="#000" stroke-width="1.5"/>
    <line x1="817" y1="70" x2="809" y2="77" stroke="#000" stroke-width="1.5"/>

    <!-- Menu bar -->
    <rect x="484" y="84" width="332" height="18" fill="#f0f0f0"/>
    <line x1="484" y1="102" x2="816" y2="102" stroke="#d4d0c8" stroke-width="1"/>
    <text x="492" y="96" fill="#000" font-family="'Press Start 2P', monospace" font-size="5">File</text>
    <text x="522" y="96" fill="#000" font-family="'Press Start 2P', monospace" font-size="5">Edit</text>
    <text x="552" y="96" fill="#000" font-family="'Press Start 2P', monospace" font-size="5">View</text>
    <text x="586" y="96" fill="#000" font-family="'Press Start 2P', monospace" font-size="5">Favorites</text>
    <text x="650" y="96" fill="#000" font-family="'Press Start 2P', monospace" font-size="5">Help</text>

    <!-- Navigation bar -->
    <rect x="484" y="102" width="332" height="20" fill="#f0f0f0"/>
    <line x1="484" y1="122" x2="816" y2="122" stroke="#808080" stroke-width="1"/>
    <!-- Nav buttons -->
    <rect x="487" y="105" width="18" height="14" fill="#f0f0f0" stroke="#ffffff" stroke-width="1"/>
    <text x="492" y="115" fill="#333" font-size="10">&#9664;</text>
    <rect x="507" y="105" width="18" height="14" fill="#f0f0f0" stroke="#ffffff" stroke-width="1"/>
    <text x="512" y="115" fill="#333" font-size="10">&#9654;</text>
    <!-- Address bar -->
    <rect x="530" y="105" width="280" height="14" fill="white" stroke="#808080" stroke-width="1"/>
    <text x="536" y="115" fill="#000" font-family="'Courier New', monospace" font-size="7">https://maw.dev/</text>

    <!-- Content area (inset border) -->
    <rect x="484" y="123" width="332" height="320" fill="#808080"/>
    <rect x="486" y="125" width="330" height="318" fill="#ffffff"/>
    <rect x="485" y="124" width="330" height="318" fill="white"/>

    <!-- Page content -->
    <foreignObject x="490" y="128" width="320" height="310">
      <div xmlns="http://www.w3.org/1999/xhtml" style="font-family: 'Press Start 2P', monospace; padding: 12px; background: linear-gradient(180deg, #f8f9fa 0%, #e9ecef 100%); height: 100%; overflow: hidden;">
        <!-- Page title with gradient bar -->
        <div style="background: linear-gradient(to right, #000080, #1084d0); padding: 6px 10px; margin: -12px -12px 12px -12px;">
          <span style="color: white; font-size: 8px; font-weight: bold;">Welcome!</span>
        </div>

        <p style="font-size: 6px; color: #333; line-height: 1.8; margin-bottom: 10px;">
          I'm Mauricio, a Senior Full-Stack Developer &amp; Technical Lead.
        </p>

        <!-- Tech Stack Section -->
        <div style="margin-bottom: 10px;">
          <div style="background: #f0f0f0; border: 2px solid; border-color: #dfdfdf #808080 #808080 #dfdfdf; padding: 6px 8px; margin-bottom: 8px;">
            <span style="font-size: 5px; color: #000080; font-weight: bold;">TECH STACK</span>
          </div>
          <div style="display: flex; flex-wrap: wrap; gap: 4px;">
            <span style="background: #003fc7; color: white; padding: 3px 6px; font-size: 5px;">React</span>
            <span style="background: #3178c6; color: white; padding: 3px 6px; font-size: 5px;">TypeScript</span>
            <span style="background: #339933; color: white; padding: 3px 6px; font-size: 5px;">Node.js</span>
            <span style="background: #f0db4f; color: #333; padding: 3px 6px; font-size: 5px;">JavaScript</span>
            <span style="background: #ff9900; color: white; padding: 3px 6px; font-size: 5px;">AWS</span>
            <span style="background: #000; color: white; padding: 3px 6px; font-size: 5px;">Next.js</span>
            <span style="background: #4fc08d; color: white; padding: 3px 6px; font-size: 5px;">Python</span>
            <span style="background: #627eea; color: white; padding: 3px 6px; font-size: 5px;">Web3</span>
            <span style="background: #2496ed; color: white; padding: 3px 6px; font-size: 5px;">Docker</span>
            <span style="background: #f24e1e; color: white; padding: 3px 6px; font-size: 5px;">Firebase</span>
            <span style="background: #764abc; color: white; padding: 3px 6px; font-size: 5px;">GraphQL</span>
            <span style="background: #47a248; color: white; padding: 3px 6px; font-size: 5px;">MongoDB</span>
          </div>
        </div>

        <!-- Links Section -->
        <div style="margin-bottom: 8px;">
          <div style="background: #f0f0f0; border: 2px solid; border-color: #dfdfdf #808080 #808080 #dfdfdf; padding: 6px 8px; margin-bottom: 8px;">
            <span style="font-size: 5px; color: #000080; font-weight: bold;">CONNECT</span>
          </div>
          <div style="display: flex; flex-wrap: wrap; gap: 6px;">
            <div style="background: #c0c0c0; border: 2px solid; border-color: #ffffff #808080 #808080 #ffffff; padding: 4px 8px;">
              <span style="font-size: 5px; color: #000;">&#127760; maw.dev</span>
            </div>
            <div style="background: #c0c0c0; border: 2px solid; border-color: #ffffff #808080 #808080 #ffffff; padding: 4px 8px;">
              <span style="font-size: 5px; color: #000;">&#128101; LinkedIn</span>
            </div>
            <div style="background: #c0c0c0; border: 2px solid; border-color: #ffffff #808080 #808080 #ffffff; padding: 4px 8px;">
              <span style="font-size: 5px; color: #000;">&#128187; GitHub</span>
            </div>
          </div>
        </div>

        <!-- Fun footer -->
        <div style="border-top: 1px solid #d4d0c8; padding-top: 8px; margin-top: 4px;">
          <p style="font-size: 5px; color: #808080; text-align: center;">Best viewed with Netscape Navigator 4.0</p>
        </div>
      </div>
    </foreignObject>

    <!-- Status bar -->
    <rect x="484" y="444" width="332" height="18" fill="#f0f0f0"/>
    <line x1="484" y1="444" x2="816" y2="444" stroke="#ffffff" stroke-width="1"/>
    <!-- Status text inset -->
    <rect x="487" y="447" width="220" height="12" fill="#f0f0f0" stroke="#808080" stroke-width="1"/>
    <text x="492" y="456" fill="#000" font-family="'Press Start 2P', monospace" font-size="4">Done</text>
    <!-- Status zone -->
    <rect x="714" y="447" width="98" height="12" fill="#f0f0f0" stroke="#808080" stroke-width="1"/>
    <text x="720" y="456" fill="#000" font-family="'Press Start 2P', monospace" font-size="4">Internet</text>

    <!-- ====== DECORATIVE ELEMENTS ====== -->
    <!-- Small sun -->
    <circle cx="780" cy="30" r="16" fill="#FFD700" opacity="0.8"/>
    <circle cx="780" cy="30" r="12" fill="#FFF8DC" opacity="0.6"/>

  </svg>
  <!-- === End of SVG Profile Card === -->

</body>
</html>
