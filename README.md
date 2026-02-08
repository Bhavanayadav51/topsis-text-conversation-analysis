# TOPSIS Analysis for Text Conversational Models

## Objective
To identify the best pre-trained conversational model for medical text
conversations using the TOPSIS multi-criteria decision-making method.

## Domain
Medicine

## Text Scenarios
T1 – Doctor–patient diagnosis conversation  
T2 – Medicine dosage clarification  
T3 – Symptom explanation  
T4 – Side-effects discussion  
T5 – Mental health counselling conversation  

## Models Used
M1 – DialoGPT-medium  
M2 – BlenderBot  
M3 – GPT-2  
M4 – T5-base  

## Parameters
P1 – Response relevance (Benefit)  
P2 – Fluency (Benefit)  
P3 – Context understanding (Benefit)  
P4 – Medical correctness (Benefit)  
P5 – Computational cost (Cost)  
P6 – Model size (Cost)  

## Methodology
For each medical text (T1–T5), the four conversational models were evaluated
using six parameters. The TOPSIS method was applied separately for each text
to compute the Topsis Score and Rank for every model.

## Results
The results show that the best conversational model varies depending on the
medical text context. BlenderBot generally achieved higher ranks, indicating
strong performance in medical conversational scenarios.
