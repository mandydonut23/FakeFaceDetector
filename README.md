# FakeFaceDetector
This repository contains scripts to build a detector of AI-generated faces. It contains scripts for training MobileNetV2, ViT-B/16, a logistic regression meta-classifier, and Ollama Vision 3.2 11B.

Folder Structure:
1_mobilenetv2: contains the .ipynb files for training the initial and finetuned mobilenetv2.
2_vitb16_training: contains the .ipynb files for training the initial and finetuned vit-B/16.
3_metaclassifier_training: contains the .ipynb files to get the output class probabilities of the finetuned mobilenetv2 and vit-b/16, and then train the metaclassifier. 
4_ollama_training: contains the colab notebook to train ollama. It is hard to read, so here's the colab link: https://colab.research.google.com/drive/1tbjbCWS1HfsIwGTot9oaD4LVRn6ipGPU?usp=sharing 
5_explainability_function: contains the .ipynb to run the SHAP function for mobilenetv2. 
FakeFace_detector.ipynb: is the actual script for the AI-generated tool. 
