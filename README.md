# Fine-tuning
This repository contains the materials and code for our graduation project, focused on fine-tuning large language models (LLM)
# Fine-Tuned Llama2 on a single dataset using LoRA and QLoRA techniques


# Fine-Tuning:
The process of taking a pre-trained model and adapting it to a new task or dataset.

# LoRA:
Efficiently adapts pre-trained models by updating a smaller subset of parameters, reducing computational cost and memory usage while preserving model performance.

# QLoRA:
Enhances LoRA by applying quantization, further minimizing resource consumption and enabling deployment on hardware with limited capabilities without sacrificing accuracy.


# How they work:

LoRA: LoRA inserts small, trainable matrices (low-rank matrices) into the model. These matrices are much smaller than the full set of model parameters.

QLoRA: After applying LoRA's technique of using low-rank matrices, QLoRA compresses these matrices using quantization. This further reduces the model size and resource requirements.


# Dataset used in training:

Dataset Name: PiyushLavaniya/HTML_Dataset_for_LLama2_Finetuning.
Dataset Link: https://huggingface.co/datasets/PiyushLavaniya/HTML_Dataset_for_LLama2_Finetuning/viewer/default/train
</br>
</br>
- It's a small dataset (2k rows). We couldn't use a larger dataset because of the limited computational resources.
- We found a dataset (501k rows) to improve python coding and we tried to use it to fine-tune Llama2 using LoRA and QLoRA but we ran out of computational resources on Colab so I had to use the HTML (2k rows) dataset. Dataset Link: https://huggingface.co/datasets/luisroque/instruct-python-llama2-500k
- Buying extra resources from Colab or subscribing in the pro version isn't available in Jordan.


</br>
</br>
</br>
</br>
</br>

# Graduation Project Team
#    - COMPS 💻

Github of team members:

- Ahmad Elwan: https://github.com/AhmadElwan
- Hamza Radaideh: https://github.com/HamzaRadaideh
- Mohammad Ahmad: https://github.com/mosubehi
- Khaled Samara: https://github.com/Khaled270


