Hi, I'm Stanislav. I study computer science and business at Lehigh University.

Over the past three years I've worked on a range of technical projects: computer vision in manufacturing plants, AI tools inside companies, blockchain identity, research pipelines, and a few startups with friends. I like taking something complex and getting it to the point where people actually use it.

Today, even my friends at top AI labs and big tech companies write about 95% of their code with AI. So writing the code is rarely the hardest part. The hard part is everything around it:

1. Making something people actually like to use.
2. Solving a real business problem, not an imagined one.
3. Earning or saving real money, not projected money.

That's what I try to focus on.

Many of these are enterprise or client apps, so the code is private and I can't share it. Each one has a short explanation below; where the code is public, there's a link.

[stanislavli.xyz](https://www.stanislavli.xyz/) · [LinkedIn](https://www.linkedin.com/in/stanislavli/) · [X](https://x.com/stanislavlii)

&nbsp;

## Work

| Project | Problem | What I did | Stack | Code |
|---|---|---|---|---|
| **Vision quality checks**<br><sub>Freshpet · 2025 to 2026</sub> | Pet food plants checked product quality by hand, which is slow and easy to miss. | With a small team, helped bring four computer vision checks into production across three plants. Built the operator app for confirming flagged items and the alert service for QA. | Python, TypeScript, computer vision, Docker | Private<br><sub>enterprise app</sub> |
| **Approved-sources assistant**<br><sub>Freshpet · 2026</sub> | Sales and marketing spent time hunting for research they were allowed to use externally. | Built an internal assistant that answers only from approved documents and shows sources. Helped write the process for approving new AI use cases. | LLMs, retrieval, guardrails | Private<br><sub>enterprise app</sub> |
| **Identity verification (KYC)**<br><sub>Oracle · 2026</sub> | Regulated issuers must verify identity before they can use a blockchain network. | Working with Oracle engineers on a five-person team, built identity verification modules on Hyperledger Besu, including a DID registry ported from Fabric to Solidity. | Solidity, Hardhat, TypeScript | [did](https://github.com/stanislavli3/did)<br><sub>rest private</sub> |
| **Research data pipelines**<br><sub>Lehigh CV Lab · 2024 to 2025</sub> | A U.S. Army funded research program spent too long and too much compute on data processing. | Automated the lab's data processing so researchers could iterate faster. Studied how AI search ranks AI-generated images against real ones. | Python, PyTorch, GPUs | Private<br><sub>research code</sub> |

## Startups and client work

| Project | Problem | What I did | Stack | Code |
|---|---|---|---|---|
| **Yük**<br><sub>Freight dispatch · 2026</sub> | Freight deals in Central Asia are made in Telegram and WhatsApp groups and over the phone. | With my co-founder, built a system that turns those messages into orders, with a dispatch board, truck map and driver app. First customer went live in two weeks. | Python, Pydantic AI, Claude, React | Private<br><sub>company app</sub> |
| **Ragu**<br><sub>Payments · 2026</sub> | Every bank and QR provider in Kyrgyzstan is a separate integration for small businesses. | With two co-founders, built one API and checkout for QR, cards and Apple Pay. Designed so Ragu never holds customer money or sees card data. | TypeScript, Next.js, Postgres, MCP | Private<br><sub>company app</sub> · [site](https://ragu-payments.vercel.app) |
| **Operations ledger**<br><sub>Cold brew maker · 2026</sub> | A small beverage maker ran stock, production and debts on paper and WhatsApp. | Built a Russian-language app with four daily entries that shows cost per bottle, margin by client and overdue debts. | TypeScript, Next.js, Postgres | Private<br><sub>client app</sub> |
| **Sani School**<br><sub>Edtech · 2025</sub> | Children in Kyrgyzstan had few good options for online math and English. | Co-founded the school and ran finance. Built the website and a tool that places each child in a group of four at the same level. | React, TypeScript, clustering | Private<br><sub>company app</sub> |
| **nawa**<br><sub>Launch films · 2026</sub> | Tech companies in the US and MENA need launch videos in Arabic and English. | Part of the studio; built its website. | Next.js, TypeScript, GSAP | Private<br><sub>company site</sub> · [site](https://nawaprod.com/) |

## Open source

| Project | Problem | What it does | Stack | Code |
|---|---|---|---|---|
| **Orbit**<br><sub>Team project · 2026</sub> | Turning CAD files into a list of parts and suppliers is slow, manual work. | Extracts parts from CAD, finds suppliers, drafts outreach and exports a costed bill of materials. I worked on the product, the AI pipeline and AI cost tracking. | Python, TypeScript, Claude, Postgres | [repo](https://github.com/stanislavli3/orbit) · [site](https://orbit-cloud-landing-84.vercel.app/) |
| **RAG optimization agent**<br><sub>2026</sub> | Company AI assistants are usually tuned by hand and rarely tested. | Builds a test set from your documents, then tries and scores different retrieval and prompt settings. | Python, RAGAS, LangChain, React | [repo](https://github.com/stanislavli3/rag-optimization-agent) · [site](https://rag-optimization-agent.vercel.app) |
| **Sputnik**<br><sub>Prototype · 2026</sub> | Business teams wait on analysts for simple questions about ERP data. | An early prototype that answers plain English questions with read-only SQL, a review queue and an audit log. | Python, FastAPI, DuckDB, React | [repo](https://github.com/stanislavli3/sputnik) |
| **Taxi trip-time prediction**<br><sub>Course project · 2026</sub> | Predicting trip times from raw, noisy GPS data. | Map matching plus gradient boosting on San Francisco taxi data, with a classmate. A simple rule came surprisingly close to the full model. | Python, HMM, CatBoost | [repo](https://github.com/stanislavli3/mini-google-map) |
| **Margins**<br><sub>Mac app · 2026</sub> | Highlights from books get lost and never connect. | A Mac reader with colour-coded highlights, notes, ideas linked across books and an end-of-book report. | Swift, SwiftUI | [repo](https://github.com/stanislavli3/margins) |
| **Knowledge database**<br><sub>Prototype · 2024</sub> | Notes and ideas end up scattered. | An early prototype of a notes app that maps how ideas connect. | React, Django | [repo](https://github.com/stanislavli3/Neural-Inspired-Knowledge-Database) |
| **MNIST classifier**<br><sub>Coursework · 2026</sub> | Learning how neural network training works end to end. | A simple PyTorch digit classifier written from scratch. | PyTorch | [repo](https://github.com/stanislavli3/MNISTClassification) |
| **NEAT network**<br><sub>Coursework · 2024</sub> | Learning how network structure itself can be evolved. | Evolved networks with NEAT to play a simple volleyball game, then trained their weights with backpropagation. | Python, JAX, NumPy | Private<br><sub>coursework</sub> |

&nbsp;

Always happy to talk if you're working on something similar.
