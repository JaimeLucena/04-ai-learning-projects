# 04-AI learning Projects

> **A curated collection of production-ready AI applications showcasing advanced LangChain, LangGraph, CrewAI, and RAG patterns.**

This repository is the **fourth module** in a progressive learning path on **Generative AI Engineering**, designed to bridge the gap between foundational concepts and real-world AI application development.

---

## 📚 Overview

This repository contains **7 comprehensive, production-ready AI projects** that demonstrate advanced patterns and architectures used in modern AI applications. Each project is a complete, working application with:

- **Full-stack architecture** (FastAPI backend + Streamlit frontend)
- **Production-ready code** with best practices
- **Comprehensive documentation** and examples
- **Real-world use cases** and scenarios

Perfect for developers who have completed the foundational courses and want to build **real AI applications** that solve actual problems.

---

## 🗺️ Learning Path

This is the **fourth step** in your Generative AI learning journey. Make sure you've completed the previous modules:

### 📘 [01-Python Fundamentals](https://github.com/JaimeLucena/01-python-fundamentals)

**Essential Python concepts for AI development**

Learn the Python fundamentals you actually need for LangChain and AI development:
- Python syntax basics
- Data structures (lists, dictionaries, sets, tuples)
- Control flow and functions
- Decorators and context managers
- Environment variables and secrets management
- Type hints and Pydantic

**Perfect for:** Beginners who want to learn Python specifically for AI development.

---

### 📗 [02-LangChain Beginners](https://github.com/JaimeLucena/02-langchain-beginners)

**Master LangChain fundamentals through hands-on notebooks**

A comprehensive guide to LangChain covering:
- LangChain Expression Language (LCEL)
- Prompt templates and chain composition
- RAG (Retrieval-Augmented Generation) fundamentals
- Vector stores (Chroma, FAISS)
- Text embeddings and document loaders
- Text splitters and retrieval strategies

**Perfect for:** Developers ready to build LLM applications with LangChain.

---

### 📙 [03-Agents and Apps Foundations](https://github.com/JaimeLucena/03-agents-and-apps-foundations)

**Build and orchestrate modern AI agents**

Learn to build production-ready AI applications:
- AI agents fundamentals (LangGraph & CrewAI)
- Memory management (temporary vs persistent)
- Multi-agent orchestration
- Code architecture patterns (modular, layered, hexagonal)
- FastAPI backend development
- Streamlit frontend integration

**Perfect for:** Developers ready to build full-stack AI applications with agents.

---

### 📕 04-AI learning Projects (You are here!)

**Build production-ready AI applications**

This repository contains 7 complete projects that demonstrate:
- Advanced RAG implementations
- Multi-agent systems
- Sentiment analysis
- Conversational AI with memory
- Ticket routing and classification
- Marketing automation
- Database querying with natural language

**Perfect for:** Developers who want to see and build real-world AI applications.

---

## 🚀 Projects in This Repository

### 1. 🤖 [CrewAI Marketing Team](https://github.com/JaimeLucena/crewai-marketing-team)

**Multi-agent marketing automation system**

A complete marketing automation application that creates comprehensive marketing campaigns using CrewAI multi-agent orchestration. Four specialized agents work together to generate marketing strategies, content plans, social media posts, and campaign timelines.

**Key Features:**
- 🤖 Four specialized agents: Strategist, Content Creator, Social Media Specialist, Campaign Manager
- 📝 Comprehensive campaign generation (strategies, content, social posts)
- 📊 Interactive Streamlit dashboard with task management
- 💾 SQLite database for persistent task storage
- 🌍 Multi-language support
- ⚡ Full FastAPI REST API

**Technologies:** CrewAI, LangChain, FastAPI, Streamlit, SQLAlchemy, OpenAI

**Perfect for learning:** Multi-agent orchestration, marketing automation, task delegation, structured outputs

---

### 2. 🧠 [Google Reviews Sentiment Analysis](https://github.com/JaimeLucena/google-reviews-sentiment)

**Intelligent sentiment analysis for business reviews**

A complete sentiment analysis application that fetches Google Business reviews and analyzes them using LangChain LCEL and OpenAI. Extracts sentiment, key aspects, and provides actionable insights for businesses.

**Key Features:**
- 🧠 Advanced sentiment analysis with aspect extraction
- 📍 Google Places API integration
- 🎯 Identifies what customers talk about (service, food, price, etc.)
- 🌍 Multi-language support with automatic detection
- 📊 Precise sentiment scoring (-1 to +1)
- ⚡ Batch processing for multiple reviews

**Technologies:** LangChain LCEL, OpenAI, FastAPI, Streamlit, Google Places API

**Perfect for learning:** LangChain LCEL patterns, sentiment analysis, API integration, structured outputs

---

### 3. 💬 [LangGraph Memory Chatbot](https://github.com/JaimeLucena/langgraph-memory-chatbot)

**Production-ready conversational AI with dual memory modes**

A sophisticated chatbot built with LangGraph featuring dual memory modes (temporary and persistent), tool integration (Wikipedia, Weather), and a beautiful Streamlit UI. Demonstrates advanced conversation management and state persistence.

**Key Features:**
- 🔄 Dual memory modes (temporary in-memory vs persistent SQLite)
- 🛠️ Tool integration (Wikipedia summaries, weather information)
- 🧠 Smart context management with automatic message trimming
- 🚀 FastAPI backend with session management
- 🎨 Clean Streamlit UI with chat history
- 📊 LangGraph workflow orchestration

**Technologies:** LangGraph, LangChain, FastAPI, Streamlit, SQLite, OpenAI

**Perfect for learning:** LangGraph workflows, memory management, tool integration, conversational AI

---

### 4. 🎫 [LangGraph Ticket Routing](https://github.com/JaimeLucena/langgraph-ticket-routing)

**Intelligent ticket classification with multi-agent system**

An intelligent ticket routing application that automatically classifies support tickets into categories (Finance, Technical Support, HR, Sales, General) using LangGraph multi-agent orchestration. Three specialized agents work together to analyze, classify, and validate tickets.

**Key Features:**
- 🤖 Three-agent system: Analyzer, Classifier, Validator
- 🎯 Automatic ticket classification into 5 categories
- 📊 Interactive dashboard with statistics and analytics
- 🔄 Reclassification capabilities
- 💾 SQLite database for persistent storage
- 🎨 Example templates for each category

**Technologies:** LangGraph, LangChain, FastAPI, Streamlit, SQLAlchemy, OpenAI

**Perfect for learning:** Multi-agent systems, ticket classification, state management, conditional routing

---

### 5. 🏠 [RAG Database Chat](https://github.com/JaimeLucena/rag-database-chat)

**Natural language to SQL with RAG**

A complete RAG application that transforms natural language questions into SQL queries. Users can query a real estate database using plain English, and the system generates SQL, executes it, and returns human-friendly answers.

**Key Features:**
- 🧠 Intelligent SQL generation from natural language
- 💾 SQLite database with real estate data (properties, agents, clients)
- 🎨 Integrated Streamlit UI and FastAPI backend
- 🔄 Complete RAG pipeline with LangChain
- 📊 Pre-seeded with sample data
- 🚀 Production-ready architecture

**Technologies:** LangChain, OpenAI, FastAPI, Streamlit, SQLite, SQLAlchemy

**Perfect for learning:** RAG fundamentals, SQL generation, natural language to database queries, LangChain patterns

---

### 6. 📄 [RAG PDF LangChain](https://github.com/JaimeLucena/rag-pdf-langchain)

**PDF document intelligence with LangChain LCEL**

A complete RAG application that analyzes PDF documents using LangChain LCEL. Upload PDFs, extract text, create embeddings, and query documents using semantic search. Perfect for document intelligence and knowledge base creation.

**Key Features:**
- 📄 PDF processing with automatic text extraction
- 🔍 Semantic search with FAISS vector store
- 💬 Context-aware Q&A based on document content
- ⚡ Real-time processing
- 🎨 Dual interface (Streamlit UI + FastAPI API)
- 🔄 LangChain LCEL composable chains

**Technologies:** LangChain LCEL, OpenAI, FastAPI, Streamlit, FAISS, PyPDF

**Perfect for learning:** RAG architecture, PDF processing, vector embeddings, LangChain LCEL patterns

---

### 7. 📄 [RAG PDF Python](https://github.com/JaimeLucena/rag-pdf-python)

**PDF document intelligence with pure Python**

A RAG application similar to the LangChain version but built with pure Python and sentence transformers. Demonstrates how to build RAG systems without heavy frameworks, using local embeddings and FAISS for vector search.

**Key Features:**
- 📄 PDF text extraction and intelligent chunking
- 🧠 Semantic search with FAISS and sentence transformers
- 💬 Context-aware answers using GPT models
- 🎨 Dual interface (Streamlit UI + FastAPI API)
- ⚡ Local embeddings (no API calls for embeddings)
- 🔄 Complete RAG pipeline implementation

**Technologies:** Python, OpenAI, FastAPI, Streamlit, FAISS, Sentence Transformers, PyPDF

**Perfect for learning:** RAG fundamentals, vector embeddings, local model usage, building RAG from scratch

---

## 🎯 What You'll Learn

By exploring these projects, you'll master:

### 🤖 Advanced AI Patterns
- Multi-agent orchestration with CrewAI and LangGraph
- RAG (Retrieval-Augmented Generation) implementations
- Memory management and state persistence
- Tool integration and function calling
- Sentiment analysis and aspect extraction

### 🏗️ Architecture & Design
- Full-stack AI application architecture
- Modular and scalable code organization
- Database integration and persistence
- API design and RESTful endpoints
- Frontend-backend separation

### 🛠️ Production Practices
- Error handling and validation
- Type hints and Pydantic models
- Environment configuration
- Async/await patterns
- Testing and debugging strategies

### 📊 Real-World Applications
- Marketing automation
- Business intelligence
- Customer support systems
- Document intelligence
- Conversational AI

---

## 🚀 Getting Started

### Prerequisites

- **Python 3.10+** installed
- **OpenAI API Key** ([Get one here](https://platform.openai.com/api-keys))
- **uv** package manager ([Installation guide](https://github.com/astral-sh/uv))
- Completion of previous learning modules (recommended)

### Quick Start

1. **Choose a project** that interests you from the list above
2. **Clone the repository** for that specific project
3. **Follow the project's README** for detailed setup instructions
4. **Run the application** and start exploring!

Each project has its own:
- Detailed README with setup instructions
- Environment configuration guide
- Example use cases
- API documentation
- Learning objectives

---

## 📚 Project Comparison

| Project | Focus | Key Technology | Complexity | Use Case |
|---------|-------|----------------|------------|----------|
| **CrewAI Marketing** | Multi-agent systems | CrewAI | Advanced | Marketing automation |
| **Sentiment Analysis** | NLP & APIs | LangChain LCEL | Intermediate | Business intelligence |
| **Memory Chatbot** | Conversational AI | LangGraph | Advanced | Customer support |
| **Ticket Routing** | Classification | LangGraph | Advanced | Support systems |
| **RAG Database** | SQL generation | LangChain | Intermediate | Data querying |
| **RAG PDF LangChain** | Document intelligence | LangChain LCEL | Intermediate | Knowledge bases |
| **RAG PDF Python** | RAG fundamentals | Pure Python | Intermediate | Learning RAG |

---

## 🎓 Recommended Learning Order

If you're new to these projects, we recommend this learning path:

1. **Start with RAG projects** (Database or PDF) - Understand RAG fundamentals
2. **Move to Sentiment Analysis** - Learn LangChain LCEL patterns
3. **Explore Memory Chatbot** - Master LangGraph and memory management
4. **Try Ticket Routing** - Learn multi-agent classification
5. **Finish with Marketing Team** - Build complex multi-agent systems

---

## 🛠️ Technology Stack

These projects use modern, production-ready technologies:

### AI/ML Frameworks
- **LangChain** - LLM framework and abstractions
- **LangGraph** - Workflow orchestration and state management
- **CrewAI** - Multi-agent coordination
- **OpenAI** - GPT models for text generation

### Backend
- **FastAPI** - High-performance Python web framework
- **SQLAlchemy** - ORM for database operations
- **SQLite** - Embedded database

### Frontend
- **Streamlit** - Python-native web UI framework

### Vector Stores & Search
- **FAISS** - Efficient similarity search
- **Chroma** - Vector database (in some projects)

### Tools
- **uv** - Fast Python package manager
- **Pydantic** - Type-safe models and validation

---

## 📖 Additional Resources

### Documentation
- [LangChain Documentation](https://python.langchain.com/)
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [CrewAI Documentation](https://docs.crewai.com/)
- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [Streamlit Documentation](https://docs.streamlit.io/)

### Related Repositories
- [01-Python Fundamentals](https://github.com/JaimeLucena/01-python-fundamentals)
- [02-LangChain Beginners](https://github.com/JaimeLucena/02-langchain-beginners)
- [03-Agents and Apps Foundations](https://github.com/JaimeLucena/03-agents-and-apps-foundations)

---

## 🤝 Contributing

Found a bug or have a suggestion? Contributions are welcome!

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

---

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Author

**Jaime Lucena**  
Generative AI Engineer — Building AI applications & sharing what I learn along the way 🚀

- **GitHub**: [@JaimeLucena](https://github.com/JaimeLucena)
- **LinkedIn**: [linkedin.com/in/jaimelucena](https://linkedin.com/in/jaimelucena)

---

## ⭐ Support

If you find these projects helpful, please consider giving them a star on GitHub ⭐  
It helps others discover this learning series!

---

## 🎯 Next Steps

After completing these projects, you'll be ready to:

- ✅ Build your own AI applications from scratch
- ✅ Understand production-ready AI architectures
- ✅ Implement advanced patterns like multi-agent systems
- ✅ Create RAG systems for document intelligence
- ✅ Deploy AI applications to production

**Ready to build real AI applications?**  
Pick a project that interests you and start building! 🚀

---

<div align="center">

**Made with** ❤️ **for the AI learning community**

⭐ **Star this repo if you found it helpful!**

</div>

