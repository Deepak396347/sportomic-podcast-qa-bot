# Elon Musk Podcast Q&A Bot

## Overview

This project is an AI-powered Podcast Question Answering Bot developed for the Sportomic AI Internship Assignment.

The bot allows users to ask questions about a podcast and receive:

- Relevant transcript-based answers
- Accurate timestamps
- Direct YouTube jump links

## Features

- Transcript extraction from YouTube videos
- Semantic search using Sentence Transformers
- Vector database using FAISS
- Timestamp retrieval
- Gradio web interface
- Direct YouTube timestamp navigation

## Tech Stack

- Python
- YouTube Transcript API
- Sentence Transformers
- FAISS
- Gradio
- NumPy

## Workflow

1. Extract transcript from YouTube
2. Create transcript chunks
3. Generate embeddings
4. Store vectors in FAISS
5. Accept user query
6. Perform semantic search
7. Return answer and timestamp

## Sample Questions

- What advice does Elon Musk give to entrepreneurs?
- What does Elon Musk think about AI?
- What does Elon Musk think about education?

## Accuracy Verification

| Question | Timestamp | Correct? |
|-----------|-----------|-----------|
| What advice does Elon Musk give to entrepreneurs? | 00:20:40 | Yes |
| What does Elon Musk think about AI? | 01:27:11 | Yes |
| What does Elon Musk think about education? | 01:12:28 | Yes |
| What is Elon Musk most excited about right now? | 00:19:58 | Yes |
| What does Elon Musk say about useful products and services? | 00:18:33 | Yes |

## Author

Deepak Pandey
