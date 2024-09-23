# Comparative Study of ML and ANN Models for Predicting Wine Quality

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

### Running Locally

1. **Prerequisites:** Ensure you have Python 3.x installed on your system.
2. **Clone the repository:** 
   ```bash
   git clone https://github.com/ratulbanik/Comparative-Study-of-ML-and-ANN-Models-for-Predicting-Wine-Quality.git
   ```
3. **Navigate to the project directory:** `cd Comparative-Study-of-ML-and-ANN-Models-for-Predicting-Wine-Quality`
4. **Create a virtual environment (recommended):** `python3 -m venv .venv`
5. **Activate the environment:**
    * Windows: `.venv\Scripts\activate`
    * macOS/Linux: `source .venv/bin/activate`
6. **Install dependencies:** `pip install -r requirements.txt`
7. **Start Jupyter Notebook:** `jupyter notebook`
8. **Open the notebook:** Click on `Wine_Quality_Analysis.ipynb` within the Jupyter interface to open and run the notebook.

## Running in Google Colab

You can run this project directly in your browser using Google Colab. Here's how:

1. **Open the notebook in Colab:** Click on the "Open in Colab" badge: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github.com/ratulbanik/Comparative-Study-of-ML-and-ANN-Models-for-Predicting-Wine-Quality/blob/main/notebooks/california_housing_analysis.ipynb)
2. **Connect to a runtime:** Colab will prompt you to connect to a runtime environment. Select a GPU or TPU runtime if your analysis requires it.
3. **Run the cells:** The notebook is now ready! Execute the cells in order to run the code.

**Note:** You might need to install some dependencies within the Colab notebook if they are not already available in the Colab environment.

## Author & Contact 

* **GitHub:** [ratulbanik](https://github.com/ratulbanik)
* **LinkedIn:** [https://www.linkedin.com/in/ratul-banik/](https://www.linkedin.com/in/ratul-banik/) 
