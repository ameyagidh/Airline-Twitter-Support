# AutoReplyTwitterhandle

## Business Overview

Natural Language Processing (NLP) plays a crucial role in enabling computers to interpret text and spoken words, similar to humans. Social media sentiment analysis is a significant application of NLP, providing valuable insights from platforms like Twitter. This project automates the process of analyzing tweets and responding to them, enhancing customer engagement and satisfaction.

## Aim

The objective is to automatically reply to query-related tweets with a trackable ticket ID, generated based on predicted query categories using deep learning models. This process is fully automated using tweepy API and Big Data techniques, with final deployment on AWS.

<img width="748" alt="Screenshot 2024-03-18 at 3 53 09 AM" src="https://github.com/ameyagidh/AutoReplyTwitterhandle/assets/65457905/83e3d923-322e-496f-83ac-9bc0909f015c">

## Data Description

The project utilizes an "airline tweets" dataset for training, consisting of fields like airline names, actual text, sentiment class (positive, negative, or neutral), and topic class (e.g., Baggage Issue, Customer Experience). This dataset is essential for training the machine learning models used in the project.

## Tech Stack

- Language: Python3
- Services: Confluent Kafka, Spark
- Libraries: tweepy, Flask, kafka, spacy, sklearn, keras, numpy, pyspark, nltk, matplotlib, os

## Approach

The approach involves preprocessing the dataset, training sequential models including LSTM for sentiment and topic classification, named entity extraction, and finally, deploying the system on AWS. Each step is meticulously executed to ensure efficient processing and accurate responses.

## Modular Code Structure

The code is organized into two parts: Engines and Helpers. The Engines consist of various Python scripts responsible for training and inference, while the Helpers contain classes for different tasks such as model evaluation, preprocessing, and reply handling.

## Key Takeaways

This project provides valuable insights into various aspects of NLP and Big Data processing, including data cleaning, model training, deployment on cloud infrastructure, and integration with social media APIs. It also demonstrates the importance of automation in customer support and engagement.

## Architecture Diagram

![Architecture Diagram](architecture_diagram.png)

For detailed instructions on running the code and setting up the environment, please refer to the README file.
