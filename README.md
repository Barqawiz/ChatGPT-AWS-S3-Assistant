# ChatGPT AWS S3 Assistant

This repository contains a ChatGPT-based implementation for AWS S3 tasks using the functions feature. The chatbot allows you to perform various operations on your S3 buckets through a conversation-driven approach withou complex code. By using OpenAI's function calling capabilities, the chatbot intelligently identifies and executes S3 actions.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Barqawiz/ChatGPT-AWS-S3-Assistant/blob/main/openai%20functions%20-%20s3%20bucket%20automation.ipynb)

## Features
- List S3 buckets
- List objects within a bucket
- Download a file from a specific bucket to a local directory.
- Upload a file to a specific bucket from a local or remote source.
- Search for a specific file within a bucket (exact or partial match).

## Setup
Create `.env` file with the following fields:
```
AWS_ACCESS_KEY_ID=<your-key>
AWS_SECRET_ACCESS_KEY=<your-key>
OPENAI_API_KEY=<your-key>
```
Install the requirements:
```
pip install -r requirements.txt
```

## Run
```
jupyter notebook
```

## Conversation Flow
<img src="resources/auto-gpt-conversation.jpg">

## License
MIT License

Copyright (c) 2023 Albarqawi
