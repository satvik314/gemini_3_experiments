# 🚀 Gemini 3 Pro Cookbook

> **Created by [Build Fast with AI](https://www.buildfastwithai.com)**

A comprehensive collection of Jupyter notebooks demonstrating the capabilities of Google's Gemini 3 Pro model. This cookbook covers everything from basic usage to advanced implementations including RAG, Agents, and Streamlit applications.

## 📚 Table of Contents

### Getting Started
1. **[01_getting_started_with_gemini_3_pro.ipynb](notebooks/01_getting_started_with_gemini_3_pro.ipynb)** - Basic usage with Google Gen AI SDK
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/01_getting_started_with_gemini_3_pro.ipynb)

2. **[02_advanced_features.ipynb](notebooks/02_advanced_features.ipynb)** - Streaming, Function Calling & System Instructions
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/02_advanced_features.ipynb)

### RAG (Retrieval Augmented Generation)
3. **[03_basic_rag_chromadb.ipynb](notebooks/03_basic_rag_chromadb.ipynb)** - RAG implementation with ChromaDB
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/03_basic_rag_chromadb.ipynb)

4. **[04_advanced_rag_langchain.ipynb](notebooks/04_advanced_rag_langchain.ipynb)** - Advanced RAG with LangChain & semantic search
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/04_advanced_rag_langchain.ipynb)

### Agents
5. **[05_langgraph_research_agent.ipynb](notebooks/05_langgraph_research_agent.ipynb)** - LangGraph powered research assistant
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/05_langgraph_research_agent.ipynb)

6. **[06_crewai_multi_agent.ipynb](notebooks/06_crewai_multi_agent.ipynb)** - Multi-agent system with CrewAI
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/06_crewai_multi_agent.ipynb)

7. **[07_autonomous_agent_langgraph.ipynb](notebooks/07_autonomous_agent_langgraph.ipynb)** - Autonomous agent for data analysis
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/07_autonomous_agent_langgraph.ipynb)

### Streamlit Applications
8. **[08_streamlit_chatbot.ipynb](notebooks/08_streamlit_chatbot.ipynb)** - Interactive chatbot with Streamlit
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/08_streamlit_chatbot.ipynb)

9. **[09_streamlit_document_qa.ipynb](notebooks/09_streamlit_document_qa.ipynb)** - Document Q&A application
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/09_streamlit_document_qa.ipynb)

10. **[10_streamlit_image_analysis.ipynb](notebooks/10_streamlit_image_analysis.ipynb)** - Image analysis application
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/10_streamlit_image_analysis.ipynb)

### Advanced Topics
11. **[11_multimodal_capabilities.ipynb](notebooks/11_multimodal_capabilities.ipynb)** - Working with text, images, and video
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/11_multimodal_capabilities.ipynb)

12. **[12_long_context_prompting.ipynb](notebooks/12_long_context_prompting.ipynb)** - Long context handling & efficient prompting
    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/satvik314/gemini_3_experiments/blob/main/notebooks/12_long_context_prompting.ipynb)

## 🎯 Prerequisites

- Python 3.8+
- Google AI API key (get it from [Google AI Studio](https://makersuite.google.com/app/apikey))
- Basic understanding of Python and Jupyter notebooks

## 🛠️ Installation

```bash
pip install google-generativeai langchain langchain-google-genai chromadb langgraph crewai streamlit
```

## 🔑 API Key Setup

Set your Google AI API key as an environment variable:

```python
import os
os.environ['GOOGLE_API_KEY'] = 'your-api-key-here'
```

Or use Google Colab's secrets feature for secure key management.

## 🎓 Learn More

Want to master Generative AI and build production-ready applications?

Check out our comprehensive **[Gen AI Crash Course](https://www.buildfastwithai.com/genai-course)** where you'll learn:
- Advanced prompt engineering techniques
- Building production-ready AI applications
- RAG implementation best practices
- Agent frameworks and orchestration
- Deployment and scaling strategies

## 🤝 Contributing

Contributions are welcome! Feel free to submit issues or pull requests.

## 📝 License

MIT License - feel free to use these notebooks for learning and building your own projects!

## 🔗 Connect

- Website: [Build Fast with AI](https://www.buildfastwithai.com)
- Course: [Gen AI Crash Course](https://www.buildfastwithai.com/genai-course)

---

**Built with ❤️ by Build Fast with AI**
