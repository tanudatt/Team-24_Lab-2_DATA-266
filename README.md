# Team 24 – Multimodal AI-Powered Document Understanding & Image Generation

## Overview
This repository contains all code, documentation, and evaluation files for **Lab 2** submitted by **Team 24**.

The lab is divided into three major parts, each demonstrating a different capability of agentic and generative AI:

---

### Part 1: Multimodal Retrieval-Augmented Generation (RAG)
Extracts structured and unstructured data from a PDF (including figures and tables), embeds it semantically using sentence transformers, and answers natural language queries using FAISS-based retrieval and large language model generation.

---

### Part 2: Stable Diffusion Fine-Tuning
Fine-tunes `runwayml/stable-diffusion-v1-5` using a custom dataset of landscape images. Generates high-quality visuals from text prompts and evaluates them using:
### Google Drive Link: https://drive.google.com/drive/folders/16DuDfD0v3gWoweqZwGQ70nOnzd4zROcR?usp=drive_link

- **Inception Score**: `8.2500 ± 0.3200`
- **CLIP Similarity Score**: `0.7840`  
  *(Min: 0.7500, Max: 0.8100)*

---

### Part 3: Agentic AI Travel Assistant
A fully agentic assistant that integrates **real-time flight, weather, and hotel APIs**. It dynamically plans round-trip itineraries and generates natural language outputs using autonomous agents and LLMs.

---

## Highlights

### Part 1: Multimodal RAG
- Extracted visual content from PDFs using **PyMuPDF**
- Generated embeddings using **Sentence Transformers**
- Indexed content with **FAISS** for similarity search
- Generated responses using **OpenAI GPT** or **FLAN-T5**
- Achieved a **Kaggle score of 0.6868**

---

### Part 2: Stable Diffusion
- LoRA-based fine-tuning of diffusion model
- Prompt-based image generation
- Evaluated with IS & CLIP metrics showing high fidelity

---

### Part 3: Travel Assistant
- Uses autonomous agents to make decisions
- Integrates APIs for live data fetching
- Fully interactive user experience

---

## Repository Structure

```plaintext
├── Part1_Multimodal_RAG/
│   └── Team-24_Lab-2_Part-1.ipynb
├── Part2_Stable_Diffusion/
│   └── Team_24_Lab_2_Part_2.ipynb
├── Part3_Agentic_Travel_Assistant/
│   └── Team-24_Lab-2_PART-3.ipynb
├── submission.csv
└── README.md
