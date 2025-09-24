<div align="center">
  <img src="https://emojis.slackmojis.com/emojis/images/1531845129/4308/blob-wave.gif?1531845129" width="60" />

  <img src="https://raw.githubusercontent.com/Roberstxx/Roberstxx/main/roberstxx-logooo2.gif" alt="¡Hola! Soy Roberstxx" width="500"/>

  **Desarrollador en formación** · Web · Python · Datos
</div>

---

Soy un desarrollador en formación con muchas ganas de crecer. Actualmente estoy aprendiendo desarrollo web, Python y bases de datos, pero también me interesan áreas como la seguridad informática, la inteligencia artificial y el análisis de datos.

Aquí comparto proyectos que reflejan mi camino de aprendizaje. Algunos están en proceso; otros son ideas que voy puliendo con el tiempo. Me interesa crear soluciones útiles, entender cómo funcionan las cosas por dentro y escribir código que tenga sentido, incluso si todavía estoy aprendiendo a hacerlo mejor cada día.

También estoy explorando diseño de interfaces, automatización, organización de horarios y cómo usar la programación para resolver problemas reales.

Este perfil no es una vitrina perfecta: es una bitácora de lo que voy aprendiendo, construyendo y soñando. 🚀

---

### 🛠️ Herramientas que estoy aprendiendo
<div align="center">
  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
    <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white" />
    <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=sqlite&logoColor=white" />
    <img src="https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white" />
  </p>
</div>

---

### 📚 En camino
- 🌐 Frameworks web (Django, Flask, React)
- 🔒 Seguridad informática
- 🤖 Análisis de datos + IA

---

### 📊 Estadísticas de GitHub
<div align="center">

<!-- Streak de commits -->
[![GitHub Streak](https://streak-stats.demolab.com?user=Roberstxx&theme=whatsapp-dark2&card_width=830)](https://git.io/streak-stats)

<!-- Stats generales -->
<img height="200" src="https://github-readme-stats.vercel.app/api?username=Roberstxx&show_icons=true&theme=gotham" />

<!-- Lenguajes principales -->
<img height="200" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Roberstxx&layout=compact&langs_count=8&hide=jupyter%20notebook&card_width=330&theme=gotham" />

</div>

---

### 🐍 Snake de contribuciones
> **Nota:** Para que funcione, debes configurar GitHub Actions con el archivo `generate-snake.yml`.  
> Este archivo generará la animación automáticamente.

```yaml
name: Generate Snake

on:
  schedule: [{ cron: "0 0 * * *" }]
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: Roberstxx
          outputs: |
            dist/github-contribution-grid-snake.svg
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
      - name: Deploy to output branch
        uses: peaceiris/actions-gh-pages@v3
        with:
          personal_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./dist
          publish_branch: output
