<h1>🚗 Car Price Prediction</h1>

<h2>📌 Overview</h2>
<p>
    This project predicts the selling price of used cars based on various features such as manufacturing year, fuel type, transmission type, and number of owners. 
    The model is built using <strong>Random Forest Regressor</strong> and incorporates <strong>feature scaling and encoding</strong> for accurate predictions.
</p>

<h2>📂 Dataset</h2>
<p>The dataset used for training the model contains the following features:</p>
<ul>
    <li><strong>Year:</strong> Year of manufacture</li>
    <li><strong>Present_Price:</strong> Current ex-showroom price (in lakhs)</li>
    <li><strong>Driven_kms:</strong> Total distance driven (in kilometers)</li>
    <li><strong>Fuel_Type:</strong> Type of fuel (Petrol, Diesel, CNG)</li>
    <li><strong>Transmission:</strong> Manual or Automatic transmission</li>
    <li><strong>Owner:</strong> Number of previous owners</li>
    <li><strong>Selling_Price:</strong> The target variable (price at which the car was sold)</li>
</ul>

<h2>🛠️ Technologies Used</h2>
<ul>
    <li>Python</li>
    <li>Pandas, NumPy</li>
    <li>Matplotlib, Seaborn</li>
    <li>Scikit-Learn</li>
    <li>Random Forest Regressor</li>
    <li>Pipeline & ColumnTransformer</li>
</ul>

<h2>⚙️ Installation & Setup</h2>
<p>Follow these steps to set up the project:</p>
<ol>
    <li>Clone the repository:</li>
    <pre><code>git clone https://github.com/your-username/Car-Price-Prediction.git
cd Car-Price-Prediction</code></pre>

    <li>Install dependencies:</li>
    <pre><code>pip install -r requirements.txt</code></pre>

    <li>Run the script:</li>
    <pre><code>python car_price_prediction.py</code></pre>
</ol>

<h2>📊 Model Evaluation</h2>
<p>The model's performance is evaluated using the following metrics:</p>
<ul>
    <li><strong>Mean Absolute Error (MAE):</strong> Measures average absolute errors.</li>
    <li><strong>Mean Squared Error (MSE):</strong> Measures average squared errors.</li>
    <li><strong>Root Mean Squared Error (RMSE):</strong> The square root of MSE.</li>
    <li><strong>R² Score:</strong> Indicates how well the model explains variance in data.</li>
</ul>

<h2>🔍 Feature Importance</h2>
<p>A feature importance plot is generated using <strong>Random Forest</strong> to visualize the most influential factors affecting car prices.</p>

<h2>🚀 How to Use</h2>
<p>You can make predictions using the pre-trained model:</p>
<pre><code>python -c "import car_price_prediction; car_price_prediction.predict_car_price()"</code></pre>

<h2>🏗️ Future Enhancements</h2>
<ul>
    <li>Implement additional models for better accuracy (XGBoost, Gradient Boosting).</li>
    <li>Deploy the model using Flask or FastAPI.</li>
    <li>Create a web interface for user-friendly price prediction.</li>
</ul>

<h2>📜 License</h2>
<p>This project is open-source and free to use under the <strong>MIT License</strong>.</p>

### What You Need to Update:
- Replace `your-username` with your actual GitHub username.
- Update **https://github.com/Deepika-DJ1972/** and **https://www.linkedin.com/in/deepika-joseph-a0a1ab205/** with your details.
- Save this as `README.md` in your repository.

Would you like any modifications or additions? 😊
