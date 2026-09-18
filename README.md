# GenAI Course Projects 🚀

A comprehensive collection of Generative AI applications and chatbots built using **Streamlit**, **LangChain**, and **Ollama (Llama 3)**. These projects demonstrate advanced AI concepts including Retrieval-Augmented Generation (RAG), dynamic system prompting, cross-lingual reasoning, and sentiment analysis.

## 📁 Projects Overview

### Task 1: Dynamic Knowledge Base Chatbot
- A document-QA bot that allows users to upload PDF/TXT files and ask questions.
- Built with local embeddings and FAISS vector databases.

### Task 2: Multi-Modal Assistant
- An advanced version of the knowledge base that accepts text, documents, and images.
- Extracts context from mixed-media inputs.

### Task 3: Medical Expert Chatbot (MedChatbot)
- A highly strict, domain-specific AI trained exclusively on the **MedQuAD** (Medical Question Answering Dataset).
- Features rigorous safety guardrails that refuse to answer non-medical or general knowledge questions.

### Task 4: arXiv CS Expert Chatbot
- A computer science research assistant utilizing the **arXiv dataset**.
- Includes adjustable difficulty levels (Beginner, Intermediate, Advanced) to tailor complex algorithmic explanations to the user's expertise.

### Task 5: Sentiment-Aware Customer Service Bot
- A dynamic customer support agent that utilizes `TextBlob` to actively read the user's emotional state in real-time.
- Automatically adjusts its persona to be highly empathetic if the user is frustrated, or enthusiastic if the user is happy.

### Task 6: Multilingual Contextual Chatbot (PolyglotBot)
- A cross-lingual AI using `langdetect` and Llama 3 to seamlessly switch between languages (English, Spanish, French, German, etc.).
- Maintains conversational memory and context across language barriers and provides automatic English translations for transparency.

## 🛠️ Tech Stack
- **Frontend:** Streamlit
- **LLM Engine:** Ollama (Llama 3 local inference)
- **Framework:** LangChain & LangChain Community
- **Datastores:** FAISS
- **Utilities:** TextBlob, LangDetect, HuggingFace Embeddings

*(Note: The trained Vector Databases for Tasks 3 & 4 are hosted externally on Google Drive due to size constraints. Download the source zip file above to view the code).*
