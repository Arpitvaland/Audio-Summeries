# Audio-Summeries


## Abstract

This project focuses on advanced techniques in Text Summarization and Voice Over generation. The report evaluates the approach, analysis, programming, results' quality, and a discussion of the outcomes.

## I. Introduction

The project revolves around the synthesis of text summarization and voice over generation. The scoping review reveals various architectures, including sentence extraction, feature extraction, sentence compression, and language modeling.

The goal is to identify significant content in a text and create a condensed version suitable for specific needs. The surge in interest is fueled by advancements in automated speech recognition, audio quality, and the popularity of natural language interfaces.

## II. Understanding the Approaches

Two main techniques, Extractive and Abstractive summarization, are explored. Extractive summarizes by identifying important words or utterances, while Abstractive aims for a concise summary by paraphrasing the original purpose.

For Extractive summarization, a weighted importance of sentences is determined using the "en-core-web-sm" English core web text small model by Spacy. Word frequency, sentence scores, and sorting sentences based on importance are pivotal steps.

Abstractive summarization involves sequence-to-sequence with LSTM modeling, creating an encoder-decoder to train the model for generating summaries.

## III. The Dataset

The CNN daily mails dataset by TensorFlow is used for training and testing the model, ensuring it aligns with real-world scenarios.

## IV. Cleaning the Text Data

The dataset undergoes thorough cleaning, including converting to lowercase, tokenizing, punctuation removal, stopwords removal, extra space removal, repeated characters removal, and stemming.

## V. Training the Model

A Sequence to Sequence encoding with bidirectional LSTM is used to train the model. This architecture is prevalent in various technologies, including voice-activated gadgets and language translation services like Google Translate.

## VI. Evaluation of the Model

Validation and training data loss are plotted for model evaluation, and the Transformer library is utilized for training.

## VII. Deploying the Model to Make Summarizations

The Google Text to Speech (TTS) module is employed to generate audio files. A Streamlit app is created and deployed on Hugging Face for accessibility.

## Deployed App Link

[NLP Audio Summarizer - a Hugging Face Space by pat229988](#)


