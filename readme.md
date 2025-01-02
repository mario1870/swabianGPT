# SwabianGPT 🥨

A dialect translation model that translates between Standard German and Swabian using fine-tuned LLMs.

## About

SwabianGPT is a specialized language model trained to translate between Standard German and the Swabian dialect. The model uses the LLAMA 3.1 8B architecture and was fine-tuned using QLoRA and DPO techniques.

For a detailed explanation of the training process and technical details, check out my blog post:
[SwabianGPT: How I finetuned a LLM for dialect-translation](https://www.marioraach.de/blog/9)

## Models

The following models are available on the Hugging Face Hub:

- [DPO Model](https://huggingface.co/Mario12355/swabian_german_translator) - Model with preference optimization

## Features

Bidirectional translation between Standard German and Swabian
Real-time streaming translation output
Optimized for efficiency using 4-bit quantization
Fine-tuned with human preference data

## Training Details
The model was trained in two stages:

1. Supervised Fine-Tuning (SFT) with over 12,000 translation pairs
2. Direct Preference Optimization (DPO) using human-annotated preferences

## Limitations

The Swabian dialect varies significantly by region
Translation quality may vary for complex or idiomatic expressions
The model works best with clear, simple sentences

## License
The code in this repository is licensed under the MIT License. However, please note that the training data and fine-tuned models have their own licensing terms.
