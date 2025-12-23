---
library_name: peft
license: other
base_model: baidu/ERNIE-4.5-0.3B-PT
tags:
- base_model:adapter:baidu/ERNIE-4.5-0.3B-PT
- llama-factory
- lora
- transformers
pipeline_tag: text-generation
model-index:
- name: train_2025-12-23-08-34-28
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# train_2025-12-23-08-34-28

This model is a fine-tuned version of [baidu/ERNIE-4.5-0.3B-PT](https://huggingface.co/baidu/ERNIE-4.5-0.3B-PT) on the puyi_data dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 0.0003
- train_batch_size: 2
- eval_batch_size: 8
- seed: 42
- gradient_accumulation_steps: 8
- total_train_batch_size: 16
- optimizer: Use adamw_torch with betas=(0.9,0.999) and epsilon=1e-08 and optimizer_args=No additional optimizer arguments
- lr_scheduler_type: cosine
- num_epochs: 3.0

### Training results



### Framework versions

- PEFT 0.17.1
- Transformers 4.57.1
- Pytorch 2.9.1+cu128
- Datasets 4.0.0
- Tokenizers 0.22.1