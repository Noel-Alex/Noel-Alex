<div align="center">

# Noel Alex

### Building systems that turn unstructured information into useful intelligence.

**AI Systems · Distributed Infrastructure · Document Intelligence · Search & Research Tooling**

<br/>

<a href="https://www.linkedin.com/in/noel-alex-b1731128b/">
  <img src="https://img.shields.io/badge/LinkedIn-Noel_Alex-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:noelalex404@gmail.com">
  <img src="https://img.shields.io/badge/Email-noelalex404%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"/>
</a>
<a href="https://github.com/Noel-Alex?tab=followers">
  <img src="https://img.shields.io/github/followers/Noel-Alex?label=Follow&style=flat-square&logo=github" alt="GitHub followers"/>
</a>

<br/><br/>

`B.Tech CSE — Data Science` · `VIT Vellore` · `Class of 2027`

</div>

---

## About me

I am a Computer Science and Engineering student at **Vellore Institute of Technology**, specialising in **Data Science**.

My work sits at the intersection of **artificial intelligence, distributed systems, information retrieval, and developer infrastructure**. I am especially interested in systems that can ingest large, messy collections of information, preserve where every claim came from, and turn that evidence into something searchable, explainable, and useful.

I enjoy taking projects beyond the demo stage—designing the architecture, building evaluation harnesses, investigating failure modes, adding observability, and making the system reproducible enough for someone else to run.

At VIT, I have served as a **Senior Tech Member at GDG on Campus VIT**, formerly GDSC VIT, helping organise technical initiatives, recruitment, workshops, and large student events.

---

## What I am working on

* **Evidence-grounded research systems** for navigating large multimodal archives
* **Document intelligence pipelines** combining OCR, evidence fusion, reconciliation, confidence scoring, and human review
* **Distributed crawling and search infrastructure** built around Rust, Kafka, ScyllaDB, and containerised workers
* **Knowledge-graph and vector-search systems** with explicit provenance and contradiction handling
* **Agentic workflows** whose outputs remain inspectable, reproducible, and tied to their sources

---

## Selected systems

<table>
<tr>
<td width="50%" valign="top">

### [Stretchy](https://github.com/Noel-Alex/stretchy)

A local-first, evidence-grounded research and investigation system for large multimodal archives.

Stretchy is designed around exact source provenance, durable research workflows, truthful operational telemetry, and a coordinator-owned control plane with replaceable compute workers.

<br/>

`Research Infrastructure` `Local-first` `Multimodal Retrieval` `Provenance`

</td>
<td width="50%" valign="top">

### [ORACLE](https://github.com/Noel-Alex/Oracle)

**Omnidirectional Research Agent with Corpus Logic and Epistemological Engine.**

A distributed research platform combining document ingestion, vector retrieval, typed knowledge graphs, specialist agents, evidence collection, hypothesis generation, contradiction checking, and source-backed report generation.

<br/>

`Python` `LangGraph` `Qdrant` `FalkorDB` `NATS` `FastAPI`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [Arachne](https://github.com/Noel-Alex/Arachne)

A distributed web crawler written in Rust and designed for resilient, high-throughput exploration of the web.

Its coordinator-and-worker architecture uses Kafka for durable task distribution and ScyllaDB for crawl state, metadata, and link-graph persistence.

<br/>

`Rust` `Apache Kafka` `ScyllaDB` `Docker` `Distributed Systems`

</td>
<td width="50%" valign="top">

### [Logos](https://github.com/Noel-Alex/Logos)

The search and indexing counterpart to Arachne.

Logos explores distributed indexing, BM25 and authority-based ranking, sharded query execution, Tantivy-backed retrieval, and low-latency search infrastructure.

<br/>

`Rust` `Tantivy` `BM25` `PageRank` `gRPC` `Information Retrieval`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### [SketchUp MCP](https://github.com/Noel-Alex/sketchup-mcp)

A Model Context Protocol integration that allows AI agents to inspect and control SketchUp.

It connects a Python MCP server to a SketchUp extension over a JSON-based TCP protocol, enabling scene inspection, component manipulation, material control, transformations, and prompt-assisted 3D modelling.

<br/>

`Python` `Ruby` `MCP` `TCP` `AI Tooling`

</td>
<td width="50%" valign="top">

### [UltraChat](https://github.com/Noel-Alex/ultra-chat-backend-GDG)

An AI-enhanced Discord platform developed with the VIT Google developer community.

The project explores chat summarisation, retrieval-augmented conversation memory, authentication, persistent summaries, and scalable community tooling.

<br/>

`LLMs` `RAG` `Discord` `REST APIs` `Collaborative Engineering`

</td>
</tr>
</table>

---

## Engineering interests

### Evidence-grounded AI

I am interested in AI systems that do more than produce convincing text. Their answers should remain connected to inspectable sources, uncertainty should be visible, and conclusions should be reproducible.

### Search and information retrieval

I enjoy working on crawling, parsing, chunking, embeddings, vector search, graph traversal, ranking, entity extraction, and the infrastructure required to make those components work together.

### Distributed systems

Message-driven architectures, horizontal workers, durable queues, failure recovery, storage design, observability, and performance engineering are recurring parts of the systems I build.

### Applied machine learning

My ML work includes NLP, language models, document understanding, entity and relation extraction, retrieval systems, computer vision, classification, and model evaluation.

---

## Technical toolbox

| Area                      | Technologies                                                                                       |
| ------------------------- | -------------------------------------------------------------------------------------------------- |
| **Languages**             | Python, Rust, TypeScript, JavaScript, Java, C, C++, SQL, Bash                                      |
| **Machine learning**      | PyTorch, Transformers, scikit-learn, LangGraph, LangChain, vLLM, GLiNER, Text Embeddings Inference |
| **Retrieval and data**    | Qdrant, FalkorDB, Neo4j, PostgreSQL, ScyllaDB, MongoDB, Tantivy                                    |
| **Distributed systems**   | Apache Kafka, NATS JetStream, worker queues, event-driven pipelines, gRPC                          |
| **Backend and web**       | FastAPI, REST APIs, React, Vite, Node.js                                                           |
| **Infrastructure**        | Docker, Docker Compose, Linux, GitHub Actions, AWS                                                 |
| **Observability**         | Prometheus, Grafana, Loki, Promtail                                                                |
| **Automation and agents** | MCP, tool-calling agents, browser automation, Selenium, structured workflows                       |

---

## How I like to build

```text
Evidence over appearance.
Measurements over assumptions.
Replaceable components over rigid stacks.
Inspectable systems over black boxes.
A working deployment over a perfect diagram.
```

I care about the less glamorous parts of engineering too: benchmarks, contracts, recovery paths, tracing, test coverage, data quality, operational visibility, and honest documentation of what is and is not ready.

---

## Beyond the terminal

When I am not building something unnecessarily ambitious, I am usually reading about science or philosophy, strength training, watching anime, experimenting with hardware, or planning the next unnecessarily ambitious thing.

---

<div align="center">

### Let’s build something difficult and useful.

I am interested in research collaborations, open-source work, and engineering opportunities involving **AI systems, distributed infrastructure, search, document intelligence, and applied machine learning**.

<br/>

<a href="mailto:noelalex404@gmail.com">
  <img src="https://img.shields.io/badge/Start_a_conversation-Email_me-111827?style=for-the-badge&logo=gmail&logoColor=white" alt="Email Noel"/>
</a>

<br/><br/>

<sub>Built with curiosity, excessive benchmarking, and a healthy distrust of unexplained outputs.</sub>

</div>
