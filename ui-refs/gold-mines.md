# UI "Gold Mines" — Koleksi Referensi Component

Disimpan 2026-08-12 (dari tweet @alaymanguy + riset lanjutan). Semua link diverifikasi.

## A. AI-Native / Agent Interfaces (paling relevan)

| # | Nama | Link | Isi | Lisensi |
|---|------|------|-----|---------|
| 1 | Beautiful UI | https://beautiful-ui-five.vercel.app/ | 19 primitives AI-native: thinking traces, streaming text+sources, approval card, tool chips, task rows, prompt bar, recommendation+confidence, context cards, diff table, insight cards, selection actions | Free copy-paste |
| 2 | AI Elements (Vercel) | https://elements.ai-sdk.dev/ | Prebuilt composable AI SDK components: Conversation, Message, PromptInput; streaming + status states + type-safe; ganti ChatSDK | MIT (AI SDK) |
| 3 | assistant-ui | https://www.assistant-ui.com/ | React chat UI ChatGPT-like, streaming, tool calls, generative UI; integrasi Vercel AI SDK | OSS |
| 4 | CopilotKit | https://www.copilotkit.ai/ | SDK agent UI: chat, streaming, tool calls, HITL (human-in-the-loop), generative UI; CopilotChat/Sidebar/Popup | MIT |
| 5 | Deep Chat | https://deepchat.dev/ | AI chat component injectable, semua framework (React/Vue/Angular/vanilla), connect semua AI provider | OSS |
| 6 | HuggingFace Chat UI | https://github.com/huggingface/chat-ui | Codebase open-source di belakang HF Chat; theming env-driven | OSS |
| 7 | Loquix (dev.to) | https://dev.to/alexander_lukashov/i-evaluated-every-ai-chat-ui-library-in-2026-heres-what-i-found-and-what-i-built-4p10 | Evaluasi semua AI chat UI library 2026 (assistant-ui, Deep Chat, AI SDK, dll) + web component custom | Artikel |

## B. Marketplace & Registry (copy-paste)

| # | Nama | Link | Isi |
|---|------|------|-----|
| 8 | 21st.dev | https://21st.dev/ | Marketplace komponen shadcn oleh design engineers; paste ke AI tool; `npx shadcn` install |
| 9 | Origin UI | https://originui.com/ | 500+ copy-paste components React+Tailwind, extension shadcn |
| 10 | Watermelon UI | https://ui.watermelon.sh/ | 260+ components premium (Tailwind+Radix+Framer), blocks, dashboards, templates; install via shadcn registry |
| 11 | Kibo UI | https://www.kibo-ui.com/ | shadcn-based, React+TS+Tailwind+Lucide+Radix |

## C. Animasi & Efek

| # | Nama | Link | Isi |
|---|------|------|-----|
| 12 | Magic UI | https://magicui.design/ | 150+ animated components/effects free, React+TS+Tailwind+Motion; companion shadcn |
| 13 | Aceternity UI | https://ui.aceternity.com/ | Animated copy-paste components + blocks (3D cards, shaders, logo clouds); free + Pro |
| 14 | Liquid Metal | https://metal.jakubantalik.com/ | WebGL metal shader effect untuk buttons/UI; 3 presets (Jakub Antalik) |

## D. Dashboard / Data

| # | Nama | Link | Isi |
|---|------|------|-----|
| 15 | Tremor | https://tremor.so/ | 35+ components charts/dashboards, Tailwind+Radix, aksesibel, copy-paste |
| 16 | Catalyst (Tailwind) | https://tailwindcss.com/plus/ui-kit | UI kit app React+Tailwind+Headless UI; bagian Tailwind Plus (berbayar) |

## E. General (fallback)

- shadcn/ui — https://ui.shadcn.com/ (base semua registry di atas)
- Radix UI — https://www.radix-ui.com/ (headless primitives)
- Untitled UI — https://www.untitledui.com/ (design system React)

## Rekomendasi Pakai (konteks Rafi)

- **MangRAG** → AI Elements (Vercel) utk chat streaming; Beautiful UI utk thinking/approval/sources; Context Cards persis pola citation MangRAG.
- **Dashboard XAU** → Tremor utk chart/stat; Insight Cards dari Beautiful UI.
- **Job aggregator** → Origin UI/Watermelon utk filter table; 21st.dev utk cari komponen cepat.
- **Portofolio** → Magic UI/Aceternity utk hero animasi (hati-hati: disiplin Tasteskill — 1 accent, jangan mesh blob).

## Catatan Lisensi

- Free copy-paste: Beautiful UI, Magic UI, Origin UI, Watermelon UI, Kibo, 21st.dev (community), AI Elements.
- OSS: assistant-ui, CopilotKit (MIT), Deep Chat, Tremor, HF Chat UI.
- Berbayar: Aceternity Pro (sebagian), Catalyst/Tailwind Plus.
