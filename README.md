# Anomaly-Detection_project
Using Neural Network to analyze and detect the faults in power system data and increase interpretability using Explainable AI

Normally, a power system operates under balanced conditions. When the system becomes unbalanced due to the failures of insulation at any point or due to the contact of live wires, a short–circuit or fault, is said to occur in the line. 
Faults may occur in the power system due to the number of reasons like natural disturbances (lightning, high-speed winds, earthquakes), insulation breakdown, falling of a tree, bird shorting, etc.

# DATASET 
https://www.kaggle.com/datasets/esathyaprakash/electrical-fault-detection-and-classification

WE SIMULATE THE CIRCUIT UNDER NORMAL CONDITIONS AS WELL AS UNDER VARIOUS FAULT CONDITIONS. WE THEN COLLECT AND SAVE THE MEASURED LINE VOLTAGES AND LINE CURRENTS AT THE OUTPUT SIDE OF THE POWER SYSTEM. WE COLLECTED NEARLY 12000 DATA POINTS, AND THEN THE DATA IS LABELED.
[0 0 0 0] - No Fault
[1 0 0 1] - LG fault (Between Phase A and
Gnd)
[0 0 1 1] - LL fault (Between Phase A and
Phase B)
[1 0 1 1] - LLG Fault (Between Phases A,B and
ground)
[0 1 1 1] - LLL Fault(Between all three phases)
[1 1 1 1] - LLLG fault( Three phase
symmetrical fault

# Overview of the project

Model:
•Deep learning model (neural network) used to detect faults in the transmission system.
•The model was trained using the normalized features and fault types as the target.
•classification model plays a crucial role in identifying different fault types in the electrical transmission system by learning from features like current and voltage values.
•Explainability:
•SHAP (SHapley Additive explanations) was applied to provide explanations
• for the model's predictions, helping us understand feature importance.
•Explainability method provides transparency into how each feature impacts the model's decisions, improving trust and model interpretability
