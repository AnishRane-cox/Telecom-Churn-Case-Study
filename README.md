# Telecom Customer Churn Prediction

## Business Problem Overview
In the telecom industry, customers can choose from multiple service providers and frequently switch between them. This results in an average annual churn rate of **15-25%**. Given that acquiring a new customer is **5-10 times more expensive** than retaining an existing one, telecom companies must focus on customer retention strategies. This project aims to build a predictive model to identify customers likely to churn and provide actionable insights for retention efforts.

## Data Overview
The dataset consists of various customer usage patterns, call details, and recharge behaviors. Below are the key acronyms used in the dataset:

### **Call & Network Metrics**
| Acronym  | Description  |
|----------|-------------|
| CIRCLE_ID | Telecom circle area to which the customer belongs |
| LOC      | Local calls within the same telecom circle |
| STD      | STD calls outside the calling circle |
| IC       | Incoming calls |
| OG       | Outgoing calls |
| T2T      | Calls within the same operator (mobile-to-mobile) |
| T2M      | Calls from the operator to another operator's mobile |
| T2O      | Calls from the operator to another operator's fixed line |
| T2F      | Calls from the operator to its own fixed lines |
| T2C      | Calls from the operator to its own call center |
| ONNET    | All calls within the same operator network |
| OFFNET   | All calls outside the operator’s network |
| ROAM     | Indicates if the customer was roaming during the call |
| SPL      | Special calls |
| ISD      | International calls |

### **Usage & Financial Metrics**
| Acronym  | Description  |
|----------|-------------|
| ARPU     | Average Revenue Per User |
| MOU      | Minutes of Usage (voice calls) |
| AON      | Age on Network (number of days a customer has been with the operator) |
| RECH     | Recharge transactions |
| NUM      | Number of recharge transactions |
| AMT      | Recharge amount in local currency |
| MAX      | Maximum recharge amount |
| DATA     | Mobile internet usage |
| 2G, 3G   | Type of network used |
| AV       | Average usage values |
| VOL      | Mobile internet usage volume in MB |
| PCK      | Prepaid service schemes (PACKS) |
| NIGHT    | Special schemes for night usage |
| MONTHLY  | Service schemes with a month-long validity |
| SACHET   | Short-term service schemes (less than a month) |
| VBC      | Volume-based cost (charged per usage when no pack is purchased) |
| FB_USER  | Service schemes for Facebook and social networking usage |

### **Time-based Metrics**
| Acronym  | Description  |
|----------|-------------|
| *.6      | KPI for June |
| *.7      | KPI for July |
| *.8      | KPI for August |

## Project Objective
- **Predict customer churn** based on call patterns, recharge behavior, and internet usage.
- **Identify key factors** that contribute to churn.
- **Provide actionable insights** to reduce churn and improve customer retention strategies.

## Methodology
1. **Data Preprocessing:**
   - Handling missing values
   - Encoding categorical variables
   - Feature engineering
   
2. **Exploratory Data Analysis (EDA):**
   - Understanding customer behavior
   - Identifying key trends affecting churn
   
3. **Feature Selection & Engineering:**
   - Removing multicollinearity
   - Selecting the most relevant predictors
   
4. **Model Development:**
   - Building and evaluating classification models
   - Comparing performance using accuracy, precision, recall, and F1-score
   
5. **Insights & Recommendations:**
   - Identifying high-risk churn segments
   - Suggesting proactive customer retention strategies

## Expected Outcomes
- A machine learning model capable of predicting customer churn with high accuracy.
- Insights into the most important factors influencing churn.
- Actionable recommendations for improving customer retention.

## Tools & Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Machine Learning Models:** Logistic Regression, Random Forest, Gradient Boosting
- **Data Visualization Tools:** Matplotlib, Seaborn

## Contributors
- **[Your Name]** - Data Science & Machine Learning
- **[Other Contributors]** - Data Engineering, Business Analysis

## Contact
For inquiries or collaborations, please reach out at **anishrane2000@gmial.com**.

