# STEMLLaVA
Finetuning multimodal LLMs on STEM datasets.
## Planned Procedure
 - [x] Compile and preprocess multiple datasets
 - [ ] Finetune [LLaVA v1.5 13b](https://arxiv.org/abs/2310.03744) on this data using [QLoRA](https://arxiv.org/abs/2310.03744)
 - [ ] Release on Huggingface so that anybody can use it!
## Datasets
There are ~1 million samples which I will be using to train this model. Those one million samples all come from the datasets listed below:
 - [MetaMath](https://huggingface.co/datasets/meta-math/MetaMathQA)
 - [Camel AI Math](https://huggingface.co/datasets/camel-ai/math)
 - [ArXiv Math](https://huggingface.co/datasets/ArtifactAI/arxiv-math-instruct-50k)
 - [Camel AI Chemistry](https://huggingface.co/datasets/camel-ai/chemistry)
 - [Camel AI Physics](https://huggingface.co/datasets/camel-ai/physics)
 - [Camel AI Biology](https://huggingface.co/datasets/camel-ai/biology)
 - [ArXiv Physics](https://huggingface.co/datasets/ArtifactAI/arxiv-physics-instruct-tune-30k)
 - [GSM8K](https://huggingface.co/datasets/gsm8k)
 - [MMLU](https://huggingface.co/datasets/cais/mmlu)
 - [Evol Instruct Code](https://huggingface.co/datasets/nickrosh/Evol-Instruct-Code-80k-v1)
 - [GlaiveAI Code Assistant v2](https://huggingface.co/datasets/glaiveai/glaive-code-assistant-v2)
 - [ArXiv Computer Science and ML](https://huggingface.co/datasets/ArtifactAI/arxiv-cs-ml-instruct-tune-50k)
 - [ScienceQA](https://huggingface.co/datasets/cnut1648/ScienceQA-LLAVA)
