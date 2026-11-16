<h1 align="center">Ziya Özgül</h1>

<p align="center">
  <i>I build apps on my own, from the first screen to the store release.</i><br/>
  <sub>ANKARA, TR &nbsp;·&nbsp; MOBILE &nbsp;·&nbsp; WEB &nbsp;·&nbsp; DESKTOP &nbsp;·&nbsp; AI</sub>
</p>

<p align="center">
  <a href="https://ziya-özgül.com">ziya-özgül.com</a> &nbsp;·&nbsp; <a href="https://linkedin.com/in/ziyaozguldeveloper">linkedin</a>
</p>

<br/>

### the road so far

```mermaid
%%{init: {'theme': 'neutral', 'gitGraph': {'mainBranchName': 'web', 'showCommitLabel': true}}}%%
gitGraph
  commit id: "2021 · react"
  commit id: "10+ freelance clients"
  branch embedded
  commit id: "2022 · takosan intern"
  checkout web
  branch mobile
  commit id: "2023 · react native"
  commit id: "2024 · bites intern"
  branch ai
  commit id: "2024 · nixara" type: HIGHLIGHT
  commit id: "2025 · shapely" type: HIGHLIGHT
  commit id: "2025 · legal ai" type: HIGHLIGHT
  checkout web
  merge mobile id: "2026 · restaurant pos"
  checkout mobile
  commit id: "2026 · anatomicana"
```

<sub>highlighted commits have a language model inside.</sub>

<br/>

### currently building

**Legal AI assistant**: an agent for Turkish law. It reads a case file, pulls related court decisions and constitutional articles, and helps a lawyer decide what to do next.

```mermaid
%%{init: {'theme': 'neutral'}}%%
flowchart LR
  pdf[case.pdf] --> split[turkish-aware split] --> db[(pgvector)]
  db --> agents{{agents<br/>gpt · claude · gemini}}
  agents --> petition[petition draft]
  agents --> cal[case calendar]
```

> Tested with a lawyer on their real case files. Most of what broke wasn't the prompts. It was how Turkish words got split before retrieval.

**Anatomicana**: an anatomy learning app. I'm modelling the anatomy in 3D myself.

- [x] 3D anatomy models
- [x] muscle and bone reference library
- [ ] dissection-level detail &nbsp;<sub>← here now</sub>
- [ ] launch

<br/>

### shipped

<table>
  <tr>
    <td width="33%" valign="top">
      <b>Nixara</b><br/>
      <sub>ASTROLOGY · iOS + ANDROID</sub><br/><br/>
      Five personalized AI features on OpenAI and Anthropic, live on the App Store and Google Play.<br/><br/>
      <sub><code>react native</code> <code>convex</code> <code>clerk</code></sub>
    </td>
    <td width="33%" valign="top">
      <b>Shapely</b><br/>
      <sub>AI WRITING APP</sub><br/><br/>
      Writes in five languages and routes between GPT-4o and Gemini depending on the user's plan.<br/><br/>
      <sub><code>gpt-4o</code> <code>gemini</code> <code>firebase</code></sub>
    </td>
    <td width="33%" valign="top">
      <b>Restaurant POS</b><br/>
      <sub>DESKTOP + WEB + MOBILE</sub><br/><br/>
      For a friend's restaurant: an Electron till, a Next.js QR menu and a staff app on one backend.<br/><br/>
      <sub><code>electron</code> <code>next.js</code> <code>supabase</code></sub>
    </td>
  </tr>
</table>

<sub>also made for myself: a gym tracker, and an app for my cat's food, water, vet visits and vaccines.</sub>

<br/>

### tools

| | |
|:--|:--|
| <sub>LANGUAGES</sub> | <kbd>TypeScript</kbd> <kbd>JavaScript</kbd> <kbd>Python</kbd> <kbd>SQL</kbd> <kbd>Dart</kbd> |
| <sub>MOBILE & DESKTOP</sub> | <kbd>React Native</kbd> <kbd>Expo</kbd> <kbd>Flutter</kbd> <kbd>Electron</kbd> |
| <sub>WEB</sub> | <kbd>React</kbd> <kbd>Next.js</kbd> <kbd>Node.js</kbd> <kbd>Express</kbd> <kbd>Tailwind</kbd> |
| <sub>DATA</sub> | <kbd>PostgreSQL</kbd> <kbd>Supabase</kbd> <kbd>Firebase</kbd> <kbd>Convex</kbd> <kbd>MongoDB</kbd> <kbd>MySQL</kbd> |
| <sub>AI</sub> | <kbd>OpenAI</kbd> <kbd>Anthropic</kbd> <kbd>Gemini</kbd> <kbd>RAG</kbd> <kbd>pgvector</kbd> <kbd>agents</kbd> |
| <sub>EVERY DAY</sub> | <kbd>Claude Code</kbd> <kbd>Cursor</kbd> <kbd>Docker</kbd> <kbd>Git</kbd> <kbd>n8n</kbd> |

<br/>

<img src="https://raw.githubusercontent.com/ZiyaOzgul/ZiyaOzgul/main/github-isocalendar.svg" alt="contribution calendar" width="100%"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ZiyaOzgul/ZiyaOzgul/output/github-contribution-grid-snake-dark.svg"/>
  <img alt="contribution snake" src="https://raw.githubusercontent.com/ZiyaOzgul/ZiyaOzgul/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>
