<!-- Encabezado animado compatible con GitHub (SVG inline, sin <style>) -->
<p align="center">
  <svg width="860" height="140" viewBox="0 0 860 140" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="¡Hola! Soy Roberstxx">
    <defs>
      <!-- Degradado azul → morado -->
      <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#4F46E5"/>
        <stop offset="100%" stop-color="#9333EA"/>
      </linearGradient>

      <!-- Clip para “revelar” el texto (efecto escritura) -->
      <clipPath id="reveal">
        <rect id="r" x="40" y="40" width="0" height="60" rx="4" ry="4">
          <animate attributeName="width" from="0" to="780" dur="3.0s" fill="freeze" begin="0.1s"/>
        </rect>
      </clipPath>
    </defs>

    <!-- Texto principal con degradado y efecto de revelado -->
    <g clip-path="url(#reveal)">
      <text x="40" y="84" font-size="48" font-weight="700" fill="url(#grad)">¡Hola! Soy Roberstxx</text>
    </g>

    <!-- Cursor que parpadea y avanza -->
    <rect x="40" y="48" width="3" height="44" fill="#7C3AED">
      <animate attributeName="x" from="40" to="820" dur="3.0s" fill="freeze" begin="0.1s"/>
      <animate attributeName="opacity" values="1;0;1" dur="1s" repeatCount="indefinite"/>
    </rect>

    <!-- Subtítulo -->
    <text x="40" y="116" font-size="16" font-weight="600" fill="#475569">Desarrollador en formación · Web · Python · Datos</text>
  </svg>
</p>

<!-- Descripción -->
Soy un desarrollador en formación, con muchas ganas de crecer. Actualmente estoy aprendiendo desarrollo web, Python y bases de datos, pero también me interesan áreas como la seguridad informática, la inteligencia artificial y el análisis de datos.

Aquí comparto proyectos que reflejan mi camino de aprendizaje. Algunos están en proceso; otros son ideas que voy puliendo con el tiempo. Me interesa crear soluciones útiles, entender cómo funcionan las cosas por dentro y escribir código que tenga sentido, incluso si todavía estoy aprendiendo a hacerlo mejor cada día.

También estoy explorando diseño de interfaces, automatización, organización de horarios y cómo usar la programación para resolver problemas reales.

Este perfil no es una vitrina perfecta: es una bitácora de lo que voy aprendiendo, construyendo y soñando. 🚀

---

<!-- Caja de herramientas con borde “autodibujado” (puro SVG, sin CSS externo) -->
<p align="center">
  <svg width="860" height="250" viewBox="0 0 860 250" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Herramientas que estoy aprendiendo">
    <!-- Marco y animación de trazo -->
    <rect x="12" y="12" width="836" height="226" rx="16" ry="16" fill="white" stroke="#6D28D9" stroke-width="3"
          stroke-dasharray="2200" stroke-dashoffset="2200">
      <animate attributeName="stroke-dashoffset" from="2200" to="0" dur="2.4s" fill="freeze" begin="0.4s"/>
    </rect>

    <!-- Títulos -->
    <text x="32"  y="52" font-size="20" font-weight="700" fill="#0F172A">🔧 Herramientas que estoy aprendiendo</text>
    <text x="520" y="52" font-size="20" font-weight="700" fill="#0F172A">📚 En camino</text>

    <!-- Listas -->
    <text x="52" y="86"  font-size="16" fill="#1F2937">• HTML, CSS, JavaScript</text>
    <text x="52" y="114" font-size="16" fill="#1F2937">• Python y Tkinter</text>
    <text x="52" y="142" font-size="16" fill="#1F2937">• Git y GitHub</text>
    <text x="52" y="170" font-size="16" fill="#1F2937">• Bases de datos (MongoDB, SQL)</text>
    <text x="52" y="198" font-size="16" fill="#1F2937">• Diseño responsivo y desarrollo de interfaces</text>

    <text x="520" y="86"  font-size="16" fill="#64748B">• Frameworks web</text>
    <text x="520" y="114" font-size="16" fill="#64748B">• Seguridad informática</text>
    <text x="520" y="142" font-size="16" fill="#64748B">• Análisis de datos + IA</text>
    <text x="520" y="170" font-size="16" fill="#64748B">• Y mucho más…</text>
  </svg>
</p>

---

Si pasas por aquí y ves algo que te gusta (o algo que podría mejorar), ¡siéntete libre de dejar feedback! 🙌

<!-- Tips de edición rápidos:
- Cambia los colores del degradado en <linearGradient id="grad">.
- Ajusta la velocidad de animaciones con los atributos dur="...".
- Todo es SVG inline para máxima compatibilidad con GitHub. -->

