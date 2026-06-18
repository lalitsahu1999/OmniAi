# AI Router System

## Purpose

AI Router is the brain of OmniMind AI.

It decides:

* Which model to use
* Which provider to call
* How to handle failures
* How to switch models
* How to optimize cost

---

## Supported Providers

Gemini

Groq

OpenRouter

HuggingFace

Replicate

Fal AI

Black Forest Labs

Ollama

Custom OpenAI Compatible APIs

---

## Routing Modes

### Auto

System selects best model.

### Manual

User selects model.

### Hybrid

User selects category and router selects model.

---

## Model Categories

### Chat

Gemini Flash

DeepSeek Chat

Qwen

Llama

Gemma

---

### Coding

DeepSeek Coder

Qwen Coder

CodeLlama

StarCoder2

---

### Reasoning

DeepSeek R1

Gemini Thinking

Qwen Reasoning

---

### Research

Gemini

DeepSeek R1

Qwen

---

### Image

FLUX

SDXL

---

### Music

MusicGen

Bark

---

### Video

Wan 2.1

CogVideoX

---

## Failover Logic

Example:

Gemini
↓
DeepSeek
↓
Qwen
↓
Llama

---

## Error Handling

Quota Exceeded

Rate Limited

Invalid API Key

Provider Down

Network Error

---

## User Notification

Never silently fail.

Always display:

Provider

Reason

Alternative Model

Retry Option

---

## Model Registry

All models must be configurable through JSON.

No hardcoded models.

---

## Future

Model Marketplace

Custom Providers

Community Models
