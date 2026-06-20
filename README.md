# Agentic AI & Knowledge Graph Systems Portfolio

## About

I am a Senior AI and Software Engineer with 20+ years of experience in software engineering, semantic technologies, knowledge graphs, enterprise AI systems, and large-scale data platforms.

My recent work focuses on designing and building production-grade AI systems that combine:

- Large Language Models (LLMs)
- Agentic workflows (multi-step reasoning systems)
- Knowledge Graphs and Ontologies
- Retrieval-Augmented Generation (RAG)
- Semantic reasoning and information extraction pipelines
- Virtual Knowledge Graph (VKG) and federated semantic data access systems

These systems are primarily built for enterprise environments and often operate under confidentiality constraints. Therefore, this portfolio emphasizes architecture, system design, and engineering approaches rather than proprietary implementations.

---

# Project 1: Agentic Ontology Mapping System

## Problem

Enterprise systems often contain heterogeneous schemas that must be aligned with domain ontologies to enable semantic interoperability, knowledge graph construction, and data integration across systems.

Manual ontology mapping is slow, expert-heavy, and not scalable.

## Solution

Designed a multi-agent AI system that assists ontology engineers in mapping structured schemas to domain ontologies using LLM reasoning and human-in-the-loop validation.

The system generates candidate mappings, validates them through iterative refinement, and ensures ontology consistency.

## Architecture

\[
\text{Source Schema}
\rightarrow
\text{Schema Understanding Layer}
\rightarrow
\text{LLM Agent: Candidate Mapping Generation}
\rightarrow
\text{Ontology Reasoning Layer (OWL / RDFS)}
\rightarrow
\text{LLM Agent: Validation \& Refinement Loop}
\rightarrow
\text{Human-in-the-Loop Review}
\rightarrow
\text{Knowledge Graph / RDF Store}
\]

## Key Technologies

- Python  
- LangGraph  
- OpenAI GPT models  
- Claude models  
- RDF / OWL / RDFS  
- FastAPI  
- SPARQL  

## Highlights

- Multi-agent reasoning pipeline  
- Ontology-aware LLM prompting  
- Human-in-the-loop validation loop  
- Production-ready API layer  
- Configurable LLM backend abstraction  

---

# Project 2: Knowledge Graph Construction from Technical Documentation (Core Domain Work)

## Problem

Network vendor documentation (Huawei, Cisco, Juniper) contains:

- CLI commands
- Configuration modes (views)
- Hierarchical command structures
- Parameter dependencies

This knowledge is unstructured and difficult to query, reuse, or reason over.

## Solution

Built a full pipeline that transforms vendor documentation into structured ontologies and knowledge graphs.

The system extracts CLI semantics, models configuration behavior, and generates structured representations for reasoning and AI applications.

## Architecture

\[
\text{Vendor Documentation}
\rightarrow
\text{Document Preprocessing}
\rightarrow
\text{Command \& Structure Extraction (Regex + Rules)}
\rightarrow
\text{Ontology Construction Layer}
\rightarrow
\text{Knowledge Graph Generation Layer}
\]

\[
\rightarrow \text{RDF Graph (GraphDB / Jena)}
\quad + \quad
\rightarrow \text{Property Graph (TinkerPop / Gremlin)}
\]

\[
\rightarrow \text{SPARQL Queries}
\quad + \quad
\rightarrow \text{Graph Traversals}
\]

## Key Technologies

- Python  
- RDF / RDFS / OWL  
- SPARQL  
- rdflib  
- Apache TinkerPop  
- Gremlin  
- GraphDB / Jena  
- Regex-based parsing pipelines  

## Highlights

- Large-scale technical document parsing  
- Multi-vendor semantic normalization (Huawei / Cisco / Juniper)  
- Ontology-driven knowledge extraction  
- Dual graph backend (RDF + property graph)  
- Performance-optimized extraction pipeline  

---


# Project 3: BI Connector (Virtual Knowledge Graph SQL Access Layer)

## Problem

Enterprise knowledge graphs and virtual knowledge graph (VKG) systems are typically accessed via SPARQL or graph APIs, which are not compatible with standard BI tools used in organizations.

This creates a gap between semantic knowledge systems and business intelligence ecosystems.

## Solution

Designed a **SQL-access layer over Virtual Knowledge Graphs (VKGs)** using Ontop-based semantic mappings.

The system exposes RDF/ontology-based data as relational views using a PostgreSQL-compatible interface, enabling BI tools to query knowledge graphs as if they were relational databases.

## Architecture

\[
\text{Virtual Knowledge Graph (Ontop)}
\rightarrow
\text{SPARQL / OBDA / R2RML Mapping Layer}
\rightarrow
\text{Relational View Generation}
\rightarrow
\text{PostgreSQL Wire Protocol Layer}
\rightarrow
\text{BI Tools (Tableau / PowerBI / DBeaver / Metabase)}
\]

## Key Capabilities

- SQL interface over semantic knowledge graphs  
- PostgreSQL-compatible wire protocol  
- Dynamic and standalone deployment modes  
- Relational views defined via SPARQL SELECT queries  
- Auto-generated and user-defined views  
- TLS-secured deployment support  

## Supported Clients

- Tableau  
- PowerBI  
- Metabase  
- DBeaver  
- Excel  
- PostgreSQL JDBC / ODBC drivers  
- Python (limited cursor support)

## Deployment Modes

### Standalone Mode
- Single database configuration
- OBDA / R2RML mappings
- Ontology-driven relational schema exposure

### Dynamic Mode
- Multi-configuration management
- Runtime configuration updates via REST APIs
- Web-based management endpoints

## Key Technologies

- Java 11+
- Ontop Virtual Knowledge Graph Engine
- PostgreSQL wire protocol emulation
- OBDA / R2RML mapping languages
- RDF / OWL ontologies
- Docker-based deployment
- TLS / secure communication layers

## Highlights

- Bridges semantic web systems with BI ecosystems  
- Enables SQL-based access to knowledge graphs  
- Enterprise-ready VKG deployment model  
- Supports both static and dynamic configurations  
- Integrates semantic mappings with BI tooling pipelines  

---

# Engineering Practices

## AI Systems Engineering

- Agentic AI architectures  
- Multi-step reasoning pipelines  
- LLM orchestration (LangGraph / LangChain)  
- Human-in-the-loop systems  
- Structured output design  
- Evaluation pipelines  

## Knowledge Graph Engineering

- RDF / OWL modeling  
- Ontology design and alignment  
- SPARQL query design  
- Property graph modeling (Gremlin)  
- VKG (Virtual Knowledge Graph) architectures  
- Cross-model transformation (RDF ↔ property graph ↔ SQL interface)

## Backend Engineering

- Python production systems  
- Java-based enterprise services  
- FastAPI  
- Async system design  
- API orchestration  
- Distributed data pipelines  

## Data & Storage Systems

- GraphDB / Jena  
- Ontop VKG engine  
- PostgreSQL  
- Redis  
- TinkerPop / Gremlin  
- BI tool integration layers  

---

# Research Background

- PhD in Computer Science  
- Postdoctoral Researcher, University of Pennsylvania  
- 20+ scientific publications  
- 700+ citations  
- Publications in:
  - ACM SIGMOD  
  - PODS  
  - JAIR  
  - ECAI  
  - BPM  

---

# Selected Areas of Interest

- Agentic AI systems  
- Knowledge graphs and semantic reasoning  
- Virtual Knowledge Graphs (VKG)  
- Retrieval-Augmented Generation (RAG)  
- Ontology engineering  
- Enterprise AI architectures  
- Information extraction from technical systems  
- AI-assisted knowledge management  

---

# Confidentiality Note

Some systems described in this portfolio were developed for enterprise clients under confidentiality agreements.

As such, source code and implementation details cannot be disclosed. However, system architecture, design decisions, and engineering methodologies can be discussed in detail for academic, research, or interview purposes.