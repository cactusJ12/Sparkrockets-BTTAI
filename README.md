# SparkRockets Breakthrough Tech AI: Startup Venture Capital Selector Engine

Welcome to the **SparkRockets Breakthrough Tech AI** repository! This project is an AI-powered matchmaking engine designed to connect startups with the most relevant venture capital investors, optimizing fundraising efforts through intelligent algorithms.

----------

## **Table of Contents**

1.  [Project Overview](#project-overview)
2.  [Our Approach](#our-approach)
3.  [Installation](#installation)
4.  [Usage](#usage)
5.  [Results and Key Findings](#results-and-key-findings)
6.  [Contributing](#contributing)
7.  [License](#license)
8.  [Credits and Acknowledgments](#credits-and-acknowledgments)

----------

## **Project Overview**

### **Objective**

The primary goal of the **Startup Venture Capital Selector Engine** is to

-   Provide startups with a curated list of venture capital firms aligned with their business goals.
-   Enhance matchmaking accuracy using machine learning, NLP techniques, and data-driven insights.

### **Key Features**

1.  **Comprehensive Investor Database**  
    Enriched profiles with geography, check size, funding stage, and more.
    
2.  **Matchmaking Algorithm**  
    Intelligent pairing of business ideas with investors based on semantic similarity.
    
3.  **Actionable Insights**  
    Recommendations prioritize efficiency, helping startups secure investments faster.
    

----------

## **Our Approach**

### **1. Data Understanding and Preparation**

-   Aggregated and cleaned investor data across two datasets, investors and ideas.
-   Standardized text features using NLP preprocessing (tokenization, lemmatization, stop-word removal).
-   Addressed missing values and ensured data consistency.

### **2. Feature Engineering**

-   Generated embeddings using **Word2Vec** to capture semantic relationships.
-   Applied one-hot encoding for categorical features.
-   Standardized data for cosine similarity computations.

### **3. Modeling and Algorithms**

-   Implemented **cosine similarity** for initial scoring.
-   Used **K-nearest neighbors** (KNN) for grouping and classification.
-   Developed a **collaborative filtering** model leveraging SVD for advanced recommendations.
-   Evaluated model accuracy using RMSE (0.0852).

----------

## **Installation**

### Prerequisites

-   Python 3.8+
-   Required libraries: `numpy`, `pandas`, `scikit-learn`, `nltk`, `gensim`, `surprise`

### Steps

1.  Clone this repository:
    
    ```bash
    git clone https://github.com/cactusJ12/Sparkrockets-BTTAI.git
    
    ```
    
2.  Navigate to the project directory:
    
    ```bash
    cd Sparkrockets-BTTAI
    
    ```
    
3.  Install dependencies:
    
    ```bash
    pip install -r requirements.txt
    
    ```

----------

## **Usage**

### Running the Model in Jupyter Notebook

1.  **Open the Notebook**
    
    -   In Visual Studio Code or Google Colab, open the main notebook file: `Sparkrockets_BTTAI.ipynb`.
2.  **Prepare the Input Data**
    
    -   Ensure your dataset (`startup_ideas.csv`) is uploaded to the appropriate working directory.
3.  **Run the Notebook**
    
    -   Execute the cells sequentially to preprocess the data, generate embeddings, and run the matchmaking algorithm.
4.  **Output**
    
    -   The notebook will generate:
        -   **Top-N Investor Matches:** A CSV file (`investor_matches.csv`) listing relevant investors for each business idea.
        -   **Visualizations:** Graphs showing similarity scores and matching patterns.

----------

### Running the Model in Google Colab

1.  **Open the Colab Notebook**
    
    -   Upload or link `Sparkrockets_BTTAI.ipynb` in Google Colab.
2.  **Upload Input Data**
    
    -   Upload your dataset (`startup_ideas.csv`) directly to the Colab runtime.
3.  **Install Dependencies**
    
    -   Run the setup cell to install any required libraries:
        
        ```python
        !pip install -r requirements.txt
        
        ```
        
4.  **Run the Notebook**
    
    -   Execute all cells to complete data preprocessing, modeling, and evaluation.
5.  **Download Outputs**
    
    -   Save the generated CSV file and visualizations to your local machine.

----------

## **Results and Key Findings**

### **Model Insights**

-   High accuracy with RMSE of **0.0852**.
-   Semantic relationships effectively captured niche investor interests.

### **Patterns**

-   **Niche Focus Areas:** Investors matched to thematic ideas like AI, fintech, or sustainability.
-   **Broad Investment Interests:** Overlap observed for versatile investors (e.g., Lair East Labs).

### **Challenges and Learnings**

-   Real-world NLP projects require thoughtful preprocessing and robust algorithms.
-   Importance of maintaining data integrity for actionable results.

----------

## **Contributing**

We welcome contributions to improve our matchmaking engine!  
If you'd like to contribute, please reach out to the repository owner via GitHub to discuss your ideas and next steps.

----------

## **License**

This project is licensed under the Apache License 2.0. See the [LICENSE](https://chatgpt.com/c/LICENSE) file for details.

----------

## **Credits and Acknowledgments**

### **Team**

-   Jessica Guan
-   Sunwoong Jang
-   Cami Zheng
-   Itzalen Lopez

### **Advisors**

-   Rebecca Aurelia Dsouza
-   Wim De Pril

----------
