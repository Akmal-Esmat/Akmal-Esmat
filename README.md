<!-- ============ NEOFETCH CARD ============ -->
<div align="center">
  ### 💻 System Info
  <a href="https://github.com/jeantimex/neofetch-profile">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://neofetch-profile.vercel.app/api?username=Akmal-Esmat&theme=github-dark"/>
      <img alt="Neofetch Stats" src="https://neofetch-profile.vercel.app/api?username=Akmal-Esmat&theme=github-dark"/>
    </picture>
  </a>
</div>

<br/>

<!-- ============ WAKATIME AUTO-SYNC BLOCK ============ -->
<div align="center">
  ### ⏱️ Coding Activity
  <!--START_SECTION:waka-->
  <!--END_SECTION:waka-->
</div>

<br/>

<!-- ============ CONTRIBUTION SNAKE ============ -->
<div align="center">
  ### 🐍 Contribution Activity
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Akmal-Esmat/Akmal-Esmat/output/github-contribution-grid-snake-dark.svg"/>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Akmal-Esmat/Akmal-Esmat/output/github-contribution-grid-snake.svg"/>
    <img src="https://raw.githubusercontent.com/Akmal-Esmat/Akmal-Esmat/output/github-contribution-grid-snake.svg" width="100%" alt="Contribution Snake"/>
  </picture>
</div>

<br/>

<details>
<summary>⚙️ <b>Workflow Configuration (snake.yml)</b></summary>

```yaml
name: generate-snake

on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:
  push:
    branches: [ main ]

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        id: snake-gif
        with:
          github_user_name: Akmal-Esmat
          outputs: |
            dist/github-contribution-grid-snake-dark.svg?palette=github-dark
            dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
