# OpenBookAI - Unified Analytical Tool for AI Models

OpenBookAI is an advanced analytical platform designed to aggregate and synthesize responses from multiple leading AI models such as ChatGPT, Gemini, and Copilot. This tool leverages machine learning algorithms to provide comprehensive insights from diverse AI perspectives, enhancing the accuracy and depth of data analysis.

## Table of Contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
  - [Features](#features)
  - [Project Architecture](#project-architecture)
- [Built with](#built-with)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
- [Usage](#usage)
- [Author](#author)
- [Contact Developer](#contact-developer)

## Overview

OpenBookAI integrates various state-of-the-art AI models to provide a unified analysis platform. It includes features like text summarization, topic extraction, and image adaptation based on extracted topics.

### Screenshot

#### OpenBookAI Query Interface
![screenshot_query_interface](/screenshots/openbookai_screenshot1.png)
#### OpenBookAI Analysis Results
![screenshot_analysis_results](/screenshots/openbookai_screenshot2.png)

### Links

- [Live Demo](#) (Replace with actual link)
- [Project Repository](https://github.com/yourusername/OpenBookAI) (Replace with actual link)

### Features

- **Text Summarization:** Uses BERT-based models for generating concise summaries.
- **Topic Extraction:** Leverages spaCy for extracting key topics from the text.
- **Image Adaptation:** Fetches relevant images based on extracted topics using Google Custom Search API.
- **Interactive Web Interface:** Built with Flask and accessible via ngrok.

### Project Architecture

```plaintext
OpenBookAI
│
├── models
│   ├── BERT-based Summarizer
│   ├── spaCy Topic Extractor
│   └── Google Custom Search Integration
│
├── web
│   ├── Flask App
│   └── ngrok Integration
│
├── notebooks
│   └── Jupyter Notebooks for Model Training and Testing
│
└── requirements.txt
