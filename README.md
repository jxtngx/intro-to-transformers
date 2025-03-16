# Introduction to Transformers

This repo serves as a guide to transformer variations, and is a companion reference to the [torchtune cookbook](https://github.com/jxtngx/torchtune-cookbook), [llamastack cookbook](https://github.com/jxtngx/llamastack-cookbook), and [applied llama engineering](https://github.com/jxtngx/applied-llama-engineering) e2e post-training flow and agent application.

Ideally, the order in which to reference the repos is:

1. this repo
2. torchtune-cookbook
3. llamastack-cookbook
4. applied-llama-engineering

## Transformer Variations

### Encoder Decoder Transformers

The original transformer architecture discussed in `Attention is All You Need` belongs to this class of model. Google's [T5](https://huggingface.co/docs/transformers/model_doc/t5) is an encoder-decoder style transformer.

> [!NOTE]
> see [encoder-decoder/](./encoder-decoder/README.md) for more on encoder-decoder transformers.

### Encoder Only Transformers

Encoder only transformers include Google's [BERT](https://huggingface.co/docs/transformers/model_doc/bert).

> [!NOTE]
> see [encoder-only/](./encoder-only/README.md) for more on encoder only transformers.

### Decoder Only Transformers

Meta's [Llama](https://www.llama.com/) is a decoder only transformer.

> [!NOTE]
> see [decoder-only/](./decoder-only/README.md) for more on decoder only transformers.