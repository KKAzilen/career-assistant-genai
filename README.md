Career Assistant — AI Career Intelligence by Azilen

# 🧠 Career Assistant — AI Career Intelligence by Azilen

**Career Assistant** is an AI-powered career development platform that builds intelligent skill profiles, personalized learning pathways, and collaborative connections using real-world project data.

This repository complements our blog on [AI Career Assistance](https://www.azilen.com/blog/ai-career-assistant/) presented during Azilen’s **GenAI & Data Engineering Workshop**, where our team demonstrated how GenAI, Data Engineering, and GraphRAG can transform employee growth and learning.

---

## 🚀 Vision

To transform professional development by intelligently connecting people with peers, mentors, and personalized learning paths that accelerate career growth.

---

## 🧩 Solution Overview

Career Assistant creates a secure and confidential environment where employees can:
- Track their professional growth from live project data  
- Discover personalized learning opportunities  
- Connect with mentors and peer learners across the organization  

It integrates **Generative AI**, **Graph Databases (Neo4j)**, and **Data Pipelines** to generate evolving skill graphs and actionable insights.

---

## 🧱 Architecture Overview

CVs + Timesheets + PM Conversations
↓
GenAI Skill Engine
↓
Normalization + Deduplication
↓
GraphDB (Neo4j)
↓
Skill Graphs • Work Snippets • Learning Journeys

Core Components:
- **PM Tool → Work Snippet Generation:** Converts project manager voice summaries into structured project insights.
- **GraphRAG Retrieval:** Enables context-aware reasoning across projects, skills, and people.
- **Collaborative Learning Module:** Suggests next skills, generates learning roadmaps, and connects peer learners.

---

## 📂 Repository Contents

| Folder | Description |
|--------|--------------|
| `architecture/` | System and pipeline diagrams (Skill Graph, GraphRAG, PM Workflow) |
| `prompts/` | GenAI prompt templates for skill profiling, learning roadmap, matching |
| `data_samples/` | Example JSONs: CV, Timelog, Skill Profile |
| `notebooks/` | Demo notebooks for graph construction or retrieval |
| `LICENSE` | Open license for educational and non-commercial reuse |

---

## 🧠 Core Prompt Templates

**Skill Profile Creation**
```plaintext
You are an AI assistant that builds an Initial Skill Profile for employees.
Inputs: timelog JSON + CV document
Tasks: analyze, normalize, deduplicate, and output structured JSON

**Learning Roadmap**

You are an expert learning path architect.
Create a 10-step roadmap including titles, descriptions, time estimates, and resources.

**Peer & Expert Matching**

You are an AI matchmaking assistant for a learning platform.
Rank peers by match quality for someone learning a given technology.

---

## 💡 Key Features

Speech-to-Insight Workflow: Project managers speak, the system builds structured project intelligence.

Graph-based Skill Representation: Maps relationships between people, projects, and technologies.

AI-Assisted Learning: Personalized next-skill recommendations and guided learning paths.

Collaborative Growth: Peer discovery and mentorship matching integrated with Microsoft Teams.

---

## 🧑‍💻 Contributors

A big applause to the brilliant minds behind Career Assistant:

Preksha Kharidia · Rahul Gogia · Rajesh Chaudhari · Rushabh Parikh · Shyama Shah · Vedansh Kamdar · Dipali Rangpariya · Jaydeep Akhani · Karan Chokshi · Karan Koradiya · Manthan Bhavsar · Mohit Kapadia · Nirmita Prajapati

## 🔗 Related Azilen Services

Explore how Azilen brings applied GenAI to enterprises:

AI Agent Development Services

Generative AI Development Services

Enterprise Data Engineering Solutions

---

## 📝 Read the Full Blog

Dive deeper into the concept, architecture, and workshop demo:
➡️ AI Career Assistance: Inside Our GenAI & Data Engineering Workshop

---

## ⚖️ License

This repository is shared under the MIT License for educational and research purposes.
Please attribute Azilen Technologies when referencing or adapting the content.

---

## 🌐 About Azilen

Azilen Technologies
 partners with enterprises to design and build AI-driven product ecosystems, combining GenAI, data engineering, and human-centric design for measurable business transformation.

