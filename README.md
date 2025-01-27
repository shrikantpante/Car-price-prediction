# Car Sell Price Prediction System Using Machine Learning Algorithms.

A machine learning project to predict car sell price based on following key features:
1. **Year of manafacturing**  
2. **Model of Car**  
3. **Fuel Type**
4. **Owner Type**
5. **KM-Driven**
6. **mileage**
7. **seller_type**
8. **engine power**

---
##  Table of Contents
- Project Overview
- Features of the Dataset
- Workflow 
- Technologies Used
- Result
- Conclusion
- Future Scope
- contribution
---
## Project Overview
The car price prediction project uses a dataset containing details such as the car's brand, model, year of manufacture, mileage, fuel type, transmission, and other relevant attributes. By applying machine learning techniques, the model identifies patterns in the data to predict the selling price of a car.

The key objectives of this project include:
1. Understanding the factors that influence car prices.
2. Building a predictive model to estimate car prices.
3. Evaluating the model's performance using appropriate metrics.
---
## Features of the Dataset
The <a href='https://github.com/shrikantpante/Car-price-prediction-Model/blob/main/Processed_Cardetails.csv'> DataSet</a>
used in this project includes the following features:

1. Brand/Make: The manufacturer of the car (e.g., Toyota, BMW).
2. Model: The specific model of the car.
3. Year: The year of manufacture.
4. Mileage: The total distance traveled by the car.
5. Fuel Type: The type of fuel used (e.g., Petrol, Diesel, Electric).
6. Transmission: Type of transmission (e.g., Manual, Automatic).
7. Engine Size: The engine capacity of the car.
8. Price: The target variable representing the car's selling price.
---
## Workflow 
1. Data Collection: Dataset sourced from kaggle.
2. Data Preprocessing: Handling missing values, outliers, and encoding categorical variables.
3. Exploratory Data Analysis (EDA): Visualizing trends and relationships between features.
4. Model Training: Training machine learning models such as Linear Regression, Decision Tree.
5. Prediction: Deploying the best-performing model to predict car prices.

---
## Technologies Used 
1. Programming Language: Python
2. Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
3. Tools: Jupyter Notebook
---
## Results 
1. The best-performing model was the Decision Tree  Regressor, which outperformed other models like Linear Regression in terms of accuracy and robustness.
2. Insights from the analysis:
    1. Car Age: Older cars tend to have lower prices, with depreciation being steep in the first few years.
    2. Mileage: Higher mileage correlates with a lower price, but the impact varies by car brand and model.
    3. Fuel Type and Transmission: Diesel cars and automatic transmission cars generally fetch higher prices.
    4. Brand Influence: Premium brands like BMW and Mercedes-Benz retain value better compared to economy brands.
---
## CONCLUSION
This project demonstrates the potential of machine learning in enhancing car price prediction by leveraging data-driven insights. Traditional pricing systems often lack precision and adaptability, but the proposed system addresses these shortcomings using decision tree algorithms to deliver accurate and reliable predictions. The approach incorporates various car attributes, market trends, and data preprocessing techniques to create a model that performs with a high degree of accuracy.
The outcomes of this project can assist dealers, buyers, and sellers by providing transparent and data-backed car pricing, streamlining the decision-making process. Furthermore, the system's scalability ensures its applicability across different markets and scenarios, marking a significant improvement over conventional method.


## Future Scope 
1. Enhancing the model by incorporating additional features like location, condition, and owner history.
2. Deployment as a web application using frameworks like Flask or Django.
3. Integration with APIs for real-time car price predictions.

---
## Contributions 
Contributions are welcome! Please open an issue or submit a pull request for improvements.
