# japeto-convo-classifier

Machine learning project for Japeto Chat to categorise AI-generated chatbot responses.
Trained on 1,500+ tagged conversations, the model classifies responses into predefined categories to improve analytics accuracy and insights for chatbot owners in healthcare, government, and education.


# Project Overview

Japeto Chat enables organisations to build and manage AI-driven chatbots.
While scripted responses are pre-tagged, AI-generated responses lack category labels, limiting analytics.
This project develops a classifier to categorise AI-generated chatbot responses with an accuracy target of 85% or higher.


# Features

Classifies AI generated responses into meaningful categories

Uses a dataset of 1,500+ tagged chatbot conversations

Supports real time or batch classification

Enhances chatbot analytics dashboard visibility

Built with Python, Jupyter, scikit-learn, and transformers


# Repository Contents

Final-version-Japeto.ipynb – Jupyter Notebook with training and evaluation code

chatbot_dataset.xlsx – Training dataset of chatbot messages

README.md – Project documentation


# How to Run

* Clone the repository:

git clone https://github.com/omorros/japeto-convo-classifier.git
cd japeto-convo-classifier


* Install dependencies:

pip install -r requirements.txt


* Open the Jupyter notebook:

jupyter notebook Final-version-Japeto.ipynb


# Results

Achieved over 85% accuracy on unseen test data

Categories align with scripted chatbot analytics

Supports fallback to manual tagging if confidence is low


# About Japeto

Japeto is a UK based software agency specialising in AI-driven chatbot solutions for healthcare, government, and education sectors.
