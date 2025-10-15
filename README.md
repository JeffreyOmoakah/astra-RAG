
# Astra RAG (Microservice)

Astra RAG is a retrieval-augmented generation (RAG) microservice that powers the knowledge and reasoning layer for the Astra Wellness Chatbot. It combines natural conversation with intelligent retrieval from curated wellness resources to provide accurate, empathetic, and context-aware responses.

## Overview
The service is designed as a modular microservice that can differentiate between general wellness conversations and factual knowledge queries. When a user asks a question requiring evidence-based information, Astra RAG retrieves the most relevant context from its internal wellness corpus and generates an enhanced, human-centered response.


## Features
- Intent Routing: Automatically detects whether a user query requires retrieval or general chat.

- Retrieval-Augmented Generation (RAG): Combines semantic search with LLM reasoning to provide accurate answers grounded in the wellness dataset.

- LLM-Powered Conversations: Uses a tone-optimized language model for empathetic wellness discussions.

- Vector Search Engine: Embeds and stores curated documents for efficient semantic retrieval.

- Microservice-Ready: Exposes clean REST endpoints for integration with the main Astra frontend.

- Extendable Design: Each service (LLM, vector store, classifier) is modular and replaceable.
## Deployment

Astra RAG runs as a containerized microservice and integrates seamlessly with the Astra Wellness backend.
It can be deployed independently using Docker, and the main Astra frontend communicates with it via HTTP requests to the /chat endpoint.
## Website

Main platform: https://astra-wellness.com

## Upcoming Features

Improved hybrid retrieval (semantic + keyword search)

Contextual memory for follow-up questions

Fine-tuned intent classifier

Multilingual dataset support

Dataset management dashboard for internal updates
##Upcoming Features

Improved hybrid retrieval (semantic + keyword search)

Contextual memory for follow-up questions

Fine-tuned intent classifier

Multilingual dataset support

Dataset management dashboard for internal updates

## License

Proprietary – part of the Astra Wellness ecosystem.

