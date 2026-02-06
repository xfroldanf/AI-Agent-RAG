
# Climbing Store AI Assistant

This notebook demonstrates the use of the LangChain library with Google Gemini to create a conversational agent capable of assisting customers of a climbing e-commerce.

## Attribution

This project is based on the [Oxford AI Course - AI Agents](https://github.com/Valentina-Alto/Oxford-AI-Course---AI-Agents) repository, with modifications to use different LLM and embedding providers. 

## Business scenario

We are the owners of a climbing e-store, and we want to enhance our customer experience by creating an AI assistant. This assistant leverages Google Gemini AI to provide real-time, intelligent support to our customers, helping them with various tasks such as product inquiries, order tracking, and language translation.

### Key Features
1. Product Inquiries: The AI assistant can answer questions about different climbing products, including hiking recommendation for specific routes sponsored by the climbing store.

2. Hyper personalisation:

Customers can benefit from a personalised experience, since the AI assistant will get access to their purchase history and make relevant recommendations.

3. Conversational user interface

Customers can benefit from a conversational, chat experience that can improve the overall experience and increase engagement, differentiating the store in the market of e-commerce.

## Prerequisites
Before running this notebook, ensure you have the following prerequisites:

1. Python 3.8+: Make sure you have Python 3.8 or higher installed on your system.

2. Google Gemini API: You need access to the Google Gemini API. Ensure you have the following:
- GOOGLE_API_KEY: The API key for accessing Google Gemini service.

3. GPU (Optional): For optimal embedding performance with HuggingFace embeddings, a GPU is recommended but not required.

Required Python Packages: Install the necessary Python packages by running the following command:

```bash
pip install -r requirements.txt
```

## Technology Stack

- **LLM Provider**: Google Gemini 2.5 Flash Lite
- **Embeddings**: HuggingFace BAAI/bge-base-en-v1.5 (state-of-the-art embedding model for RAG)
- **Vector Store**: FAISS (Facebook AI Similarity Search)
- **Framework**: LangChain + LangGraph

## Running the notebook
1. Clone the repository:
```bash
git clone https://github.com/xfroldanf/AI-Agent-RAG.git
cd AI-Agent-RAG
```
2. Install Dependencies
```bash
pip install -r requirements.txt
```
3. Set environment variables

Create a `.env` file in the project root with:
```bash
GOOGLE_API_KEY=your-google-api-key-here
```

Or set it directly in your environment:
```bash
export GOOGLE_API_KEY="your-google-api-key-here"
```




