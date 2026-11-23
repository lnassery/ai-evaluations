# AI Evaluations Book Code Examples

This repository contains the code examples that accompany the *AI Evaluations* book. The goal is to provide **practical, hands‑on snippets** that bring the concepts in the book to life, so you can see how to compute metrics, run diagnostics, and build an evaluation workflow step by step.

## How to Run the Notebooks

You don’t need to install anything locally—all notebooks can run entirely in your browser.

- **Just click and run:** Open any notebook in [Google Colab](https://colab.research.google.com) and execute the cells.
- No setup and no Python installation required.

### **Why Notebooks?**
Jupyter notebooks are perfect for this project because they blend **narrative, code, and output in one place.**
- **Fairly Interactive:** You can run each cell step by step, inspect outputs, and modify code on the fly.
- **Really Accessible:** Since they run in the browser via Colab, you don’t need to set up a development environment—just click and explore.
- **Extreme Familiarity:** Most data scientists and ML engineers already know Python, making the examples easy to follow.

## What’s Inside

- **`/notebooks`** – Jupyter notebooks for each chapter.

Each notebook is self‑contained and mirrors a concept from the book.

- **Chapters 2:** Demonstrates a simplified offline evaluation for a movie recommendation system, focusing on precision as the key metric. We'll build a basic genre-weighted recommendation algorithm and evaluate its precision.
- **Chapters 3:** Illustrates how to perform a diagnostic offline evaluation that identifies potential bias in movie recommendation systems
- **Chapters 4:** Demonstrates a simple implementation of shadow traffic for evaluating AI model performance metrics.
- **Chapters 5:** Demonstrates Off-Policy Evaluation and Incremental Action Value
- **Chapters 6:** Illustrates a specific section within Chapter 6 (6.4.2) which is all about detecting feature drift during model evaluations

## Why This Repo Exists

Evaluations, whether its offline, online or an LLM-as-a-judge, are the reality check for your AI model. These examples exist for the following reasons: 
- Understand the math and code behind key evaluation metrics
- See the general construction of an evaluation with simple datasets and examples
- Use the code as a reference (or even a starting point) for your own evaluations 
