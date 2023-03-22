### Olá!!! Eu sou o Luiz Henrique 😉

- 🧠 Estudante do Senac (Técnico em Informática)
- 📖 Estudando Redes e Python 
- 🖥 Técnico em hardware 
- 😄 Pronouns: ele/dele

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Luizynhoo&show_icons=true&theme=radical)

<div style="display: inline_block"><br>
  <img align="center" alt="Rafa-Js" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-plain.svg">
  <img align="center" alt="Rafa-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">
</div>

  ##
  
  <div>
  <a href="https://instagram.com/luiz._siilva" target="_blank"><img src="https://img.shields.io/badge/-Instagram-%23E4405F?style=for-the-badge&logo=instagram&logoColor=white" target="_blank"></a>
  </div>
  
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
  ![](https://raw.githubusercontent.com/Luizynhoo/Snake-in-Contribution-Grid/output/github-contribution-grid-snake.svg) 
