## Chest X-ray Classification

This machine learning module is a pretrained image classification model built using **Teachable Machine by Google** to analyze chest X-ray images and predict one of three diagnostic outcomes:

- **Normal**
- **COVID-19**
- **Viral Pneumonia**

The model was trained on a labeled dataset of chest radiographs and exported as a Keras-compatible `.h5` file. It can be loaded directly using **TensorFlow 2.12.1** and integrated into research or diagnostic support systems.

> ⚠️ **Disclaimer:** This tool is intended for **research and educational purposes only**. It is not certified for clinical use.

---

### Model Overview

- Built using [Teachable Machine](https://teachablemachine.withgoogle.com/)
- Exported as a Keras `.h5` model
- Compatible with TensorFlow 2.x
- Uses image-based classification for chest X-rays

---

### Run on Google Colab

You can easily run this model on **Google Colab**:

1. Open this notebook: [Colab Notebook Link](https://colab.research.google.com/drive/15RpVL-fGPUYsidfT-orvKtGbgTNaxYWf?usp=sharing)
2. Download Keras Module and label file from this repository to colab files, and paste their path inside code
3. Upload your X-ray image that you want to test, and paste its path inside code
4. Run the notebook cells to:
   - Load the model
   - Preprocess the image
   - Get prediction: `Normal`, `COVID-19`, or `Viral Pneumonia`

---

### References
This Dataset was used to develop this module [Covid-19 Image Dataset by Pranav Raikote](https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset) in Kaggle
