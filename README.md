# Uncorking Quality: A Comparative Analysis of Wine Prediction Models

## Project Overview

This project performs a comparative analysis of three machine learning models (specify the models - e.g., Random Forest, Decision Tree, SVM) against a sequential Artificial Neural Network (ANN). The goal is to determine which model provides the best classification accuracy for predicting wine quality based on its chemical properties. 

### Motivation 

Understanding the factors driving wine quality is valuable for both winemakers seeking to improve their product and consumers looking to make informed choices. This project provides insights into predictive modeling techniques applicable to similar quality assessment problems.

## Dataset

The dataset used for this analysis is the Wine Quality Dataset available at [https://archive.ics.uci.edu/dataset/186/wine+quality](https://archive.ics.uci.edu/dataset/186/wine+quality).

**Citation:**

P. Cortez, A. Cerdeira, F. Almeida, T. Matos, and J. Reis. "Modeling Wine Preferences by Data Mining from Physicochemical Properties." In Decision Support Systems, Elsevier, 47(4):547-553. 

**Key Features:**

* **Fixed Acidity:** The concentration of non-volatile acids, primarily tartaric acid, which contributes to the wine’s tartness.
* **Volatile Acidity:** The concentration of volatile acids, mainly acetic acid, which can give wine an unpleasant vinegar taste if too high.
* **Citric Acid:** A minor acid in wine that can add freshness and flavor.
* **Residual Sugar:** The amount of sugar remaining after fermentation, influencing the sweetness of the wine.
* **Chlorides:** The concentration of salt in the wine, which can affect its taste and preservation.
* **Free Sulfur Dioxide:** The amount of SO2 that is not bound to other molecules, acting as an antimicrobial and antioxidant.
* **Total Sulfur Dioxide:** The total amount of SO2, both free and bound, used to preserve the wine.
* **Density:** The density of the wine, which can be related to its alcohol and sugar content.
* **pH:** The measure of acidity or alkalinity, affecting the wine’s taste and stability.
* **Sulphates:** Additives that can contribute to the wine’s preservation and enhance its flavor.
* **Alcohol:** The alcohol content of the wine, influencing its body and taste.
* **Quality:** The target variable, typically a score given by wine experts based on sensory data.

## Instructions to Run 

1.  **Dependencies:**  
    * This project requires the following Python libraries:
       ```
       pandas
       numpy
       seaborn
       matplotlib
       termcolor
       scikit-learn
       imblearn
       ```

2.  **Running the Notebook:**
    1. Clone the repository:  `git clone [Your Repository URL - We'll get this in the next step]`
    2. Navigate to the project folder: `cd wine-quality-analysis` 
    3. Install dependencies: `pip install -r requirements.txt`
    4. Open the Jupyter Notebook: `jupyter notebook`
    5. Run all cells in the notebook to reproduce the analysis.

## Author & Contact 

* **GitHub:** [ratulbanik](https://github.com/ratulbanik)
* **LinkedIn:** [https://www.linkedin.com/in/ratul-banik/](https://www.linkedin.com/in/ratul-banik/) 