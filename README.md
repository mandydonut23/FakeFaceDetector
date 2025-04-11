# FakeFaceDetector

This repository contains scripts to build a detector of AI-generated faces. It contains scripts for training MobileNetV2, ViT-B/16, a logistic regression meta-classifier, and Ollama Vision 3.2 11B.

---

### Folder Structure:

1. **1_mobilenetv2**: contains the .ipynb files for training the initial and finetuned MobileNetV2.

2. **2_vitb16_training**: contains the .ipynb files for training the initial and finetuned ViT-B/16.

3. **3_metaclassifier_training**: contains the .ipynb files to get the output class probabilities of the finetuned MobileNetV2 and ViT-B/16, and then train the metaclassifier.

4. **4_ollama_training**: contains the Colab notebook to train Ollama. It is hard to read, so here's the Colab link:  
   [Ollama Colab Link](https://colab.research.google.com/drive/1tbjbCWS1HfsIwGTot9oaD4LVRn6ipGPU?usp=sharing)

5. **5_explainability_function**: contains the .ipynb to run the SHAP function for MobileNetV2.

---

### FakeFace_detector.ipynb:

This is the actual script for the AI-generated face detection tool.
