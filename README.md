# Video_Rag

This project implements a **Video-based Retrieval-Augmented Generation (RAG) pipeline** that enables question answering from YouTube videos. It extracts video transcripts, processes key video frames, generates embeddings, and retrieves the most relevant video segments to answer user queries.

## Features
- **Retrieves YouTube video transcripts** using `YouTubeTranscriptApi`
- **Extracts key video frames** using OpenCV
- **Generates embeddings for both text and images** (CLIP & OpenAI Embeddings)
- **Stores and retrieves relevant video segments** via Pinecone VectorDB
- **Processes user queries** and answers question
