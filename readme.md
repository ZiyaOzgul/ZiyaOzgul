```console
$ whoami
ziya özgül · ankara, tr
i build mobile, web and desktop apps on my own, from the first screen to the store release.
lately, most of them have a language model somewhere inside.
```

```console
$ git log --reverse --date=format:%Y --format="%ad  %s" -- career/
2021  learn react, start freelancing: 10+ client sites on fiverr & upwork
2022  embedded c internship @ takosan: automotive displays over uart/spi/i2c
2023  switch to react native + expo
2024  mobile internship @ bites: replace a 3rd-party video player, bundle -10–15%
2024  build nixara: astrology app, 5 ai features, live on app store + google play
2025  build shapely: ai writing app in 5 languages, gpt-4o/gemini routed by plan
2025  start a legal ai assistant for turkish law
2026  build a restaurant pos for friends: electron + next.js + react native, one backend
2026  start anatomicana: human anatomy in 3d, modelled bone by bone
```

### currently open in my editor

**legal ai assistant**: an agent that reads a case file, pulls related court decisions and constitutional articles, and helps a lawyer decide what to do next.

```text
 case.pdf ──▶ split (turkish-aware) ──▶ embed ──▶ pgvector
                                                    │
                                                    ▼
 calendar ◀── petition draft ◀── agents ◀── precedents + articles
                                 gpt · claude · gemini
```

I tested it with a lawyer on their real case files. Most of what broke wasn't the prompts. It was how Turkish words were being split before retrieval.

**anatomicana**: an anatomy learning app. I'm building the 3d models myself, along with a muscle and bone reference library. Right now I'm working on dissection-level detail while keeping it smooth on a phone.

### things i made because i needed them

- a gym tracker, because i didn't want to pay for one
- an app that tracks my cat's food, water, vet visits and vaccines

### a rule i keep

> AI writes a lot of my first drafts. Nothing ships until I've read it, tested it and watched it run against real use.
> (claude code and cursor daily; jest, vitest, pytest, maestro, appium for the checking part.)

```jsonc
// ~/package.json
{
  "name": "ziya",
  "dependencies": {
    "react": "since 2021",
    "react-native": "since 2023",          // + expo, eas
    "typescript": "everywhere",
    "next": "*", "node": "*", "electron": "*", "flutter": "*",
    "postgres": "*", "supabase": "*", "firebase": "*", "convex": "*", "mongodb": "*",
    "openai": "*", "anthropic": "*", "gemini": "*", "pgvector": "*",
    "docker": "*", "kubernetes": "*", "n8n": "*"
  },
  "repository": "you're looking at it"
}
```

[ziya-özgül.com](https://ziya-özgül.com) · [linkedin](https://linkedin.com/in/ziyaozguldeveloper)

<br/>

<img src="https://raw.githubusercontent.com/ZiyaOzgul/ZiyaOzgul/main/github-isocalendar.svg" alt="contribution calendar"/>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ZiyaOzgul/ZiyaOzgul/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ZiyaOzgul/ZiyaOzgul/output/github-contribution-grid-snake.svg"/>
  <img alt="contribution snake" src="https://raw.githubusercontent.com/ZiyaOzgul/ZiyaOzgul/output/github-contribution-grid-snake.svg"/>
</picture>
