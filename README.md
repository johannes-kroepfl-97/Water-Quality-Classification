# Water Quality Classification

This project revolves around the classification of water potability based on various parameters.

In the data preprocessing stage, missing values were handled by substituting them with the mean, a suitable approach considering the normal distribution of the attributes. Data was standardized to make it suitable for machine learning algorithms.

Initial exploratory data analysis involved generating heatmaps and pairplots to understand the attribute correlations. To select the optimal model, we employed a grid search strategy, providing systematic model selection and hyperparameter tuning.

Moreover, we used PolynomialFeatures for feature engineering, creating interaction terms and squared versions of the original features, aiming to enhance model performance.

This project showcases the application of different machine learning techniques in the context of water quality classification. The objective extends beyond developing a reliable model, to understanding the significance of different features in determining water potability.
