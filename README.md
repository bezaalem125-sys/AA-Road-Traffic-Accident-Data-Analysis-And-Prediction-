# Addis Ababa Road Traffic Accident Analysis

## Project Overview

This project explores road traffic accident data from Addis Ababa, Ethiopia, using data analysis, visualization, and machine learning. It investigates patterns in accident severity and builds Decision Tree classification models to predict accident severity from the available dataset features.

## Objectives

- Explore and understand the road traffic accident dataset.
- Clean and prepare data for analysis.
- Visualize accident patterns and relationships.
- Build a Decision Tree classification model.
- Compare standard and class-balanced model performance.
- Examine the challenges of predicting less common accident severity classes.

## Tools and Technologies

- Python
- Jupyter Notebook
- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn

## Methodology

1. Data loading and exploration
2. Data cleaning and preprocessing
3. Exploratory data analysis and visualization
4. Label encoding of categorical variables
5. Training and evaluating a Decision Tree classifier
6. Comparing standard and class-balanced models
7. Interpreting results and limitations

## Key Findings

The standard Decision Tree model achieved approximately 81.67% accuracy, while the class-balanced model achieved approximately 71.18% accuracy.

However, the dataset contains imbalanced severity classes. The standard model performed much better on the majority class than on fatal and serious injury cases. Class balancing improved recall for the less common classes, but overall accuracy decreased.

These findings show why accuracy alone is not enough to evaluate a model when classes are imbalanced.

## Limitations

- Model performance depends on the available dataset and selected features.
- The severity classes are imbalanced.
- Performance on less common severity classes remains limited.
- The model is an educational analysis and should not be treated as a validated real-world road-safety prediction system.

## Project Structure

- `AA_Road_Traffic_Accident.ipynb` — notebook containing the analysis, visualizations, and machine learning workflow.
- `data/` — datasets, only if redistribution is permitted.

## Author

Created as a data analysis and machine learning project focused on road traffic accident severity in Addis Ababa, Ethiopia.