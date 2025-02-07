# 💻 Laptop Price Prediction - Data Science Project  

### 📌 Project Overview  
This project aims to **predict the price of laptops** based on various features like **brand, RAM, storage, processor type, and GPU**. We use **machine learning models** to analyze the impact of different specifications on laptop prices and develop an accurate price prediction system.  

---

## 📂 Dataset  
The dataset contains various laptop features, including:  

- **Brand** (e.g., Dell, HP, Lenovo, Apple)  
- **Model**  
- **Processor** (e.g., Intel i5, AMD Ryzen 7)  
- **RAM Size** (e.g., 4GB, 8GB, 16GB)  
- **Storage Type** (HDD, SSD)  
- **Storage Capacity** (e.g., 256GB, 512GB, 1TB)  
- **GPU** (Graphics Card)  
- **Screen Size** (e.g., 14", 15.6")  
- **Operating System** (Windows, macOS, Linux)  
- **Price** (Target variable)  

---

## 🛠️ Technologies Used  
- **Programming Language:** Python 🐍  
- **Libraries Used:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn  
- **Machine Learning Models:** Linear Regression, Random Forest, Decision Tree  

---

## 📊 Exploratory Data Analysis (EDA)  
Before training models, we perform **EDA** to understand the dataset:  

1. **Check Missing Values:** Handle missing or incorrect data.  
2. **Feature Distribution:** Visualize the impact of RAM, processor, and storage on price.  
3. **Outlier Detection:** Identify and remove extreme values that may affect predictions.  
4. **Correlation Analysis:** Find relationships between features and price.  

📌 **Key Insights:**  
- Laptops with **higher RAM and SSD storage** tend to be more expensive.  
- **Apple laptops** generally have a **higher price range** than other brands.  
- **Processor type** plays a significant role in determining price.  

---

## 🏗️ Data Preprocessing  
To prepare the dataset for modeling:  

1. **Convert categorical data** (e.g., brand, OS) into numerical form using **One-Hot Encoding**.  
2. **Normalize numerical features** (e.g., RAM size, storage capacity) to maintain consistency.  
3. **Handle missing values** by using median imputation or dropping irrelevant rows.  
4. **Split data** into **80% training & 20% testing**.  

---

## 🤖 Model Selection & Training  
We trained multiple models and evaluated their performance:  

| Model | R² Score (Accuracy) |  
|--------|----------------|  
| **Linear Regression** | 85% |  
| **Decision Tree Regressor** | 88% |  
| **Random Forest Regressor** | 95% |  

📌 **Best Model:** Random Forest Regressor achieved **95% accuracy**, making it the most reliable model for price prediction.  

---

## 📌 Key Findings  
- The **processor and RAM size** are the most important factors influencing price.  
- **SSDs significantly increase the laptop price** compared to HDDs.  
- **Apple laptops are generally more expensive** than other brands with similar specs.  

---

## 🚀 How to Use the Model  
You can use the trained model to **predict laptop prices** for new specifications:  




2nd project 

 

# Food Delivery Time Prediction

## 📌 Project Overview
Predicting the estimated delivery time for food orders is crucial for both restaurants and customers. This project aims to build a machine learning model that accurately predicts delivery time based on various features such as distance, order preparation time, weather conditions, and restaurant details.

## 📊 Dataset Details
The dataset consists of multiple features that influence food delivery time:
- **Restaurant Location**: The latitude and longitude of the restaurant.
- **Customer Location**: The latitude and longitude of the customer.
- **Order Preparation Time**: Time taken by the restaurant to prepare the order.
- **Weather Conditions**: Impact of weather on delivery time.
- **Traffic Conditions**: Influence of traffic on delays.
- **Delivery Distance**: The distance between the restaurant and the customer.
- **Vehicle Type**: Type of vehicle used for delivery.

After data exploration, we identified missing values, outliers, and unnecessary columns, which were cleaned and preprocessed.

## 🔄 Data Preprocessing
### Steps Taken:
1. **Handling Missing Values**: Imputed missing data using appropriate techniques.
2. **Feature Selection**: Dropped irrelevant columns that do not impact delivery time prediction.
3. **Encoding Categorical Data**:
   - Used **Label Encoding** for categorical variables like weather and vehicle type.
4. **Feature Scaling**:
   - Applied **StandardScaler** to normalize numerical features.
5. **Train-Test Split**: The dataset was split into 80% training and 20% testing.

## 🏆 Model Selection & Evaluation
Multiple regression models were trained to predict delivery time. Below are the models used along with their evaluation metrics:

| Model                     | R² Score (Accuracy) |
|---------------------------|--------------------|
| Linear Regression         | 74.5%              |
| Decision Tree Regression  | 78.2%              |
| **Random Forest Regression** | **85.6% (Best Model)** |

- **Linear Regression**: Performed decently but struggled with non-linearity in data.
- **Decision Tree Regression**: Improved accuracy but prone to overfitting.
- **Random Forest Regression**: Gave the best performance with **85.6% accuracy**, making it the final model for prediction.

## 🔥 Key Insights
- Distance and traffic conditions significantly impact delivery time.
- Weather conditions slightly affect predictions but are not the strongest factors.
- Random Forest Regression provided the best accuracy due to its ability to handle complex patterns in data.

## 🚀 Conclusion
This project successfully builds a predictive model for food delivery time estimation. The **Random Forest Regression model** outperforms other models and is recommended for deployment in real-world applications.

## 📂 Future Enhancements
- Integrate real-time traffic data for better predictions.
- Improve feature engineering by considering additional factors like rider experience.
- Deploy the model as a web application for live predictions.

---
### 💡 Connect with Me
If you have any suggestions or queries, feel free to reach out!

📧 Email: [Your Email]  
📌 LinkedIn: [Your LinkedIn Profile]  
📂 GitHub: [Your GitHub Profile]



   
