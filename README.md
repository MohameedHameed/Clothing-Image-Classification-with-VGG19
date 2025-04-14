# 👕 Clothing Image Classification with VGG19

A deep learning project using **VGG19** to classify clothing images into categories like shirts, pants, and dresses. Includes data preprocessing, model training, and evaluation. Built with **Python** and **TensorFlow/Keras**.

## 📁 Project Structure

- `training.ipynb` – Notebook for training the VGG19 model on a custom dataset.
- Second_our test VGG19.ipynb` – Notebook for testing the trained model on new images.

---
## 🛠️ Requirements

Install the required packages:

```bash
pip install tensorflow numpy matplotlib opencv-python
```

---
## 📊 Dataset Format

The dataset should be organized in folders, each representing a class:

```
/clothing-dataset/train, test, and validation
  ├── dress/
  ├── hat/
  ├── pants/
  └── ...
```

---

## 🚀 How to Use

1. **Train the model**  
   Open `training.ipynb`, configure your dataset path, and run the training cells.

2. **Test the model**  
   Open second_our test VGG19.ipynb`, load your saved model, and run predictions on new images.

---
## 📸 Example Predictions

You can visualize prediction results inside the testing notebook. Images are labeled with predicted classes using OpenCV and matplotlib.

---

## 📚 Related Research Paper

This project is based on or related to a scientific publication:

🔗 [IEEE Paper: Clothing Image Classification Using VGG19](https://ieeexplore.ieee.org/abstract/document/10639001)

---
## 🙌 Author

Created by **Mohammed Hameed**.  
Feel free to open issues or contribute!
