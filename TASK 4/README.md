# Task 4: General Health Query Chatbot

## Objective

The objective of this task was to develop a simple General Health Query Chatbot capable of answering common health-related questions using prompt engineering and basic Natural Language Processing (NLP) techniques. The chatbot is designed to provide general health information while avoiding medical diagnosis and prescription recommendations.

## Dataset and Model

No external dataset was required for this task. The chatbot was developed using Python and prompt-based responses with a safety filtering mechanism to ensure responsible interactions.

## Tools and Libraries Used

* Python
* Google Colab
* Transformers (optional)
* PyTorch (optional)

## Methodology

### 1. Prompt Engineering

A structured prompt was designed to guide the chatbot's behavior. The chatbot was instructed to:

* Provide general health information.
* Use simple and friendly language.
* Avoid diagnosing diseases.
* Avoid prescribing medications.
* Recommend consulting healthcare professionals for serious symptoms.

### 2. Safety Filter

A safety filtering mechanism was implemented to detect harmful or sensitive queries such as:

* Suicide
* Self-harm
* Overdose

If such keywords are detected, the chatbot immediately advises the user to seek professional help instead of generating a response.

### 3. Interactive Chat Loop

The chatbot continuously accepts user questions until the user enters "exit" to terminate the session.

## Example Questions

* What causes a sore throat?
* How can I lower my blood pressure?
* What are the symptoms of dehydration?
* What causes headaches?
* How much water should I drink daily?

## Results

The chatbot successfully answered general health-related questions and provided informative responses in a user-friendly manner. The safety filter effectively blocked potentially harmful queries and encouraged users to seek professional medical assistance when appropriate.

## Key Features

* Interactive command-line chatbot
* General health information support
* Prompt engineering implementation
* Safety filtering for harmful queries
* Easy-to-use interface

## Conclusion

This task demonstrated the application of prompt engineering, chatbot development, and safety-aware AI design. The chatbot provides basic health information while maintaining ethical boundaries by avoiding diagnosis and medication recommendations. The project highlights fundamental NLP and conversational AI concepts relevant to AI/ML engineering.
