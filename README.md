# Vision2Text – Deep Image Captioning

## 📌 Overview
Vision2Text is a deep learning system that automatically generates meaningful captions for images using a **CNN-LSTM architecture**.

## 💡 Why This Project?
It bridges **Computer Vision and NLP** by converting visual information into human-readable descriptions, with applications in accessibility, image search, and AI assistants.

## 🎯 Objectives
- Extract image features using InceptionV3
- Generate captions using LSTM
- Apply NLP preprocessing
- Evaluate captions using BLEU scores

## 📊 Dataset
**Flickr8k Dataset** – 8,000 images with multiple human-written captions.

## 🛠️ Tech Stack
**Python | TensorFlow | Keras | InceptionV3 | CNN | LSTM | NLP | NumPy | Pandas | Matplotlib**

## 🔄 Project Flow

```text
Image → Preprocessing → InceptionV3 → Feature Extraction
      → Word Embedding → LSTM → Caption Generation → BLEU Evaluation
## ⚡ Quick Start
```
## ⚙️ Installation

```bash
pip install tensorflow keras numpy pandas matplotlib pillow
jupyter notebook Vision2Text.ipynb
```
