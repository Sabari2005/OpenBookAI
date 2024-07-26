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

#### OpenBookAI Interface
![screenshot_interface](/screenshots/OpenBookAI_interface.png)
#### OpenBookAI Query1 Interface
![screenshot_query1_interface](/screenshots/OpenBookAI_explaining_OSI_Layer.png)
#### OpenBookAI Query2 Interface
![screenshot_query2_interface](/screenshots/OpenBookAI_explaining_CPU_Scheduling.png)

### Links

- [Demo Video](https://youtu.be/kNFYi1nSVDY?si=BCVsleZFAo8UBVPt)
- [Project Repository](https://github.com/Sabari2005/OpenBookAI)

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
```

## Built With
- Python
- Jupyter Notebook
- NumPy
- Pandas
- scikit-learn (sklearn)
- Sentence Transformers
- Textstat
- Transformers
- spaCy
- Flask
- pyngrok

## Installation

### Prerequisites
- Python 3.7 or higher
- pip (Python package installer)

### Setup

1. **Clone the repository:**
    ```bash
    git clone https://github.com/Sabari2005/OpenBookAI.git
    cd OpenBookAI
    ```

2. **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3. **Download the required models:**
    ```python
    import nltk
    nltk.download('punkt')
    ```

4. **Run the development server:**
    ```bash
    jupyter notebook
    ```

5. **Set up ngrok for secure tunneling:**
    ```bash
    ngrok authtoken your_ngrok_authtoken
    ngrok http 5000
    ```

### Access the application:
- Open your web browser and go to the provided ngrok URL or localhost URL.

## Author

- Website - [SABARI VADIVELAN](https://in.linkedin.com/in/sabari-vadivelan-s-637667258)
- Website - [UVARAJAN_D](https://www.linkedin.com/in/uvarajan-dev/)
- Website - [KAMAL M](https://www.linkedin.com/in/kamal-m-857925258/)
- Website - [SARATHI S](https://www.linkedin.com/in/sarathi-senthil-547877258/)

## Contact Developer

- Discord - [SABARI VADIVELAN](https://discord.com/users/1102493010538799225)
- Discord - [UVARAJAN](https://discord.com/users/1084096662412210376)
- Discord - [KAMAL](https://discord.com/users/1086220089684152340) 
- Discord - [SARATHI](https://discord.com/users/1187035919048527902) 
