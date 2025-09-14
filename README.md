# shell_final_project

This project is a Flood Prediction App built using Python and Streamlit. The app takes in different environmental inputs such as rainfall, temperature, soil moisture, and river level. Based on these inputs, it predicts the risk of flooding (Low, Moderate, or High).

Rainfall (mm): Measures how much rain has fallen.

Temperature (°C): Helps to understand evaporation and climate conditions.

Soil Moisture: A slider (0 to 1) showing how wet the soil is.

River Level (m): Shows how high the river water has risen.

When the user clicks the Predict button, the app applies simple decision rules to estimate flood risk:

If rainfall is very high, or if soil is too wet and river level is high → High risk of flood.

If rainfall or river level is moderately high → Moderate risk.

Otherwise → Low risk.

The app provides results in a clear and user-friendly way using colored messages:

✅ Green for Low Risk

🟠 Orange for Moderate Risk

⚠️ Red for High Risk

This project shows how data and technology can be combined to help predict natural disasters. It is simple, interactive, and easy to understand, making it a good starting point for disaster management applications.
