# Tunisian_TTS_System

---
language:
- ar
base_model:
- coqui/XTTS-v2
pipeline_tag: text-to-speech
---


### Finetuning XTTS V2 on Tunisian custom dataset

## Model Details

### Model Description

<!-- Provide a longer summary of what this model is. -->

This model is a fine-tuned version of [coqui ai/xtts v2](https://huggingface.co/coqui/XTTS-v2) on the tunisian_custom dataset (2h and 30mn).
It achieves the following results of loss on the evaluation sets:
First evaluation set: 0.0274
Second evaluation set: 0.0946

#### Training Hyperparameters
batch_size=2
num_of_epochs=6
grad_accumulation_steps=1
Max permitted audio size in seconds=11


### Model repository 

<!-- Provide the basic links for the model. -->

- **link:** [(https://huggingface.co/amenIKh/Tunisian_TTS/settings)]




