# Customer Segmentation Analysis for Online Retail

This project is a part of AAI-500 course in Applied Artificial Intelligence program at the University of San Diego(USD). 

-- Project Status: Completed

## Installation & Setup
To set up the project environment, follow these steps:

```bash
# Clone the repository
git clone https://github.com/your-repo/online-retail-customer-segmentation.git
cd online-retail-customer-segmentation

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate     # Windows

# Install dependencies
pip install -r requirements.txt
```
## Project Objective
The main purpose of the project is to analyze the Online Retail dataset to perform customer segmentation. The goal is to derive actionable insights for targeted marketing strategies by grouping customers based on their purchasing behavior.

## Dataset
The dataset used in this project is the **Online Retail Dataset**, sourced from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/352/online+retail). It contains transactional data for an online retail store, including details such as:
- Invoice numbers
- Stock codes
- Product descriptions
- Quantities
- Invoice dates
- Unit prices
- Customer IDs
- Country information

The dataset consists of **8 variables** and approximately **541,909 rows**.

## Project Structure
```
├── README.md                   # Project Documentation
├── requirements.txt             # List of dependencies
├── venv/                        # Virtual environment
├── resources/                   # Input and output files
│   ├── data/                     # Data storage
│       ├── input/                # Raw input data
│       ├── output/               # Processed results
├── notebooks/                    # Jupyter notebooks
│   ├── 01_data_cleaning.ipynb
│   ├── 02_eda.ipynb
│   ├── 03_customer_segmentation_rfm.ipynb
│   ├── 03_rfm_analysis_kmeans.ipynb
│   ├── 04_customer_segmentation_kmeans.ipynb
│   ├── 04_kmeans_cluster_model.ipynb
│   ├── Archive/                   # Older versions of notebooks
```

## Data Preprocessing & Cleaning
 **Notebook:** `01_data_cleaning.ipynb`
Handles missing values, removes duplicates, and corrects data types.

**Notebook:** `02_eda.ipynb`
Performs Exploratory  Data Analysis.

## Customer Segmentation Approaches
### K-means Approach
**Notebook:** `03_rfm_analysis_kmeans.ipynb`
Uses **Recency, Frequency, and Monetary (RFM) analysis** to categorize customers.

**Notebook:** `04_kmeans_cluster_model.ipynb`
**Segmenting customers using K-means algorithm.**

### DBSCAN Approach
**Notebook:** `03_customer_segmentation_rfm.ipynb`
Uses **DBSCAN clustering with Recency, Frequency, Monetary (RFM) analysis** to categorize customers.


## How to Use This Project
### Running Jupyter Notebooks
1. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to the `notebooks/` folder and execute the notebooks in order:
   - `01_data_cleaning.ipynb`
   - `02_eda.ipynb`
   - `03_rfm_analysis_kmeans.ipynb`
   - `04_kmeans_cluster_model.ipynb`
   - `03_customer_segmentation_rfm.ipynb`

## Methods Used

This project employs the following methods for customer segmentation:

* **Data Manipulation:**  Data cleaning, handling missing values, feature scaling.
* **Data Visualization:**  Interactive visualizations to explore customer behavior and present segmentation results.
* **Machine Learning:**
    * RFM (Recency, Frequency, Monetary) analysis for initial customer behaviour.
    * K-Means clustering to group customers based on their RFM scores.
* **Inferential Statistics:** Descriptive statistics to characterize customer segments (e.g., purchase frequency, order value).

## Technologies
**Core:**

* Python
* Pandas 
* NumPy 
* Scikit-learn 
* Plotly
* matplotlib
* seaborn
* scipy

**Data Handling:**

* CSV data format

**Development:**

* Jupyter Notebook
* Git/GitHub

## Acknowledgments

We would like to express our sincere gratitude to Dr. Zahid Hussain Wani, professor for the AAI-500 course, for his invaluable guidance and support throughout this project.

## Contact & Contributions
📩 For any queries or contributions, please reach out to AAI-500 Group 7.

