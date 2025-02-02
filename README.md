# 🚀 DIMEE: Distributed Inference on Mobile, Edge, and Cloud – An Early Exit Approach  

This repository contains the official implementation of **DIMEE: Distributed Inference on Mobile, Edge, and Cloud** – a novel **Early Exit Approach** to optimize inference efficiency across resource-constrained environments.  

---

## 📋 Table of Contents  
- [✨ Introduction](#-introduction)  
- [🛠 Requirements](#-requirements)  
- [📖 Training](#-training)  
- [⚡ Inference](#-inference)  
- [📊 Datasets](#-datasets)  
- [🙏 Acknowledgements](#-acknowledgements)  

---

## ✨ Introduction  
Deep Neural Networks (DNNs) demand high computational power, making deployment on edge and mobile devices challenging. **DIMEE** leverages **Early Exit strategies** to distribute inference dynamically across mobile, edge, and cloud environments, reducing latency and computational cost.  

---

## 🛠 Requirements  
Ensure you have the following dependencies installed before running the code:  

```bash
pip install torch==1.4.0 transformers==2.5.1
```

## 📖 Training
Fine-tune a pre-trained language model and train the internal classifiers using the command:

```bash
bash finetune_(al)bert.sh
```

## ⚡ Inference
Run inference using the following command:

```bash
bash patience_infer_(al)bert.sh
```

## 📊 Datasets
We use benchmark GLUE datasets, available at [GLUE Datasets](https://gluebenchmark.com/).


## 🙏 Acknowledgements
We extend our gratitude to the authors of [PABEE](https://github.com/JetRunner/PABEE/tree/master) for making their work publicly available.
