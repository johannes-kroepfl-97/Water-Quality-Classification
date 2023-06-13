# Water Quality Classification

This project involves water potability classification by both looking at traditional machine learning methods using the libraries Scikit-learn, Keras, XGBoost and LightGBM, and a Feedforward Neural Network (FNN) implemented with PyTorch. Points 1-4 are visible in the `water_quality.ipynb` file and point 5 is visible in the `fnn_pytorch.ipynb` file.

## Outline:
1. **Data Preprocessing**: The data contained some missing values that were replaced by the mean, an appropriate approach given the normal distribution of the attributes. The data were standardized to make them suitable for machine learning algorithms.
2. **Exploratory Data Analysis (EDA)**: To understand the attribute correlations, we visualized the dataset by creating heatmaps and pairplots.
3. **Traditional Machine Learning Approach**: For classical algorithms we utilized a grid search methodology for hyperparameter tuning and model selection.
4. **Feature Engineering:** We used PolynomialFeatures to create interaction terms and squared versions of the original features aiming to enhance the performance of our models. This was sucessful for some models and unsucessfull for others, which is obervable by looking at `accuracy_plot.jpg` in the `results` folder. 
5. **FNN in PyTorch**: For a more sophisticated approach, we implemented a Feedforward Neural Network using PyTorch. This included an extensive search for optimal hyperparameters for the neural network. The results of the hyperparameter search are visible in the `avg_val_acc_pytorch_plot.jpg` file in the `results` folder.

All outputs, visualizations, and results from the analyses are organized and stored in the `results` folder. The project was fun and I just wanted to try out some new approaches. It can be extended in various ways, so play around with the code and then get on it. Have fun!
