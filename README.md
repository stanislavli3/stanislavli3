Hi, I'm Stanislav. I study computer science and business at Lehigh, and for three years I've worked on technical projects: computer vision in plants, AI tools inside companies, blockchain identity, research and startups.

Even my friends at top AI labs write about 95% of their code with AI. The hard part is building something that (1) people like, (2) solves a real business problem, and (3) earns or saves real money, not projected money.

Most of this is enterprise or client work (I promised them security 🙂), so the code is private. Public code is linked.

[stanislavli.xyz](https://www.stanislavli.xyz/) · [LinkedIn](https://www.linkedin.com/in/stanislavli/) · [X](https://x.com/stanislavlii)

&nbsp;

## Work

| Project | Problem | Technical complexity | Stack |
|---|---|---|---|
| **Vision quality checks**<br><sub>Freshpet · 2025 to 2026</sub> | Manual visual QA on production lines. | Computer vision inference on live line cameras across 3 plants. Thresholds tuned to the cost of a false reject vs a miss. Human-in-the-loop review that feeds labels back, plus event-driven alerting to QA. | Python, FastAPI, React, TypeScript, Docker, Azure |
| **Approved-sources assistant**<br><sub>Freshpet · 2026</sub> | No safe way to query approved research. | Retrieval restricted to an approved corpus. Every citation is verified server-side before an answer is shown. Guardrails enforced in code and covered by tests; secrets and model calls stay server-side behind SSO. | TypeScript, Node.js, React, RAG, SSO |
| **Identity verification**<br><sub>Oracle · 2026</sub> | Regulated issuers need KYC before using a blockchain network. | Port of a DID registry from permissioned-chain chaincode to EVM smart contracts with operation-level parity. Signature and nonce based authorization; schema, credential definition and revocation registries; integration tests on a local Besu network. | Solidity, Hardhat, Hyperledger Besu, TypeScript, Docker |
| **Research pipelines**<br><sub>Lehigh CV Lab · 2024 to 2025</sub> | Slow, GPU-heavy data processing. | Automated a manual, GPU-bound data pipeline to cut compute cost and iteration time. Built an evaluation harness for ranking bias in multimodal retrieval. | Python, PyTorch, GPUs |

## Startups and client work

| Project | Problem | Technical complexity | Stack |
|---|---|---|---|
| **Yük**<br><sub>Logistics · 2026</sub> | Freight dispatch runs in chat groups, with no system of record. | LLM extraction of noisy, multilingual chat messages into typed orders. Multi-tenant isolation at the database layer with Postgres row-level security. Real-time tracking with background GPS on iOS and Android. An agent limited to typed, tenant-scoped MCP tools, red-teamed for prompt injection and gated by evals. Infrastructure as code on AWS. | FastAPI, Claude, Postgres (RLS), React, React Native, MCP, AWS, Terraform |
| **Ragu**<br><sub>Payments · 2026</sub> | Every bank and QR provider is a separate integration. | One API over heterogeneous bank and QR provider APIs, with idempotent requests, HMAC-signed webhooks and reconciliation against provider reports. Compliance invariants (no funds held, no card data) enforced in code and in CI. | TypeScript, Next.js, Postgres, Redis, MCP, Docker, GitHub Actions |
| **Operations ledger**<br><sub>Drinks maker · 2026</sub> | Stock, production and debts tracked on paper. | Four transaction types as the single source of truth, with every report derived from them. Accounting rules enforced as database constraints and triggers. A natural-language query box limited to fixed, parameterized queries. | Next.js, TypeScript, Postgres, Drizzle, Docker |
| **Sani School**<br><sub>Education · 2025</sub> | Mixed-level online classes. | Clustering students by placement results into same-level groups of four. Site served from the edge. | React, TypeScript, Cloudflare, clustering |
| **nawa**<br><sub>Video studio · 2026</sub> | Needed a fast site built around heavy video. | Static-exported site with scroll-driven animation and video-heavy pages kept fast; CI deploys. | Next.js, TypeScript, Tailwind, GSAP, GitHub Actions |

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
