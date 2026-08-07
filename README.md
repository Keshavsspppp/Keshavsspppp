<div align="center">

# Keshav Prasad

**Full Stack Developer** · Backend-leaning · CSE @ IIIT Naya Raipur '27

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=7F77DD&center=true&vCenter=true&width=460&lines=TypeScript+%7C+Node.js+%7C+Next.js+%7C+MongoDB;Concurrency-safe+backends+%26+clean+APIs;Ex-Intern+%40+Elevance+Skills;Open+to+SDE+%2F+Full+Stack+roles+—+2026)](https://git.io/typing-svg)

</div>

---

## About

CS undergrad at IIIT Naya Raipur. I build backends that behave correctly under concurrent load — atomic writes, race-condition handling, and tests that actually try to break the invariants rather than just cover lines.

- 💼 Ex-Intern, Full Stack Developer @ **Elevance Skills** — worked on the Internarea platform
- 🎯 Open to **SDE / Full Stack** roles — campus placements 2026
- 🏆 1st place, **StatHack** (IIT Goa) — ML + statistics
- 🧠 Competitive programmer — Codeforces, LeetCode, CodeChef
- 🔭 Currently building **assetFlow** — conflict-safe asset management with full audit trails
- 💬 Ask me about: distributed systems, API design, MongoDB internals, DSA

---

## Featured Projects

### 🏬 [darkstore-allocation-engine](https://github.com/Keshavsspppp/darkstore-allocation-engine)

**Nearest-first order allocation backend for quick-commerce.** Given a customer location and a cart, it finds the closest dark store that can fulfil the *entire* order and reserves the stock — without ever overselling.

- **Geospatial discovery** — MongoDB `$geoNear` over a 2dsphere index finds active stores inside the delivery radius, already sorted by distance
- **Atomic reservation** — `findOneAndUpdate` with stock guards decrements inventory in a single operation, so two concurrent orders can't claim the same unit
- **Full-cart availability scan** — candidates are checked nearest-first; partial fulfilment is rejected before any write happens
- **Correctness-focused testing** — property-based tests with `fast-check` plus integration tests on `mongodb-memory-server`
- **Typed end to end** — Zod request validation, centralised error handling, 100% TypeScript

`Node.js` · `TypeScript` · `Express` · `MongoDB` · `Mongoose` · `Zod` · `Jest` · `fast-check`

---

### 📋 [Trackerr](https://github.com/Keshavsspppp/Trackerr)

**Job application tracker that follows an application from first apply to offer.** Built as a real product — deployed, authenticated, and with a background job that nudges you about applications going stale.

- **Google OAuth via NextAuth** with stateless JWT sessions — no DB lookup per request, scales horizontally
- **Automated stale-application reminders** — Vercel Cron hits a secret-protected endpoint daily and sends email through Resend for anything untouched for 7+ days
- **Dashboard aggregation** — per-status breakdown and interview-rate stats computed server-side in Server Components
- **50 tests across 7 files** — unit plus property-based tests using `fast-check`
- **Shipped** — deployed on Vercel with environment-based config and a documented setup path

`Next.js 16` · `TypeScript` · `MongoDB Atlas` · `NextAuth.js` · `Resend` · `Vercel Cron` · `Vitest` · `fast-check`

<div align="center">

*More work — full-stack platforms, ML notebooks, and DSA — on the [repositories tab](https://github.com/Keshavsspppp?tab=repositories) →*

</div>

---

## Tech Stack

**Languages**
<p><img src="https://skillicons.dev/icons?i=ts,js,python,cpp,html,css" /></p>

**Frontend**
<p><img src="https://skillicons.dev/icons?i=react,nextjs,redux,tailwind" /></p>

**Backend & Data**
<p><img src="https://skillicons.dev/icons?i=nodejs,express,mongodb,firebase" /></p>

**Tools**
<p><img src="https://skillicons.dev/icons?i=git,github,vercel,postman,vscode" /></p>

---

## Competitive Programming

Regular practice across Codeforces, LeetCode, and CodeChef — mostly C++. It's where the instinct for edge cases and complexity trade-offs in the projects above comes from.

[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/YOUR_HANDLE/)
[![Codeforces](https://img.shields.io/badge/Codeforces-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/YOUR_HANDLE)
[![CodeChef](https://img.shields.io/badge/CodeChef-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/YOUR_HANDLE)

---

## GitHub Stats

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=Keshavsspppp&show_icons=true&theme=tokyonight&hide_border=true&hide=issues" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Keshavsspppp&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

</div>

---

## Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/keshavprasad-ai/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Keshavsspppp)
[![Email](https://img.shields.io/badge/Email-D4537E?style=for-the-badge&logo=gmail&logoColor=white)](mailto:keshavssp04@gmail.com)

</div>
