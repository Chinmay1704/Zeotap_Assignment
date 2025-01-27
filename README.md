# Data Science Assignment: eCommerce Transactions Dataset

## **Overview**
This assignment focuses on analyzing an eCommerce transactions dataset to derive actionable insights, build predictive models, and perform customer segmentation using clustering techniques. The project is structured into three main tasks:

1. **Exploratory Data Analysis (EDA) and Business Insights**
2. **Lookalike Model Development**
3. **Customer Segmentation and Clustering**

Each task is designed to assess data analysis, machine learning, and insight-generation skills while focusing on practical business applications.

---

## **Dataset Details**
The dataset comprises three CSV files:

1. **Customers.csv**: Contains customer profile information.
   - CustomerID: Unique identifier for each customer.
   - CustomerName: Name of the customer.
   - Region: Continent where the customer resides.
   - SignupDate: Date when the customer signed up.

2. **Products.csv**: Contains product details.
   - ProductID: Unique identifier for each product.
   - ProductName: Name of the product.
   - Category: Product category.
   - Price: Product price in USD.

3. **Transactions.csv**: Contains transaction details.
   - TransactionID: Unique identifier for each transaction.
   - CustomerID: ID of the customer who made the transaction.
   - ProductID: ID of the product sold.
   - TransactionDate: Date of the transaction.
   - Quantity: Quantity of the product purchased.
   - TotalValue: Total value of the transaction.
   - Price: Price of the product sold.

---

## **Tasks and Deliverables**

### **Task 1: Exploratory Data Analysis (EDA) and Business Insights**
- **Objective**: Analyze the dataset to identify key patterns and trends.
- **Deliverables**:
  - A Jupyter Notebook containing the EDA code.
  - A PDF report summarizing at least five business insights (max 500 words).

### **Task 2: Lookalike Model Development**
- **Objective**: Build a model to recommend 3 similar customers based on their profile and transaction history.
- **Deliverables**:
  - A Jupyter Notebook explaining the model development process.
  - A CSV file containing the top 3 lookalike customers and similarity scores for the first 20 customers (CustomerID: C0001 to C0020).

### **Task 3: Customer Segmentation and Clustering**
- **Objective**: Perform clustering to group customers based on their profile and transaction history.
- **Deliverables**:
  - A Jupyter Notebook containing the clustering code.
  - A PDF report including:
    - Number of clusters formed.
    - DB Index value.
    - Other relevant clustering metrics.
    - Visual representations of clusters.

---

## **Key Metrics and Evaluation**

1. **EDA and Business Insights**:
   - Depth and quality of insights.
   - Presentation of findings.

2. **Lookalike Model**:
   - Model accuracy and logic.
   - Quality of recommendations and similarity scores.

3. **Customer Segmentation**:
   - Clustering logic and metrics (e.g., DB Index, silhouette score).
   - Visual representation of clusters.

---

## **Tools and Libraries Used**
- **Python Libraries**:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
- **IDE**: Jupyter Notebook

---

## **File Structure**
```
├── Data/
│   ├── Customers.csv
│   ├── Products.csv
│   └── Transactions.csv
├── Notebooks/
│   ├── Task1_EDA.ipynb
│   ├── Task2_LookalikeModel.ipynb
│   └── Task3_Clustering.ipynb
├── Reports/
│   ├── Task1_BusinessInsights.pdf
│   ├── Task2_LookalikeRecommendations.csv
│   └── Task3_ClusteringReport.pdf
├── README.md
```

---

## **Instructions for Reproduction**
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```
2. Install required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebooks in the following order:
   - Task1_EDA.ipynb
   - Task2_LookalikeModel.ipynb
   - Task3_Clustering.ipynb
4. Review the output files in the `Reports/` folder.

---

## **Contact Information**
For any queries or issues, please reach out to:
- **Name**: Chinmay Khanapurkar
- **Email**: cpkhanapurkar1704@gmail.com
- **GitHub**: https://github.com/Chinmay1704/

---

**Good luck with your analysis!**
