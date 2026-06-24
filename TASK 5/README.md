# Task 5: Mental Health Support Chatbot (Fine-Tuned DistilGPT2)

## Overview

This project implements a Mental Health Support Chatbot designed to provide supportive and empathetic responses related to stress, anxiety, loneliness, academic pressure, and emotional well-being. The chatbot was developed using Hugging Face Transformers and a fine-tuned DistilGPT2 language model.

The project demonstrates the complete workflow of dataset preparation, tokenization, model fine-tuning, training, evaluation, and chatbot deployment.

---

## Objectives

* Build a chatbot that provides supportive and empathetic responses.
* Fine-tune a pre-trained language model using Hugging Face Trainer API.
* Train the model on mental health-related conversational data.
* Generate human-like responses for emotional wellness conversations.
* Deploy the chatbot through a command-line interface.

---

## Technologies Used

* Python
* Hugging Face Transformers
* Hugging Face Datasets
* Hugging Face Trainer API
* PyTorch
* Accelerate

---

## Model Used

**DistilGPT2**

DistilGPT2 is a lightweight version of GPT-2 that offers faster training and inference while maintaining strong language generation capabilities.

---

## Dataset

The original task specified the EmpatheticDialogues dataset. However, due to Hugging Face Hub access limitations (HTTP 429 rate limiting), a custom empathetic dialogue dataset was created.

The dataset contains supportive conversations covering:

* Exam Stress
* Anxiety
* Loneliness
* Academic Pressure
* Self-Doubt
* Overthinking
* Burnout
* Emotional Wellness

---

## Project Workflow

### 1. Dataset Creation

A custom dataset of empathetic conversations was created using the Hugging Face Datasets library.

### 2. Tokenization

The DistilGPT2 tokenizer was used to convert text into tokenized sequences suitable for training.

### 3. Model Fine-Tuning

The pre-trained DistilGPT2 model was fine-tuned using Hugging Face's Trainer API.

### 4. Training

The model was trained for 5 epochs on the custom mental health dialogue dataset.

### 5. Model Saving

The trained model and tokenizer were saved locally for future use.

### 6. Chatbot Deployment

A command-line chatbot interface was created to interact with the fine-tuned model.

---

## Training Results

### Initial Training

* Dataset Size: 8 examples
* Training Loss: ~1.65

### Improved Training

* Dataset Size: 14 examples
* Training Loss: ~0.097

The significant reduction in loss demonstrates successful learning of empathetic conversational patterns.

---

## Sample Interaction

**User:**
I feel stressed about exams.

**Bot:**
It's understandable to feel stressed. Try taking one step at a time and remember to take breaks.

---

## Project Structure

```text
Task5_Mental_Health_Chatbot/
│
├── Mental_Health_Chatbot.ipynb
├── chatbot.py
├── requirements.txt
├── README.md
│
├── mental_health_model/
│   ├── config.json
│   ├── generation_config.json
│   ├── model.safetensors
│   ├── tokenizer.json
│   ├── tokenizer_config.json
│   └── special_tokens_map.json
│
└── screenshots/
    ├── dataset_creation.png
    ├── training_output.png
    └── chatbot_results.png
```

---

## Installation

Install the required packages:

```bash
pip install transformers datasets accelerate evaluate torch
```

---

## Running the Chatbot

```bash
python chatbot.py
```

Example:

```text
You: I feel anxious about my future.

Bot: Many people feel uncertain about the future. Focus on what you can control today.
```

---

## Learning Outcomes

This project helped develop practical skills in:

* Natural Language Processing (NLP)
* Large Language Models (LLMs)
* Hugging Face Transformers
* Model Fine-Tuning
* Conversational AI Development
* Mental Health Chatbot Design
* Prompt Engineering
* Model Deployment

---

## Disclaimer

This chatbot is intended for educational and research purposes only. It is not a substitute for professional mental health support, counseling, diagnosis, or medical advice. Individuals experiencing serious emotional distress should seek assistance from qualified mental health professionals.

---

## Author

Adifa Jahangir

BS Artificial Intelligence

AI/ML Internship Project – Task 5

