## Olá, me chamo Eder Natan, qual a boa?</strong>

  🤔 Estudante de Engenharia de Computação - Desenvolvedor Full Stack<br>
  💬 Alguma dúvida?<br>
  📫 Contate-me no email: edernatan124@gmail.com<br>
  ⚡ Pra quem está perdido, qualquer caminho é lado.


<div style="width: 100%;">
 <h1> <img align="left" src="https://github-readme-stats.vercel.app/api?username=edernatanzz&theme=onedark&show_icons=true" alt="Eder Natan's GitHub stats" height="150" />

  <img align="left" src="https://github-readme-stats.vercel.app/api/top-langs/?username=edernatanzz&theme=onedark&layout=compact" alt="Top Langs" height="150" /></h1>
</div>

<p align="center">
  <img src="https://img.icons8.com/color/48/000000/python.png" alt="Python" />
  <img src="https://img.icons8.com/color/48/000000/java-coffee-cup-logo.png" alt="Java" />
  <img src="https://img.icons8.com/color/48/000000/html-5.png" alt="HTML" />
  <img src="https://img.icons8.com/color/48/000000/css3.png" alt="CSS" />
  <img src="https://img.icons8.com/color/48/000000/javascript.png" alt="JavaScript" />
  <img src="https://img.icons8.com/color/48/000000/django.png" alt="Django" />
</p>

name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  
<p>
  
</p>
