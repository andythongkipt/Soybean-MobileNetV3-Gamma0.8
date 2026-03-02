# Soybean Quality Classification (MobileNetV3 + Gamma Correction)

This project trains MobileNetV3Large to classify soybean seed images into 5 classes:
- Intact, Broken, Skin-damaged, Spotted, Immature

Key steps:
- Dataset download (Kaggle)
- Train/Val/Test split (80/10/10)
- Gamma correction preprocessing (e.g., γ=0.8, γ=1.3)
- Training & evaluation (accuracy, confusion matrix)
- Explainability: Grad-CAM / Grad-CAM++ / Score-CAM
