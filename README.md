# Advanced-Twitter-Bot-Detection
This project uses Machine Learning and Deep Learning models to detect whether a Twitter account is a bot or a human based on tweet content, engagement patterns, and account behavior.

It includes traditional ML models, RNN models, and advanced Transformer models such as BERT, RoBERTa, XLNet, and T5.

🔍 Project Overview

Twitter has a growing problem with automated bot accounts.
These bots spread misinformation, spam, and artificially boost online activity.

This project builds a system that:

Analyzes tweet text and user behavior

Trains multiple ML and DL models

Compares their performance

Identifies which models work best for bot detection

The project is based on the Twitter Bot Detection Dataset and the CRESCI 2017 Dataset, both widely used in research.

🧠 Models Used

The following models were trained and compared:

✔ Machine Learning

Random Forest

✔ Deep Learning (RNNs)

LSTM

GRU

✔ Transformer Models

BERT

RoBERTa

DistilBERT

XLNet

T5-Small

These models help understand both behavior patterns and textual patterns of bots.

📊 Key Findings

Transformer models performed best on structured datasets (up to 98–99% accuracy).

Real-world Twitter data is noisy, and model accuracy dropped (around 50–76% depending on model).

Bots show patterns like repeated language, abnormal retweet timing, and predictable interactions.

📁 What’s Included in This Project

Data preprocessing

Exploratory Data Analysis (EDA)

Feature extraction (text + numerical)

Training scripts for all models

Confusion matrices and evaluation results

Visualizations (word clouds, heatmaps, engagement trends)
