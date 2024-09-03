# Employee_attrition
An in-depth analysis of employee attrition using data preprocessing, exploratory data analysis (EDA), and predictive modeling. The final insights and trends were visualized in an interactive Tableau dashboard, enabling data-driven decision-making to reduce attrition."

# Employee Attrition Analysis

## **Project Overview**

XYZ Company has been facing a persistent 15% attrition rate over the past few years, significantly impacting the company's productivity and overall business performance. To address this issue, XYZ Company has engaged an HR analytics consultancy to analyze employee data, identify key drivers of attrition, and develop strategies to reduce turnover.

As the HR analyst in this project, the primary goal was to build a comprehensive dashboard that enables the organization to make informed, data-driven decisions to mitigate attrition and improve employee retention.

## **Project Steps**

**1. Data Preprocessing:** 
The data preprocessing phase was crucial to ensure that the dataset was clean, consistent, and ready for analysis. The following steps were performed:

**Handling Missing Values:** Missing data can lead to biased results, so missing values were carefully handled. Depending on the nature of the data, strategies such as mean/mode imputation or removal of records with excessive missing values were employed.

**Label Encoding:** Categorical variables, such as department names and job roles, were converted into numerical format using label encoding. This step was necessary for the machine learning algorithms to process the categorical data effectively.

**Outlier Detection and Treatment:** Outliers were identified using statistical methods like the IQR (Interquartile Range) method. Depending on the analysis, outliers were either removed or adjusted to prevent them from skewing the results.

**Scaling Numerical Features:** Numerical features were scaled to bring them to a common scale, which is particularly important for algorithms sensitive to feature magnitudes. StandardScaler was used to normalize the features, ensuring that each had a mean of 0 and a standard deviation of 1.

**2. Exploratory Data Analysis (EDA):** To gain a deeper understanding of the data, EDA was conducted using Jupyter Notebook and Tableau. This process helped to uncover patterns, trends, and potential correlations between various attributes and employee attrition. The insights gained were visualized in an interactive dashboard created in Tableau.

**3. Data Splitting and Scaling:** The dataset was then split into training and testing sets. The training data was scaled to standardize the features, ensuring that the model training process was not biased towards features with larger values.

**4. Model Building:** Multiple classification models were built to predict employee attrition, including Logistic Regression, Random Forest, and Gradient Boosting. Cross-validation was applied to evaluate model performance and detect any signs of overfitting.

**5. Addressing Class Imbalance:** To improve model performance, especially in predicting the minority class (employees who leave), oversampling techniques were applied. This balanced the class distribution and resulted in a model that performs well across both classes, demonstrating strong generalization capabilities.

## **Dashboard and Insights**

The final output of this project includes an interactive dashboard in Tableau, showcasing key insights derived from the analysis. The dashboard provides a clear view of the factors contributing to employee attrition, enabling the company's leadership to take strategic actions to reduce turnover.

## **Tools and Technologies Used**

Python: For data preprocessing, EDA, and model building.
Jupyter Notebook: For running the analysis and visualizations.
Tableau: For creating interactive dashboards and visualizing data trends.
Scikit-learn: For implementing machine learning models and cross-validation.
Imbalanced-learn: For applying oversampling techniques to address class imbalance.

## Tableau Dashboard
You can view the interactive Tableau dashboard [here](https://public.tableau.com/views/UMAMproject-2/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link).

## **Conclusion**

This project provided XYZ Company with actionable insights into the key drivers of employee attrition. By leveraging data analysis and machine learning, the company is now equipped with the tools to make data-driven decisions aimed at reducing attrition and enhancing employee retention.



