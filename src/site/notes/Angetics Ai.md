---
{"dg-publish":true,"permalink":"/angetics-ai/","tags":["gardenEntry"],"dg-note-properties":{}}
---

# What is Agentic AI?

**Agentic AI** refers to advanced AI systems that can **independently plan, make decisions, execute actions, and improve their approach** to achieve a specific goal with minimal human supervision.

Unlike traditional Generative AI, which mainly responds to prompts by generating content, Agentic AI can **take action** using external tools, APIs, databases, and software. In simple terms, it works more like a **digital teammate** that can take a goal and work through multiple steps to complete it.

## How Agentic AI Works

Agentic AI generally operates through a continuous feedback cycle known as the **PRAL loop: Perceive, Reason, Act, and Learn**.

### 1. Perceive

The AI gathers information from its environment using sources such as **APIs, websites, databases, applications, and user interactions**. This helps it understand the current situation and available information.

### 2. Reason and Plan

An **LLM acts as the brain** of the system. It analyzes the information, understands the user's goal, and divides the task into smaller, logical steps.

### 3. Act

The agent uses external **tools and APIs** to perform actions. For example, it can execute code, update a database, send an email, or interact with other software instead of simply telling the user how to do something.

### 4. Learn and Adapt

The system evaluates the results of its actions. If something goes wrong, it can identify the problem, make corrections, and modify its approach to achieve the desired outcome.

### PRAL Loop

```
[ PERCEIVE ] → Collects information from APIs, databases, and users
       ↓
[ REASON ]   → Understands the goal and creates a plan
       ↓
[ ACT ]      → Uses tools and APIs to perform actions
       ↓
[ LEARN ]    → Evaluates results and adapts to errors
       ↺
```

# Four Main Components of an Agentic AI System

Agentic AI systems typically rely on four major components:

### 1. The Brain — LLM

The **Large Language Model** provides reasoning, planning, decision-making, and understanding of context. Examples include GPT-based models and Claude.

### 2. Memory Layer

Memory allows an agent to keep track of information. **Short-term memory** manages the current task or conversation, while **long-term memory** can store previous interactions, outcomes, or preferences.

### 3. Tools and APIs

Tools give the AI the ability to interact with the outside world. These can include **email systems, databases, CRMs, calculators, web browsers, and code execution environments**.

### 4. Orchestration Framework

The orchestration layer manages the overall workflow, coordinates different steps, and determines which tools or agents should be used. Frameworks such as **LangChain, Microsoft AutoGen, and CrewAI** can be used for this purpose.

# Traditional AI vs Agentic AI

| **Traditional AI**                      | **Agentic AI**                     |
| --------------------------------------- | ---------------------------------- |
| Responds to individual prompts          | Works toward a complete goal       |
| Mainly reactive                         | Proactive                          |
| Requires frequent instructions          | Can plan independently             |
| Usually handles limited steps           | Performs multi-step reasoning      |
| Limited interaction with external tools | Uses tools, APIs, and software     |
| Mainly provides information             | Can take actions and execute tasks |
| Limited task adaptation                 | Evaluates results and adapts       |

-----


# What is Generative AI?

Generative AI is a branch of Artificial Intelligence that creates new and original content based on user prompts. It can generate text, images, videos, music, audio, presentations, and computer code by learning patterns from large amounts of existing data.

Unlike traditional AI, which mainly analyzes or classifies information, Generative AI produces entirely new outputs that resemble human-created content.

## How Generative AI Works

1. The user enters a prompt (text, image, or instruction).
    
2. The AI analyzes the prompt and understands its context.
    
3. A trained generative model predicts and creates the most relevant output.
    
4. The generated content is returned to the user in seconds.
    

## Categories of Generative AI Tools

| Category         | Examples                                  |
| ---------------- | ----------------------------------------- |
| Text Generation  | ChatGPT, Claude, Gemini                   |
| Image Generation | DALL·E, Midjourney, Adobe Firefly, Lexica |
| Video Generation | Runway, Synthesia, HeyGen, PixVerse AI    |
| Audio & Music    | ElevenLabs, Suno AI, Udio, Moises Studio  |
| Code Generation  | GitHub Copilot, Cursor AI, DeepSeek       |

## Popular Generative AI Tools (One-Line Explanation)

| Tool               | Primary Use                                                                |
| ------------------ | -------------------------------------------------------------------------- |
| ChatGPT            | Generates text, answers questions, writes code, and assists with learning. |
| Google Gemini      | AI assistant for text, coding, reasoning, and multimodal tasks.            |
| Microsoft Copilot  | Enhances productivity in Microsoft 365, Windows, and coding.               |
| Claude             | Summarizes long documents and generates high-quality written content.      |
| Perplexity AI      | AI search engine that provides answers with citations.                     |
| GitHub Copilot     | Helps developers write, complete, and debug code.                          |
| Jasper AI          | Creates marketing content, blogs, and business copy.                       |
| Copy.ai            | Generates sales, advertising, and business content.                        |
| Writesonic         | Produces SEO-friendly articles and marketing copy.                         |
| Grammarly AI       | Improves grammar, clarity, tone, and writing style.                        |
| Canva Magic Studio | Creates AI-powered designs, presentations, and graphics.                   |
| DALL·E             | Generates images from natural language prompts.                            |
| Midjourney         | Produces artistic and realistic AI-generated images.                       |
| Adobe Firefly      | Creates and edits images using generative AI tools.                        |
| Stable Diffusion   | Open-source model for customizable image generation.                       |
| Runway             | Generates and edits videos with AI.                                        |
| Pika               | Creates short videos from text or images.                                  |
| Synthesia          | Produces AI avatar videos from written scripts.                            |
| HeyGen             | Creates realistic talking-avatar videos for presentations.                 |
| ElevenLabs         | Generates natural-sounding AI voices and speech.                           |
| Suno AI            | Creates complete songs and music from text prompts.                        |
| Udio               | Generates AI music, vocals, and instrumental tracks.                       |
| DeepSeek           | AI chatbot focused on reasoning, coding, and technical tasks.              |
| Grok               | Conversational AI for problem-solving and coding assistance.               |
| Cursor AI          | AI-powered code editor that accelerates software development.              |

## Applications of Generative AI

- AI chatbots and virtual assistants
    
- Content and copywriting
    
- Graphic design and image creation
    
- Video and animation production
    
- Music and voice generation
    
- Software development and code assistance
    
- Education and research support


----

# What is Vercel?

Vercel is a cloud platform for deploying, hosting, and managing modern web applications. It is the company behind Next.js and is widely used because it makes web deployment simple and automatic. By connecting your GitHub repository, Vercel can build your project and publish it to a fast, globally distributed network without requiring any server setup or maintenance.

## Steps to Deploy a Project on Vercel

### 1. Sign in to Vercel

Create an account or log in to Vercel using your GitHub account. This allows Vercel to access and deploy your repositories securely.

### 2. Create a New Project

From the Vercel dashboard, click Add New → Project. This opens the project creation page where you can import an existing GitHub repository.

### 3. Import Your GitHub Repository

Select the repository you want to deploy and click Import. Vercel automatically detects the framework (such as Next.js, React, or Vue) and applies the recommended build settings.

### 4. Deploy the Application

Click the Deploy button to start the deployment process. Vercel will install dependencies, build the project, and publish it to a live URL. Once completed, your website is accessible online and will automatically redeploy whenever you push new changes to GitHub.

Key benefit: Vercel provides automatic deployments, global content delivery, HTTPS security, and zero server management, making it an ideal platform for hosting modern web applications.



-----







# What is a Large Language Model (LLM)?

A Large Language Model (LLM) is an advanced Artificial Intelligence (AI) system trained on enormous amounts of text, including books, websites, articles, research papers, and source code. Its purpose is to understand, interpret, and generate human-like language, enabling it to answer questions, write content, summarize information, translate languages, and even assist with programming.

## How an LLM Works

The working process of an LLM can be understood in five simple steps:

1. User Prompt – The user provides a question, instruction, or request.
    
2. Tokenization – The input text is broken into smaller units called tokens.
    
3. Context Analysis – The Transformer-based LLM analyzes the tokens and understands their meaning and relationships.
    
4. Token Prediction – The model predicts the next most probable token repeatedly until a complete response is formed.
    
5. Response Generation – The final text is generated and displayed to the user.
    

## Advantages

- Understands and processes natural language effectively.
    
- Generates coherent, human-like responses.
    
- Performs tasks such as question answering, translation, summarization, and code generation.
    
- Processes large volumes of text quickly and efficiently.
    

## Applications

LLMs are widely used across many industries, including:

- AI Chatbots (e.g., ChatGPT)
    
- Virtual Assistants
    
- Content and Copy Writing
    
- Language Translation
    
- Text Summarization
    
- Code Generation and Programming Assistance
    
- Customer Support Automation



-----

# What is a Token?

A token is the smallest unit of text that a Large Language Model (LLM) processes. Instead of reading entire sentences as humans do, the model breaks text into smaller pieces called tokens. A token may represent a whole word, part of a word, punctuation, or even a space.

### Token size (approximate)

- 1 token ≈ 4 English characters
    
- 1 token ≈ 0.75 English words
    
- 100 tokens ≈ 75 words
    

Example: The word “indivisible” may be split into three tokens: `in` + `divis` + `ible`.

# How Tokenization Works

Tokenization is the process of converting human-readable text into a format that an AI model can understand. It acts as the bridge between language and mathematics.

### 1. Subword Splitting

The tokenizer analyzes the text and divides it into tokens. Common words are usually kept as a single token, while longer or uncommon words are split into meaningful subword fragments using algorithms such as Byte Pair Encoding (BPE).

### 2. Vocabulary Lookup

Each token is assigned a unique integer ID from the model’s predefined vocabulary, which typically contains 32,000 to over 100,000 different tokens. The model works with these IDs rather than the original text.

### 3. Vector Embedding

The integer IDs are transformed into vector embeddings—high-dimensional numerical representations that capture the meaning and relationships between words. These vectors are then processed by the neural network to understand context and generate responses

-----

# What is RAG (Retrieval-Augmented Generation)?

Retrieval-Augmented Generation (RAG) is an AI framework that combines a Large Language Model (LLM) with an external knowledge source to generate accurate, relevant, and up-to-date responses. Instead of relying only on the information learned during training, RAG retrieves information from documents, databases, websites, or internal files at the time of a user's query.

This makes the responses more reliable and better suited for tasks that require current or domain-specific knowledge.

## How RAG Works

The RAG process consists of three main stages:

### 1. Retrieve

When a user submits a query, the system searches an external knowledge base for the most relevant information. This search is commonly performed using vector embeddings and similarity search, and may also include traditional keyword-based searching.

Example sources: PDFs, databases, company documents, websites, or knowledge bases.

### 2. Augment

The retrieved text is added to the user's original prompt as additional context. This enriched prompt gives the language model access to relevant information before generating a response.

### 3. Generate

The LLM reads both the user's question and the retrieved content, then generates a response that is grounded in the provided information while also using its general language understanding.

## Why is RAG Important?

RAG improves the quality and reliability of AI systems in several ways:

- Reduces hallucinations by grounding responses in real source material.
    
- Provides up-to-date knowledge without retraining the model.
    
- Supports private and domain-specific data, such as internal company documents.
    
- Enables source citations, making answers more transparent and verifiable.
    

## Common Applications

RAG is widely used in real-world AI solutions, including:

- Internal document and knowledge-base chatbots
    
- Customer support and product manual assistants
    
- Research assistants for books, PDFs, and academic papers
    
- Enterprise search engines with cited summaries
    
- Legal, healthcare, and educational information systems


-----







