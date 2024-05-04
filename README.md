# LLM Training

This project documents LLM training activities, stores the configurations and summarizes the insights.

## Phi-3 MoE Experiment

The aim of this experiment is to investigate to what extent it is possible to turn a Phi-3 model into a MoE model.
We want to use [mergekit](https://github.com/arcee-ai/mergekit) to do this.
For details see [mergekit-moe](https://github.com/arcee-ai/mergekit/blob/main/docs/moe.md).

In the past, there have been [problems with the MoE merge of Phi models](https://github.com/arcee-ai/mergekit/issues/145).
While merging of Llama based models worked well. That is the reason why we use
[vonjack/Phi-3-mini-4k-instruct-LLaMAfied](https://huggingface.co/vonjack/Phi-3-mini-4k-instruct-LLaMAfied)
as our base model.

## Licensing

Copyright (c) 2023-2024 [Philip May](https://philipmay.org)

Licensed under the **MIT License** (the "License"); you may not use this file except in compliance with the License.
You may obtain a copy of the License by reviewing the file
[LICENSE](https://github.com/PhilipMay/llm_training/blob/main/LICENSE) in the repository.
