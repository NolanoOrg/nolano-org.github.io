---
title: "Cformers"
date: 2019-01-28T15:15:26+10:00
weight: 1
---

SoTA Transformers with C-backend for fast inference on your CPU.


## Introduction
We identify three pillers to enable fast inference of SoTA AI models on your CPU:

Fast C/C++ LLM inference kernels for CPU.
Machine Learning Research & Exploration front - Compression through quantization, sparsification, training on more data, collecting data and training instruction & chat models.
Easy to use API for fast AI inference in dynamically typed language like Python.
This project aims to address the third using LLaMa.cpp and GGML.

## Guiding Principles
- Inference Speed! Focus on inference, not training.
- Precompressed models.
- Minimal setup required - soon pip install cformers should be good to get started.
- Easily switch between models and quantization types.
- Support variety of prompts.

And most importantly:
- You, the users, get to decide which direction we take this project

Github: [Cformers](https://github.com/NolanoOrg/cformers)