# 🍳 AI Recipe Generator

A simple AI-powered recipe generator built using the OpenAI API and Pydantic structured outputs.
Given a dish name, the system generates a structured recipe including ingredients, cooking time, and step-by-step instructions.

## 🚀 Features

* Generate recipes using AI
* Structured JSON output
* Type validation using Pydantic
* Clean and minimal implementation
* Easy to extend into an API or web app

## 🧰 Tech Stack

* Python
* OpenAI API
* Pydantic

## ⚙️ Setup

Install dependencies:

```
pip install openai pydantic python-dotenv
```

Create a `.env` file:

```
OPENAI_API_KEY=your_api_key_here
```

## ▶️ Usage

Run the notebook and call:

```
print(recipe_generator("burger"))
```

This will generate a structured recipe with ingredients and cooking instructions.
