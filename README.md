from sklearn.metrics import mean_squared_error, mean_absolute_error

rmse = np.sqrt(mean_squared_error(y_test_rescaled, predictions))
mae = mean_absolute_error(y_test_rescaled, predictions)
print(f"RMSE: {rmse:.2f}")
print(f"MAE: {mae:.2f}")
