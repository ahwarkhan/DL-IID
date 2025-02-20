This repository is part of the research work presented in the paper "A Lightweight Deep Learning based Intrusion Detection Approach in IoT Utilizing Explainable Artificial Intelligence".This repository contains the implementation of DL-IID, a lightweight deep learning-based intrusion detection model designed for IoT environments. The model leverages a combination of Deep Neural Networks (DNN) and Bidirectional Long Short-Term Memory (BiLSTM) for bidirectional feature extraction, along with Genetic Algorithm (GA) for efficient feature selection. Additionally, the model incorporates Explainable AI (XAI) techniques, specifically Local Interpretable Model-Agnostic Explanations (LIME), to provide transparency in decision-making. To ensure the model is suitable for resource-constrained IoT devices, Dynamic Quantization is applied post-training to reduce the model size while maintaining high detection accuracy.

The proposed DL-IID model achieves state-of-the-art performance, with an accuracy of 99.84%, precision of 100.0%, recall of 99.69%, and an F1-score of 99.84%, while reducing the model size to 108.42 KB.

Key Features

1. Deep Learning Architecture: Combines DNN and BiLSTM for bidirectional feature extraction, enhancing the detection of complex attack patterns in IoT networks.
2. Genetic Algorithm (GA): Optimizes feature selection to reduce computational complexity while preserving detection accuracy.
3. Explainable AI (XAI): Integrates LIME to provide transparency in intrusion detection, increasing trust and interpretability of the model's predictions.
4. Dynamic Quantization: Reduces the model size to 108.42 KB, making it suitable for deployment on resource-constrained IoT devices.
5. High Performance: Outperforms traditional machine learning and advanced deep learning models on multiple benchmark datasets, including CICIDS2017, CICIoMT2024, and UNSW-NB15.

Datasets

The model is evaluated on the following datasets:

1. RF Fingerprinting Dataset: Simulates 450 IoT devices with varying RF characteristics in frequency, amplitude, and phase.
2. CICIDS2017: Contains benign and frequent attack traffic, simulating real-world network conditions.
3. CICIoMT2024: Focuses on cyber-attacks targeting medical devices connected to the Internet of Medical Things (IoMT).
4. UNSW-NB15: A comprehensive dataset for network intrusion detection, containing both normal and attack traffic.
