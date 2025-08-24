<div align="center">



![Hacker Animation](https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=22&pause=1000&color=00FF00&center=true&vCenter=true&width=500&lines=$+whoami;Hello+I+am+Sreehari+Nair;Welcome+to+my+GitHub;Follow+me+for+Projects+%26+Code)

</div>
 <br/>
 


<!--
**sreeharibsnair/sreeharibsnair** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<div align="center">

[![Instagram](https://img.shields.io/badge/Instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/sreehari.nairr)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:sreeharibsnair04@gmail.com)

</div>

name: Generate Snake

on:
  schedule:
    - cron: "0 */12 * * *"   # every 12 hours
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk/svg-only@v3
        with:
          github_user_name: sreeharibsnair
          outputs: dist/snake.svg
          color_snake: "#39d353" # snake color (bright GitHub green)
          color_dots: "#161b22,#0e4429,#006d32,#26a641,#39d353"
          # matches GitHub contribution graph shades

      - name: Push to GitHub
        uses: crazy-max/ghaction-github-pages@v2
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


<p align="center">
  <img src="https://github.com/Platane/snk/raw/output/github-contribution-grid-snake.svg" alt="snake animation" />
</p>






<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Monospace&size=22&duration=3000&pause=1000&color=00FF00&center=true&vCenter=true&multiline=true&width=600&height=80&lines=>>>+INITIATING+HACKER+MODE;>>>+LOADING+PROJECTS...;>>>+ACCESS+GRANTED" alt="ascii hacker animation"/>
</p>


