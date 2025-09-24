# 🧪 My Projects

I organize my work around three core AI domains: **Computer Vision**, **NLP**, and **Multimodal AI**.  
Below you’ll find both open-source and production-grade systems I’ve built.

---

## 🖼️ Computer Vision (CV)

### 🚗 [Driver’s Assistant](https://github.com/medphisiker/drivers_helper)  
> Real-time traffic sign detection for dashcams (18–52 FPS on CPU)  
> - Optimized for edge devices

### 🐟 Real-time Fish Sorting System (Production)
> Industrial CV pipeline for a fish-processing plant with delta robot control.  
> - Segmentation + SORT tracking + length estimation  
> - Runs on NVIDIA GPU (Ubuntu Server)  
> - [Demo 1](https://youtu.be/WCiPduGcIO8?t=6) | [Demo 2 (with robot)](https://youtu.be/dGKP4fjohhM)

### 🌊 Underwater Fauna Detection (AUV) (Production)
> Deployed on **NVIDIA Jetson (ARM64)** for marine monitoring.  
> - Presented at **Eastern Economic Forum 2022**  
> - [Video demo](https://youtu.be/pVVztrvrCGw)

---


## 🗣️ Natural Language Processing (NLP)

### 💼 [CareerRank](https://github.com/medphisiker/maching_cv_and_vacancy)  
> Semantic matching of resumes and job postings using FAISS + LLM embeddings  
> - [Demo](https://youtu.be/ThIdllGH9ug?t=34)

---

## 🌐 Multimodal AI (CV + NLP + Audio)

### 😃 [Audio-Visual Emotion Recognition](https://gitlab.com/group_19200719)  
> Multimodal fusion (audio + video) for emotion detection in video calls.  
> - State-of-the-art **Intermediate Transformer Fusion**  
> - Trained on **RAVDESS** dataset  
> - 🥇 **1st place**, ODS “MLOps & Production ML 2.0”  
> - [Leaderboard](https://ods.ai/tracks/ml-in-production-spring-23/leaderboard)

### 📊 [VLMHyperBench](https://github.com/VLMHyperBenchTeam/VLMHyperBench)  
> Open framework to benchmark Vision-Language Models on **Russian documents**.  
> - Compare models across inference backends (vLLM, Transformers, etc.)  
> - Evaluate prompts, custom datasets, and metrics  
> - 🏆 **Yandex Open Source Grant 2025**  
> - Presented at **Data Fest 2025**

### 📑 **Document Processing Service (Production)**  
> Internal system for classifying and extracting data from Russian documents using **Qwen2.5-VL-7B**.  
> - Microservice architecture (dev/prod)  
> - Human-in-the-loop: user corrections → model retraining  
> - Tech stack: **vLLM, RabbitMQ, MinIO, Arize Phoenix**

---

> 💡 *"All the most interesting things happen at the intersection of fields."*  
> — My journey from acoustics to multimodal AI.