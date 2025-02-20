
# Detection of AI-Generated Sneakers Using PyTorch and GANs

This project focuses on detecting AI-generated images of sneakers, particularly those from popular brands like Nike, Adidas, and Converse. The dataset used includes a mix of real images sourced from Google Images and AI-generated images produced by MidJourney. The goal is to accurately distinguish between real and AI-generated images using Convolutional Neural Networks (CNNs) and Generative Adversarial Networks (GANs).

---

## Results

The results of this project, including generated images, evaluation metrics, and performance tables, are stored in the `results/` folder. Below is an overview of the results:

### 1. **Generated Images**
The GAN-generated sneaker images are stored in the `results/generated_images/` folder. These images showcase the synthetic sneakers created by the generator during the training process.

- Example of generated images:
  ![image](https://github.com/user-attachments/assets/97513e32-52e9-4511-8140-efbeb0aacc98)

Here’s how you can update the **Results** section of your README with your actual performance metrics:

---

## Results

The results of this project demonstrate the model's ability to distinguish between real and AI-generated sneaker images. Below are the detailed performance metrics and evaluation results:

### Performance Metrics

The model achieved the following performance on the test dataset:

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 0.97      | 0.97   | 0.97     | 266     |
| 1     | 0.95      | 0.95   | 0.95     | 171     |

- **Accuracy**: 96.34%
- **Test Loss**: 0.0926
- **Macro Avg**: 0.96 (Precision), 0.96 (Recall), 0.96 (F1-Score)
- **Weighted Avg**: 0.96 (Precision), 0.96 (Recall), 0.96 (F1-Score)

### Confusion Matrix
The confusion matrix provides a detailed breakdown of the model's predictions. It is saved in `results/confusion_matrix.png`.

- **Class 0**: Represents real images.
- **Class 1**: Represents AI-generated images.

### Interpretation of Results
- The model performs exceptionally well, with high precision, recall, and F1-scores for both classes.
- The accuracy of **96.34%** indicates that the model is highly effective at distinguishing between real and AI-generated sneaker images.
- The low test loss (**0.0926**) further confirms the model's robustness.

---
## How to Reproduce Results

To reproduce the results:

1. **Train the Model**:
   - Run the `notebooks/detection_sneakers_ai.ipynb` notebook to train the CNN and GAN models.

2. **Evaluate the Model**:
   - Evaluate the model on the test dataset and save the performance metrics in `results/performance_metrics.txt`.

3. **Generate Confusion Matrix**:
   - Generate the confusion matrix and save it in `results/confusion_matrix.png`.

4. **Plot Results**:
   - Generate training/validation curves and save them in the `results/curves/` folder.

---

By including your actual results in this structured format, you provide a clear and professional overview of your project's performance. This makes it easier for others to understand and replicate your work.
### 2. **Performance Metrics**
The model achieved the following performance on the test dataset:

Class	Precision	Recall	F1-Score	Support
0	0.97	0.97	0.97	266
1	0.95	0.95	0.95	171
Accuracy: 96.34%

Test Loss: 0.0926

Macro Avg: 0.96 (Precision), 0.96 (Recall), 0.96 (F1-Score)

Weighted Avg: 0.96 (Precision), 0.96 (Recall), 0.96 (F1-Score)

### 3. **Training and Validation Curves**
The training and validation loss/accuracy curves are saved in the `results/curves/` folder. These plots help visualize the model's learning progress.

- Example of training curves:
 ![image](https://github.com/user-attachments/assets/be3a172a-9ef7-4aaa-b2a3-388b819e45e0)


### 4. **Confusion Matrix**
The confusion matrix for the classification task is saved in `results/confusion_matrix.png`. It provides a detailed breakdown of the model's predictions.

- Confusion Matrix:
  ![image](https://github.com/user-attachments/assets/47e545d8-f06c-4810-bdde-5d5d3ca3cb28)

---

## How to View Results

1. **Generated Images**:
   - Navigate to the `results/generated_images/` folder to view the synthetic sneaker images created by the GAN.

2. **Performance Metrics**:
   - Open the `results/performance_metrics.csv` file to see the detailed evaluation metrics.

3. **Training Curves**:
   - Check the `results/curves/` folder for plots of training and validation loss/accuracy.

4. **Confusion Matrix**:
   - View the confusion matrix in `results/confusion_matrix.png`.

---

## Repository Structure

Here’s the structure of the repository for easy navigation:

```
project/
├── data/                   # Dataset (real and AI-generated images)
├── models/                 # Saved models (generator, discriminator, CNN)
├── results/                # Results (images, tables, and plots)
│   ├── generated_images/   # GAN-generated sneaker images
│   ├── curves/             # Training and validation curves
│   ├── performance_metrics.csv  # Evaluation metrics
│   └── confusion_matrix.png     # Confusion matrix
├── notebooks/              # Jupyter notebooks for training and evaluation
├── scripts/                # Utility scripts (e.g., preprocessing)
├── README.md               # Project overview
└── requirements.txt        # Dependencies
```

---

## How to Reproduce Results

To reproduce the results:

1. **Train the Model**:
   - Run the `notebooks/detection_sneakers_ai.ipynb` notebook to train the CNN and GAN models.

2. **Generate Images**:
   - Use the trained generator to create synthetic images and save them in `results/generated_images/`.

3. **Evaluate the Model**:
   - Evaluate the model on the test dataset and save the performance metrics in `results/performance_metrics.csv`.

4. **Plot Results**:
   - Generate training/validation curves and confusion matrix, and save them in the `results/` folder.

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

---.
## Author

## Alidor Mbaya : mbayandjambealidor@gmail.com
