## Multi-Layer Perceptron

A Multi-Layer Perceptron (MLP) is a class of feedforward artificial neural network. It consists of at least three layers of nodes: an input layer, one or more hidden layers, and an output layer. MLPs are capable of learning complex nonlinear functions and are widely used in supervised learning problems.


## 🛌 Dataset: Sleep Time Prediction

The dataset `sleeptime_prediction_dataset.csv` includes various lifestyle and behavioral features that impact sleep duration. The objective is to accurately predict the number of hours a person sleeps based on these inputs.


### Features may include:
- Physical activity level
- Screen time
- Coffee/tea intake
- Stress level
- Work hours
- Age, gender, etc.


### Target:
- `Sleep Duration (in hours)`


## 🏗️ MLP Architecture

- **Input Layer**: Accepts all normalized feature values
- **Hidden Layers**: One or more fully connected layers with ReLU activation
- **Output Layer**: Single neuron for continuous sleep hour prediction


## 🧰 Tools & Libraries

- Python
- Pandas
- NumPy
- Scikit-learn
- TensorFlow / Keras
- Matplotlib / Seaborn


## 📂 Notebook Breakdown

1. **Library Import** – Necessary packages for data handling and model building
2. **Data Loading** – Read the `sleeptime_prediction_dataset.csv` file
3. **Data Preprocessing** – Clean missing values, encode categorical variables, normalize inputs
4. **Model Building** – Construct MLP model using Keras Sequential API
5. **Model Training** – Fit the model using training data
6. **Evaluation** – Use MSE, MAE, and visual plots to evaluate model performance


## 📈 Results

- R^2 Score: *0.75*
- Mean Absolute Error: *0.144*
- Mean Squared Error: *0.329*
- **Visualization**: Predicted vs Actual Sleep Duration plot
