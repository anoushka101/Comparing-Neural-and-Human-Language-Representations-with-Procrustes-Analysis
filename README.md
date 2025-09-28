# 🧠 Rock Classification & Neural-Human Alignment  
**Advanced Machine Learning – Homework 4**

## Overview  
This project applies transfer learning and representational analysis to explore how neural networks process visual and linguistic data. It consists of two parts:

### Part 1: Rock Image Classification  
- Fine-tuned **ResNet50** to classify 30 rock types using grayscale images  
- Built input pipelines with preprocessing and data augmentation  
- Trained custom layers followed by full-network fine-tuning  
- Visualized training and validation performance  
- Used **Procrustes analysis** to compare neural activations with human similarity judgments

### Part 2: Language Representation Alignment  
- Analyzed sentence embeddings from a pretrained NLP model  
- Compared neural representations with human similarity data  
- Applied Procrustes alignment and computed correlation coefficients  
- Evaluated representational overlap between model and human judgments

## Tools & Libraries  
- Python, TensorFlow, Scikit-learn, NumPy, Matplotlib  
- ResNet50 (CV) and pretrained NLP embeddings  
- Procrustes analysis for representational comparison

## Results  
- Achieved meaningful classification accuracy across rock categories  
- Found moderate-to-strong correlations between neural and human representations  
- Demonstrated how pretrained models can align with human perception in both vision and language

## Notes  
- All code is provided in Jupyter notebooks (.ipynb) with corresponding PDFs  
- GPU acceleration recommended (e.g., Colab or Kaggle)  
- Resources used are cited within each notebook

---

Would you like a shorter version for your GitHub description or portfolio snippet?
