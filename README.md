# Open-Vocabulary 3D Instruction Ambiguity Detection

[![Project Page](https://img.shields.io/badge/Project-Page-green.svg)](https://jiayuding031020.github.io/ambi3d/)
[![arXiv](https://img.shields.io/badge/arXiv-24xx.xxxxx-b31b1b.svg)](https://arxiv.org/abs/24xx.xxxxx) 
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)


This repository contains the official code and dataset for the paper **"Open-Vocabulary 3D Instruction Ambiguity Detection"**.

## 🏠 Abstract

In safety-critical domains, linguistic ambiguity can have severe consequences. Yet, most embodied AI research overlooks this, assuming instructions are clear and focusing on execution rather than confirmation. 

To address this critical safety gap, we introduce:
1.  **A New Task:** Open-Vocabulary 3D Instruction Ambiguity Detection, where a model must determine if a command has a single, unambiguous meaning within a given 3D scene.
2.  **Ambi3D Benchmark:** A large-scale benchmark featuring over **700 diverse 3D scenes** and around **22k instructions**.
3.  **AmbiVer Framework:** A two-stage framework (Perception + Reasoning) that collects explicit visual evidence from multiple views to guide a VLM in judging instruction ambiguity.

Our analysis reveals that state-of-the-art 3D LLMs struggle to reliably detect ambiguity, while AmbiVer demonstrates significant effectiveness, paving the way for safer embodied AI.

## 🚀 Key Features

- **🛡️ Safety-First:** The first work to systematically define and benchmark ambiguity detection in 3D open-vocabulary settings.
- **📚 Large-Scale Dataset:** **Ambi3D** provides diverse scenarios to test the limits of current 3D agents.
- **🧠 Novel Framework:** **AmbiVer** decouples visual evidence collection from logical reasoning, outperforming end-to-end 3D-LLMs.


