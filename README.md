# Hate_Speech_Detection

**Sentinel: A Robust, Explainable, and Causally-Aware Framework for Hate Speech Detection**

This repository contains all code, models, evaluation scripts, and visualizations used in the research study titled:

> **"Explainable Large Language Models for Fair and Robust Mitigation of Misinformation, Hate, and Social Harm"**  
> *by Steve Nwaiwu*

---

## 📌 Overview

This project proposes **Sentinel**, a multi-pathway architecture for detecting hate speech that integrates:

- **Heuristic cues** (e.g., slurs, sentiment, punctuation)
- **Contextual semantics** from transformer-based models
- **Causal reasoning** to reduce spurious correlations

The Sentinel model is trained under a **multi-objective robustness regime**, combining classification accuracy, adversarial resilience, and interpretability consistency.

---

## 🧠 Core Features

- 🔍 **Dynamic Arbitration Module** to adaptively weight signals from different pathways
- 🧪 **Adversarial Evaluation Suite**: Includes structural, semantic, and feature-targeted attacks
- 🧬 **Causal Regularization**: Reduces reliance on identity terms or surface markers
- 📈 **Integrated Explainability**: Token-level attribution via Integrated Gradients
- 🌍 **Cross-domain Generalization**: Tested on HateXplain and HateEval datasets

---

## 📂 Repository Structure

