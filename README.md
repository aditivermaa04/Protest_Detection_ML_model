# 🧠 Protest Detection from Images

This project aims to **detect protest activity in images** using deep learning techniques. Inspired by the paper *["Protest activity detection and perceived violence estimation from social media images"](https://arxiv.org/abs/1807.11428)*, the model classifies whether an image represents a protest or not.

## 🔍 Motivation

With the rise of social media as a real-time news source, being able to detect protest-related content has applications in:

* Public safety
* Sociopolitical research
* Crisis response automation

This project explores how **EfficientNet**, advanced **data augmentation**, and **comparative model analysis** can improve image-based protest detection performance.

---

## 🚀 Features

* ✅ Binary image classification: **Protest** vs **Non-Protest**
* ✅ Backbone: **EfficientNet-B0 to B3**
* ✅ Data augmentation using `Albumentations` for robustness
* ✅ Comparative analysis with other CNNs (e.g., ResNet, VGG)
* ✅ Evaluation with accuracy, ROC-AUC, confusion matrix, etc.

---

## 📊 Dataset

This project uses the dataset provided in the original paper:

> Wang, Z., Hale, S. A., Adelani, D. I., & Hanna, A. (2018). *Protest activity detection and perceived violence estimation from social media images.*

You can download the dataset [here](https://github.com/zhouw12/Protest-Detection-Dataset) or refer to the paper for data access.

---

## 📈 Results

| Model           | Accuracy | ROC-AUC |
| --------------- | -------- | ------- |
| EfficientNet-B0 | **XX%**  | **YY**  |
| ResNet-50       | ...      | ...     |
| VGG16           | ...      | ...     |

> 📌 Visual results (confusion matrix, misclassified examples, Grad-CAM visualizations) can be found in `/results`.

---

## 📚 References

* [Protest Activity Detection Paper (Wang et al., 2018)](https://arxiv.org/abs/1807.11428)
* [EfficientNet: Rethinking Model Scaling](https://arxiv.org/abs/1905.11946)
* [Albumentations Library](https://github.com/albumentations-team/albumentations)

---

## 🤝 Contributing

PRs and feedback are welcome! If you’d like to contribute, fork this repo and submit a pull request.

---

