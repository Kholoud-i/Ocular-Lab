# Ocular-Lab
## Project Overview
This project analyzes human eye-movement behavior to understand how different task conditions influence reaction time and accuracy.
Using eye-tracking data, I modeled saccade dynamics (rapid eye movements between points of focus) with statistical techniques (Generalized Linear Models) to quantify performance under varying experimental conditions.

The goal was to identify how task design impacts how quickly and how precisely the visual system responds.

## Key Concepts

Saccades: Rapid eye movements that shift focus between visual targets
Latency: Time delay between stimulus presentation and eye movement initiation
Accuracy: Precision of eye landing position relative to the intended target
Generalized Linear Models (GLMs): Statistical models used to estimate how task variables affect latency and accuracy

## Methods

Data Collection

Eye-tracking recordings from human subjects performing visual tasks
Extracted saccade events and computed latency and accuracy metrics

Feature Engineering
Derived performance metrics from raw gaze coordinates
Encoded experimental task conditions 

Modeling
Applied Generalized Linear Models to estimate the effect of task conditions on:
Saccade latency
Saccade accuracy

Evaluation & Interpretation
