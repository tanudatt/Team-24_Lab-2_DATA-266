**Team 24 - Multimodal AI-Powered Document Understanding & Image Generation**

**Overview**
This repository contains all code, documentation, and evaluation files for Lab 2  submitted by Team 24.

The Lab is divided into three major parts, each demonstrating a different capability of agentic and generative AI:

**Part 1: Multimodal Retrieval-Augmented Generation (RAG)**
Extracts structured and unstructured data from a PDF (including figures and tables), embeds it semantically, and answers natural language queries using retrieval and generation.

**Part 2: Stable Diffusion Fine-Tuning**
Fine-tunes runwayml/stable-diffusion-v1-5 using a custom dataset (landscape images), generates images from text prompts, and evaluates quality via Inception Score and CLIP Similarity.

**Part 3: Agentic AI Travel Assistant**
A fully agentic assistant that integrates real-time flight, weather, and hotel APIs, dynamically plans trips, and generates interactive itinerary responses via autonomous agents.


**Highlights**


**Part 1: Multimodal Retrieval-Augmented Generation**



Extracted figures/tables using PyMuPDF and relative bounding boxes

Generated semantic embeddings using sentence-transformers

Stored embeddings using FAISS for fast similarity search

Integrated OpenAI GPT & HuggingFace FLAN-T5 for response generation

Achieved a Kaggle Public Score of 0.6868 with submitted answers



**Part 2: Fine-Tuning Stable Diffusion**



Used LoRA fine-tuning on a custom landscape dataset

Generated images from text prompts such as "sunset over ocean cliffs"

Evaluated using:

Inception Score: 8.2500 ± 0.3200

CLIP Similarity Score (avg): 0.7840

CLIP Score Range: [0.7500 – 0.8100]

Results confirm both high image diversity and prompt alignment



**Part 3: AI Travel Assistant with Autonomous Agents**



Parsed user queries like “Plan a weekend trip to Tokyo”

Called external APIs: Amadeus (flights), OpenWeather, Booking.com (hotels)

Designed memory-rich agents with tools for:

Cost-optimization

Location-based suggestions

End-to-end itinerary generation

