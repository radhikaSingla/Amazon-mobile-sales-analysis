 Mobile Sales Data Analysis
________________________________________
 Data Preprocessing
•	Imported and cleaned the dataset using Pandas and NumPy
•	Handled missing values in columns such as Memory, Storage, and Rating
•	Converted memory values (e.g., “MB”, “GB”) into numeric form using regular expressions
________________________________________
 Exploratory Data Analysis (EDA)
•	Descriptive Statistics — summary of key metrics
•	Bar Graphs — number of sales per brand
•	Pie Chart — brand sales distribution
•	Heatmap — correlation between features
•	Histograms & Scatterplots — visualize price distributions and relationships
________________________________________
 Machine Learning Model
•	Built a Linear Regression model using Scikit-Learn
•	Encoded categorical features using OneHotEncoder
•	Achieved an impressive R² Score: 0.93
________________________________________
Key Insights & Conclusions
Model Accuracy:
The Linear Regression model achieved an R² score of 0.93, showing high predictive performance.
Price Drivers:
Features like Memory, Storage, and Brand have the strongest influence on selling price.
Brand Effect:
Some brands (like Apple and Samsung) maintain higher prices even with similar specs, showing strong brand value.
Rating Correlation:
Phones with higher user ratings tend to have higher selling prices.
Discount Trends:
Premium phones receive higher discount percentages compared to budget models.
________________________________________
 Technologies Used
Category	Tools / Libraries
Programming	Python
Data Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Machine Learning	Scikit-Learn
Others	Regex, Jupyter Notebook
________________________________________
 Sample Outputs
•	 Bar Graph: Number of Sales per Brand
•	 Pie Chart: Brand Sales Distribution
•	 Heatmap: Feature Correlation
•	 Scatterplot: Rating vs Selling Price
•	 Model Output: R² = 0.93
________________________________________
 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/mobile-sales-analysis.git
cd mobile-sales-analysis
2️⃣ Install Dependencies
pip install pandas NumPy matplotlib seaborn scikit-learn
3️⃣ Run the Notebook
jupyter notebook ca2_data_science. ipynb
________________________________________
 Author
Radhika Singla
 MCA Student
________________________________________
 Conclusion
This analysis provides meaningful insights into mobile pricing trends and customer preferences.
The predictive model can be used for price estimation, market research, and competitor analysis in the mobile retail sector.

