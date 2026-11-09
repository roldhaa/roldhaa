<!-- Profile source of truth: https://github.com/roldhaa/roldhaa -->
<p align="center">
  <img src="./assets/header.svg" width="100%" alt="Harold Tcheuko Wouassi | Full-stack and mobile developer in Montréal | UQAM | Français / English" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/haroldtch/"><img src="https://img.shields.io/badge/Let's_connect-0A66C2?style=for-the-badge" alt="Connect with Harold on LinkedIn" /></a>
  <a href="https://github.com/roldhaa?tab=repositories"><img src="https://img.shields.io/badge/Explore_my_projects-181717?style=for-the-badge&amp;logo=github&amp;logoColor=white" alt="Explore my GitHub repositories" /></a>
  <a href="https://screenshot-debugger.vercel.app"><img src="https://img.shields.io/badge/Try_Screenshot_Debugger-155E75?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white" alt="Try the Screenshot Debugger live demo" /></a>
</p>

<p align="center">
  <b>Building useful software, from the first idea to the final product.</b><br />
  <sub>Open to software development jobs and internships in Greater Montréal.</sub>
</p>

<p align="center">
  <a href="#-about-me">About</a> ·
  <a href="#-selected-projects">Projects</a> ·
  <a href="#-tech-stack">Tech stack</a> ·
  <a href="#-my-contributions-in-motion">Snake</a> ·
  <a href="#-experience">Experience</a> ·
  <a href="#-en-français">Français</a>
</p>

## 💫 About me

- 🎓 Studying **Computer Science and Software Engineering at UQAM**, after a DEC in Computer Science Technology at **Cégep Édouard-Montpetit**.
- 💻 I build web applications with **Angular, React, Next.js and ASP.NET Core**, and mobile products with **Flutter**.
- 🧠 Interested in **AI integrations, real-time applications and tools that help people learn**.
- 🤝 Experience across **mobile products, client websites and community platforms**.
- 📍 Based in **Montréal, Canada**. Comfortable working in **French and English**.

## 🚀 Selected projects

### 🔍 Screenshot Debugger

> **Comprends ton bug. Apprends à le résoudre.**

Turn an error screenshot into a guided investigation, an explained correction and a reusable Markdown error card.

| Hackathon meta | |
| --- | --- |
| Event | **Hacktoberfest Hack Day Montréal x AGEEI** — 9 October 2026 |
| MLH tracks | Best Use of Gemma 4 · Best Open-Source AI Project |
| Model | Gemma 4 open-weight `gemma-4-26b-a4b-it` (Gemini API = access channel only) |
| Live demo | [screenshot-debugger.vercel.app](https://screenshot-debugger.vercel.app) (Vercel Hobby, free) |
| Source | [roldhaa/screenshot-debugger](https://github.com/roldhaa/screenshot-debugger) · MIT |

![Next.js](https://img.shields.io/badge/Next.js-111111?style=for-the-badge&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Gemma 4](https://img.shields.io/badge/Gemma%204-1C315E?style=for-the-badge&logo=google&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-243426?style=for-the-badge&logo=vitest&logoColor=6E9F18)

**[Launch the demo ↗](https://screenshot-debugger.vercel.app) · [Read the source ↗](https://github.com/roldhaa/screenshot-debugger) · [Explore the model harness ↗](https://github.com/roldhaa/screenshot-debugger/blob/main/docs/HARNESS.md)**

<details>
<summary><b>Peek under the hood: AI, validation and engineering decisions</b></summary>

- **Visual AI analysis:** Gemma 4 `gemma-4-26b-a4b-it` reads an error screenshot and the supplied context through the Gemini API.
- **Guided reasoning:** Learn / Direct modes, numbered evidence, observations separated from hypotheses, and follow-up investigation.
- **Explained corrections:** before/after diff, change notes and manual verification steps. The application never executes the fix.
- **Reusable knowledge:** export a Markdown error card and retain it in the browser.
- **Reusable engineering:** an original model harness, Zod-validated reports, a CLI sharing the web diagnostic logic, and an Agent Skill.

**Stack:** Next.js · React · TypeScript · Tailwind CSS · Zod · `@google/genai` · Vitest · **Vercel**.

The API key stays on the server (`GEMINI_API_KEY`, never `NEXT_PUBLIC_`), uploaded images are validated, and suggestions remain under the user's control. Public source code under the **MIT license**. Built on **9 October 2026**.

</details>

<br />

| Project | What I built | Explore |
| :--- | :--- | :--- |
| 🗺️ **Nid de poule** | Road-hazard reporting prototype with photos, geolocation, **Flutter, Firebase and Mapbox**. | [Source & setup ↗](https://github.com/roldhaa/niddepoule) |
| 🃏 **Super Cartes Infinies** | Multiplayer card game with **Angular, ASP.NET Core, SignalR**, JWT authentication and asynchronous matchmaking. | [Project overview ↗](https://github.com/roldhaa/Super-Cartes-Infinies-demo) |
| 💬 **Post Hub** | Forum platform with **Angular, ASP.NET Core and SQL Server**, hierarchical roles, media management and Swagger documentation. | [Project overview ↗](https://github.com/roldhaa/Posthub-demo) |

<sub>Super Cartes Infinies and Post Hub are public project presentations. Their repositories do not currently include application source code or runnable demos.</sub>

## 💻 Tech stack

**Web**

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB) ![Next.js](https://img.shields.io/badge/Next.js-111111?style=for-the-badge&logo=nextdotjs&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-0F172A?style=for-the-badge&logo=tailwindcss&logoColor=38BDF8) ![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-111111?style=for-the-badge&logo=shadcnui&logoColor=white)

**Mobile**

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white) ![Android](https://img.shields.io/badge/Android-173C2B?style=for-the-badge&logo=android&logoColor=3DDC84) ![iOS](https://img.shields.io/badge/iOS-111111?style=for-the-badge&logo=apple&logoColor=white)

**Backend & data**

![C#](https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logoColor=white) ![ASP.NET Core](https://img.shields.io/badge/ASP.NET%20Core-512BD4?style=for-the-badge&logo=dotnet&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-20232A?style=for-the-badge&logo=express&logoColor=white) ![SignalR](https://img.shields.io/badge/SignalR-512BD4?style=for-the-badge&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL%20Server-CC2927?style=for-the-badge&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-1E293B?style=for-the-badge&logo=firebase&logoColor=FFCA28)

**Cloud, quality & tools**

![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white) ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white) ![Vitest](https://img.shields.io/badge/Vitest-243426?style=for-the-badge&logo=vitest&logoColor=6E9F18) ![Zod](https://img.shields.io/badge/Zod-3E67B1?style=for-the-badge&logo=zod&logoColor=white)

<details>
<summary><b>Architecture, APIs and development practices</b></summary>

REST APIs · Entity Framework Core · Azure DevOps · Object-oriented programming · MVC · MVVM · Clean Architecture · Agile/Scrum

**AI integration:** Gemma 4 · Gemini API · `@google/genai` · schema validation with Zod.

</details>

## 🐍 My contributions in motion

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/roldhaa/roldhaa/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/roldhaa/roldhaa/output/github-snake.svg" />
    <img alt="Animated snake moving through roldhaa's GitHub contribution calendar" src="https://raw.githubusercontent.com/roldhaa/roldhaa/output/github-snake.svg" width="100%" />
  </picture>
</p>

<p align="center">
  <sub>My GitHub contribution calendar, one square at a time. Refreshed daily.</sub><br />
  <a href="https://github.com/roldhaa/roldhaa/actions/workflows/snake.yml"><img src="https://github.com/roldhaa/roldhaa/actions/workflows/snake.yml/badge.svg" alt="Contribution snake workflow status" /></a>
</p>

<details>
<summary><b>Time capsule: my contribution history, 2022 to September 2026</b></summary>

**952 contributions recorded across 2022–2026.** Public activity and anonymized private contributions.

![All-time GitHub contributions from 2022 to 2026](assets/contributions-all-time.svg)

| Year | Contributions |
| --- | ---: |
| [2026](https://github.com/roldhaa?tab=overview&from=2026-09-01&to=2026-09-25) | 486 |
| [2025](https://github.com/roldhaa?tab=overview&from=2025-12-01&to=2025-12-31) | 311 |
| [2024](https://github.com/roldhaa?tab=overview&from=2024-12-01&to=2024-12-31) | 94 |
| [2023](https://github.com/roldhaa?tab=overview&from=2023-12-01&to=2023-12-31) | 38 |
| [2022](https://github.com/roldhaa?tab=overview&from=2022-12-01&to=2022-12-31) | 23 |
| **Total** | **952** |

*Snapshot: 25 September 2026. This overview does not update automatically. Follow the year links for current counts. These are all years available on this GitHub profile.*

</details>

## 💼 Experience

| Where | What I worked on |
| :--- | :--- |
| **Spryto** · Software development<br /><sub>2024 to September 2026</sub> | Flutter and Firebase mobile product development, including authentication, video streaming and Team of the Week features. |
| **Krunch Marketing** · Web development<br /><sub>October 2025 to present</sub> | Responsive client websites and landing pages built from Figma designs, with design and marketing teams. |
| **Tail'ed** · Software development internship<br /><sub>March to May 2026</sub> | Software development for a community platform. |
| **TD Bank Group** · Bilingual customer support<br /><sub>June 2026 to present</sub> | French and English support for EasyLine banking services and digital platforms. |

## 🏆 Beyond the code

- **OSEntreprendre Challenge 2025:** national finalist in the university category with **Spryto**.
- **ApplÉTS Mobile Challenge 2025:** recipient of an **ÉTS student scholarship**, with a mobile application delivered during a **24-hour hackathon**.
- **Hacktoberfest Hack Day Montréal x AGEEI (9 October 2026):** built **[Screenshot Debugger](https://github.com/roldhaa/screenshot-debugger)** for MLH tracks Best Use of Gemma 4 and Best Open-Source AI Project — live on [Vercel](https://screenshot-debugger.vercel.app).

## 🇨🇦 En français

<details>
<summary><b>Mon profil, mes projets et ce que je recherche</b></summary>

Développeur web et mobile bilingue, diplômé en techniques de l'informatique au Cégep Édouard-Montpetit et étudiant au baccalauréat à l'UQAM.

Je développe des applications avec **Angular, React, Next.js, ASP.NET Core et Flutter**, avec un intérêt pour les applications temps réel, les produits mobiles et les intégrations IA.

Mon projet à découvrir : **[Screenshot Debugger](https://github.com/roldhaa/screenshot-debugger)** (Hacktoberfest Hack Day Montréal x AGEEI, 9 oct. 2026 — Best Use of Gemma 4 · Best Open-Source AI Project). Une capture d'erreur devient une enquête, une correction expliquée et une fiche réutilisable. **[Essayer la démo Vercel ↗](https://screenshot-debugger.vercel.app)**

Je recherche un **emploi ou un stage en développement logiciel dans le Grand Montréal**.

**[Échangeons sur LinkedIn ↗](https://www.linkedin.com/in/haroldtch/)**

</details>

---

<p align="center">
  <b>Build something useful. Learn something new. Keep going.</b><br />
  <sub>Thanks for stopping by. Let's build something together.</sub>
</p>

