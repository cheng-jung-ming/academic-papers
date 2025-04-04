# academic-papers
2025 Master's Thesis
In a dynamic and highly competitive market environment, accurately forecasting client demand is crucial for optimizing resources and controlling costs. This study explores the use of machine learning techniques to enhance the accuracy of demand forecasting, employing empirical analysis based on production and material consumption data from K Company's Xinfeng plant for the period of January to June 2024. The study utilizes Random Forest Regression (RF) as the core model and enhances its performance through data engineering and feature augmentation techniques. Furthermore, to improve the interpretability of the model, this research introduces Shapley Additive Explanations (SHAP) to analyze the impact of different features on the forecast results. The study further investigates cases with significant forecast errors, examining how data drives prediction outcomes from both macro and micro perspectives. Through SHAP analysis, we identify the most influential features—product, product-material interaction, and product-client interaction—and select the items with the highest and lowest SHAP values. Based on the SHAP influence of these items, specific optimization recommendations are provided to the company, including production plan optimization, identification of supply chain bottlenecks, and adjustments to supply strategies. These recommendations aim to assist the company in making more precise improvements in resource allocation and decision-making processes.
According to the study by Seyedan & Mafakheri (2020), neural networks (NN) are the most commonly applied machine learning technique in supply chain demand forecasting. Therefore, this study selects NN as a baseline comparison model and further evaluates the differences in predictive performance among Gradient Boosting Machine (GBM), XGBoost (XGB), and Long Short-Term Memory (LSTM) networks. The results show that, without hyperparameter tuning, both GBM and XGB failed to surpass the tuned RF model, and their hyperparameter optimization cost was relatively high, leading RF to achieve the best balance between accuracy, computational efficiency, and practical applicability. Furthermore, the LSTM model exhibited a low R² of 0.65, indicating poor performance, which may be due to the weak time-series characteristics in the data, preventing LSTM from effectively learning stable trend patterns. SHAP analysis also confirmed that time-related features had limited impact on the forecasting outcomes.
The experimental results demonstrate that the RF model exhibits outstanding predictive performance on the test dataset, with Mean Squared Error (MSE), Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE) all maintaining relatively low levels. Additionally, five-fold cross-validation confirms the model's stability and reliability. This study confirms the practicality of RF in client demand forecasting, positioning it as an effective tool for supply chain management and decision support in enterprises. Furthermore, the methodology was also tested on a Kaggle public dataset, yielding an R² of 0.98, further validating the applicability of the proposed approach and demonstrating its scalability to other similar datasets.
