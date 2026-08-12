# Beautiful UI — AI-Native Component Primitives

**Sumber:** https://beautiful-ui-five.vercel.app/ (via tweet @alaymanguy, 11 Agu 2026)
**Konteks:** "gold mine for design engineers building AI interfaces" — copy-paste ready, gaya shadcn untuk AI interfaces.

## Daftar Komponen (19)

| # | Komponen | Fungsi |
|---|----------|--------|
| 01 | Loading State | Pixel-grid loader + shimmer + elapsed time |
| 02 | Thinking | Expandable traces: steps, reasoning, search, coding |
| 03 | Streaming Text | Answer stream + inline sources + actions + follow-ups |
| 04 | Approval Card | Human-in-the-loop question sebelum agent action |
| 05 | Tool Chips | Code edits / tool calls sebagai chips compact |
| 06 | Task Rows | Status task agent live: running, failed, completed |
| 07 | Chat | Tabbed chat panel + reasoning replies + composer |
| 08 | Prompt Bar | Composer: @ sources, / commands, model picker, dictation |
| 09 | Recommendation Card | Saran agent + confidence meter + actions/alternatives |
| 10 | Context Cards | Retrieved knowledge chunks + sumber (PDF/CSV, char count) |
| 11 | Diff Table | AI-proposed edit sweeping tabel data |
| 12 | Records Table | CRM grid: tags, sorting, relationship strength, links |
| 13 | Filter Table | Status chips yang reorganize live data |
| 14 | Sidebar Nav | Workspace nav + quick search + object list |
| 15 | Search | Command search live filtering + empty state |
| 16 | Insight Cards | Paged agent insights + scrub-ready charts |
| 17 | Code Block | Agent code streaming line by line |
| 18 | Fine-tune Card | Agent adjust design props via inspector (radius, opacity, type) |
| 19 | Selection Actions | Highlight teks → hand ke agent: Explain, Improve, Shorten, Tone, Grammar |

## Pola Desain yang Perlu Ditiru

- **Demo case study (gelato)**: satu domain cerita konsisten dipakai semua komponen — bikin tiap primitif kebaca dalam konteks nyata.
- **Status chip** dengan angka count (All 5 / To Do 2 / In Progress 2 / Completed 1).
- **Sumber inline** dengan favicon-style icon per sumber + nama + domain.
- **Confidence meter** (High confidence / Needs review / No signal) pada rekomendasi agent.
- **Elapsed time** pada proses async (4s, 2s) — bikin agent terasa hidup.
- **Empty state** pada command search.

## Relevansi ke Proyek Rafi

- **MangRAG**: streaming text + sources (03, 10) langsung cocok utk jawaban RAG; thinking traces (02) utk pipeline retrieval; approval card (04) utk konfirmasi.
- **Trading dashboard**: insight cards (16) utk analisis; task rows (06) utk sinyal pipeline.
- **Job-app aggregator**: filter table (13) utk hasil scraper.
- **Portofolio**: streaming code block (17) utk demo.

## Catatan

- Site demo Vercel: https://beautiful-ui-five.vercel.app/
- Copy-paste primitives (bukan library terpasang) — tinggal ambil HTML/CSS/JS-nya.
