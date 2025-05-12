# Computer Vision Assignment

This repository contains a series of Jupyter/Colab notebooks demonstrating key deep learning techniques across multiple modalities (image, video, audio, text), focusing on:

- Supervised Contrastive Learning
- Transfer Learning (Feature Extraction and Fine-Tuning)
- Zero-Shot Learning
- 3D Imaging and Medical Imaging (CT scans, X-rays)
- Use of state-of-the-art models (EfficientNet, BiT, MLP-Mixer, ConvNeXt)

---

[Video Demo](https://youtu.be/JDbQJxnPFI0)

---

## Part 1: Supervised Contrastive Learning

**Objective**: Compare classification using:
- Traditional softmax loss (cross-entropy)
- Supervised contrastive loss (SupCon)

**Highlights**:
- Dataset: CIFAR-10 or FashionMNIST
- Visualize embeddings using t-SNE
- Evaluate accuracy, loss, confusion matrix

---

## Part 2: Transfer Learning on Multiple Modalities

### Images
`TL_Images_FeatureExtractor_FineTune.ipynb`

- Dataset: Dogs vs Cats or Flowers
- Two approaches:
  - Feature Extraction using EfficientNet
  - Fine-Tuning with additional top layers

### Videos
 `TL_Video_ActionRecognition.ipynb`

- Uses TensorFlow Hub action recognition model (e.g., MoViNet)
- Dataset: UCF101 or mini dataset

### Audio
`TL_Audio_YamNet.ipynb`

- Transfer learning using YAMNet
- Dataset: ESC-50 or UrbanSound8K

### NLP
 `TL_Text_NLP_Classification.ipynb`

- BERT-based transfer learning
- Dataset: IMDb or AG News
- TF Hub: `bert_en_uncased_L-12_H-768_A-12`

[Colab Link](https://colab.research.google.com/drive/1ENr8mVmySiK7tLFewEFJR-tc4fghXyei?usp=sharing)

---

## Part 3: Zero-Shot Transfer Learning

### CLIP Zero-Shot
 `CLIP_ZeroShot_Classification.ipynb`

- Zero-shot classification with OpenAI CLIP
- Visualizes cosine similarity of image-text pairs

[Colab Link](https://colab.research.google.com/drive/17lSavgvv7fRIf94lfTB5fRh5YvLvIRcP?usp=sharing)

###  BigTransfer (BiT) with TFHub
 `BigTransfer_TFHub_TransferLearning.ipynb`

- Uses TFHub BiT model
- Dataset: Flowers or CIFAR-10

---

## Part 4: Image Classification Benchmarks

### Datasets:
- MNIST
- FashionMNIST
- CIFAR-10

Each notebook includes:
- Baseline CNN
- Transfer Learning: EfficientNet, BiT
- State-of-the-art models: MLP-Mixer, ConvNeXt V2

###  Pneumonia Detection from Chest X-Rays
 `Pneumonia_XRay_ConvNet.ipynb`

- Dataset: Chest X-Ray dataset from Kaggle/Keras
- CNN and EfficientNet models

### CT Scan 3D Image Classification
`CTScan_3D_ImageClassification.ipynb`

- Dataset: 3D CT Scan Volumes
- Model: 3D CNN with volume rendering and classification

---

## Visualizations Included

- Training accuracy/loss plots
- Confusion matrix heatmaps
- t-SNE embeddings of feature space
- Cosine similarity scores for zero-shot
- Class Activation Maps (CAMs for X-rays)

---