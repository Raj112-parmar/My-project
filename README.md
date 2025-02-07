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

1. **Clone this repository:**  
   ```bash
   git clone https://github.com/Raj112-parmar/My-project.git
   cd My-project
