# ❔ About

This aim of this repo is to provide ready to use collection of [`ollama` model files](https://github.com/jmorganca/ollama#customize-a-model)
so **anyone can play or fork them.**

# 🔖 Resources

- [:octocat: `ollama`](https://github.com/jmorganca/ollama)https://github.com/jmorganca/ollama
- [🦙 `ollama` models library](https://ollama.ai/library)https://ollama.ai/library

# 💭  Famous quotes

## `evilops`

> "Deploying on a Friday is the epitome of irresponsibility and laziness."

# 🚀 Getting started

Below an example on how to locally run `evliops`:

```sh
# Build model
ollama create evilops -f ./models/evilops 
# Look for model
ollama list | grep evilops
# Use model
ollama run evilops "Should I deploy on friday?"
```
