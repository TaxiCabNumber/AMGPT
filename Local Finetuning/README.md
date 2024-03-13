---
license: mit
base_model: gpt2
tags:
- generated_from_trainer
model-index:
- name: Local Finetuning
  results: []
---

<!-- This model card has been generated automatically according to the information the Trainer had access to. You
should probably proofread and complete it, then remove this comment. -->

# Local Finetuning

This model is a fine-tuned version of [gpt2](https://huggingface.co/gpt2) on an unknown dataset.

## Model description

More information needed

## Intended uses & limitations

More information needed

## Training and evaluation data

More information needed

## Training procedure

### Training hyperparameters

The following hyperparameters were used during training:
- learning_rate: 5e-05
- train_batch_size: 8
- eval_batch_size: 8
- seed: 42
- optimizer: Adam with betas=(0.9,0.999) and epsilon=1e-08
- lr_scheduler_type: linear
- num_epochs: 50.0

### Training results



### Framework versions

- Transformers 4.38.2
- Pytorch 2.2.0
- Datasets 2.18.0
- Tokenizers 0.15.2
