# Simple-Chatbot
## Overview
A simple AI chatbot built with FastAPI and OpenAI API.
It provides a minimal web interface for chatting with the model.

## Features
FastAPI backend with HTML templates
Integration with OpenAI API
Environment variables managed via .env

## Installation
**Clone the repo**
```bash
git clone https://github.com/Baoying1206/Simple-Chatbot.git
cd chatbot
```
**Install dependencies**
```bash
pip install -r requirements.txt
```
**Set environment variables**

Create a .env file:
```bash
OPENAI_API_KEY=your_api_key_here
```
**Run locally**
```bash
uvicorn main:app --reload
```
**Visit:** http://127.0.0.1:8000
