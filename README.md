# Data Mining Labs

Jupyter notebooks from a Data Mining course, from exploratory analysis to deep learning. Each lab folder holds the dataset and my notebooks.

| Lab | Topic | Datasets | Methods |
|---|---|---|---|
| Lab 1 | Exploratory data analysis and preprocessing | Bank marketing, Titanic, Ho Chi Minh City real estate | pandas, histograms and distributions, scaling |
| Lab 2 | Association rule mining | Groceries, Online Retail | Apriori, FP-Growth, association rules (mlxtend) |
| Lab 3 | Classification | Red wine quality, Cleveland heart disease, toy sales | Decision Tree, Naive Bayes, Random Forest, XGBoost |
| Lab 4.1 | Neural networks in PyTorch | MNIST, CIFAR-10 | Gradient descent, MLP vs CNN, basic CNN vs VGG vs ResNet |
| Lab 4.2 | Computer vision | Pascal VOC | Object localization, Faster R-CNN, U-Net segmentation, CLIP zero-shot classification |

## Running the notebooks

```bash
pip install pandas scikit-learn mlxtend xgboost seaborn torch torchvision notebook
jupyter notebook
```
