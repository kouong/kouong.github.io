---
title : Hello Portfolio
date: 2025-08-09 12:00:00 -500
categories: [welcome]
tags: [greetings]
---


# Welcome

Welcome to my portfolio website! I'm thrilled to have you here. This space is a showcase of my journey and passion in the world of technology, particularly focusing on cloud computing and artificial intelligence.

Here, you'll find a collection of projects, insights, and experiences that highlight my skills and dedication to innovation. From intricate cloud architectures to intelligent AI solutions, each piece represents a step in my continuous learning and growth.

Feel free to explore, delve into the details of my work, and discover how I leverage cutting-edge technologies to solve real-world problems. I believe in the power of technology to transform and empower, and I hope my portfolio reflects that conviction.

Thank you for visiting, and I look forward to connecting with you!

## Cloud
In the cloud section of my portfolio, you'll discover a range of projects demonstrating my expertise in designing, deploying, and managing scalable and resilient cloud infrastructures. I've worked extensively with various cloud platforms, including AWS, Azure, and Google Cloud, leveraging their services to build robust solutions. My focus areas include serverless architectures, containerization with Docker and Kubernetes, infrastructure as code (IaC) using Terraform, and implementing CI/CD pipelines for automated deployments. I'm passionate about optimizing cloud resources for cost-efficiency and performance, ensuring high availability and disaster recovery strategies are in place.


## Artificial Intelligence
The Artificial Intelligence section of my portfolio delves into my work on creating intelligent systems that can learn, reason, and interact. I have hands-on experience in developing and deploying machine learning models to tackle complex challenges. My projects span across various domains, including natural language processing (NLP) for sentiment analysis and text summarization, as well as computer vision for object detection and image classification. I am proficient with popular frameworks like TensorFlow and PyTorch, and libraries such as scikit-learn for building robust models. I focus on the entire ML lifecycle, from data preprocessing and feature engineering to model training, evaluation, and deployment using MLOps best practices. This ensures that the solutions are not only accurate but also scalable and maintainable in production environments. I am passionate about exploring the frontiers of AI, including deep learning and reinforcement learning, to build innovative and impactful applications.


```python
from langchain_community.llms import Ollama

llm = Ollama(model="llama2")
response = llm.invoke("Tell me a very short story.")
print(response)

```

## Github actions

```yaml	
name: CI/CD Pipeline

on:
  push:
    branches:
      - main

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
    - name: Checkout repository
      uses: actions/checkout@v2

    - name: Run a one-line script
      run: echo Hello, world!

    - name: Run a multi-line script
      run: |
        echo Add other actions to build,
        echo test, and deploy your project.
```