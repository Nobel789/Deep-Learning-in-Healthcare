# Deep-Learning-in-Healthcare
Deep Learning models applied to clinical data.
Deep Learning for Healthcare 🏥
This repository contains a comprehensive curriculum of Deep Learning models applied to clinical data. It progresses from basic PyTorch implementations to advanced interpretable architectures like RETAIN and Graph Neural Networks.

🧠 Architectures Implemented
1. Sequence Modeling & Attention (RNN/RETAIN)
Problem: Predicting Heart Failure from sequential patient visits (ICD-9 codes).

Models:

RNN/GRU: Modeled temporal dependencies in patient history.

RETAIN (Reverse Time Attention): Implemented an interpretable attention mechanism that highlights which visits contributed most to the high-risk prediction.

2. Medical Imaging (CNN)
Problem: Pneumonia Detection from Chest X-Rays.

Model: Convolutional Neural Network (CNN) trained on grayscale X-ray images.

3. Graph Neural Networks (GNN)
Problem: Modeling complex interactions in health data.

Model: Message Passing Neural Network (MPNN) for graph-based health prediction.

🛠️ Tech Stack
Framework: PyTorch

Data Handling: Pandas, Numpy

Visualization: Matplotlib
