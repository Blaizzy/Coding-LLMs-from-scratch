# Coding LLMs from scratch
# Coding Llama-2
You will learn how to train and fine-tune Llama 2 model from scratch.

Throught the series you will learn about transformers architecture, different attention mechanisms (MHA, MQA and GQA), KV cache, RoPE, and Hugginface Trainer in detail.

By the end, you will have created and trained a LLaMA 2 model with 100M parameters from scratch using PyTorch to do code completion.

🎥 **YT Video Playlist:**
 - https://youtube.com/playlist?list=PLDn_JsyofyfTH5_5V1MNb8UYKxMl6IMNy&si=5Y4cm-6wrMOD1Abr



# Coding Llama-3

You will learn how to train and fine-tune Llama 3 model from scratch.

The goal is to code LLaMA 3 from scratch in PyTorch to create models with sizes 3B, 6B, 35B and 45B params.

🎥 **YT Video Playlist:**
 - https://youtube.com/playlist?list=PLDn_JsyofyfTH5_5V1MNb8UYKxMl6IMNy&si=5Y4cm-6wrMOD1Abr

📚 **Papers**:
 - Sparse Upcycling Training Mixture-of-Experts from Dense Checkpoints
: https://arxiv.org/abs/2212.05055
- Pre-training Small Base LMs with Fewer Tokens: https://arxiv.org/abs/2404.08634
Leave No Context Behind Efficient Infinite Context Transformers with Infini-attention: https://arxiv.org/abs/2404.07143



## Llama-3-6B-v0.1
<img src="./Llama-3/Part 2/assets/llama-3-6B icon.jpeg" width="500" alt="Llama-3-6B"/>

Introducing the world's first Llama-3 base model with 6B parameters. This model is a pretrained version of [prince-canuma/Llama-3-6B-v0](https://huggingface.co/prince-canuma/Llama-3-6B-v0), which was created from Meta-Llama-3-8B using a technique called [downcycling](https://youtube.com/playlist?list=PLDn_JsyofyfTH5_5V1MNb8UYKxMl6IMNy&si=9hcOol4KHIgWThgt) .
The model was continually pretrained on 1 billion tokens of English-only text from fineweb, achieving impressive results on the evaluation set:
- Loss: 2.4942


## Model Description

- **Developed by:** [Prince Canuma](https://huggingface.co/prince-canuma)
- **Sponsored by:** General
- **Model type:** Llama
- **License:** [Llama-3](https://llama.meta.com/llama3/license)
- **Pretrained from model:** prince-canuma/Llama-3-6B-v0

### Model Sources

- **Repository:** https://github.com/Blaizzy/Coding-LLMs-from-scratch/tree/main/Llama-3
- **Video:** https://youtube.com/playlist?list=PLDn_JsyofyfTH5_5V1MNb8UYKxMl6IMNy&si=5Y4cm-6wrMOD1Abr

## Uses

<!-- Address questions around how the model is intended to be used, including the foreseeable users of the model and those affected by the model. -->
You can use this model to create instruct and chat versions for various use cases such as: Coding assistant, RAG, Function Calling and more.

### Limitations

This model inherits some of the base model's limitations and some additional ones from it's creation process, such as:
 - Limited scope for coding and math: According to benchmarks, this model needs more pretraining/finetuning on code and math data to excel at reasoning tasks.
 - Language Limitations: This model was continually pretrained on english only data. If you are planning to use it for multilingual use cases I recommend fine-tuning or continued pretraining.


## Read more
https://huggingface.co/prince-canuma/Llama-3-6B-v0.1