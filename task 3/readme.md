# Task 03 — Image Classification (Dogs vs Cats)

## Objective
Classify images of cats and dogs using a
Support Vector Machine (SVM) with PCA preprocessing.

## Dataset
Dogs vs Cats Dataset from Kaggle

## Libraries Used
- NumPy, Pandas
- OpenCV (cv2)
- Scikit-learn
- Matplotlib, Seaborn

## Model Results
| Metric    | Cat  | Dog  |
|-----------|------|------|
| Precision | 0.58 | 0.57 |
| Recall    | 0.56 | 0.59 |
| F1-Score  | 0.57 | 0.58 |
| Accuracy  | 57.50% | — |

## Preprocessing
- Grayscale conversion
- Image resizing to 64x64
- StandardScaler normalization
- PCA (100 components) — 83.87% variance retained

## Features Used
- Flattened grayscale pixel values (64x64 = 4096)
- Reduced to 100 principal components via PCA