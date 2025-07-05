#TASK - 2 -DEEP LEARNING MODEL FOR IMAGE CLASSIFICATION

This project implements a deep learning model using TensorFlow to classify handwritten digits from the MNIST dataset.

---

## Steps Followed

**Step 1 – Import Libraries**
- Imported TensorFlow, NumPy, and Matplotlib.

**Step 2 – Load Dataset**
- Loaded MNIST dataset with 60,000 training images and 10,000 test images.

**Step 3 – Data Preprocessing**
- Normalized pixel values to range [0,1].
- Reshaped data to add the channel dimension.

**Step 4 – Build CNN Model**
- Used Sequential API with:
  - 2 Convolutional layers with ReLU activation.
  - MaxPooling layers.
  - Dense layers.
  - Softmax output layer for 10 classes.

**Step 5 – Compile and Train Model**
- Compiled with Adam optimizer and sparse categorical crossentropy loss.
- Trained for 5 epochs.

**Step 6 – Evaluate Model**
- Evaluated model accuracy and loss on the test dataset.

**Step 7 – Visualize Results**
- Plotted training and validation accuracy and loss per epoch.

**Step 8 – Save Model**
- Saved trained model as `mnist_cnn_model.h5`.

---

## Output

- **Test Accuracy:** ~98.9%
- **Test Loss:** ~0.0378
- Plots of training/validation accuracy and loss are included in the notebook.
<img width="600" height="400" alt="Image" src="https://github.com/user-attachments/assets/9b1d0320-5105-49f9-a456-7fa27db9e52d" />

<img width="600" height="400" alt="Image" src="https://github.com/user-attachments/assets/2d175e09-df69-4c1f-b202-b082b16452b6" />

## Tools Used

- Python
- TensorFlow
- Matplotlib

---

## Files Included

- `Task2_Image_Classification.ipynb`: Complete notebook code.
- `mnist_cnn_model.h5`: Saved trained model.
- `README.md`: This file.

---

## How to Run

1. Clone the repository.
2. Install required libraries:
