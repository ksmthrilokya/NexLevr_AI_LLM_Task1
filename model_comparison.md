# Comparing Open-Source Language Models
## Nexlevr AI & LLM Fundamentals Internship - Beginner Task 2

## Objective
Compare the outputs of three different open-source language models on an identical prompt to evaluate differences in style, depth, and approach.

## Prompt Used (identical for all 3 models)
"Explain the concept of machine learning in 3 sentences, suitable for a complete beginner."

## Models Tested
All three models were tested using HuggingChat (huggingface.co/chat).

---

### 1. Meta Llama 3.1 (8B Instruct)
**Output:**
"Based on the web search results, the concept of machine learning can be explained in 3 sentences as follows: Machine learning is a type of artificial intelligence that allows computers to learn from data and improve their performance on a task without being explicitly programmed. It involves training algorithms on large datasets to enable them to make predictions or classifications, and is commonly used in supervised learning tasks such as regression and classification. By using machine learning, computers can automatically improve their performance on a task, such as predicting house prices or identifying images, without being explicitly programmed to do so."

**Observations:** Used a web search tool before answering. Gave a more formal, technical definition mentioning supervised learning, regression, and classification. Slightly exceeded the 3-sentence limit due to the added intro line.

---

### 2. Google Gemma (3-4B Instruct)
**Output:**
"Machine learning is a way to teach computers to learn from data without being explicitly programmed. Instead of following fixed rules, these systems identify patterns and make predictions based on the information they're given. Essentially, it's like training a computer to recognize and respond to new situations by analyzing past experiences — the more data it sees, the better it gets at its task."

**Observations:** Clean, exactly 3 sentences as requested. Used a simple analogy (training/experience) that is easy for a beginner to understand. No unnecessary technical jargon.

---

### 3. Qwen (Qwen3.8-27B)
**Output:**
"Machine learning is a type of computer science where computers learn patterns from data instead of following strictly written instructions. Think of it like how you learn from examples — the more examples a system sees, the better it gets at recognizing patterns and making predictions. For instance, by studying thousands of labeled photos, a machine can learn to tell the difference between a cat and a dog in a new image it has never seen before."

**Observations:** Included a visible "Thinking" step before answering. Used a relatable example (cat vs. dog image recognition) to make the concept concrete. Balanced both simplicity and a real-world example.

---

## Summary Comparison

| Model | Sentence Count | Style | Used Extra Tools | Best For |
|---|---|---|---|---|
| Llama 3.1 8B | 3 (+ intro line) | Formal, technical | Web search | Technical accuracy |
| Gemma 3-4B | Exactly 3 | Simple, analogy-based | None | True beginners |
| Qwen 3.8-27B | 3 | Example-driven | Visible reasoning step | Concrete understanding |

## Conclusion
All three open-source models successfully explained machine learning within the requested constraints. Gemma gave the most concise, beginner-friendly answer. Llama 3.1 leaned more technical and used a web search tool for grounding. Qwen balanced simplicity with a concrete real-world example, making it the most relatable for a true beginner audience.

## Author
Kolluru Sai Mani Thrilokya
