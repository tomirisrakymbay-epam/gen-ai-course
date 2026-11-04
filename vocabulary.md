## 1. Core Model Architectures & Paradigms
* **Large Language Model (LLM)**
Definition: A type of artificial intelligence model trained on vast amounts of text data to understand, summarize, generate, and predict human-like textual content using deep neural networks (predominantly Transformers).

* **Transformer Architecture**
Definition: The foundational deep learning architecture behind modern GenAI models that uses self-attention mechanisms to weigh the importance of different tokens in an input sequence regardless of their positional distance.

* **Multimodal AI**
Definition: AI systems capable of processing, understanding, and generating content across multiple modalities simultaneously, such as text, vision, audio, and structured data.

* **Diffusion Model**
Definition: A class of generative models primarily used for visual media generation that works by systematically removing noise from a randomized signal to construct high-fidelity images or video.

## 2. Data Integration & Architecture
* **Retrieval-Augmented Generation (RAG)**
Definition: An architectural pattern that enhances model outputs by dynamically retrieving relevant facts, passages, or records from external enterprise knowledge stores and passing them into the model's context window during prompting.

* **Embeddings**
Definition: Dense mathematical vector representations of text, images, or audio where items with semantic similarity are positioned close to each other in a high-dimensional vector space.

* **Vector Database**
Definition: A specialized database designed to store, index, and query high-dimensional vector embeddings efficiently using similarity search algorithms (e.g., Cosine Similarity, Euclidean Distance).

* **Chunking**
Definition: The process of splitting large source documents into smaller, semantically coherent blocks of text suitable for vector indexing and retrieval in RAG systems.

## 3. Engineering & Steering
* **Prompt Engineering**
Definition: The practice of structuring, optimizing, and refining text inputs and system instructions to guide generative models toward producing accurate, relevant, and properly formatted outputs.

* **Context Window**
Definition: The maximum amount of information (measured in tokens) that a generative model can process, read, and retain at any single point of interaction.

* **Token / Tokenization**
Definition: The fundamental unit of text (such as a word, sub-word, or character sequence) processed by modern language models; tokenization is the act of converting raw text into these numeric tokens.

* **System Prompt / System Instruction**
Definition: A foundational instruction set provided to an LLM at the beginning of an execution context that defines the model's identity, operational guardrails, formatting rules, and behavior.

## 4. Fine-Tuning & Alignment
* **Fine-Tuning**
Definition: The process of taking a pre-trained base model and further training it on a specific, targeted dataset to adapt its behavior or specialize its domain knowledge.

* **PEFT (Parameter-Efficient Fine-Tuning)**
Definition: A family of techniques (such as LoRA) that updates only a small subset of model parameters during fine-tuning, dramatically reducing computational costs and memory requirements.

* **LoRA (Low-Rank Adaptation)**
Definition: A popular PEFT method that freezes the main pre-trained model weights and injects trainable rank decomposition matrices into the network layers to allow efficient domain customization.

* **RLHF (Reinforcement Learning from Human Feedback)**
Definition: An alignment method where models are trained using reward signals derived from human ratings to align their responses with human intent, safety guidelines, and preferences.

## 5. Agentic Workflows & System Operations
* **AI Agent / Agentic Workflow**
Definition: An autonomous system driven by an LLM that can dynamically reason, plan multi-step execution paths, execute tools/APIs, and evaluate intermediate steps to achieve complex goals.

* **Function Calling / Tool Use**
Definition: The ability of a generative model to evaluate context and return structured parameters (e.g., JSON) designed to trigger external web services, database queries, or code execution.

* **Grounding**
Definition: The practice of anchoring model outputs directly to verifiable, real-world data sources (like real-time APIs or corporate files) to eliminate speculation and lower error rates.

* **Guardrails**
Definition: Safety filters and validation layers placed around AI systems to inspect both user inputs and model responses for security threats, toxic content, or protocol violations.

## 6. Model Behavior & Evaluation
* **Hallucination**
Definition: A phenomenon where a generative AI model generates plausible-sounding but completely inaccurate, ungrounded, or fabricated information.

* **Temperature**
Definition: A hyperparameter controlling the randomness and creativity of a model's sampling choices; lower values produce deterministic outputs, while higher values yield more varied responses.

* **Latency vs. Throughput**
Definition: Latency refers to the total time taken for an AI model to process a request and generate an initial response, whereas throughput measures the volume of tokens produced over a given timeframe (tokens/sec).

* **Catastrophic Forgetting**
Definition: The tendency of an AI model to completely lose previously learned capabilities or general knowledge when continuously trained on a new, narrow task.
Here is the updated vocabulary list incorporating **Test-Driven Development (TDD)**, **Domain-Driven Design (DDD)**, **DevOps / MLOps**, and **API/RAG** technical terms into your GenAI SME dictionary:

## 7. Software Engineering & Architecture (TDD & DDD)

* **Test-Driven Development (TDD)** 
*Definition:* A software development methodology where developers write automated test cases before writing the operational code (Red-Green-Refactor cycle). In GenAI systems, TDD is adapted into

**Eval-Driven Development**, where validation benchmarks and evaluation suites are written before building prompt pipelines or fine-tuning models.

* **Domain-Driven Design (DDD)**
*Definition:* A software design approach focused on modeling complex business domains based on input from domain experts. In GenAI development, DDD ensures that AI system components, agents, and prompt contexts accurately reflect the real-world domain structures, terms, and constraints.

* **Bounded Context**
*Definition:* A core pattern in DDD that defines explicit boundaries within which a specific domain model applies. In GenAI applications, Bounded Contexts help establish clear ownership, distinct prompt engineering rules, and isolated vector retrieval spaces for different business modules.

* **Ubiquitous Language**
*Definition:* A common, rigorous language shared by both domain experts and technical developers. In GenAI engineering, establishing a Ubiquitous Language ensures consistency across system prompts, function schemas, database models, and training datasets.

* **Eval / Evaluation Framework**
*Definition:* The GenAI testing equivalent of unit tests in TDD; an automated test pipeline designed to evaluate model outputs against predefined metrics (such as faithfulness, relevance, toxicity, and semantic similarity).
