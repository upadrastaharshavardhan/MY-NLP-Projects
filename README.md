# 🧠 Harsha Vardhan — GitHub NLP / AI Project Audit

> **Deep repo-by-repo audit of NLP, RAG, LLM, semantic search, agentic AI and natural-language testing projects.**
>
> **Author:** Upadrasta Harsha Vardhan  
> **GitHub:** https://github.com/upadrastaharshavardhan  
> **Audit focus:** NLP usage, text intelligence, embeddings, retrieval, LLMs, agents, natural-language interfaces and AI-assisted QA.

---

## Executive Summary

This audit separates **true NLP implementations** from projects that merely consume an LLM.

### Strongest NLP projects

| Rank | Repository | NLP Level | Why it matters |
|---|---|---:|---|
| 🥇 | [Token-efficient-rag-V1](https://github.com/upadrastaharshavardhan/Token-efficient-rag-V1) | ⭐⭐⭐⭐⭐ | Explicit NLP/embeddings/retrieval stack: Sentence Transformers, BM25, NLTK, scikit-learn, tiktoken, semantic chunking, query classification, reranking and context compression |
| 🥈 | [TestDNA-AI-Operating-System-v5](https://github.com/upadrastaharshavardhan/TestDNA-AI-Operating-System-v5) | ⭐⭐⭐⭐⭐ | Semantic Search, Engineering Memory, AI Copilot, requirement intelligence, knowledge graph and natural-language interaction |
| 🥉 | [Copilot-for-Playwright-v2](https://github.com/upadrastaharshavardhan/Copilot-for-Playwright-v2) | ⭐⭐⭐⭐⭐ | Plain-English requirement → Gherkin → executable Playwright test; AI generation, RCA and self-healing |
| 4 | [Copilot-for-Playwright-v2.1](https://github.com/upadrastaharshavardhan/Copilot-for-Playwright-v2.1) | ⭐⭐⭐⭐½ | Evolution of the natural-language QA automation workflow |
| 5 | [Copilot-for-Playwright-v3](https://github.com/upadrastaharshavardhan/Copilot-for-Playwright-v3) | ⭐⭐⭐⭐½ | Advanced AI QA generation/orchestration direction |
| 6 | [Playwright-AI-Operating-System-PAIOS](https://github.com/upadrastaharshavardhan/Playwright-AI-Operating-System-PAIOS) | ⭐⭐⭐⭐½ | Requirement intelligence, natural-language QA and autonomous testing |
| 7 | [Playwright-AI-Operating-System-PAIOS-V2](https://github.com/upadrastaharshavardhan/Playwright-AI-Operating-System-PAIOS-V2) | ⭐⭐⭐⭐½ | Expanded AI-QE/NL workflow |
| 8 | [TestDNA-AI-Organization-v3](https://github.com/upadrastaharshavardhan/TestDNA-AI-Organization-v3) | ⭐⭐⭐⭐ | AI organization + semantic/engineering intelligence |
| 9 | [TestDNA-AI-Intelligence-v2](https://github.com/upadrastaharshavardhan/TestDNA-AI-Intelligence-v2) | ⭐⭐⭐⭐ | Intelligence, semantic search and engineering memory direction |
| 10 | [TestDNA-AI-Genesis-v1](https://github.com/upadrastaharshavardhan/TestDNA-AI-Genesis-v1) | ⭐⭐⭐⭐ | Foundation of TestDNA intelligence/memory |
| 11 | [AgenticTestForge-V2](https://github.com/upadrastaharshavardhan/AgenticTestForge-V2) | ⭐⭐⭐⭐ | Agentic natural-language-to-testing workflow |
| 12 | [TestForge-AI-Agents-for-Playwright](https://github.com/upadrastaharshavardhan/TestForge-AI-Agents-for-Playwright) | ⭐⭐⭐⭐ | AI agents for requirement interpretation and test generation |
| 13 | [AgenticTestForge](https://github.com/upadrastaharshavardhan/AgenticTestForge) | ⭐⭐⭐⭐ | Earlier agentic testing implementation |
| 14 | [ai-root-cause-investigator](https://github.com/upadrastaharshavardhan/ai-root-cause-investigator) | ⭐⭐⭐½ | NLP/LLM interpretation of logs and failure explanations |
| 15 | [qgate-ai](https://github.com/upadrastaharshavardhan/qgate-ai) | ⭐⭐⭐½ | AI quality-gate / intelligent QA direction |
| 16 | [Neo-pulse-brain-V2](https://github.com/upadrastaharshavardhan/Neo-pulse-brain-V2) | ⭐⭐⭐½ | Personal AI memory and natural-language interaction |
| 17 | [pulse-meeting-brief-agent](https://github.com/upadrastaharshavardhan/pulse-meeting-brief-agent) | ⭐⭐⭐½ | Meeting text summarization/brief generation direction |
| 18 | [ForgeLM](https://github.com/upadrastaharshavardhan/ForgeLM) | ⭐⭐⭐½ | LLM/model engineering; NLP is intrinsic to the model, but this is better classified as LLM engineering than classical NLP |

> **Important:** A project can use NLP concepts without being a “classical NLP project.” The audit therefore distinguishes **NLP algorithms**, **NLP infrastructure**, **LLM application**, and **agentic natural-language workflows**.

---

# 🔬 Audit Methodology

Each repository is classified against these dimensions:

- **Text processing**
- **Tokenization**
- **NLP libraries**
- **Embeddings**
- **Semantic similarity**
- **Semantic chunking**
- **Query classification**
- **Keyword retrieval / BM25**
- **Vector retrieval**
- **Reranking**
- **RAG**
- **LLM integration**
- **Natural-language interface**
- **Agentic reasoning**
- **Structured output**
- **Evaluation / NLP metrics**
- **QA automation integration**

Confidence levels:

- 🟢 **Verified** — directly supported by repository content/dependencies.
- 🟡 **Strong evidence** — architecture/README clearly describes the capability, but code-level verification is incomplete.
- ⚪ **Likely / architectural** — project direction strongly suggests NLP usage, but it should not be presented as a verified implementation detail.

---

# 🥇 1. Token-efficient-rag-V1

**Repository:** https://github.com/upadrastaharshavardhan/Token-efficient-rag-V1

### NLP classification

**★★★★★ — Strongest explicit NLP repository**

### Verified NLP stack

```text
Sentence Transformers
       │
       ├── Semantic embeddings
       │
       ▼
Semantic / structure-aware chunking
       │
       ▼
Query classification
       │
       ├── JSON retrieval
       ├── BM25
       └── Vector search
              │
              ▼
          Hybrid Retrieval
              │
              ▼
           Reranking
              │
              ▼
      Context Compression
              │
              ▼
             LLM
```

### Explicit NLP dependencies

- `sentence-transformers`
- `rank-bm25`
- `nltk`
- `scikit-learn`
- `tiktoken`
- `numpy`

The repository's requirements explicitly place these under **NLP / Embeddings / Retrieval**.

### NLP capabilities

| Capability | Status |
|---|---|
| Semantic embeddings | ✅ |
| Semantic chunking | ✅ |
| Query classification | ✅ |
| BM25 | ✅ |
| Vector search | ✅ |
| Hybrid retrieval | ✅ |
| Reranking | ✅ |
| Token accounting | ✅ |
| Context compression | ✅ |
| Natural-language QA | ✅ |
| RAG | ✅ |
| Retrieval evaluation | ✅ |
| Faithfulness evaluation | ✅ |
| Citation accuracy | ✅ |

### Why this is valuable

This is not simply “I used OpenAI.”

It demonstrates an actual **information-retrieval/NLP pipeline**:

> document processing → semantic representation → classification → retrieval → ranking → compression → generation.

### Resume keywords

`NLP | Semantic Search | Sentence Transformers | Embeddings | BM25 | Information Retrieval | RAG | Query Classification | Reranking | Context Compression | Token Optimization`

---

# 🥈 2. TestDNA-AI-Operating-System-v5

**Repository:** https://github.com/upadrastaharshavardhan/TestDNA-AI-Operating-System-v5

### Classification

**★★★★★ — Enterprise NLP / Semantic Intelligence / Agentic AI**

The repository explicitly describes:

- Semantic Search
- Engineering Memory
- AI Copilot
- Requirement Intelligence
- Knowledge Graph
- Natural-language interface
- Repository intelligence
- Multi-agent intelligence

### NLP architecture

```text
Engineering Artifacts
        │
        ▼
Repository Intelligence
        │
        ▼
Semantic Representation
        │
        ├── Semantic Search
        ├── Engineering Memory
        ├── Knowledge Graph
        └── Requirement Intelligence
                │
                ▼
             AI Copilot
                │
                ▼
        Agentic Decision / Action
```

### NLP classification

| Area | Assessment |
|---|---|
| Semantic search | ✅ |
| Natural language interface | ✅ |
| Requirement understanding | ✅ |
| Engineering-memory retrieval | ✅ |
| Knowledge representation | ✅ |
| LLM reasoning | ✅ |
| Agentic workflow | ✅ |
| Classical NLP algorithms | ⚪ Not sufficiently verified |

### Best positioning

Do **not** call this merely an NLP project.

Call it:

> **Enterprise semantic intelligence and agentic AI platform with NLP/LLM-powered engineering memory and natural-language interaction.**

---

# 🥉 3. Copilot-for-Playwright-v2

**Repository:** https://github.com/upadrastaharshavardhan/Copilot-for-Playwright-v2

### Classification

**★★★★★ — Applied NLP for QA Automation**

The repository explicitly supports:

```text
Plain-English User Story
        ↓
AI / Template Interpretation
        ↓
Gherkin Feature
        ↓
Playwright Specification
        ↓
Executable Test
```

### Verified capabilities

- Plain-English user stories
- Natural-language test generation
- Gherkin generation
- Python / TypeScript test generation
- Self-healing locator suggestions
- Failure RCA
- Natural-language failure interpretation
- Excel/CSV test-pack processing
- Template-driven language interpretation
- Optional Claude integration

### Important architecture decision

The project deliberately separates:

**Smart Template Mode**

from

**Live AI Mode**

This is important engineering because bulk generation avoids an LLM call for every spreadsheet row.

### NLP classification

**Applied NLP / LLM application — very strong**

### Resume keywords

`Natural Language Processing | LLM | Prompt Engineering | Test Generation | Gherkin | Requirement Understanding | AI QA | Self-Healing | Root Cause Analysis`

---

# 4–5. Copilot-for-Playwright-v2.1 / v3

### v2.1

https://github.com/upadrastaharshavardhan/Copilot-for-Playwright-v2.1

### v3

https://github.com/upadrastaharshavardhan/Copilot-for-Playwright-v3

These represent the evolution of the natural-language QA automation concept.

Core NLP relationship:

```text
Requirement
   ↓
Language Understanding
   ↓
Test Intent
   ↓
Test Structure
   ↓
Automation Code
```

### Classification

**★★★★½ — Applied NLP / Agentic QA**

These should be presented as a **family of AI-assisted test-generation projects**, not three unrelated NLP projects.

---

# 6–7. Playwright AI Operating System

### V1

https://github.com/upadrastaharshavardhan/Playwright-AI-Operating-System-PAIOS

### V2

https://github.com/upadrastaharshavardhan/Playwright-AI-Operating-System-PAIOS-V2

### NLP role

PAIOS applies natural language to Quality Engineering:

```text
Business Requirement
       ↓
Requirement Intelligence
       ↓
Test Design
       ↓
Agent Planning
       ↓
Browser Automation
       ↓
Validation
```

### Classification

**★★★★½ — NLP + LLM + Agentic QA**

Best keywords:

`NLP | Requirement Intelligence | LLM Agents | Autonomous Testing | Natural Language QA | Playwright`

---

# 8–10. TestDNA Intelligence Family

## TestDNA-AI-Genesis-v1

https://github.com/upadrastaharshavardhan/TestDNA-AI-Genesis-v1

## TestDNA-AI-Intelligence-v2

https://github.com/upadrastaharshavardhan/TestDNA-AI-Intelligence-v2

## TestDNA-AI-Organization-v3

https://github.com/upadrastaharshavardhan/TestDNA-AI-Organization-v3

### Evolution

```text
v1
Engineering Memory
      ↓
v2
Intelligence + Semantic Search
      ↓
v3
AI Organization + Multi-Agent Intelligence
      ↓
v4
Autonomous Enterprise
      ↓
v5
AI Operating System
```

These repositories should be treated as a **single technology evolution** when presenting your portfolio.

### NLP relevance

- Semantic search
- Engineering-memory retrieval
- Requirement intelligence
- Natural-language interaction
- AI Copilot
- Knowledge graph
- Agent communication

### Classification

**★★★★ — Semantic/LLM/Agentic NLP**

---

# 11–13. Agentic TestForge Family

## AgenticTestForge

https://github.com/upadrastaharshavardhan/AgenticTestForge

## AgenticTestForge-V2

https://github.com/upadrastaharshavardhan/AgenticTestForge-V2

## TestForge-AI-Agents-for-Playwright

https://github.com/upadrastaharshavardhan/TestForge-AI-Agents-for-Playwright

### Core idea

```text
Natural Language Requirement
          ↓
Agent
          ↓
Planning
          ↓
Test Design
          ↓
Playwright Automation
          ↓
Execution
          ↓
Analysis
```

### Classification

**★★★★ — Applied NLP / Agentic AI**

These are especially relevant to your **AI Automation Tester** profile.

---

# 14. ai-root-cause-investigator

**Repository:** https://github.com/upadrastaharshavardhan/ai-root-cause-investigator

### NLP role

The core problem is natural-language interpretation of technical failure information.

```text
Logs / Stack Trace
       ↓
Text Interpretation
       ↓
Failure Classification
       ↓
Root Cause Reasoning
       ↓
Recommended Fix
```

### Classification

**★★★½ — NLP/LLM applied to software diagnostics**

Strong resume area:

`AI Root Cause Analysis | Log Intelligence | LLM Reasoning | Failure Classification`

---

# 15. qgate-ai

**Repository:** https://github.com/upadrastaharshavardhan/qgate-ai

### Classification

**★★★½ — AI Quality Intelligence**

Potential NLP role:

- interpreting quality signals
- generating quality decisions
- natural-language explanations
- AI-assisted quality gates

Use more conservative wording unless the implementation is further code-audited.

---

# 16. Neo-pulse-brain-V2

**Repository:** https://github.com/upadrastaharshavardhan/Neo-pulse-brain-V2

### Classification

**★★★½ — Personal AI Memory / Natural Language AI**

Conceptually:

```text
User Input
   ↓
Language Understanding
   ↓
Memory Retrieval
   ↓
Context Assembly
   ↓
LLM
   ↓
Personalized Response
```

Best classification:

**AI memory + LLM application**, rather than classical NLP.

---

# 17. pulse-meeting-brief-agent

**Repository:** https://github.com/upadrastaharshavardhan/pulse-meeting-brief-agent

### NLP relevance

Meeting intelligence naturally maps to:

- text understanding
- summarization
- information extraction
- action-item extraction
- meeting brief generation

### Classification

**★★★½ — NLP/LLM productivity application**

---

# 18. ForgeLM

**Repository:** https://github.com/upadrastaharshavardhan/ForgeLM

### Classification

**★★★½ — LLM / Language Model Engineering**

This is important:

ForgeLM is **language-model engineering**, not necessarily a classical NLP pipeline.

You can claim:

`LLM | Language Models | Generative AI | Model Engineering`

but avoid claiming:

`NER | POS Tagging | Dependency Parsing | Classical NLP`

unless those are actually implemented.

---

# 📊 Master NLP Audit Matrix

| Repository | NLP | Embeddings | Semantic Search | RAG | BM25 | LLM | Agents | Natural Language → QA | NLP Confidence |
|---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|---:|
| Token-efficient-rag-V1 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚪ | ⚪ | 🟢 Verified |
| TestDNA-AI-OS-v5 | ✅ | ⚪ | ✅ | ⚪ | ⚪ | ✅ | ✅ | ⚪ | 🟢/🟡 |
| Copilot-for-Playwright-v2 | ✅ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ⚪ | ✅ | 🟢 |
| Copilot-for-Playwright-v2.1 | ✅ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ⚪ | ✅ | 🟡 |
| Copilot-for-Playwright-v3 | ✅ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ✅ | ✅ | 🟡 |
| PAIOS | ✅ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ✅ | ✅ | 🟡 |
| PAIOS-V2 | ✅ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ✅ | ✅ | 🟡 |
| TestDNA Genesis v1 | ✅ | ⚪ | ✅ | ⚪ | ⚪ | ✅ | ⚪ | ⚪ | 🟡 |
| TestDNA Intelligence v2 | ✅ | ⚪ | ✅ | ⚪ | ⚪ | ✅ | ✅ | ⚪ | 🟡 |
| TestDNA Organization v3 | ✅ | ⚪ | ✅ | ⚪ | ⚪ | ✅ | ✅ | ⚪ | 🟡 |
| AgenticTestForge | ✅ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ✅ | ✅ | 🟡 |
| AgenticTestForge V2 | ✅ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ✅ | ✅ | 🟡 |
| TestForge AI Agents | ✅ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ✅ | ✅ | 🟡 |
| AI Root Cause Investigator | ✅ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ⚪ | ⚪ | 🟡 |
| qgate-ai | ⚪ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ⚪ | ⚪ | 🟡 |
| Neo-pulse-brain-V2 | ✅ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ✅ | ⚪ | 🟡 |
| pulse-meeting-brief-agent | ✅ | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ✅ | ⚪ | 🟡 |
| ForgeLM | ✅* | ⚪ | ⚪ | ⚪ | ⚪ | ✅ | ⚪ | ⚪ | 🟡 |

`*` ForgeLM is best classified as language-model engineering rather than classical NLP.

---

# 🧬 NLP Technology Map

```text
                         YOUR NLP PORTFOLIO
                                │
          ┌─────────────────────┼─────────────────────┐
          │                     │                     │
          ▼                     ▼                     ▼
     NLP / IR               LLM APPLICATIONS       AGENTIC AI
          │                     │                     │
          │                     │                     │
   Token-efficient-RAG     Copilot Playwright      TestDNA OS
          │                PAIOS                    AgenticTestForge
          │                Neo-Pulse                V.A.L.I
          │                Meeting Agent            AI RCA
          │                ForgeLLM
          │
          ├── Embeddings
          ├── BM25
          ├── Semantic Search
          ├── Query Classification
          ├── Reranking
          ├── Context Compression
          └── Retrieval Evaluation
```

---

# 🎯 What You Can Claim on Your Resume

## Strong NLP statement

> **Hands-on experience building NLP and GenAI systems involving semantic chunking, embeddings, semantic search, BM25 retrieval, query classification, hybrid retrieval, reranking, context compression, RAG and LLM-powered natural-language interfaces.**

## Strong AI Automation statement

> **Built AI-powered QA systems that transform natural-language requirements into Gherkin and executable Playwright automation, with self-healing locators, AI root-cause analysis and agentic test orchestration.**

## Strong GenAI statement

> **Designed agentic AI platforms combining LLM reasoning, engineering memory, semantic search, multi-agent orchestration and autonomous Quality Engineering workflows.**

---

# 🏆 Best 5 Repositories to Show Recruiters

### 1. Token-efficient-rag-V1
**Best for:** NLP / RAG / Information Retrieval

### 2. TestDNA-AI-Operating-System-v5
**Best for:** Agentic AI / Enterprise AI / Semantic Intelligence

### 3. Copilot-for-Playwright-v2
**Best for:** NLP + QA Automation + LLM

### 4. Playwright-AI-Operating-System-PAIOS
**Best for:** AI Automation / Autonomous QA

### 5. ForgeLM
**Best for:** LLM / Language Model Engineering

---

# 💼 Interview Positioning

If an interviewer asks:

### “Do you have NLP experience?”

Use this answer:

> **Yes. My strongest hands-on NLP work is in my Token-Efficient Adaptive RAG project, where I implemented semantic document processing, semantic chunking, Sentence Transformer embeddings, query classification, BM25 and vector retrieval, hybrid search, reranking and context compression. I also applied NLP/LLM capabilities to TestDNA-AI for semantic engineering search and natural-language interaction, and to my Copilot for Playwright projects for converting natural-language requirements into Gherkin and executable automation.**

### “Is your experience classical NLP?”

> **My experience is primarily modern applied NLP rather than traditional NLP research. I have worked more with semantic representations, embeddings, information retrieval, RAG, language-model applications, text classification and natural-language interfaces than with classical tasks such as POS tagging or dependency parsing.**

This is the most accurate way to position your portfolio.

---

# 📌 Portfolio Classification

| Skill | Portfolio Evidence | Strength |
|---|---|---:|
| NLP | RAG + semantic processing | ⭐⭐⭐⭐⭐ |
| Information Retrieval | BM25 + hybrid retrieval | ⭐⭐⭐⭐⭐ |
| Embeddings | Sentence Transformers | ⭐⭐⭐⭐⭐ |
| Semantic Search | TestDNA + RAG | ⭐⭐⭐⭐⭐ |
| RAG | Token-efficient RAG | ⭐⭐⭐⭐⭐ |
| LLM | ForgeLM / ForgeLLM / Copilot | ⭐⭐⭐⭐⭐ |
| Agentic AI | TestDNA / PAIOS / TestForge | ⭐⭐⭐⭐⭐ |
| AI Testing | Copilot / PAIOS / AgenticTestForge | ⭐⭐⭐⭐⭐ |
| Playwright | Copilot / PAIOS / TestForge | ⭐⭐⭐⭐⭐ |
| Classical NLP | Limited verified evidence | ⭐⭐ |
| Computer Vision | Brain Tumor projects | ⭐⭐⭐ |
| Deep Learning | Brain Tumor / ForgeLM ecosystem | ⭐⭐⭐⭐ |

---

# 🔗 Core Repository Links

- https://github.com/upadrastaharshavardhan/Token-efficient-rag-V1
- https://github.com/upadrastaharshavardhan/TestDNA-AI-Operating-System-v5
- https://github.com/upadrastaharshavardhan/TestDNA-AI-Organization-v3
- https://github.com/upadrastaharshavardhan/TestDNA-AI-Intelligence-v2
- https://github.com/upadrastaharshavardhan/TestDNA-AI-Genesis-v1
- https://github.com/upadrastaharshavardhan/Copilot-for-Playwright-v2
- https://github.com/upadrastaharshavardhan/Copilot-for-Playwright-v2.1
- https://github.com/upadrastaharshavardhan/Copilot-for-Playwright-v3
- https://github.com/upadrastaharshavardhan/Playwright-AI-Operating-System-PAIOS
- https://github.com/upadrastaharshavardhan/Playwright-AI-Operating-System-PAIOS-V2
- https://github.com/upadrastaharshavardhan/AgenticTestForge
- https://github.com/upadrastaharshavardhan/AgenticTestForge-V2
- https://github.com/upadrastaharshavardhan/TestForge-AI-Agents-for-Playwright
- https://github.com/upadrastaharshavardhan/ai-root-cause-investigator
- https://github.com/upadrastaharshavardhan/qgate-ai
- https://github.com/upadrastaharshavardhan/Neo-pulse-brain-V2
- https://github.com/upadrastaharshavardhan/pulse-meeting-brief-agent
- https://github.com/upadrastaharshavardhan/ForgeLM
- https://github.com/upadrastaharshavardhan/ForgeLLM

---

# ⚠️ Audit Integrity Note

This document intentionally separates **verified repository evidence** from **architecture-level inference**.

The GitHub connector exposes repository search and file retrieval, but not every repository currently has an available code-search index. Therefore:

- `🟢 Verified` = supported by files/dependencies/README inspected.
- `🟡 Strong evidence` = supported by repository architecture/description, but deeper source verification is still recommended.
- `⚪` = not verified and should not be claimed as an implementation detail.

The strongest source-verified NLP evidence currently available is **Token-efficient-rag-V1**, whose dependency file explicitly lists Sentence Transformers, BM25, NLTK, scikit-learn and tiktoken under NLP/embeddings/retrieval.

---

## ⭐ Final Portfolio Story

Your GitHub portfolio is best described as:

> **AI Automation + NLP + RAG + Agentic AI + LLM Engineering**

rather than simply:

> “NLP Developer”

Your strongest differentiator is the combination:

```text
NLP / Information Retrieval
          +
LLMs
          +
RAG
          +
Agentic AI
          +
Playwright
          +
Quality Engineering
```

That combination is significantly more distinctive for **AI Automation Engineer, GenAI Engineer, AI QA Engineer, SDET/AI, Agentic AI Engineer and Applied AI Engineer** roles.

---

**Built by Upadrasta Harsha Vardhan**
