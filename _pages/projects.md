---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

Below, you can find the projects I completed during my B.Sc., M.Sc. degrees, and work experience.

## Fin-AiDea

### Independent Project
Fin-AiDea is an advanced platform designed to help you gain insights into financial models for your portfolio by predicting future prices. This tool provides valuable predictions based on sophisticated models but does not offer specific investment advice.

[Repository](https://github.com/doganparlak/AiDea)

## AIDa - Roleplay Chatbot

### Abdi Business Technologies
The project aims to assist medical representatives in training on specific medicines, aiming to enhance sales performance. I created a chatbot which represents medical professional personas (doctors, pharmacists), fine-tuned the model and built a Retrieval-Augmented Generation (RAG) system to provide accurate, context-aware responses. The chatbot operates in a speech-to-speech format for realistic training simulations.

## AI Candidate Analysis

### Abdi Business Technologies
The project aims to provide an end-to-end AI-supported hiring process. I led the development of this project, which includes CV analysis based on seniority-specific job descriptions, candidate filtering, personalized interview questions with follow-ups, and a bot that joins interviews to assess and evaluate candidates operating in a speech-to-speech format.

## Apranax & Youplus Chatbot

### Abdi Business Technologies
By leveraging a RAG model built on Azure, the project delivers a chatbot that provides users with accurate and up-to-date product information.

[Youplus](https://www.youplus.com.tr)


## Unknown Data Classification through Ensemble Learning

### Case Study
The project showcases a classification task designed to achieve a targeted cross entropy loss on an unknown tabular dataset. Utilizing various machine learning algorithms such as LightGBM, XGBoost, Multi-Layer Perceptron (MLP), and Random Forest, both individually and as an ensemble, the approach encompasses data preprocessing using the UMAP (Uniform Manifold Approximation and Projection) model to extract meaningful features from the raw tabular data. Following preprocessing, each algorithm is trained on the data, and an ensemble of models is constructed to determine their contributions to the final prediction using Gaussian Process Minimization. This case study was completed for the hiring process of SWC Capital and is presented as a Jupyter notebook, detailing the entire pipeline from data preprocessing to ensemble learning.

[Repository](https://github.com/doganparlak/UnknownDataClassification)


## Real-Time Arbitrage Monitoring

### Case Study
A project aimed at analyzing real-time book ticker data from Binance with the goal of identifying potential triangular arbitrage opportunities. This project utilizes WebSocket streams to acquire the book ticker data and employs algorithms that consider both ask and bid prices to identify potential arbitrage opportunities. The study demonstrates the liquidity of symbols, arbitrage triggers, and frequency of observed arbitrages, along with paired symbols. The results are compiled and presented in a comprehensive presentation for interpretation, providing insights into the efficiency of the market and the potential for triangular arbitrage opportunities in real-time book ticker data from Binance.

[Repository](https://github.com/doganparlak/ArbitrageMonitoring)


## Player Workload

### UEFA, Intelligence Center
Utilizing datasets from Transfermarkt, OPTA, and UEFA, I led the integration of online data repositories for strategic off-pitch football research. This involved incorporating statistical and machine learning analysis to study player workload.

[Presentation](/files/player_workload.pdf)

## Metric Implementation and Technical Analysis

### UEFA, Football Department
I was provided with tracking and event data from the Champions League match between LOSC and Ajax Amsterdam, which took place on November 27, 2019. I utilized this data to implement the following metrics: ball location, press classification, progression classification, pass classification, running total of ball out of play, and running total of effective time.

[Presentation](/files/technical_analysis_presentation.pdf)

## An Open-Source Implementation of FIFA’s Enhanced Football Intelligence 

### University of Zurich and ETH Zurich, Master's Thesis
Research Question: Were the concepts in the Enhanced Football Intelligence document sufficiently detailed to allow for reproduction of FIFA’s match reports?  
The goal of the thesis was to provide an open-source implementation of the concepts in the [Enhanced Football Intelligence](https://www.fifatrainingcentre.com/media/native/world-cup-2022/Enhanced%20Football%20Intelligence%20EN.pdf) document and validate it using FIFA World Cup 2022 data. Where necessary, ambiguities were resolved, alternatives were tested, and potential improvements were included.

[Library](https://gitlab.uzh.ch/dogan.parlak/EFI)

## Formations and Passing

### ETH Zurich, Social Networks Lab

We have employed spatio-temporal tracking data obtained from UEFA to generate an automatic formation detection and role assignment algorithm. Utilizing the same dataset, we have worked on clustering passing patterns of players and teams by building spatial networks.

[Repository](https://github.com/doganparlak/FormationDetectionRoleAssignment)

## Italy v Spain Match Analysis, EURO 2020

### ETH Zurich, Soccer Analytics

We analyzed EURO 2020 semi-final match Italy against Spain. Various analysis techniques regarding players’ movement, passing, shooting, in-game and end-of-game match probabilities, set-pieces, player valuations, ratings were examined. Results of these analyses were collected in a match report based on the event data obtained from Statsbomb, and the tracking data obtained from UEFA was generated.

[Report](/files/soccer_analytics.html)

## UniFi: A Unified Framework for Portfolio Management

### University of Zurich, Master's Research Project

We have created a framework which provides its users the opportunity to compare different portfolio allocation methodologies. The framework consisted of three main layers. Initial one was a financial environment layer in which users could either fetch or import their own data and apply feature engineering. The second layer was the model layer. It enabled users to either use a conventional model or a reinforcement learning model as the portfolio allocation algorithm. Lastly, the evaluation layer was utilized to apply back-testing and view the performance of the chosen algorithm with preferred performance metrics.

[Framework](https://github.com/doganparlak/uniFi)
[Report](/files/Master_s_Project_Report_Final.pdf)

## Creating Evidence in a Real-World Health Data Science Scenario

### University of Zurich, Data Science in Digital Health
The objective of the DigitalHealth project is to gain previously unknown knowledge and create evidence regarding the Swiss COVID-19 situation. The task involves discovering interesting patterns and validating them through hypothesis generation.

[Repository](https://github.com/doganparlak/DigitalHealth)

## Cryptocurrency Price Direction Prediction

### University of Zurich, Finance and Machine Learning

We set up a binary classification task which predicted the direction of “close prices” of the cryptocurrencies: ADA, BTC, DOGE, ETH and LTC utilizing high level frequency (minute level) data. Feature engineering was done to handcraft the most prevalent technical features used in technical analysis. Model-dependent and model-agnostic feature selection methods were utilized to select the most informative and relevant features. A Decision Tree model was built as a baseline and aimed to improve the prediction accuracy in varying time horizons using Support Vector Machine, Logistic Regression, Artificial Neural Network, Recurrent Neural Network and Random Forest models.

[Report](/files/Project_Report_Final.pdf)

## Alzheimer Phase Detection

### University of Zurich, Applied Business Modelling and Analaytics

I set up a multilabel classification task that utilizes fMRI images of distinct people who faced Alzheimer and predict the phase of their disease. There were four stages of the disease namely Non-Demented, Mild Demented, Moderate Demented and Very Mild Demented. A Convolutional Neural Network was built to train, validate and test the objective.

[Report](/files/Written Report_Revised.pdf)

## Bee Smart

### Bilkent University, Bachelors Graduation Project

The project have embedded components consisting of GSM, GPS, microphone, weight, and temperature sensors to monitor the smart hive in addition to Edge Learning. Main aim was to predict the internal conditions of the hive using bee sounds, while simultaneously reporting the results to a cloud server to establish the IoT communication over MQTT with Android and Web applications for the clients.

## Financial Risk Optimizing for Lending Club Lenders

### Bilkent University, Statistical Learning and Data Analytics

A binary classification task was constructed to predict whether the borrowers were going to fully pay their debt based on distinct loans considering the features of the borrowers. Dataset contained 1.300.000 loans with 75 features such as current, late, fully paid and latest payment information. Logistic Regression, Multi-Layer Perceptron, Random Forest and Support Vector Machine models were individually implemented from scratch.

## Fully Automated Crossword Generator

### Bilkent University, Artificial Intelligence

We developed a program that inputs clues of a 5x5 New York Times mini-puzzle and its solution. Its objective was to generate new clues. We have utilized definition extraction and scheme generation.
## Athlete Test

### Bilkent University, Microprocessors

We have developed an athlete test that uses distance, alcohol, heart rate and temperature sensors to determine the condition of an athlete. C++ programming language was used to program the board KL25Z. Keypad and LCD components were configured in order to obtain and display data using Arduino Uno.

## Goal Detector for Football Matches

### Bilkent University, Introductionn to Digital Circuit Design

We built a system that uses ultrasonic distance sensor and infrared distance sensor to detect whether a ball passes the goal line. Arduino Uno was used to obtain data from infrared distance sensor. VHDL was utilized to program Basys3 on Vivado to gather the data from ultrasonic distance sensors and to interpret the collected data.





