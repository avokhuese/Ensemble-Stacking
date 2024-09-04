# Ensemble Stacking (Simple and Weighted Average Ensemble) for Time Series Prediction

#Introduction and Description
In this paper, we present Hybrid Ensemble Stacking of Long Short-Term Memory (LSTM) networks and Autoregressive Integrated Moving Average (ARIMA) models to enhance time series data forecasting. Our approach is applicable across diverse datasets such as Jena Climate Data, US Dollar Tether (USDT) cryptocurrency data, and agricultural humidity sensor data. Traditionally, ARIMA is criticized for its inability to capture complex nonlinear patterns, reliance on complete data, privacy concerns, and limited accuracy with volatile time series, while LSTM faces computational inefficiency, labeled anomaly data, and a lack of generalization. To address these issues, the study proposes an ensemble stacking approach that leverages the strengths of both models. 
Data augmentation techniques such as Jittering, Rotation, Scaling, Magnitude Warping, Window Warping, and Permutations are applied to enhance predictive performance. Results demonstrate that the ensemble stacked meta learner model consistently outperforms individual base models (ARIMA and LSTM) across all datasets. Comparative analyses with and without data augmentations further highlight the improved predictive capabilities of the stacked ensemble. The paper identifies challenges associated with each model and augmentation technique, providing insights into the complexities of time series forecasting.  The ensemble stacking approach emerges as a strategic solution to overcome the limitations of individual models, offering enhanced forecasting accuracy across diverse datasets.
