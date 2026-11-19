<h1 align="center">Hi, I'm Toiba Zehra </h1>
<h3 align="center">B.Tech CSE (AI/ML) • Builder • Research Enthusiast</h3>

<p align="center">
I build tools for learning, verification, and the gap between "looks right" and "can prove it."
</p>

<p align="center">
<img src="https://img.shields.io/badge/EdTech-9b59b6?style=flat-square" />
<img src="https://img.shields.io/badge/Applied%20AI%20%26%20RAG-3498db?style=flat-square" />
<img src="https://img.shields.io/badge/Verifiable%20Credentials-2980b9?style=flat-square" />
<img src="https://img.shields.io/badge/Interactive%20Visualization-e67e22?style=flat-square" />
<img src="https://img.shields.io/badge/Computational%20Linguistics-27ae60?style=flat-square" />
</p>

Most of what's here starts from the same place: the parts of learning that felt broken when I was the one in the classroom, bored, lost, or too embarrassed to ask. I also tutor students up to grade 12, which keeps me honest about what actually helps someone understand something. The newer work asks a second question: how do you build software that can show its work instead of just sounding confident?

---

## Learning

<table>
<tr>
<td width="50%" valign="top">

### [Forge](https://github.com/toibawani/forge)
Daily skill practice: 5 to 15 minute challenges in coding, design, writing, and analysis that add up to a record of what someone can actually do. Users get a streak and a history of scored attempts; recruiters will be able to filter by consistency and quality over time. Built so far: auth, a practice runner with server-measured sessions, immutable attempts, scoring, a dashboard, and DPDP-compliant account deletion and consent. Not live yet. The recruiter search and the skill progression system are still to come.

`Next.js` `Supabase` `TypeScript`

</td>
<td width="50%" valign="top">

### [Gloss](https://github.com/toibawani/gloss)
Explains NCERT textbooks line by line for NEET, JEE, and UPSC students. The first release covers Class 11 Biology chapters 8 and 9. It's an installable PWA with no backend and no accounts: progress and spaced revision (1, 3, 7, 21 days) live on the device, and the content is validated JSON.

`React` `Vite` `TypeScript` `Zod`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [Velora](https://github.com/toibawani/Velora)
A learning platform built around hands-on visual simulations instead of passive content. Streak tracking, a personal dashboard, smart revision, and a flow-state game are being built out on top of it.

`React 18` `Canvas API` `Web Audio API`

</td>
<td width="50%" valign="top">

### [Visiq](https://github.com/toibawani/Visiq)
Interactive science simulations you can push around until the concept clicks, rather than read about and forget. Currently being rebuilt with a better interface and more simulations.

`JavaScript` `p5.js`

</td>
</tr>
</table>

---

## Systems and verification

<table>
<tr>
<td width="50%" valign="top">

### [Clausewright](https://github.com/toibawani/clausewright)
Question answering over contracts that cites its sources or declines to answer. Contracts have structure (Article, Section, Subsection, cross-references), and fixed-size chunking destroys it, so I chunk along that hierarchy, retrieve with dense embeddings plus BM25 fused by Reciprocal Rank Fusion, and check every citation against what was actually retrieved. Built from scratch, no LangChain. A retrieval eval baseline and a CI regression gate are in the repo. LLM answer quality hasn't been evaluated yet, so there are no accuracy claims here.

`Python` `FastAPI` `FAISS` `SQLite`

</td>
<td width="50%" valign="top">

### [Meritos](https://github.com/toibawani/meritos)
A proof-of-competence platform: a credential you can verify cryptographically instead of a certificate you have to take on trust. did:merit identity, W3C Verifiable Credentials, Merkle receipts, and zero-knowledge disclosure, so you can prove one thing without handing over everything else.

`TypeScript` `Next.js` `WebCrypto`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [envcheck](https://github.com/toibawani/envcheck)
A small CLI that finds drift across your `.env*` files: missing keys, typos, empty values, orphans, duplicates. It catches the bug that only shows up in production because staging had the variable and prod didn't.

`TypeScript`

</td>
<td width="50%" valign="top">

### [kashmir-land-plan](https://github.com/toibawani/kashmir-land-plan)
Many farmers in Jammu & Kashmir have land sitting unused or half-used and no clear place to start. You enter plot size, water access, and your main difficulty, and get 2 to 3 practical options plus a checklist of who to ask and what to check. It doesn't promise subsidies or tell anyone what to do. It's an offline-first PWA in vanilla JavaScript with no backend, no login, and 168 automated tests, plus printable sheets for all 20 districts to take to the agriculture office. The Hindi and Urdu text still needs a native speaker's review, and I haven't run it with real users yet.

`JavaScript` `PWA`

</td>
</tr>
</table>

---

<details>
<summary><b>Earlier work</b></summary>
<br>

- **[Aurelia](https://github.com/toibawani/aurelia)**: a calmer task manager for people who find most productivity apps more stressful than helpful (React, TypeScript, Vite)
- **[Lerno](https://github.com/toibawani/Lerno)**: a bite-sized daily facts app (React Native, Expo)
- **[Calculam](https://github.com/toibawani/calculam)**: a calculation workspace for finance, science, and everyday math (React, TypeScript, Vite)
- **[Shrinking Room](https://github.com/toibawani/Shrinking-Room)**: a puzzle game where the room physically shrinks while you solve it (JavaScript, Canvas)

</details>

---

## Technologies

**Languages:** Python, TypeScript / JavaScript, C++
**Frontend:** React, Next.js, Vite, Canvas API, p5.js
**Backend and retrieval:** FastAPI, Supabase, FAISS, BM25, SQLite
**Tools:** Git, GitHub Actions, Expo

---

## Beyond code

I've published two books, one on philosophy and relationships and one of poetry, and I debate competitively. Writing and teaching are why I care so much about explanations that actually land.

---

## Get in touch

toibawani14@gmail.com
