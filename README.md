<h1 align="center">
<img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center&vCenter=true&width=500&height=70&duration=4000&lines=Hi+There!+👋;+I'm+MithunBaadkar!;" />
</h1>

- uses: Platane/snk@v3
  with:
    
    github_user_name: ${{ github.repository_owner }}

    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

  env:
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


<picture>
  <source media="(prefers-color-scheme: dark)" srcset="github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="github-snake.svg" />
  <img alt="github-snake" src="github-snake.svg" />
</picture>

<!--
**MithunBaadkar/MithunBaadkar** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

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
