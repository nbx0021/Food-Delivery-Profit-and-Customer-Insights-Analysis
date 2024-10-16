
# Food Delivery Profit and Customer Insights Analysis

## 📋 Project Overview

This project aims to analyze the profit margins, customer behavior, discount effects, and delivery performance of a food delivery service. The dataset includes various attributes such as order value, discount types, profit margins, and delivery times, providing insights into key performance indicators.

Key analyses include:
- 📊 Profit margins with and without discounts
- 📉 Effect of delivery time on profit
- 📈 Customer segmentation based on spending and profit
- 🏷️ Discount analysis and its impact on orders

## 🗂️ Data Overview

The dataset contains detailed information on:
- **Order Details**: Order Value, Delivery Fee, Discounts, Profit, etc.
- **Customer Information**: Customer ID, Customer Segments, and more
- **Delivery Information**: Delivery Time Taken, Restaurant ID, etc.

## 📊 Key Insights and Visualizations

### 1. **Profit Before vs. After Refunds**
The following chart compares total profit before and after refunds, showcasing the impact of refunds on business profitability:

![profit before vs after](https://github.com/user-attachments/assets/13853930-b5a6-4c09-a451-43ec342fa23f)

### 2. **Customer Segmentation by Total Discounts Used**
Visualizing customer segments based on total discounts applied, allowing for better targeting of marketing campaigns.


![c_segmentation by t dicount](https://github.com/user-attachments/assets/45b3d814-9be8-4cd3-b47b-547fa6805b95)

### 3. **Delivery Time Impact on Profit**
This line plot shows how longer delivery times affect average profit per order.

![d time impact on profit](https://github.com/user-attachments/assets/910db488-82ff-4547-b6a7-aac82e30f98a)

## 💡 Techniques Used

- **Data Cleaning**: Handled missing values and standardized discount information.
- **Exploratory Data Analysis (EDA)**: Derived insights using visualizations (Seaborn, Matplotlib).
- **Customer Segmentation**: Applied K-Means clustering for identifying distinct customer groups based on average spending and profit.
- **Profitability Analysis**: Compared profits before and after applying refunds and discounts.

## 📊 Libraries Used

- `Pandas` for data manipulation
- `Seaborn` & `Matplotlib` for visualizations
- `Scikit-learn` for K-Means clustering
- `NumPy` for numerical computations

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/food_delivery_analysis.git
   ```
2. Navigate to the project directory and install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis:
   ```bash
   jupyter notebook cleaning_data.ipynb
   ```

## 📷 Screenshots

### Correlation Heatmap
Visualizes relationships between different variables in the dataset.

![heatmap](https://github.com/user-attachments/assets/8aea1fbe-9874-4af9-92e9-e4284f4c28ee)

### Profit Distribution by Discount Type
This box plot highlights the profit margins across different discount categories.

![profit margin](https://github.com/user-attachments/assets/d1e6459a-e917-4614-a1a6-2c0152b322d0)

---

## 🤝 Contributing

Feel free to open an issue or submit a pull request with improvements! All contributions are welcome.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


---

### **Steps to Add Images:**
1. **Upload your images to the repository**:
   - Place all your relevant images (plots, charts, screenshots) in a folder (e.g., `images/`).
   - In the `README.md`, use the syntax:
     ```markdown
     ![Alt text](path/to/image.png)
     ```

2. **Use relative paths**:
   - If you upload the images to a subfolder within your repository, use relative paths:
     ```markdown
     ![Customer Segmentation](images/customer_segmentation.png)
     ```

3. **Visualize badges for an enhanced look**:
   - Consider adding badges for technologies used, license, or GitHub actions. For example:
     ```markdown
     ![Python](https://img.shields.io/badge/Python-3.8-blue)
     ![License](https://img.shields.io/badge/license-MIT-green)
     ```
