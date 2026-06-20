# Agentic AI & Knowledge Graph Systems Portfolio

## About

I am a Senior AI and Software Engineer with 20+ years of experience in software engineering, semantic technologies, knowledge graphs, enterprise systems, and AI-powered applications.

My recent work has focused on building production systems that combine Large Language Models (LLMs), Retrieval-Augmented Generation (RAG), knowledge graphs, ontology reasoning, and agentic workflows to support knowledge-intensive business processes.

Most of my recent projects were developed for enterprise customers and are subject to confidentiality agreements. Therefore, this repository focuses on architecture, design decisions, and technical approaches rather than proprietary source code.

---

# Project 1: Agentic Ontology Mapping Assistant

## Problem

Organizations often need to align existing data schemas with domain ontologies to enable semantic integration, knowledge graph construction, and data interoperability.

Manual schema-to-ontology mapping is time-consuming and requires significant domain expertise.

## Solution

Designed and implemented an AI-assisted ontology mapping platform using LangGraph and Large Language Models.

The system automatically proposes mappings between source schemas and ontology concepts while keeping domain experts in the validation loop.

## Architecture

```text
Source Schema
      |
      v
Schema Analysis
      |
      v
Ontology Reasoning
      |
      v
Agent 1: Candidate Mapping Generation
      |
      v
Agent 2: Mapping Validation & Refinement
      |
      v
Evaluation Layer
      |
      v
FastAPI Services
      |
      v
User Interface
      |
      v
Human Review & Approval
```

## Key Technologies

* Python
* LangGraph
* OpenAI GPT Models
* Claude Models
* FastAPI
* RDF
* OWL
* SPARQL

## Highlights

* Multi-agent workflow design
* Ontology-guided prompting
* Human-in-the-loop validation
* Configurable LLM backends
* Production deployment

---

# Project 2: Knowledge Graph Construction from Technical Documentation

## Problem

Network vendors publish thousands of pages of technical documentation describing commands, configurations, protocols, and operational procedures.

This information is valuable but difficult to search, maintain, and reuse.

## Solution

Built automated pipelines that transform technical documentation into structured knowledge graph representations.

The resulting knowledge graph supports semantic search, information retrieval, configuration analysis, and AI-assisted applications.

## Architecture

```text
Technical Documentation
          |
          v
Document Parsing
          |
          v
Knowledge Extraction
          |
          v
Ontology Population
          |
          v
Knowledge Graph
          |
          +----> Semantic Search
          |
          +----> SPARQL Queries
          |
          +----> Property Graph Deployment
```

## Key Technologies

* Python
* RDF
* RDFS
* OWL
* SPARQL
* Apache TinkerPop
* Gremlin

## Highlights

* Large-scale document processing
* Semantic modeling
* Knowledge graph construction
* Knowledge extraction
* RDF-to-property graph transformation

---

# Project 3: Knowledge-Grounded Retrieval-Augmented Generation

## Problem

LLMs often struggle with specialized enterprise knowledge and may generate inaccurate or unverifiable answers.

## Solution

Designed Retrieval-Augmented Generation (RAG) pipelines that combine semantic retrieval, ontology reasoning, and knowledge graph context with LLM generation.

## Architecture

```text
User Question
      |
      v
Retrieval Layer
      |
      +----> Knowledge Graph
      |
      +----> Semantic Search
      |
      v
Context Construction
      |
      v
Large Language Model
      |
      v
Grounded Response
```

## Key Technologies

* Python
* LangChain
* LangGraph
* OpenAI
* Claude
* Knowledge Graphs
* RDF/OWL

## Highlights

* Knowledge-grounded generation
* Enterprise information retrieval
* Explainable AI outputs
* Reduced hallucination risk

---

# Engineering Practices

## Backend Engineering

* Python
* FastAPI
* REST APIs
* Async Programming
* API Integration

## AI Engineering

* Agentic AI Systems
* LangGraph
* LangChain
* Prompt Engineering
* Structured Outputs
* Human-in-the-Loop Workflows
* Evaluation Pipelines

## Knowledge Graphs & Semantic Technologies

* RDF
* RDFS
* OWL
* SPARQL
* Ontology Engineering
* Knowledge Representation
* Semantic Reasoning

## Data Technologies

* PostgreSQL
* Redis
* Data Pipelines
* Data Integration
* Data Modeling

## LLM Platforms

* OpenAI
* Claude

---

# Research Background

* PhD in Computer Science
* Postdoctoral Researcher, University of Pennsylvania
* 20+ scientific publications
* 700+ citations
* Publications in ACM SIGMOD, PODS, JAIR, ECAI, and BPM

---

# Selected Areas of Interest

* Agentic AI Systems
* Knowledge Graphs
* Retrieval-Augmented Generation (RAG)
* Ontology Engineering
* Enterprise AI Applications
* Information Retrieval
* Semantic Technologies
* AI-Assisted Knowledge Management

---

# Note on Confidentiality

The projects described here are representative examples of systems and architectures I have worked on. Detailed source code cannot be shared because the original implementations were developed for enterprise customers and are protected by confidentiality agreements.

I am happy to discuss system architecture, implementation trade-offs, design decisions, and technical challenges during the interview process.
