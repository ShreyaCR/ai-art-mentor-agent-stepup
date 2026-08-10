# 🎨 AI Art Mentor Agent

An AI-powered multimodal art mentor built with Python, OpenAI API and Gradio.

The application allows artists to upload a painting and receive AI-generated feedback, artistic guidance and improvement suggestions. The agent can also use web search when additional information is required and maintains persistent user memory for more personalized interactions.

## 🚀 Project Overview

This project demonstrates how agentic AI can be applied to a creative domain by combining multimodal interaction, tool use, persistent memory and an interactive web interface.

Instead of building a simple chatbot, I designed an AI assistant capable of:

- Understanding user questions about art
- Providing painting critiques
- Giving artistic improvement suggestions
- Accepting uploaded painting images
- Using an external web-search tool
- Maintaining persistent memory
- Producing responses through a Gradio web interface

## 🧠 Key Features

### 1. Painting Critique
Users can upload a painting and receive AI-generated feedback about composition, color, values and possible improvements.

### 2. Multimodal Interaction
The application supports image input along with natural-language questions.

### 3. Tool Use
The agent can use a web-search tool when additional information is required.

### 4. Persistent Memory
User information and previous interactions can be stored using JSON-based memory.

### 5. Gradio Interface
A simple web interface allows users to interact with the AI mentor without directly working with the Python code.

## 🏗️ System Architecture
## 🖥️ Application Preview

The AI Art Mentor provides an interactive interface where users can upload a painting, ask questions and receive AI-generated artistic feedback.
```text
User
  │
  ▼
Gradio Interface
  │
  ▼
AI Art Mentor Agent
  │
  ├── OpenAI API
  │
  ├── Image Input
  │
  ├── Web Search Tool
  │
  └── Persistent Memory
          │
          ▼
     AI-generated
     Art Feedback

