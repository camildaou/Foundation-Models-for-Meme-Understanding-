# Foundational Models for Meme Understanding

Evaluation of Vision-Language Models (VLMs) for hateful and misogynistic meme detection.

## Overview

This project investigates the ability of multimodal foundation models to understand harmful content in memes, focusing on the interaction between images and embedded text.

We evaluate:
- **Qwen2.5-VL-7B**
- **LLaVA-1.5-7B**
- **SigLIP + BERT** supervised baseline

Experiments are conducted on the **FHM-FG** and **MAMI** benchmarks, combining OCR, prompt engineering, multimodal classification, and quantitative and qualitative error analysis.

## Key Components

- OCR-based meme text extraction and preprocessing
- Balanced dataset construction
- Zero-shot, few-shot, and Chain-of-Thought prompting
- VLM inference on GPU clusters using SLURM
- Supervised SigLIP + BERT multimodal baseline
- Accuracy, F1, Macro-F1, and GMean-F1 evaluation
- Qualitative analysis of model failure cases

## Team

Developed by an **international, multicultural team of six** at Télécom Paris.

**Authors:** Hugo Foulon, Tia Hakmeh, Camil Daou, Philibert Pierson de Brabois, Samir Alsabbagh, and Théo Renaudo.

**Supervisors:** Assoc. Prof. Mehwish Alam and Assoc. Prof. Patricia Chiril.

## Report

[Read the full project report](./Hateful_Memes_Project_Report.pdf)
