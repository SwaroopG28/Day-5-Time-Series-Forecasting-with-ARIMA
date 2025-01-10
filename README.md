## 📊 **Day 5: Time Series Forecasting with ARIMA – Airline Passenger Dataset**

### 📄 **Project Overview**
This project focuses on using **Time Series Forecasting** with the **ARIMA (AutoRegressive Integrated Moving Average)** model to predict monthly airline passenger counts. The dataset, **Airline Passenger Dataset**, provides historical passenger data over time, making it ideal for understanding trends, seasonality, and forecasting.

**Dataset Link:** [Airline Passenger Dataset](https://www.kaggle.com/datasets/rakannimer/air-passengers)

---

### 🎯 **Objective**
- Analyze historical airline passenger data.
- Identify trends, seasonality, and stationarity.
- Build an **ARIMA Model** for time series forecasting.
- Evaluate model performance using **MAE**, **RMSE**, and **MAPE**.
- Forecast future passenger counts.

---

### 📊 **Dataset Description**
- **Month:** Timestamp indicating each observation (Monthly data).
- **Passengers:** Number of airline passengers for each month.

**Time Frame:** Monthly data from **January 1949 to December 1960**.

---

### 🛠️ **Steps Performed**

#### **1. Data Preprocessing**
- Loaded the dataset and parsed the `Month` column as a datetime object.
- Set `Month` as the index for time series analysis.
- Handled any missing values.

#### **2. Exploratory Data Analysis (EDA)**
- Visualized the time series to identify trends, seasonality, and cyclic patterns.
- Performed **ADF (Augmented Dickey-Fuller) Test** to check stationarity.
- Differenced the data to achieve stationarity if needed.

#### **3. Model Building – ARIMA**
- Used **ACF (Autocorrelation Function)** and **PACF (Partial Autocorrelation Function)** plots to identify ARIMA parameters `(p, d, q)`.
- Built and trained the ARIMA model using the selected parameters.
- Fine-tuned the model using hyperparameter optimization.

#### **4. Model Evaluation**
- Evaluated the model using:
   - **Mean Absolute Error (MAE)**
   - **Root Mean Squared Error (RMSE)**
   - **Mean Absolute Percentage Error (MAPE)**
- Visualized the actual vs predicted values.

#### **5. Forecasting**
- Generated forecasts for future passenger counts.
- Visualized the forecasted values with confidence intervals.

---

### 📊 **Results**
- The ARIMA model successfully captured trends and seasonality.
- **Error Metrics:**
   - **MAE:** *X.XX*
   - **RMSE:** *X.XX*
   - **MAPE:** *X.XX*
- Forecasted passenger counts showed consistency with historical patterns.

---

### 📈 **Visualizations**
- **Time Series Plot:** Historical passenger data.
- **ADF Test Results:** Stationarity analysis.
- **ACF and PACF Plots:** Parameter selection.
- **Forecast Plot:** Future passenger predictions.
