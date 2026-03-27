# Ollama With Claude Code 🔥

> Run Claude Code Free With 'ollama'.
> 
---
## Prerequisites
---
Before starting, make sure you have:

| Requirement | Version | Check |
|---|---|---|
| Node.js | v18.0.0 or higher | `node --version` |
| npm | Latest | `npm --version` |
| Git | Any recent version | `git --version` |
| Claude | Any recent version | `claude --version` |
| Ollama | Any recent version | `ollama --version` |


## Step 1 — Install Claude Code

Install the Claude Code CLI globally via npm:

```bash
npm install -g @anthropic-ai/claude-code
```

Verify the installation:

```bash
claude --version
```

---

## Step 2 — Install claude-code-router

`claude-code-router` is a local proxy that intercepts Claude Code's API calls and forwards them to your chosen provider (Qwen in this case).

```bash
npm install -g claude-code-router
```

## Step 3 — Install Ollama

`ollama` an open-source tool that enables you to run Large Language Models (LLMs)—such as Llama 3, Mistral, and Gemma—locally on your own computer

### Download It From Here : 
[ollama.com](https://ollama.com/download).


## Step 4 — Install Any Model

Install Any Model From Ollama:

```bash
ollama pull [your_model_here]
```

My Recomendation Models : 
Model :       Size : Context  Input : 
qwen3.5:0.8b  1.0GB   256K    Text, Image
qwen3.5:4b    3.4GB   256K    Text, Image
qwen3:0.6b    500mb   N/A      N/A

Verify the installation:

```bash
ollama run [your_model_here]
```

---
## Step 5 — Launch Claude Code With OpenRouter

```python
ollama launch claude --model your_model
```
