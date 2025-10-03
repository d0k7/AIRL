# AIRL Internship Assignment

## Q1: Vision Transformer (ViT) on CIFAR-10

This notebook implements the Vision Transformer (ViT) model from scratch using PyTorch and trains it on the CIFAR-10 dataset.

### Steps:
1. Model implementation (ViT).
2. Data augmentation with RandAugment and RandomErasing.
3. Training with AdamW and mixed precision.
4. Evaluation and saving the best model.

**Best Accuracy**: 88.95%

---

## Q2: Text-driven Image Segmentation with SAM 2

This notebook performs object detection using OWL-ViT and segmentation using SAM 2, based on a text prompt.

### Steps:
1. Detect objects in the image using OWL-ViT.
2. Segment the object with SAM 2 using the bounding box.
3. Overlay the segmentation mask on the image.

---

## How to Run

1. Open the notebook in Google Colab.
2. Upload your own images and provide a text prompt.
3. Follow the steps in the notebook to run the model.

---

## Results
Both notebooks demonstrate successful object detection and segmentation, with an example segmentation of a dog.

