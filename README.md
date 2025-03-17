# MNIST KNN Classification

## Description
This project applies **K-Nearest Neighbors (KNN)** to classify handwritten digits from the **MNIST dataset**. The dataset consists of grayscale images (28x28 pixels) of digits (0-9), which are flattened into 1D vectors and normalized before classification. 

The project includes:
- **Data Preprocessing**: Flattening and normalizing images.
- **KNN Classification**: Testing different K values (2 to 100).
- **Model Evaluation**: Comparing accuracy scores for different values of K.
- **Visualization**: Accuracy vs. K-Value plot.

## Installation
Make sure you have Python and the required libraries installed:

```bash
pip install numpy matplotlib tensorflow scikit-learn
```

## Running the Project
Run the main script to train and test the KNN classifier:

```bash
python mnist_knn_classification.py
```

Then, generate the visualization:

```bash
python accuracy_vs_k_plot.py
```

## Outputs
- **knn_accuracies.npy**: Saved accuracy values for KNN models.
- **accuracy_vs_k_plot.png**: Visualization of accuracy vs. K-value.

## Example Output
```
K=2, Accuracy=0.95
K=3, Accuracy=0.96
K=4, Accuracy=0.96
...
Best K=5, Accuracy=0.97
```

## Repository Structure
```
mnist-knn-classification/
│── mnist_knn_classification.ipynb  # Main script
│── accuracy_vs_k_plot.png       # Accuracy plot
│── README.md                    # Project documentation
```

## License
This project is open-source under the MIT License.

---
🚀 **Happy Coding!**
