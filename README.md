# Superstore-Marketing-Campaign
# Superstore Customer Response Prediction

## Overview
This project aims to predict customer responses to marketing campaigns in a superstore setting. Using Exploratory Data Analysis (EDA) and Machine Learning (ML) models, we identify key factors influencing customer engagement and build a predictive model to estimate the likelihood of a positive response.

## Dataset
- The dataset consists of 2,216 customer records, including demographics, spending behavior, and response to marketing campaigns.
- Key features include:
  - **Demographics**: Age, income, education level, marital status.
  - **Spending Behavior**: Amount spent on different product categories (Wines, Fruits, Meat, Fish, Sweets, Gold).
  - **Engagement**: Number of previous campaigns accepted, number of dependents, recency of purchase.
  - **Target Variable**: Whether the customer responded positively (1) or negatively (0) to a campaign.

## Exploratory Data Analysis (EDA)
The EDA process focused on:
1. **Understanding Demographics**: Analyzing age, income, and education distributions.
2. **Spending Patterns**: Identifying which product categories customers spend the most on.
3. **Response Trends**:
   - Customers with higher spending on Wines and Meat Products tend to respond positively.
   - Recency and frequency of purchases correlate with response probability.
4. **Feature Engineering**:
   - Creating new variables such as total spending and customer loyalty score.
   - Encoding categorical variables for ML models.

## Machine Learning Approach
We trained multiple models to predict customer response:
1. **Decision Tree**

2. **K-Nearest Neighbors (KNN)**
   - Accuracy: 84.55%
3. **Logistic Regression**
   - Precision: 0.75 (Negative Response), 0.76 (Positive Response)
   - Recall: 0.95 (Negative Response), 0.36 (Positive Response)

### Best Model:
- **KNN performed best with an accuracy of 84.55%.**

## Key Insights
- Recency and total spending significantly influence customer responses.
- Higher spending on Wines and Meat Products increases response probability.
- Personalized promotions for high-value customers can improve engagement.

## Future Improvements
- Improve recall for positive responses by refining feature selection.
- Explore ensemble models for better predictive performance.
- Further segmentation of customer groups for targeted marketing.

## Repository Structure
```
├── data/                  # Raw dataset files
├── notebooks/             # Jupyter notebooks for EDA & ML
│   ├── superstore_eda.ipynb
│   ├── superstore_ML.ipynb
├── src/                   # Python scripts for data processing & modeling
├── README.md              # Project documentation
```

## How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/superstore-prediction.git
   cd superstore-prediction
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run EDA and model training notebooks in Jupyter:
   ```sh
   jupyter notebook notebooks/superstore_eda.ipynb
   jupyter notebook notebooks/superstore_ML.ipynb
   ```

## License
This project is open-source and available under the MIT License.

## Contact
For questions or collaborations, reach out to [avwaruteelohorrr@gmail.com].

