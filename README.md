# Cybersecurity Threat Classification using ML  

## **How to Run the Code**  

### **Prerequisites**  
Download the dataset from [Darknet Dataset](https://www.unb.ca/cic/datasets/darknet2020.html).
Ensure you have the following installed:  
- Python (≥3.8)  
- Jupyter Notebook or JupyterLab  
- Required Python libraries (install using the command below)  

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
```

### **Steps to Run the Notebook**  

1. **Open Jupyter Notebook**  
   Run the following command in the terminal or command prompt:  

   ```bash
   jupyter notebook
   ```  
   Then, navigate to the folder containing the notebook file (**SecPen.ipynb**).  

2. **Load the Dataset**  
   - Ensure the dataset file (e.g., **Darknet.csv**) is in the same directory as the notebook.  
   - If the dataset is large, you may use a smaller sample for testing.  

3. **Run the Notebook Cells Sequentially**  
   - **Data Preprocessing**: Handles missing values, normalization, and feature selection.  
   - **Model Training**: Trains **Random Forest, SVM, and XGBoost** models.  
   - **Evaluation & Visualization**: Displays model accuracy, confusion matrices, and feature importance graphs.  

4. **Analyze the Results**  
   - Accuracy, precision, recall, and F1-score for each model are shown.  
   - Visualizations help understand model performance.  
