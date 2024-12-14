# Water Potability Prediction

This project uses machine learning to predict water potability based on various water quality features. The solution involves cleaning the data, training a Random Forest model, and generating predictions for test data.

## Project Details

### Steps Followed:

1. **Data Cleaning** 🧹
   - Extracted numeric values from text columns to ensure valid data.
   - Filled missing values with column averages.

2. **Data Preparation** 📊
   - Split the dataset into training and validation sets.

3. **Model Training** 🤖
   - Trained a Random Forest Regressor model on the training data.

4. **Model Evaluation** 📈
   - Calculated validation error (Mean Squared Error) to assess model performance.

5. **Prediction** 🔮
   - Used the trained model to predict potability for the test dataset.

6. **Submission** 📤
   - Saved the predictions in a CSV file for submission.

### Files Included:

- `train.csv`: The training dataset containing water quality features and potability labels.
- `test.csv`: The test dataset containing water quality features without labels.
- `submission.csv`: The file containing the predicted potability values for the test dataset.

## Potential Uses

- **Public Health Monitoring** 🏥: Identifying areas with unsafe drinking water to take corrective actions.
- **Water Quality Assurance** 💧: Helping water treatment facilities monitor and maintain water standards.
- **Research and Development** 🔬: Assisting in studies related to water safety and its impact on health.
- **Policy Making** 📜: Providing data-driven insights to inform water safety regulations and standards.
- **IoT Integration** 🌐: Using predictions in real-time systems to monitor water quality in smart homes or cities.
