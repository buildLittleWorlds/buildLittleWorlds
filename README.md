## Understanding AI: Theory to Practice

Three course series that teach AI from foundations to application—using data you can't Google.

---

### The Problem With Most AI Education

You can find tutorials on "how to use transformers" anywhere. But:
- Most teach you to call APIs without understanding what's happening
- Standard datasets (iris, titanic, MNIST) let students copy answers from the internet
- Theory courses and practical courses rarely connect

These courses take a different approach.

---

## The Three Series

### 1. Types & Computation — *What is computation?*

Before neural networks, before transformers, there was lambda calculus. This series teaches the foundations of computation through fictional scholars grappling with classification paradoxes.

| Course | Technical Content |
|--------|-------------------|
| [The Pure Passage Calculus](https://github.com/buildLittleWorlds/types-pure-passage-calculus) | Lambda calculus, beta reduction, Church encodings |
| [Combinatorial Reduction](https://github.com/buildLittleWorlds/types-combinatorial-reduction) | Combinatory logic (computation without variables) |
| [Typed Passages](https://github.com/buildLittleWorlds/types-typed-passages) | Simply typed lambda calculus |
| [Continuous Domains](https://github.com/buildLittleWorlds/types-continuous-domains) | Domain theory, fixed points |
| [Dependent Classifications](https://github.com/buildLittleWorlds/types-dependent-classifications) | Dependent types |
| [Normalization](https://github.com/buildLittleWorlds/types-normalization) | Normalization and termination |
| [Equivalence via Passage](https://github.com/buildLittleWorlds/types-equivalence) | Homotopy Type Theory |

*Why this matters for AI:* Type systems constrain what programs can do. Understanding types helps you understand why certain model architectures work and others don't.

---

### 2. Category Theory & LLMs — *Why do transformers work?*

Category theory reveals the mathematical structure underneath attention mechanisms. This series shows that Query-Key-Value decomposition, multi-head attention, and residual streams aren't arbitrary design choices—they emerge naturally from categorical structure.

| Course | Technical Content |
|--------|-------------------|
| [Relational Foundations](https://github.com/buildLittleWorlds/category-relational-foundations) | Categories, morphisms, composition |
| [Weighted Passages](https://github.com/buildLittleWorlds/category-theory-weighted-passages) | Enriched categories, attention as weighted morphisms |
| [Document Functors](https://github.com/buildLittleWorlds/category-theory-document-functors) | Presheaves, embeddings as functors |
| [Natural Transformations](https://github.com/buildLittleWorlds/category-theory-natural-transformations) | Coherent representation shifts |
| [The Probing Lemma](https://github.com/buildLittleWorlds/category-theory-probing-lemma) | Yoneda perspective on embeddings |
| [Linguistic Categories](https://github.com/buildLittleWorlds/category-theory-linguistic-categories) | Language structure as category |
| [Attention and Enrichment](https://github.com/buildLittleWorlds/category-theory-attention-enrichment) | Full transformer architecture |

*Why this matters for AI:* When you understand *why* transformers work mathematically, you can reason about their behavior instead of treating them as black boxes.

---

### 3. Applied AI Infrastructure — *How do you build with transformers?*

The practical series. Go from using pre-trained models to building a complete domain-specific AI system with RAG and fine-tuning.

| Course | What You Build |
|--------|----------------|
| [The Archivist's Inference Engine](https://github.com/buildLittleWorlds/archivist-inference-engine) | Use HuggingFace pipelines for NLP tasks |
| [The Expedition Cartographer's Workshop](https://github.com/buildLittleWorlds/expedition-cartographer-workshop) | Embeddings and semantic search |
| [The Space Builders of Mirado](https://github.com/buildLittleWorlds/space-builders-mirado) | Deploy apps with Gradio and HF Spaces |
| [The Forge at Yeller Quarry](https://github.com/buildLittleWorlds/forge-yeller-quarry) | Fine-tune models with LoRA |
| [The Densworld Oracle](https://github.com/buildLittleWorlds/densworld-oracle) | Build RAG systems with LlamaIndex |
| [The Wanderer's Experiments](https://github.com/buildLittleWorlds/wanderer-experiments) | Model evaluation and selection |

*Why this matters:* These are the skills in demand right now—embeddings, fine-tuning, RAG, deployment.

---

## How They Connect

**Types & Computation** → **Category Theory & LLMs** → **Applied AI Infrastructure**

1. **Understand computation** — What does it mean to compute? Lambda calculus shows that computation is transformation.
2. **Understand transformers** — Category theory reveals why attention mechanisms work. They're not arbitrary; they emerge from mathematical structure.
3. **Build with transformers** — Apply that understanding to real systems: RAG, fine-tuning, deployment.

You can take any series independently. But together, they provide depth that most AI education lacks.

---

## What Makes These Different

**Uncheateable datasets.** All courses use data from Densworld—a fictional universe I've been building for years. Students can't Google "Yeller Quarry creature migration patterns" because no one else has analyzed this data. The skills transfer; the context is unique.

**Theory connects to practice.** The category theory series explains *why* attention mechanisms work. The types series explains *what* computation is. The applied series uses that understanding to build real systems.

**Fiction as pedagogy.** Each course is taught through fictional scholars whose philosophical frameworks map to real techniques. Kelleth Mund's "Pure Passage Calculus" is lambda calculus. Tessery Vold's "Relational Framework" is category theory. The fiction forces understanding deep enough to embed concepts in narrative.

---

## Who Is This For?

I'm genuinely testing this. These courses might be valuable for:
- **Self-learners** who want depth, not just API calls
- **Undergraduates** in CS or math who want applied AI with theoretical grounding
- **Working engineers** who want to understand what they're building
- **High schoolers** in AI clubs who want something beyond tutorials
- **Corporate training** programs that need uncheateable assessments

If you use these courses and find them valuable (or not), I'd like to know.

---

## Getting Started

**New to programming?** Start with the [Applied AI series](https://github.com/buildLittleWorlds/archivist-inference-engine)—it teaches practical skills with minimal prerequisites.

**Want theoretical foundations?** Start with [Types & Computation](https://github.com/buildLittleWorlds/types-pure-passage-calculus) to understand what computation is, then move to [Category Theory](https://github.com/buildLittleWorlds/category-relational-foundations) to see why transformers work.

**Just want to build?** Jump straight to [The Forge at Yeller Quarry](https://github.com/buildLittleWorlds/forge-yeller-quarry) (fine-tuning) or [The Densworld Oracle](https://github.com/buildLittleWorlds/densworld-oracle) (RAG systems).

All notebooks run in Google Colab—no local setup required.

---

## About

I'm Daniel Plate—AI researcher and professor at [Lindenwood University](https://www.lindenwood.edu/).

**Recent publications:**
- *Beyond Code: Redefining Programming Education Beyond STEM* (CRC Press/Routledge, 2025)
- *The Case Against Disclosure: Defending Creative Autonomy in the Age of AI* (Common Ground, 2025)
- *Generative AI in the English Composition Classroom* (Routledge, 2024)

**Contact:** DPlate@lindenwood.edu

---

*These are personal projects, not institutional materials. The Densworld archive and all derived datasets are original creative and intellectual property.*
