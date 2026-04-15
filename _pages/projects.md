---
layout: single
title: "Projects"
permalink: /projects/
author_profile: true
---

## Narrative Similarity: Hybrid Embedding + LLM Ensemble
*SemEval 2026 Task 4 · Prompt Engineering, LLMs, NLP*

- Designed structured prompting strategies for LLMs to solve narrative similarity reasoning tasks.
- Implemented few-shot and aspect-grounded prompting, improving model accuracy from **70.5% → 77.5%** on the development dataset.
- Conducted prompt sensitivity experiments revealing how framing and label priming influence model predictions.
- Built a hybrid ensemble combining embedding similarity models and LLM-based reasoning using complementarity-driven model selection.
- Achieved **75% test accuracy**, **ranked 3rd out of 47 international systems**, approaching the human annotator ceiling of 78%.

---

## Knowledge Graph from Text Documents using LLMs
*LLMs, Knowledge Graphs, NLP*

- Built a knowledge graph system from unstructured documents using LLMs to extract entities and relationships.
- Implemented entity recognition, relationship extraction, and interactive graph visualisation with a clean user interface.
- Added contextual navigation linking graph nodes and edges directly to source PDF pages, reducing time spent locating evidence.

---

## Mass Attendance System
*Computer Vision, Deep Learning*

- Built a real-time facial recognition system for large-scale classroom attendance under varying lighting, pose, and crowd density.
- Implemented **ResNet50** for face detection and **FaceNet512** for feature extraction, handling occlusions, tilted faces, and multi-orientation scenarios.
- Validated at ICFAI University (CSE Department) on 100 students with a labelled 60-identity dataset — achieving **100% recognition accuracy** after camera and hardware optimisation.
- Designed an automated preprocessing pipeline to select high-quality facial samples from noisy inputs.

---

## Astrowala.com Web App
*Web Development, Cloud Infrastructure · [Live →](https://astrowala.world)*

- Developed and deployed a production-ready e-learning platform for astrology courses with automated enrollment, course assignment, and content expiration — actively used by **300+ students**.
- Designed cost-efficient infrastructure using the **Google Drive API on a Virtual Machine** for video delivery, achieving an **80% reduction** in storage and streaming costs vs. AWS S3/Azure Blob.
- Implemented session-based authentication with single-device enforcement, geolocation-based anomaly detection, and automated email alerts.
- Managed end-to-end production operations including maintenance, performance tuning, and MongoDB database management.

---

## OCR on Historical Books
*OCR, Document Analysis, Computer Vision*

- Conducted an in-depth literature review of OCR systems for historical documents, identifying gaps in degraded text recognition.
- Evaluated and fine-tuned multiple OCR pipelines for low-quality scans, degraded text, and image artefacts.
- Analysed real-world edge cases including noise, skewed pages, faded ink, and complex layouts.
- Optimised preprocessing thresholds across the OCR pipeline to increase extraction precision and reduce manual correction effort.

---

## HistoAI – Ecosystem for Historical Books
*RAG, Knowledge Graphs, LLMs, System Architecture*

- Led requirements gathering and recurring stakeholder reviews, translating real-world needs into technical specifications.
- Designed an end-to-end system: structured data extraction → knowledge graph generation → RAG-based chatbot for context-aware querying.
- Managed scope, priorities, and delivery timelines, ensuring on-time delivery despite evolving requirements.
- Resolved RAG chatbot performance challenges through targeted literature reviews, experimentation, and plug-and-play solutions.