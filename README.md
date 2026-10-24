<p align="center">
  <img src="llm-lab-world.png" alt="Pixel-art exploration map connecting an evaluation lab, adapter workshop, retrieval archive and backend power station." width="100%" />
</p>

<h1 align="center">Suryadeepsinh's Engineering Lab</h1>
<p align="center"><strong>AI Platform Engineer · LLM evaluation & fine-tuning · Backend systems</strong><br />Python, TypeScript and the systems around models.</p>

<p align="center">
  <a href="#01-evaluation-chamber">Evaluation chamber</a> ·
  <a href="#02-adapter-forge">Adapter forge</a> ·
  <a href="#03-retrieval-archive">Retrieval archive</a> ·
  <a href="#04-reliability-engine-room">Engine room</a>
</p>

Welcome, explorer. I'm Suryadeepsinh Gohil, an AI Platform Engineer on Syncrope's Data Platform Team. I work across backend engineering, applied AI and LLM evaluation. Pick a room below and open its field notes.

## 01 Evaluation chamber

**The mission: make model behavior inspectable.**

In separate client engagements, I create terminal-based LLM training tasks and evaluate model attempts against instructions and expected outcomes.

<details>
<summary><strong>Open the field notes: tasks, attempts and grading</strong></summary>

- Task authoring for work performed in a terminal environment.
- Reviewing completion, task difficulty and consistency between requirements and grading decisions.
- Examining where a model attempt succeeds, fails or exposes ambiguity in the task.

Client task content and evaluation artifacts remain private. This is task and evaluation work; it does not imply ownership of a full reinforcement-learning training pipeline.

</details>

## 02 Adapter forge

**The mission: adapt a model with a smaller trainable footprint.**

My Syncrope contributions include parameter-efficient fine-tuning of Mistral 7B with QLoRA.

<details>
<summary><strong>Inspect the mechanism: frozen base, trainable adapters</strong></summary>

The base model weights stay frozen in 4-bit NF4 while low-rank adapters are trained. This is the specific method behind the fine-tuning work, rather than a claim of pretraining a foundation model.

</details>

## 03 Retrieval archive

**The mission: connect answers to evidence and bound agent execution.**

On a small team, I contributed to LangGraph orchestration and retrieval fusion across BM25, vector search and knowledge-graph expansion, with bounded critique loops, retry budgets and timeouts.

**[Read the Agentic RAG case study](https://suryadeepsinh-gohil.vercel.app/projects/agentic-rag-knowledge-graph)**

<details>
<summary><strong>Open the map: what you can inspect</strong></summary>

The public case study describes architecture and implementation choices. The underlying application and evaluation artifacts are not published here, so this is an experience write-up rather than a runnable benchmark.

</details>

## 04 Reliability engine room

**The mission: inspect retry and timeout configuration before runtime.**

My backend work spans NestJS/TypeScript workflows with MongoDB state, BullMQ/Redis, and Kafka-based integrations.

**[Explore Stormcheck](https://github.com/Suryadeep02/Stormcheck)**, a small Python static-analysis tool with a CLI, local web UI, example topologies and tests.

<details>
<summary><strong>Open the source hatch: code, tests and boundaries</strong></summary>

- [Analysis engine](https://github.com/Suryadeep02/Stormcheck/blob/main/src/stormcheck/analysis.py)
- [Existing tests](https://github.com/Suryadeep02/Stormcheck/tree/main/tests)
- [CI runs](https://github.com/Suryadeep02/Stormcheck/actions)

It analyzes a declared topology. Its findings depend on that model and the input configuration; it is not a production traffic simulator or an outage-prevention guarantee.

</details>

---

**Back at base:** Python · TypeScript · APIs · durable workflows · data platforms · retrieval · evaluation

I'm interested in remote AI platform, applied AI, forward-deployed engineering and AI-evaluation work.

**[Portfolio](https://suryadeepsinh-gohil.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/suryadeepsinh-gohil/)**

<sub>The map is an illustration. The work descriptions and linked artifacts carry the evidence.</sub>
