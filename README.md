# AI Study Assistant

A simple Python application that uses **Mellea** and an AI model to create a study plan from a list of topics.

## 🎯 Project Overview

The application takes a list of study topics and asks an AI model to create a structured study plan.

The goal is to demonstrate how Python can interact with a local AI model using the **Mellea** framework.

## 📁 Project Structure

```text
ai-study-assistant/
└── study_assistant.py
```

## ⚙️ Requirements

* Python 3.10+
* Mellea
* A supported local AI model

Install Mellea with:

```bash
pip install mellea
```

## 📝 Your Task

The `study_assistant.py` file contains a function called:

```python
def create_study_plan(topics):
```

Your task is to implement this function using **Mellea**.

The function should:

1. Receive a list of study topics.
2. Send an appropriate prompt to an AI model.
3. Ask the AI to organize the topics into a study plan.
4. Return the AI-generated study plan.

The `main()` function is already provided and should not need to be modified.

## 📚 Input

The application starts with the following topics:

```python
topics = [
    "Python functions",
    "Git and GitHub",
    "Machine learning",
    "Linear regression",
    "Neural networks",
]
```

## 💻 Running the Application

Run:

```bash
python study_assistant.py
```

## 💡 Sample Output

The exact output will depend on the AI model and prompt, but it should be similar to:

```text
MY STUDY TOPICS
----------------------------------------
1. Python functions
2. Git and GitHub
3. Machine learning
4. Linear regression
5. Neural networks

AI STUDY PLAN
----------------------------------------

1. Python Functions
   Review function definitions, parameters,
   arguments, and return values.

2. Git and GitHub
   Practice repositories, branches, commits,
   pushes, and pull requests.

3. Machine Learning
   Review supervised and unsupervised learning
   and understand the basic machine learning workflow.

4. Linear Regression
   Study features, targets, the mathematical model,
   and how predictions are generated.

5. Neural Networks
   Review neurons, layers, activation functions,
   and the basic training process.
```

## 🤖 About Mellea

**Mellea** is an AI application framework that allows Python programs to interact with generative AI models.

In this project, Mellea is used to send instructions to an AI model and receive a generated study plan.

The main programming challenge is to design an effective prompt and integrate the AI response into the Python function.

## 🎓 Learning Objective

By completing this project, you will practice:

* Python functions
* Lists and strings
* Prompt design
* Generative AI
* Calling an AI model from Python
* Processing AI-generated responses
