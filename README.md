# Air-Temperature-Forecasting-with-LSTM
This project uses a Long Short-Term Memory (LSTM) neural network to forecast air temperature (AT) in degress from historical weather and air quality data from 2017 to 2023. The goal is to compare a baseline LSTM with an improved LSTM design and evaluate which model performs better.

## Approach
- Baseline Model: single-layer LSTM with Dense output.
- Improved Model: stacked LSTM with dropout and dense layers.
- Training Objective: minimize Mean Squared Error (MSE) using Adam optimizer.
- Evaluation Metrics: MSE, MAE, R².

## Results
<img width="691" height="470" alt="image" src="https://github.com/user-attachments/assets/9a707974-2528-4465-b4fd-881ed7a3db40" />
<img width="702" height="470" alt="image" src="https://github.com/user-attachments/assets/56430f0d-2a18-4cb0-82da-ff88f3be0bc8" />
<img width="1262" height="276" alt="image" src="https://github.com/user-attachments/assets/e347b710-220f-41a2-91b0-77782d8e872d" />
The improved model predicted closer to actual values and reduced errors compared to the baseline.

## Conclusion
The improved LSTM outperformed the baseline, with lower error and higher accuracy. This confirms that model design improvements directly increase forecasting performance. LSTM networks can be effectively applied to environmental forecasting and climate studies.

## Tools & Frameworks
- Programming & Data Handling: Python · Pandas · NumPy
- Visualization: Matplotlib · Seaborn
- Preprocessing & Evaluation: Scikit-learn (RobustScaler, MSE, MAE, R²)
- Deep Learning: TensorFlow/Keras (LSTM, Dense, Dropout, Adam)
