<!-- Encabezado animado (SVG inline compatible con GitHub) -->
<p align="center">
  <svg width="820" height="140" viewBox="0 0 820 140" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="¡Hola! Soy Roberstxx">
    <defs>
      <!-- Degradado azul → morado -->
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#4F46E5"/>
        <stop offset="100%" stop-color="#9333EA"/>
      </linearGradient>

      <!-- Tipografía “robusta” embebida en SVG (fallback a sans-serif si no carga) -->
      <style>
        <![CDATA[
        .title {
          font: 700 48px/1.2 ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, "Helvetica Neue", Arial, "Apple Color Emoji", "Segoe UI Emoji";
          letter-spacing: 0.5px;
        }
        .subtitle {
          font: 500 16px/1.2 ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, Arial;
          fill: #64748B;
        }
        /* Cursor parpadeante */
        .caret {
          animation: blink 1s step-start infinite;
        }
        @keyframes blink { 50% { opacity: 0; } }

        /* Efecto “escritura”: se revela con un rectángulo que se ensancha */
        ]]>
      </style>

      <!-- Clip que se expande para “descubrir” el texto -->
      <clipPath id="reveal">
        <rect id="revealRect" x="40" y="40" width="0" height="60" rx="4" ry="4">
          <animate attributeName="width" from="0" to="740" dur="3.2s" fill="freeze" begin="0.2s"/>
        </rect>
      </clipPath>
    </defs>

    <!-- Texto principal con degradado y efecto de revelado -->
    <g clip-path="url(#reveal)">
      <text x="40" y="84" class="title" fill="url(#grad)">¡Hola! Soy Roberstxx</text>
    </g>

    <!-- Cursor que “sigue” la escritura -->
    <rect x="40" y="50" width="2" height="44" fill="#6D28D9" class="caret">
      <animate attributeName="x" from="40" to="780" dur="3.2s" fill="freeze" begin="0.2s"/>
    </rect>

    <!-- Subtítulo fijo -->
    <text x="40" y="112" class="subtitle">Desarrollador en formación · Web · Python · Datos</text>
  </svg>
</p>

<!-- Descripción (tu mismo texto, ligeramente pulido) -->
Soy un desarrollador en formación, con muchas ganas de crecer. Actualmente estoy aprendiendo desarrollo web, Python y bases de datos, pero también me interesan áreas como la seguridad informática, la inteligencia artificial y el análisis de datos.

Aquí comparto proyectos que reflejan mi camino de aprendizaje. Algunos están en proceso; otros son ideas que voy puliendo con el tiempo. Me interesa crear soluciones útiles, entender cómo funcionan las cosas por dentro y escribir código que tenga sentido, incluso si todavía estoy aprendiendo a hacerlo mejor cada día.

También estoy explorando diseño de interfaces, automatización, organización de horarios y cómo usar la programación para resolver problemas reales.

Este perfil no es una vitrina perfecta: es una bitácora de lo que voy aprendiendo, construyendo y soñando. 🚀

---

<!-- Caja de herramientas con borde “autodibujado” -->
<!-- NOTA: todo el contenido está dentro del propio SVG para que el borde animado encierre el texto sin usar CSS externo -->
<p align="center">
  <svg width="860" height="260" viewBox="0 0 860 260" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Herramientas que estoy aprendiendo">
    <defs>
      <style>
        <![CDATA[
        .box-title {
          font: 700 20px ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, Arial;
          fill: #0F172A;
        }
        .item {
          font: 500 16px ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Ubuntu, Cantarell, Noto Sans, Arial;
          fill: #1F2937;
        }
        .muted {
          fill: #64748B;
        }
        ]]>
      </style>

      <!-- Trayecto del marco (rectángulo con esquinas redondeadas) -->
      <path id="frame" d="M20,20 h820 a12,12 0 0 1 12,12 v196 a12,12 0 0 1 -12,12 h-820 a12,12 0 0 1 -12,-12 v-196 a12,12 0 0 1 12,-12 z" />
    </defs>

    <!-- Borde que se dibuja con stroke-dasharray -->
    <use href="#frame" fill="white" />
    <use href="#frame"
         fill="none"
         stroke="#6D28D9"
         stroke-width="2.5"
         stroke-linecap="round"
         stroke-dasharray="2080"
         stroke-dashoffset="2080">
      <animate attributeName="stroke-dashoffset" from="2080" to="0" dur="2.6s" fill="freeze" begin="0.4s"/>
    </use>

    <!-- Título -->
    <text x="40" y="60" class="box-title">🔧 Herramientas que estoy aprendiendo</text>

    <!-- Lista (usa bullets con emojis para más legibilidad) -->
    <text x="60" y="95" class="item">• HTML, CSS, JavaScript</text>
    <text x="60" y="122" class="item">• Python y Tkinter</text>
    <text x="60" y="149" class="item">• Git y GitHub</text>
    <text x="60" y="176" class="item">• Bases de datos (MongoDB, SQL)</text>
    <text x="60" y="203" class="item">• Diseño responsivo y desarrollo de interfaces</text>

    <!-- “En camino” -->
    <text x="560" y="95" class="box-title">📚 En camino</text>
    <text x="560" y="122" class="item muted">• Frameworks web</text>
    <text x="560" y="149" class="item muted">• Seguridad informática</text>
    <text x="560" y="176" class="item muted">• Y mucho más…</text>
  </svg>
</p>

---

Si pasas por aquí y ves algo que te gusta (o algo que podría mejorar), ¡siéntete libre de dejar feedback! 🙌
