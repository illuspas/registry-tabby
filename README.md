# 🧑‍🔬 Tabby Registry

## Completion models (`--model`)

We recommend using

* For **1B to 3B models**, it's advisable to have at least **NVIDIA T4, 10 Series, or 20 Series GPUs**, or **Apple Silicon** like the M1.
* For **7B to 13B models**, we recommend using **NVIDIA V100, A100, 30 Series, or 40 Series GPUs**.

We have published benchmarks for these models on https://leaderboard.tabbyml.com for Tabby's users to consider when making trade-offs between quality, licensing, and model size.

| Model ID | License |
| -------- | ------- |
| [Qwen2.5-Coder-0.5B](https://huggingface.co/Qwen/Qwen2.5-Coder-0.5B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-1.5B](https://huggingface.co/Qwen/Qwen2.5-Coder-1.5B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-3B](https://huggingface.co/Qwen/Qwen2.5-Coder-3B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-7B](https://huggingface.co/Qwen/Qwen2.5-Coder-7B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-14B](https://huggingface.co/Qwen/Qwen2.5-Coder-14B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
| [Qwen2.5-Coder-32B](https://huggingface.co/Qwen/Qwen2.5-Coder-14B) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |


## Chat models (`--chat-model`)

To ensure optimal response quality, and given that latency requirements are not stringent in this scenario, we recommend using a model with at least 1B parameters.

| Model ID | License |
| -------- | ------- |
| [Qwen3-Coder-30B-A3B-Instruct](https://huggingface.co/Qwen/Qwen3-Coder-30B-A3B-Instruct) | [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |


## Embedding models

| Model ID | License |
| -------- | ------- |
| [Qwen3-Embedding-0.6B-GGUF](https://huggingface.co/Qwen/Qwen3-Embedding-0.6B-GGUF)| [Apache 2.0](https://choosealicense.com/licenses/apache-2.0/) |
