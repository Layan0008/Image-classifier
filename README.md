# Image-classifier
# 🧠 Image Classification (Teachable Machine + TensorFlow)

This project uses a model trained with [Teachable Machine] to classify images as either **cat** or **dog** using TensorFlow in Python.

---

##  Files

- `keras_model.h5`: Trained model (Keras format)
- `labels.txt`: Class labels
- `predict.py`: Python script to load model and predict image class
- `dog5.jpeg`: Test image
- `result`: Screenshot of result

---

##  How It Works

1. Model trained on Teachable Machine with 2 classes: `dog` and `cat`
2. Exported in **Keras format**
3. `predict.py`:
   - Loads model and image
   - Preprocesses input (resize to 224x224, normalize)
   - Predicts class using TensorFlow

---

##  Example Output

```bash
Predicted class: Cat
