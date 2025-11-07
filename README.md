Mobile Sales Data Analysis
 
 --Data Preprocessing--

Imported and cleaned the dataset using Pandas and NumPy

Handled missing values in columns such as Memory, Storage, and Rating

Converted memory values (e.g., “MB”, “GB”) into numeric form using regular expressions

-- Exploratory Data Analysis (EDA)--

Descriptive Statistics — summary of key metrics

Bar Graphs — number of sales per brand

Pie Chart — brand sales distribution

Heatmap — correlation between features

Histograms & Scatterplots — visualize price distributions and relationships

-- Machine Learning Model--

Built a Linear Regression model using sklearn

Encoded categorical features with OneHotEncoder

Achieved an impressive R² Score: 0.93

 --Key Insights & Conclusions--

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

-- Technologies Used --
Category	Tools / Libraries
Programming	Python
Data Analysis	Pandas, NumPy
Visualization	Matplotlib, Seaborn
Machine Learning	Scikit-Learn
Others	Regex, Jupyter Notebook

--Sample Outputs--

-- Bar Graph: Number of Sales per Brand --

 Pie Chart: Brand Sales Distribution

 Heatmap: Feature Correlation

 Scatterplot: Rating vs Selling Price

 Model Output: R² = 0.93

 How to Run the Project

Clone the repository

git clone https://github.com/<your-username>/mobile-sales-analysis.git
cd mobile-sales-analysis


Install the dependencies

pip install pandas numpy matplotlib seaborn scikit-learn


Run the notebook

jupyter notebook ca2_data_science.ipynb

-- Author:

Radhika Singla


-- Conclusion --

This analysis provides meaningful insights into mobile pricing trends and customer preferences.
The predictive model can be used for price estimation, market research, and competitor analysis in the mobile retail sector.
