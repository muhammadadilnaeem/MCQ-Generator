# **Generative AI Project: MCQ Generator using OpenAI, Langchain Streamlit**

## **Author: Muhammad Adil Naeem**

[![GitHub](https://img.shields.io/badge/GitHub-Profile-green?style=for-the-badge&logo=github)](https://github.com/muhammadadilnaeem) 
[![Twitter/X](https://img.shields.io/badge/Twitter-Profile-red?style=for-the-badge&logo=twitter)](https://twitter.com/adilnaeem0) 
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/muhammad-adil-naeem-26878b2b9/)
## Overview
The **MCQ Generator** is a comprehensive project designed to generate multiple-choice questions (MCQs) from provided text, evaluate the complexity of these questions, and present them through a user-friendly web interface. This project leverages LangChain and Streamlit for its core functionality.

## Table of Contents
- [**Generative AI Project: MCQ Generator using OpenAI, Langchain Streamlit**](#generative-ai-project-mcq-generator-using-openai-langchain-streamlit)
  - [**Author: Muhammad Adil Naeem**](#author-muhammad-adil-naeem)
  - [Overview](#overview)
  - [Table of Contents](#table-of-contents)
  - [Project Structure](#project-structure)
  - [Features](#features)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Configuration](#configuration)
  - [Data](#data)
  - [Experiments](#experiments)
  - [Acknowledgements](#acknowledgements)

## Project Structure
```plaintext
MCQ-Generator-main/
├── .gitignore
├── README.md
├── doubt.txt
├── mcq_training_data.txt
├── requirements.txt
├── response.json
├── setup.py
├── streamlit.py
├── experiments/
│   ├── machine_learning_quiz.csv
│   └── mcq.ipynb
└── src/
    ├── __init__.py
    └── mcqgenerater/
        ├── MCQgenerater.py
        ├── __init__.py
        ├── logger.py
        └── utils.py
```

## Features
- **MCQ Generation**: Generate MCQs from provided text using advanced natural language processing techniques.
- **Complexity Evaluation**: Assess the complexity of the generated MCQs.
- **Web Interface**: User-friendly web interface to interact with the MCQ generator.

## Installation
To install the necessary dependencies, run the following command:
```bash
pip install -r requirements.txt
```

## Usage
To use the MCQ generator, run the `streamlit.py` script:
```bash
streamlit run streamlit.py
```

## Configuration
You can configure various aspects of the project in the `setup.py` file and adjust logging settings in `src/mcqgenerater/logger.py`.

## Data
The project includes example training data (`mcq_training_data.txt`) and a sample response file (`response.json`).

## Experiments
The `experiments` directory contains a Jupyter notebook (`mcq.ipynb`) and a CSV file with machine learning quiz data (`machine_learning_quiz.csv`).



## Acknowledgements
We would like to thank the developers of LangChain and Streamlit for their excellent tools and frameworks. Also ineuron, for giving us the opportunity to work on this project.
