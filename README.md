# ⚛️ Physics RAG Bot

A Physics Explanation Bot built using Retrieval-Augmented Generation (RAG).
Ask any physics question and get a clear explanation with equations.

## What it does
- Retrieves answers from OpenStax University Physics textbooks (Vol 1, 2, 3)
- Explains physics concepts clearly
- Displays equations in clean plain text format (F = ma, V = IR, etc.)

## Tech Stack
- LangChain — RAG framework
- Groq + openai/gpt-oss-20b — LLM for answer generation
- ChromaDB — Vector database
- HuggingFace Embeddings — Text to vector conversion
- OpenStax Physics — Knowledge base (free academic textbooks)
- Google Colab — Runtime environment

## How to Run
1. Open the notebook in Google Colab
2. Add your Groq API key in Colab Secrets
3. Run all cells from top to bottom
4. Ask any physics question!

## Example Questions
- What is Newton's Third Law?
- Explain Ohm's Law with formula
- What is the equation for kinetic energy?
- Explain conservation of energy

## Knowledge Base
- OpenStax University Physics Volume 1 (Mechanics, Newton's Laws, Waves)
- OpenStax University Physics Volume 2 (Electromagnetism, Circuits, Optics)

## Get Groq API Key
Free API key available at: https://console.groq.com
