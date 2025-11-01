# Project Title

Smart Incident Detection from IT Logs

## Project Participants

- First Name: Aymane 
- Last Name: Bouzaidi Tiali
- cnet ID: abouzaiditiali
- Project Role: Lead Developer / ML Engineer

## Project Description

- Problem: IT operations teams rely on massive logs from servers, switches, and 
applications to detect incidents. Manual log inspection is error-prone and 
slow, leading to downtime.
- Why important: Automating anomaly detection in IT logs can reduce 
mean-time-to-detection (MTTD) and prevent service outages.
- Course theme: This project lies at the intersection of networking and 
ML—network infrastructure produces continuous telemetry data, which ML can 
process to identify incidents faster and more accurately.
- Related work: Studies such as DeepLog (Du et al., 2017) and LogAnomaly use 
LSTMs and sequence models for anomaly detection in logs.
- Goal: Research and prototype-level implementation of an ML-based incident 
detection pipeline capable of learning normal patterns from IT log sequences.

## Data

- Dataset: I will use the BGL Log Dataset from the Loghub collection 
(logs from a BlueGene/L supercomputer, around 4.6 million messages, 
both normal and anomalous).
- Access & licensing: Available via GitHub under research license 
via Loghub. 
- https://github.com/logpai/loghub
- Relevance: The dataset provides real-world IT/log-infrastructure events 
and labeled anomalies, making it suitable for training and evaluating incident 
detection models.

## Deliverables

1. Clean Jupyter Notebook implementing log parsing, feature extraction, 
model training, and evaluation.
2. Sphinx report with results and discussion.
3. Visualization of detected anomalies and correlation with known incidents.
