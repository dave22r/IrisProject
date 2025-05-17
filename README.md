# Iris Species Classification

## Project Overview

This project classifies iris flowers into three species (*Iris setosa*, *Iris versicolor*, *Iris virginica*) using petal and sepal measurements from the Iris dataset. A k-nearest neighbors (k-NN) model, built with R and tidymodels, achieves 97% accuracy. Petal length and width are the strongest predictors, with a petal-only model reaching 100% accuracy, compared to 79.5% for sepal-only. Visualizations show clear species separation in petal measurements. The project demonstrates machine learning, data analysis, and visualization skills, with applications in botany and agriculture.

## Dataset

The dataset, sourced from [Kaggle](https://www.kaggle.com/datasets/uciml/iris), contains 150 observations with five variables:
- **SepalLengthCm**: Sepal length (cm)
- **SepalWidthCm**: Sepal width (cm)
- **PetalLengthCm**: Petal length (cm)
- **PetalWidthCm**: Petal width (cm)
- **Species**: Iris species (*setosa*, *versicolor*, *virginica*)


## Results

- **Model Performance**:
  - Full model (all predictors): 97% accuracy
  - Petal-only model: 100% accuracy
  - Sepal-only model: 79.5% accuracy
- **Key Findings**:
  - Petal length and width are highly discriminative.
  - Sepal measurements show overlapping species clusters.
- **Visualizations**: Scatter plots compare predicted vs. actual species.

## References

- Fisher, R. A. (1936). Iris Species. [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/iris)
- tidymodels documentation: [tidymodels.org](https://www.tidymodels.org/)

