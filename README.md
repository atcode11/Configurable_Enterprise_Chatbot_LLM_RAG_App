# Configurable_Enterprise_Chatbot_LLM_RAG_App
This Chatbot is build specifically as a reusable and configurable sample app to share with enterprises or prospects.

🤩 It leverages DataStax RAGStack for production-ready use of the following components:
🚀 The Astra DB Vector Store for Semantic Similarity search to enable Retrieval Augmented Generation
🧠 It uses Astra DB as Short Term Memory to keep track of what was said and generated
🦜🔗 LangChain for linking OpenAI and Astra DB
👑 It uses Streamlit as the framework to easily create Web Applications
It uses a StreamingCallbackHandler to stream output to the screen which prevents having to wait for the final answer
It allows for new Content to be uploaded, Vectorized and Stored into the Astra DB Vector Database so it can be used as Context
It offers a configurable localization through localization.csv
It offers a guided experience on-rails through rails.csv
