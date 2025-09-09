# 🚖 Uber Ride Booking - EDA & Classification

## 📌 Project Overview
This project analyzes **NCR (Delhi-NCR) ride booking data** to explore patterns, perform **Exploratory Data Analysis (EDA)**, and build a **classification model** to understand booking behaviors.  

The dataset contains ride booking details, which are used for:  
- Understanding booking trends.  
- Identifying peak booking times.  
- Exploring cancellation patterns.  
- Building predictive models for classification.  

---

## 📂 Repository Structure
 ```bash
├── ncr_ride_bookings.csv        # Dataset (raw ride booking data)
├── uber-eda-classifacation.ipynb # Jupyter Notebook with analysis & modeling
├── README.md                    # Project documentation
 ```

---

## 🔍 Key Steps in the Project
1. **Data Loading & Cleaning**  
   - Handled missing values and duplicates.  
   - Converted datetime fields for analysis.  

2. **Exploratory Data Analysis (EDA)**  
   - Ride distribution by time, location, and type.  
   - Cancellation trends & user behavior.  
   - Visualization with matplotlib & seaborn.  

3. **Feature Engineering**  
   - Extracted features like day, hour, weekday, weekend.  
   - Created target variable for classification.  

4. **Classification Modeling**  
   - Applied ML algorithms (Logistic Regression, Random Forest, etc.).  
   - Compared model performance with accuracy, precision, recall, and F1-score.  

---

## 📊 Technologies Used
- **Python** (Pandas, NumPy)  
- **Matplotlib & Seaborn** (Visualization)  
- **Scikit-learn** (Machine Learning models)  
- **Jupyter Notebook**  

---

## ⚙️ Method to Run (with Virtual Environment)

1. **Create and Activate Virtual Environment**  
   ```bash
   # Create virtual environment
   python -m venv venv

   # Activate (Windows)
   venv\\Scripts\\activate

   # Activate (Linux/Mac)
   source venv/bin/activate```

## 📌 Future Scope
- Add deep learning models for better prediction.
- Deploy as a Flask/Django web app.
- Integrate with real-time ride data APIs.

## 👨‍💻 Author
#### Your Name - Dhruv Kumar
- 📧 dhruvkumar60229@gmail.com
- 🌐 linkedin.com/in/dhruv-kumar-a97428292
