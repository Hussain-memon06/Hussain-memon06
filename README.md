# Hussain

**I build AI systems that ship agentic workflows, LLM-powered tools, and full-stack applications with real backends and real users in mind.**

I work primarily on agentic AI and applied LLM systems: orchestration with LangGraph, retrieval and tool use, structured outputs, human-in-the-loop workflows, and the unglamorous infrastructure that makes these things reliable in production. My background is in business, not CS, I taught myself the fundamentals through Harvard's CS50x and the Stanford / DeepLearning.AI specializations, then moved into building. That path means I think about AI products from both sides: what's technically sound and what actually solves a problem someone will pay for.

Currently focused on agentic systems for sales, research, and business automation.

---

## Featured Projects

### Dossify,  AI Lead Research Agent with Human-in-the-Loop
An agentic B2B lead research system. Paste a company URL; the agent researches the company, builds a structured dossier, identifies a likely decision-maker, detects buying signals (hiring, funding, launches, partnerships), scores against a user-defined ICP, drafts a personalized outreach email, and pauses at a human approval gate before sending.

Built as a multi-step LangGraph workflow with durable pause/resume, source-verified anti-hallucination checks, and observability baked in.

**Stack:** LangGraph · LangChain · FastAPI · Next.js · TypeScript · Postgres/Supabase · Tavily · Hunter.io · SendGrid · Langfuse · Docker · Railway · Vercel
**Repo:** [→ Dossify](https://github.com/Hussain-memon06/saas-lead-agent)

### Sales Lead Qualifier, ICP Scoring & Outreach Generator
A lead qualification tool that scrapes a company's site, researches the business, scores it against a configurable Ideal Customer Profile, and generates a tailored outreach email. Returns a Hot/Warm/Cold qualification with a confidence score derived from actual evidence density not LLM guesswork.

Designed deliberately so the **scoring is deterministic and separated from the LLM**. The model is used for understanding and writing; the score itself is auditable and reproducible. Handles unscrapable sites with honest fallback output instead of hallucinating. Supports single-lead and bulk CSV processing.

**Stack:** Next.js · FastAPI · TypeScript · Python · SQLAlchemy · SQLite · Tailwind · Gemini / OpenAI · Vercel · Railway
**Repo:** [→ Sales Lead Qualifier](https://github.com/Hussain-memon06/sales-lead-qualifier)

---

## Foundations

Two from-scratch implementations I built to understand what's actually happening inside the models I use day-to-day:

- **GPT from scratch (PyTorch)** - token + positional embeddings, multi-head self-attention, transformer blocks, training loop, generation. Inspired by Karpathy's tutorial.
- **Micrograd** - scalar autograd engine and MLP from first principles: computational graphs, backprop, neuron/layer/MLP abstractions, gradient descent.

These aren't flagship projects, but they're how I built confidence with the internals rather than treating LLMs as opaque APIs.

Earlier: a Flask quiz app built as my CS50x final project, full routing, sessions, templating, and a JS timer. Useful context for my software-engineering progression, not a portfolio centerpiece.

---

## Tech Stack

**AI / Agents:** LangGraph · LangChain · OpenAI · Gemini · prompt engineering · structured outputs · RAG · tool use · human-in-the-loop workflows
**Backend:** Python · FastAPI · SQLAlchemy · Postgres · SQLite · REST APIs
**Frontend:** TypeScript · Next.js · React · Tailwind CSS
**Infra & Tooling:** Docker · Vercel · Railway · Supabase · Langfuse · Git
**ML Foundations:** PyTorch · TensorFlow · NumPy · neural networks · transformers · backpropagation

---

## Background

I came into AI from a business background, which means I treat shipped, working systems as the real measure of progress. Before building, I worked through serious coursework to make sure my fundamentals were solid:

<details>
<summary><b>Certifications</b></summary>

| Certificate | Institution | Verify |
|---|---|---|
| CS50x: Intro to Computer Science | Harvard | [Link](https://courses.edx.org/certificates/99f005f766664b8c8c6f77e451aaab27) |
| Deep Learning Specialization | DeepLearning.AI | [Link](https://www.coursera.org/account/accomplishments/specialization/76GVZRTMRN2J) |
| Machine Learning Specialization | Stanford Online | [Link](https://www.coursera.org/account/accomplishments/specialization/C8ME7L7JE5BR) |
| Probability & Statistics for ML & Data Science | DeepLearning.AI | [Link](https://coursera.org/verify/specialization/7PERH9S18YYK) |
| Python 3 Programming Specialization | University of Michigan | [Link](https://www.coursera.org/account/accomplishments/specialization/AUZP47B37BP8) |

</details>

---

## Open to

Freelance work and collaboration on agentic AI systems, LLM-powered internal tools, and AI-driven business automation. If you're building something in this space, I'd like to hear about it.

**Contact:** [LinkedIn](https://linkedin.com/in/muhammad-hussain16/)
