Hi, I'm Stanislav. I study computer science and business at Lehigh, and for three years I've worked on technical projects: computer vision in plants, AI tools inside companies, blockchain identity, research and startups.

Even my friends at top AI labs write about 95% of their code with AI. The hard part is building something that (1) people like, (2) solves a real business problem, and (3) earns or saves real money, not projected money.

Most of this is enterprise or client work (I promised them security 🙂), so the code is private. Public code is linked.

[stanislavli.xyz](https://www.stanislavli.xyz/) · [LinkedIn](https://www.linkedin.com/in/stanislavli/) · [X](https://x.com/stanislavlii)

&nbsp;

## Work

| Project | Problem | What I did | Stack | Code |
|---|---|---|---|---|
| **Vision quality checks**<br><sub>Freshpet · 2025 to 2026</sub> | Manual visual QA on production lines. | Took 4 CV models to prod across 3 plants. Built the human-in-the-loop QA app and a FastAPI alerting service pushing detections to Teams. | Python, FastAPI, React, TypeScript, Docker, Azure | Private |
| **Approved-sources assistant**<br><sub>Freshpet · 2026</sub> | No safe way to query approved research. | Solo-built a RAG assistant with server-side citation checks and guardrails, behind company SSO. Wrote the AI governance tiers. | TypeScript, Node.js, React, RAG, SSO | Private |
| **Identity verification**<br><sub>Oracle · 2026</sub> | Regulated issuers need KYC on-chain. | Ported a DID registry from Fabric chaincode to Solidity; built KYC credential modules on Besu. | Solidity, Hardhat, Hyperledger Besu, TypeScript, Docker | [did](https://github.com/stanislavli3/did) |
| **Research pipelines**<br><sub>Lehigh CV Lab · 2024 to 2025</sub> | Slow, GPU-heavy data processing. | Automated the data pipeline to cut compute cost and iteration time. Ran retrieval-bias evals on AI search. | Python, PyTorch, GPUs | Private |

## Startups and client work

| Project | Problem | What I did | Stack | Code |
|---|---|---|---|---|
| **Yük**<br><sub>Logistics · 2026</sub> | Freight dispatch runs in chat groups, no system of record. | LLM pipeline turning multilingual chats into orders; multi-tenant TMS with live map; driver app with background GPS; MCP agent with typed, tenant-scoped tools behind a 90% eval gate. | FastAPI, Claude, Postgres (RLS), React, React Native, MCP, AWS, Terraform | Private |
| **Ragu**<br><sub>Payments · 2026</sub> | Every bank and QR provider is a separate integration. | Payment orchestration API and hosted checkout (QR, cards, Apple Pay) with HMAC-signed webhooks and reconciliation. Never touches funds or card data. | TypeScript, Next.js, Postgres, Redis, MCP, Docker, GitHub Actions | [site](https://ragu-payments.vercel.app) |
| **Operations ledger**<br><sub>Drinks maker · 2026</sub> | Stock, production and debts on paper. | Ledger with accounting rules enforced in Postgres; unit cost, margin and receivables reports. | Next.js, TypeScript, Postgres, Drizzle, Docker | Private |
| **Sani School**<br><sub>Education · 2025</sub> | Mixed-level online classes. | Built the site and a clustering model that groups students by level. | React, TypeScript, Cloudflare, clustering | Private |
| **nawa**<br><sub>Video studio · 2026</sub> | Needed a fast, cinematic marketing site. | Built the site with scroll-driven animation and CI deploys. | Next.js, TypeScript, Tailwind, GSAP, GitHub Actions | [site](https://nawaprod.com/) |

## Open source

| Project | Problem | What it does | Stack | Code |
|---|---|---|---|---|
| **Orbit**<br><sub>Team project · 2026</sub> | CAD to costed BOM is manual. | CAD and drawing parsing into a structured BOM, cost estimation, supplier agent; per-call LLM cost instrumentation. | Django, Celery, Redis, Postgres, React, Claude, S3, Docker, GitHub Actions | [repo](https://github.com/stanislavli3/orbit) |
| **RAG optimization agent**<br><sub>2026</sub> | RAG pipelines are hand-tuned and untested. | Generates a synthetic eval set from your corpus, then tree-searches 432 pipeline configs scored with RAGAS. | Python, RAGAS, LangChain, ChromaDB, sentence-transformers, Docker | [repo](https://github.com/stanislavli3/rag-optimization-agent) |
| **Sputnik**<br><sub>Prototype · 2026</sub> | Text-to-SQL on ERP data is risky. | Read-only text-to-SQL with risk scoring, review queue, audit log and RBAC. | Python, FastAPI, DuckDB, Pydantic, JWT, GitHub Actions | [repo](https://github.com/stanislavli3/sputnik) |
| **Taxi trip times**<br><sub>Course project · 2026</sub> | ETA from noisy GPS traces. | HMM map matching onto OpenStreetMap, per-segment speed table, gradient-boosted correction. | Python, HMM, OSMnx, CatBoost, LightGBM | [repo](https://github.com/stanislavli3/mini-google-map) |
| **Margins**<br><sub>Mac app · 2026</sub> | Highlights don't connect across books. | Native reader with typed highlights, cross-book idea graph and reports; local-only storage. | Swift, SwiftUI, PDFKit | [repo](https://github.com/stanislavli3/margins) |
| **Knowledge database**<br><sub>Prototype · 2024</sub> | Notes stay disconnected. | Notes app with a planned GNN and LLM linking layer. | React, Django REST, Clerk | [repo](https://github.com/stanislavli3/Neural-Inspired-Knowledge-Database) |
| **MNIST classifier**<br><sub>Coursework · 2026</sub> | Learning the training loop. | MLP digit classifier with a hand-written training loop. | PyTorch | [repo](https://github.com/stanislavli3/MNISTClassification) |
| **NEAT network**<br><sub>Coursework · 2024</sub> | Learning neuroevolution. | Evolved topologies with NEAT, then trained weights with backprop. | Python, JAX, NumPy | Private |

&nbsp;

Always happy to talk if you're working on something similar.
