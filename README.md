<div align="center">

# Keshav Prasad

**Full Stack Developer** · Final-year B.Tech CSE @ IIIT Naya Raipur '27

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=16&pause=1000&color=7F77DD&center=true&vCenter=true&width=480&lines=TypeScript+%7C+Node.js+%7C+Next.js+%7C+MongoDB;Production-grade+full+stack+systems;Ex-Full+Stack+Intern+%40+Elevance+Skills;Open+to+SDE+roles+—+2027+grad)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/keshavprasad-ai/)
[![LeetCode](https://img.shields.io/badge/LeetCode_1748-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/vCtAUvUZ5B/)
[![Codeforces](https://img.shields.io/badge/Codeforces_Pupil-1F8ACB?style=for-the-badge&logo=codeforces&logoColor=white)](https://codeforces.com/profile/keshavssp04)
[![CodeChef](https://img.shields.io/badge/CodeChef_1669-5B4638?style=for-the-badge&logo=codechef&logoColor=white)](https://www.codechef.com/users/keshavssp04)

</div>

---

## About

Final-year Computer Science undergrad at **IIIT Naya Raipur** (2023–2027). I build full stack systems end to end — and I care most about the parts that only show up under load: concurrent writes, cache behaviour, and tests that try to break invariants rather than just cover lines.

Previously a **Full Stack Developer intern at Elevance Skills**, where I shipped features on a production platform used by real users.

- 🎯 **Open to SDE / Full Stack roles** — 2027 graduate
- 💼 Ex-Intern, Full Stack Developer @ Elevance Skills
- 🧠 Active competitive programmer — LeetCode 1748, Codeforces Pupil, CodeChef 1669
- 💬 Ask me about: system design, API design, MongoDB internals, DSA

---

## Featured Projects

### ⚡ [SnapCDN](https://github.com/Keshavsspppp/SnapCDN) — Three-tier image CDN

A self-hosted content delivery layer for images, built to cut cold-path latency to near-zero on repeat requests.

- **Three-tier cache hierarchy** — in-memory → disk → origin, so hot assets never touch the slow path
- **Cut p50 latency from ~1.6s to ~3ms** on cached reads
- **Security-hardened** — validated uploads, signed access, and protection against path traversal on the storage layer
- Designed around cache-key correctness so stale or poisoned entries can't be served

`Node.js` · `TypeScript` · `Caching` · `Image Processing`

---

### 🏬 [darkstore-allocation-engine](https://github.com/Keshavsspppp/darkstore-allocation-engine) — Quick-commerce order allocation

Given a customer location and a cart, finds the nearest dark store that can fulfil the **entire** order and reserves the stock — without ever overselling.

- **Geospatial discovery** — MongoDB `$geoNear` over a 2dsphere index returns in-radius stores pre-sorted by distance
- **Atomic reservation** — `findOneAndUpdate` with stock guards decrements inventory in one operation, so concurrent orders can't claim the same unit
- **Full-cart availability scan** — candidates checked nearest-first; partial fulfilment rejected before any write
- **Property-based testing** with `fast-check` plus integration tests on `mongodb-memory-server`

`Node.js` · `TypeScript` · `Express` · `MongoDB` · `Zod` · `Jest` · `fast-check`

---

### 📋 [Trackerr](https://github.com/Keshavsspppp/Trackerr) — Job application tracker

Tracks an application from first apply to offer. Built as a real product — deployed, authenticated, with a background job that nudges you about applications going stale.

- **Google OAuth via NextAuth** with stateless JWT sessions — no DB lookup per request, scales horizontally
- **Automated stale-application reminders** — Vercel Cron hits a secret-protected endpoint daily, emails via Resend for anything untouched 7+ days
- **Server-side dashboard aggregation** — per-status breakdown and interview-rate stats in Server Components
- **50 tests across 7 files** — unit plus property-based tests using `fast-check`

`Next.js 16` · `TypeScript` · `MongoDB Atlas` · `NextAuth.js` · `Resend` · `Vercel Cron` · `Vitest`

<div align="center">

*More on the [repositories tab](https://github.com/Keshavsspppp?tab=repositories) →*

</div>

---

## Tech Stack

**Languages**
<p><img src="https://skillicons.dev/icons?i=cpp,c,python,ts,js,html,css" /></p>

**Frontend**
<p><img src="https://skillicons.dev/icons?i=react,nextjs,redux,tailwind" /></p>

**Backend**
<p><img src="https://skillicons.dev/icons?i=nodejs,express" /></p>

**Databases**
<p><img src="https://skillicons.dev/icons?i=mongodb,mysql,firebase" /></p>

**Tools**
<p><img src="https://skillicons.dev/icons?i=git,github,postman,vercel,vscode" /></p>

---

## Competitive Programming

C++ is my contest language. Regular practice is where the instinct for edge cases and complexity trade-offs in the projects above comes from.

| Platform | Handle | Rating |
|---|---|---|
| [LeetCode](https://leetcode.com/u/vCtAUvUZ5B/) | `vCtAUvUZ5B` | **1748** contest rating |
| [CodeChef](https://www.codechef.com/users/keshavssp04) | `keshavssp04` | **1669** highest |
| [Codeforces](https://codeforces.com/profile/keshavssp04) | `keshavssp04` | **1207** — Pupil |

---

## GitHub Stats

<div align="center">

<img height="150" src="https://github-readme-stats.vercel.app/api?username=Keshavsspppp&show_icons=true&theme=tokyonight&hide_border=true&hide=issues" />
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Keshavsspppp&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" />

</div>

---

<div align="center">

**Open to SDE / Full Stack opportunities** — reach me on [LinkedIn](https://www.linkedin.com/in/keshavprasad-ai/) or at keshavssp04@gmail.com

</div>
