![](https://raw.githubusercontent.com/4arjun/4arjun/main/header.png)
<h1 align="center">Hi, I'm <a href="https://www.linkedin.com/in/4arjun" target="_blank">Arjun Ajith</a></h1>


<img width="40%" align="right" src="https://github.com/SauravMukherjee44/SauravMukherjee44/blob/03193437b82d681c9caa24657c4ebec746dc628f/workbench.svg">

I'm a final-year Computer Science student and full-stack engineer. I'm a **Top 15 contributor** to [Gumroad](https://github.com/antiwork/gumroad)'s open-source codebase (by merged PRs), with **25+ merged pull requests** spanning large-scale Inertia.js migrations, a **150x performance fix**, and root-cause debugging of race conditions and payment failures on a live platform used by 90k+ creators. Outside of that, I build backend systems with Django and REST APIs, and craft interfaces with React — and I'm always looking for the next hard problem to dig into.

<br clear="right"/>

<h2 align="center">🚀 Open Source @ Gumroad</h2>

<p align="center">Production-impact contributions to <a href="https://github.com/antiwork/gumroad">antiwork/gumroad</a> — a live SaaS platform.</p>

- 🏆 **Top 15 contributor** to Gumroad Open Source by merged PRs, with **25+ PRs** merged across performance, reliability, and payments systems
- ⚡ Migrated **5 major creator-facing pages** (Discover, Library/Reviews/Wishlists, UTM Analytics, PDF Reader, Video Streaming) from legacy Rails + React-on-Rails to **Inertia.js** — deferred props on the Discover page cut load time from **~5 seconds to near-instant**
- 📉 Cut computational overhead by **150x** by replacing O(n) array lookups with a memoized Map, reducing ~90,000 comparisons to ~600 on a 300-file product
- 🐛 Diagnosed and fixed a stale-closure **race condition** that silently blocked product saves and navigation — a community **bounty-earning fix ($100)**
- 💳 Restored payout access for creators in **Kazakhstan** by identifying a Stripe cross-border restriction and rerouting payouts through PayPal
- 🎨 Resolved multiple UI regressions from a large-scale SCSS-to-Tailwind CSS migration — including a second **bounty-earning fix ($100)**

<h1 align="center">Technical Skills</h1>

<p align="center">Full-stack development with production experience across React, Django, and Docker — backed by real open-source and internship works</p>

<p align="center">

   <!-- Frontend -->
   <img alt="HTML5" src="https://img.shields.io/badge/html5-%23E34F26.svg?&style=for-the-badge&logo=html5&logoColor=white" />
   <img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?&style=for-the-badge&logo=css3&logoColor=white" />
   <img alt="JavaScript" src="https://img.shields.io/badge/javascript-%23323330.svg?&style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" />
   <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
   <img alt="Next.js" src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white" />
   <img alt="Inertia.js" src="https://img.shields.io/badge/Inertia.js-9553E9?style=for-the-badge&logo=inertia&logoColor=white" />
   <img alt="Tailwind CSS" src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />

   <!-- Backend -->
   <img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
   <img alt="Django" src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white" />
   <img alt="Django REST Framework" src="https://img.shields.io/badge/Django_REST-ff1709?style=for-the-badge&logo=django&logoColor=white" />
   <img alt="REST API" src="https://img.shields.io/badge/REST_API-02569B?style=for-the-badge&logo=fastapi&logoColor=white" />
   <img alt="OAuth" src="https://img.shields.io/badge/OAuth-4285F4?style=for-the-badge&logo=google&logoColor=white" />

   <!-- Data -->
   <img alt="Pandas" src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
   <img alt="scikit-learn" src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white" />
   <img alt="OpenCV" src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" />

   <!-- Databases & Infra -->
   <img alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" />
   <img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
   <img alt="Kafka" src="https://img.shields.io/badge/Kafka-231F20?style=for-the-badge&logo=apachekafka&logoColor=white" />
   <img alt="Microsoft Azure" src="https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoft-azure&logoColor=white" />

   <!-- Tools -->
   <img alt="Git" src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
   <img alt="GitHub" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
   <img alt="Postman" src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />
   <img alt="Linux" src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" />

</p>

<h1 align="center">Projects</h1>

| Project | Description |
| :---: | :--- |
| [Vitalia.ai](https://github.com/4arjun/Vitalia.ai) | AI-powered nutrition and health insights app — Django REST APIs for barcode-based product analysis (OpenCV/Pyzbar), OpenFoodFacts integration, and OpenAI-powered ingredient-risk insights. |
| [AmpPay](https://github.com/4arjun/AmpPay) | Real-time energy monitoring platform — Django backend ingesting live Arduino sensor data, with a Pandas/scikit-learn predictive billing model to forecast usage and estimate bills. |
| [My Portfolio Website](https://arjunajith.netlify.app/) | Personal portfolio site built with HTML5, CSS3, and JavaScript. |
| [InterviewPrep](https://github.com/4arjun/InterviewPrep) | A collaborative platform for sharing coding interview questions, feedback, and mock interview sessions. |
| [TEDxMEC Website](https://github.com/adamsyy/TEDxMEC-23) | Official website for TEDxMEC, showcasing talks and events. |
| [Convovoice](https://github.com/4arjun/convovoice-backend) | AI-powered platform for interactive, conversational language learning. |
| [Knowledger](https://github.com/4arjun/django-test/) | An education platform built on a decentralized chain (ICP). |
| [MerchHub](https://merchhub.excelmec.org/) | Online store for Excel MEC merchandise — shirts, hoodies, and branded gear. |

<h1 align="center">Achievements & Recognition</h1>

<p align="center">

🏆 &nbsp;<b>Top 15 Contributor</b>, Gumroad Open Source — 25+ merged PRs<br>
🧠 &nbsp;<b>650+ DSA problems</b> solved on LeetCode<br>
🥇 &nbsp;<b>Winner, MECLABS 2024</b> — Ranked 1st among 100+ teams across Kerala<br>
🥇 &nbsp;<b>Winner, BitWise Coding Competition</b> — 1st place among 200+ participants<br>
🌍 &nbsp;<b>Millennium Fellow</b> — Selected for a global leadership program by the UN Academic Impact (UNAI) & MCN

</p>

<h1 align="center">Let's Get Connected</h1>

<div align="center">

<a href="https://www.linkedin.com/in/4arjun/" target="_blank"><img alt="LinkedIn" src="https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="https://github.com/4arjun" target="_blank"><img alt="GitHub" src="https://img.shields.io/badge/github-%23121011.svg?&style=for-the-badge&logo=github&logoColor=white" /></a>
<a href="https://twitter.com/Arjunajith__" target="_blank"><img src="https://img.shields.io/badge/twitter-%2300acee.svg?&style=for-the-badge&logo=twitter&logoColor=white&alt=twitter" /></a>
<a href="mailto:arjunajith440@gmail.com"><img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://www.instagram.com/arjunajith__/"><img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white"></a>

</div>
