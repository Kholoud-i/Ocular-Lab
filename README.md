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

Eye-tracking recordings from human subjects performing visual tasks, extracted saccade events and computed latency and accuracy metrics.

Feature Engineering

Derived performance metrics from raw gaze coordinates, encoded experimental task conditions. 

## Modeling
Applied Generalized Linear Models to estimate the effect of task conditions on:
Saccade latency & Saccade accuracy

## Evaluation & Interpretation
The saccade dynamics data were rigorously evaluated using Generalized Linear Models to quantify the impact of task conditions on both latency and accuracy. 
Model diagnostics confirmed appropriate fit, with residuals showing no systematic deviations and variance inflation factors indicating minimal multicollinearity among predictors. 
Analysis revealed that task complexity significantly modulates saccade latency: higher cognitive load was associated with prolonged initiation times, consistent with the increased processing demands reported in prior oculomotor research. 
Similarly, saccade accuracy exhibited condition-dependent modulation, with more challenging visual targets eliciting larger endpoint errors, suggesting that attentional allocation and motor planning are constrained under higher task demands.

Correlational analysis between latency and accuracy demonstrated a modest speed–accuracy tradeoff, highlighting the interdependence of temporal and spatial aspects of saccadic control.
These findings underscore the sensitivity of saccade metrics as biomarkers for cognitive processing efficiency and visuomotor integration. Overall, the results provide a quantitatively 
robust characterization of how experimental manipulations influence oculomotor behavior, offering insights into underlying neural mechanisms and informing the design of tasks in both research and applied settings, such as human-computer interaction or clinical assessment of visual-motor function.

## Applications

Cognitive neuroscience research
Human-computer interaction
Clinical and behavioral performance analysis

