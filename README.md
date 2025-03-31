#Energy Efficiency Prediction with MLP

This project uses a **Multilayer Perceptron (MLP)** to predict the **Heating Load** of buildings based on their physical and thermal characteristics. The dataset comes from the **UCI Machine Learning Repository** and contains 768 samples with 8 input features.

## Dataset
The dataset includes the following input features:
- **X1**: Relative building compactness
- **X2**: Total surface area (m²)
- **X3**: Total wall area (m²)
- **X4**: Roof area (m²)
- **X5**: Total building height (m)
- **X6**: Orientation (category 2 to 5)
- **X7**: Total glazing area (m²)
- **X8**: Glazing distribution (category 0 to 5)

The target variable is **Y1**: Heating Load, which is what we are trying to predict.

## Model
The MLP model is trained using the above features to predict the heating load. Training is done using **scikit-learn** and **TensorFlow**.

## Results
Model performance is evaluated using metrics such as heating load prediction accuracy.
