---
title: "Int-3 and beyond"
date: 2019-02-28T15:15:34+10:00
weight: 3
video: "https:&#x2F;&#x2F;www.canva.com&#x2F;design&#x2F;DAFeWYBq6SQ&#x2F;view?embed"
---

GPTQ-style quantization improves performance over naive Round-to-Nearest (RtN) baseline in nearly all cases, but it degrades for smaller model depending on the type of quantization performed.

The bin-size for Int4 quantization can be further increased from the current size of 32 without much performance degradation, leading to a 15% reduction in RAM required to store weights for even the 7B LLaMa model.

LLaMa 13B can be int3 quantized (with much larger bin size) with not much additional performance drops over int4 quantization, leading to a 30-35% reduction in RAM required to store weights for larger models.

While int2 quantization is not usable for LLaMa 13B, larger models may be 2-bit quantize-able without much performance drop.

