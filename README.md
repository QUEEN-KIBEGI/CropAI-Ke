# CropAI-Ke
# 🌿 AI-Based Crop Health Detection (Kenyan Context)

This project applies **Artificial Intelligence (AI)** to assist small-scale farmers in **Kenya** by automatically identifying **healthy vs diseased crop images** using image classification techniques and pre-trained models.

---

## 📌 Objectives

- Use AI and computer vision to detect plant diseases in crops like maize, tomato, banana, etc.
- Collect and label image data from Kenyan sources.
- Train and evaluate a few-shot model using transfer learning.
- Demonstrate a lightweight model for practical use by local farmers.
- Document and discuss the effectiveness of AI in African agriculture.

---

## 🗂️ Dataset

Images were collected via **Google Image Search** using the `site:` filter to target **Kenyan websites** such as:
- [kalro.org](https://kalro.org)
- [kilimo.go.ke](https://kilimo.go.ke)
- [farmbizafrica.com](https://farmbizafrica.com)

Each image is labeled as:
- `healthy` — crops showing no signs of disease.
- `unhealthy` — crops with visible disease symptoms.

> 🔗 See `plant_disease_dataset.csv` for file paths and labels.  
> 🔗 See `image_log_with_urls.csv` for source URLs.

---

## 🧠 Model and Techniques

- **Transfer Learning** with pre-trained models:
  - `MobileNetV2`
- **Few-shot learning** approach: trained on fewer than 50 images per class.
- **Image Preprocessing & Augmentation**:
  - Resize, normalize, rotate, flip, zoom, contrast adjustment.

