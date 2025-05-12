# Multimodal Large Language Models with LangChain, Gemini & BLIP-2

This notebook demonstrates various **vision-language tasks** using **Multimodal Large Language Models (MLLMs)**. It integrates several state-of-the-art tools and models for **image captioning**, **visual question answering (VQA)**, **image classification**, **OCR**, **object detection**, and **agent-based multimodal reasoning** using **LangChain** and **Gemini Pro**.

---

[Colab Link](https://colab.research.google.com/drive/13cVF8V1hIh7uc1q44Hqdtja9t_EPWzzR?usp=sharing)

[Video Demo](https://youtu.be/vMMvsemGp0M)

---

## Features Demonstrated

### Image Captioning with ViT-GPT2
Generates natural language captions from images using the ViT-GPT2 model.

### Visual Question Answering (VQA)
- **BLIP (Base)**: Answers specific questions about images.
- **BLIP-2**: Provides more detailed, natural language answers using larger LLMs.

### Image Classification and Similarity (Zero-Shot)
- Using **CLIP** for zero-shot classification (no training needed).
- Computes image-text similarity between captions and images.

### OCR (Text Extraction)
- Uses **Tesseract OCR** to extract embedded text from images.

### Object Detection (Grounding)
- Uses **OWL-ViT** for grounded object detection based on label prompts.

### LangChain Agent with Gemini Pro
- Demonstrates **tool-using LLMs** by calling BLIP-2 as a vision tool through LangChain’s agent framework and Gemini Pro.