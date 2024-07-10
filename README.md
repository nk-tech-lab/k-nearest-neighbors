Sure! Here's an updated README with the description for `knn_no_sklearn.ipynb` added:

```markdown
# K-Nearest Neighbors (KNN) Implementation

This repository contains three Jupyter notebooks demonstrating the implementation of the K-Nearest Neighbors (KNN) algorithm on 2D and 3D artificial datasets. The notebooks follow the guide provided by DigitalOcean's community tutorial on KNN in Python.

## Notebooks

1. knn_2d.ipynb
2. knn_3d.ipynb
3. knn_no_sklearn.ipynb

## Dependencies

The notebooks require the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using pip:

```bash
pip install -r requirements.txt
```

## Description

### knn_2d.ipynb

This notebook covers:

- Data Creation: Generate a 2D dataset with 500 samples.
- Visualization: Scatter plot of the dataset.
- Data Splitting: Split into training and testing sets (80-20).
- Model Building: Instantiate KNN models with different neighbor values (1, 5, 10, 100).
- Evaluation: Train and evaluate model accuracy.

### knn_3d.ipynb

This notebook covers:

- Data Creation: Generate a 3D dataset with 500 samples.
- Visualization: 3D scatter plot of the dataset.
- Data Splitting: Split into training and testing sets (80-20).
- Model Building: Instantiate KNN models with different neighbor values (1, 5, 10, 100).
- Evaluation: Train and evaluate model accuracy.

### knn_no_sklearn.ipynb

This notebook covers:

- Data Creation: Generate a dataset with 500 samples.
- Visualization: 2D and 3D scatter plots of the dataset.
- Data Splitting: Split into training and testing sets (80-20).
- Custom KNN Implementation: Implement the KNN algorithm from scratch without using scikit-learn.
- Evaluation: Train and evaluate model accuracy using the custom KNN implementation.

## Usage

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```

2. Navigate to the directory:

   ```bash
   cd <repository-directory>
   ```

3. Open the Jupyter notebooks:

   ```bash
   jupyter notebook knn_2d.ipynb
   jupyter notebook knn_3d.ipynb
   jupyter notebook knn_no_sklearn.ipynb
   ```

4. Run the cells in each notebook to execute the KNN implementation steps.

## References

- [DigitalOcean Community Tutorial on KNN in Python](https://www.digitalocean.com/community/tutorials/k-nearest-neighbors-knn-in-python)
```

---

This README provides a concise guide to understanding and running the provided notebooks. Feel free to modify it according to your needs.
```