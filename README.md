Hi, I'm Stanislav. I study computer science and business at Lehigh University.

Over the past three years I've worked on a range of technical projects: computer vision in manufacturing plants, AI tools inside companies, blockchain identity, research pipelines, and a few startups with friends. I like taking something complex and getting it to the point where people actually use it.

Many of these are enterprise or client apps, so the code is private and I can't share it here. I've written a short explanation of each one instead. Where the code is public, there's a link.

[stanislavli.xyz](https://www.stanislavli.xyz/) · [LinkedIn](https://www.linkedin.com/in/stanislavli/) · [X](https://x.com/stanislavlii)

&nbsp;

## Work

**Vision quality checks, Freshpet**<br>
<sub>Enterprise app · private, code can't be shared</sub><br>
Pet food plants check product quality by hand, which is slow and easy to miss. With a small team, I helped bring four computer vision checks into production across Freshpet's three plants: foreign material detection, cut quality grading, pallet label traceability and anomaly detection. I built the operator app where QA confirms or rejects what the model flags, and the alert service that sends detections to the QA team.<br>
<sub>Python, TypeScript, computer vision, Docker</sub>

**Approved-sources assistant, Freshpet**<br>
<sub>Enterprise app · private, code can't be shared</sub><br>
Sales and marketing teams spent time hunting for research they were allowed to use externally. I built an internal assistant that answers only from approved documents and shows its sources, and helped write the process the company now uses to review and approve new AI use cases.<br>
<sub>LLMs, retrieval, guardrails, AI governance</sub>

**Identity verification on enterprise Ethereum, Oracle**<br>
<sub>Enterprise project · registry code public, the rest private</sub><br>
Regulated issuers need to verify identity (KYC) before they can use a blockchain network. Working with Oracle engineers on a five-person team, I built identity verification modules on Hyperledger Besu, including a decentralized identifier (DID) registry ported from Fabric chaincode to Solidity.<br>
<sub>Solidity, Hardhat, TypeScript, Hyperledger Besu</sub> · [did](https://github.com/stanislavli3/did)

**Research data pipelines, Lehigh Computer Vision Lab**<br>
<sub>Research code · private</sub><br>
For a U.S. Army funded materials science program, I automated the lab's data processing so researchers could iterate faster and spend less on compute. I also studied how AI search ranks AI-generated images against real ones.<br>
<sub>Python, PyTorch, GPU computing</sub>

## Startups and client work

**Yük, freight dispatch**<br>
<sub>Company app · private, code can't be shared</sub><br>
In Central Asia, freight deals are made in Telegram and WhatsApp groups and over the phone. With my co-founder, I built Yük, which reads those messages, turns them into structured orders, and gives the company a dispatch board, a map of trucks and a driver app. Our first customer, a logistics company, went live in two weeks.<br>
<sub>Python, Pydantic AI, Claude, TypeScript, React, mobile</sub>

**Ragu, payments for Kyrgyz small businesses**<br>
<sub>Company app · private, code can't be shared</sub><br>
Every bank and QR provider in Kyrgyzstan is a separate integration, so small businesses can't easily bill customers online. With two co-founders, I built one API and hosted checkout for QR, cards and Apple Pay, with subscriptions, payment links and webhooks. It is designed so Ragu never holds customer money or sees card data; the money goes straight from the payer to the merchant's own bank.<br>
<sub>TypeScript, Next.js, Postgres, MCP</sub> · [site](https://ragu-payments.vercel.app)

**Operations ledger for a cold brew maker**<br>
<sub>Client app · private, code can't be shared</sub><br>
A small beverage maker in Bishkek ran stock, production and customer debts on paper and WhatsApp. I built a Russian-language app with four daily entries (receive materials, produce a batch, ship, record a payment) that shows the owner cost per bottle, margin by client and overdue debts. The accounting rules live in the database, and a small Ask box answers questions with fixed, safe queries.<br>
<sub>TypeScript, Next.js, Postgres, Drizzle</sub>

**Sani School, online school for children**<br>
<sub>Company app · private</sub><br>
An online math and English school for children in Kyrgyzstan that I co-founded and helped run as CFO. Besides pricing and fundraising, I built the website and a small clustering tool that places each child in a group of four at the same level.<br>
<sub>React, TypeScript, clustering</sub>

**nawa, launch films**<br>
<sub>Company site · private</sub><br>
A small studio I'm part of, making launch films for tech companies in the US and MENA, in Arabic and English. I built the studio's website.<br>
<sub>Next.js, TypeScript, Tailwind, GSAP</sub> · [nawaprod.com](https://nawaprod.com/)

## Open source

**[Orbit](https://github.com/stanislavli3/orbit)**, a Lehigh team project. Turning CAD files into a list of parts and suppliers is slow, manual work for hardware teams. Orbit extracts the parts from CAD, finds suppliers, drafts outreach and exports a costed bill of materials. I worked on the product, the AI pipeline and measuring what each AI action costs. · [live](https://orbit-cloud-landing-84.vercel.app/)<br>
<sub>Python, TypeScript, React, Claude, Postgres</sub>

**[rag-optimization-agent](https://github.com/stanislavli3/rag-optimization-agent)**. Company AI assistants are usually tuned by hand and rarely tested. This agent builds a small test set from your own documents, then tries different chunking, retrieval, reranking and prompt settings and scores each one. · [live](https://rag-optimization-agent.vercel.app)<br>
<sub>Python, RAGAS, LangChain, ChromaDB, React</sub>

**[sputnik](https://github.com/stanislavli3/sputnik)**. Business teams wait on analysts for simple questions about their ERP data. Sputnik answers them in plain English, checks its own SQL before running it, and only ever reads data, with audit logs and roles.<br>
<sub>Python, FastAPI, DuckDB, React</sub>

**[mini-google-map](https://github.com/stanislavli3/mini-google-map)**, a course project with a classmate. Predicts taxi trip times in San Francisco from raw GPS data, with map matching and gradient boosting. Our main lesson: a very simple rule came surprisingly close to the full model.<br>
<sub>Python, HMM map matching, gradient boosting</sub>

**[margins](https://github.com/stanislavli3/margins)**. A small Mac app for reading PDF and EPUB, with colour-coded highlights, notes, ideas that connect across books, and an end-of-book report.<br>
<sub>Swift, SwiftUI</sub>

**[Neural-Inspired-Knowledge-Database](https://github.com/stanislavli3/Neural-Inspired-Knowledge-Database)**. An early prototype of a notes app that maps how ideas connect.<br>
<sub>React, Django</sub>

**[MNISTClassification](https://github.com/stanislavli3/MNISTClassification)**. A simple PyTorch digit classifier, written from scratch for a course.<br>
<sub>PyTorch</sub>

**NEAT network** (coursework, private). Evolved neural network architectures with NEAT to play a simple volleyball game, then trained their weights with backpropagation.<br>
<sub>Python, JAX, NumPy</sub>

&nbsp;

Always happy to talk if you're working on something similar.
