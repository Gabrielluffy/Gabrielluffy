### Olá sou Gabriel Santos | Bem vindo ao meu Perfil 👋

- 🎓 Formado em Jogos Digitais ...
- 🎮 Game Developer 
- 🌱 Estou sempre estudando Unity e C# ... 
<br>
<div align="center">
  <a href="https://github.com/gabrielluffy">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=gabrielluffy&show_icons=true&theme=radical&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=gabrielluffy&layout=compact&langs_count=7&theme=radical"/>
</div>

  
 <h4> Linguagens e Ferramentas que eu utilizo : </h4> 
<div style="display: inline_block"><br>
  <img align="center" alt="Csharp" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/csharp/csharp-original.svg">  
  <img align="center" alt="Unity" height="30" width="40" src="https://files.rubixdev.de/logos/unity.svg">
  <img align="right" alt="fall-pic" height="150" style="border-radius:50px;" src="https://media.giphy.com/media/bGgsc5mWoryfgKBx1u/giphy.gif">
</div>

 <div>
![Snake animation](https://github.com/gabrielluffy/gabrielluffy/blob/output/github-contribution-grid-snake.svg)
   
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
 </div>          
          
