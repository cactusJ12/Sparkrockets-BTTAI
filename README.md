# Sparkrockets-BTTAI
Sparkrockets-BTTAI project Github file

# Access Test

Overview
This project focuses on building a machine learning-powered venture capital selector engine. The tool aims to streamline the matching process between startups and venture capitalists by analyzing key characteristics of startups and aligning them with the investment preferences of venture capitalists.

The project uses machine learning techniques such as clustering, vector similarity analysis, and recommendation systems to develop a robust and scalable solution.

Project Structure
1. Data Preparation
Notebook: Sun's_model.ipynb

Objective: Prepares and preprocesses datasets for analysis and modeling.
Datasets Used:
NYC venture capital data (cleaned_nyc.csv)
OpenVC data (cleaned_openvc.csv)
Austrian venture capital data (cleaned_austrian.csv)
Key Steps:
Imports and cleans datasets.
Combines data from multiple sources for uniformity and downstream use.
Outputs clean datasets for modeling.

2. Machine Learning Models
Notebook: Model_CamiZheng.ipynb

Objective: Implements clustering and recommendation systems for venture capital selection.
Techniques and Models:
Word2Vec: Converts text features into vector embeddings for better similarity calculations.
MiniBatchKMeans: Groups startups based on key characteristics for clustering.
SVD (Singular Value Decomposition): Builds recommendation models to align startup features with VC preferences.
Evaluation Metrics:
Cosine similarity for vector matching.
Silhouette score and Davies-Bouldin score for clustering performance.
Visualizations: Uses matplotlib to display model insights and results.

Setup Instructions
1. Clone the Repository
bash
Copy code
git clone https://github.com/yourusername/venture-capital-selector.git
cd venture-capital-selector
2. Install Dependencies
Install Python dependencies using the provided requirements.txt file:

bash
Copy code
pip install -r requirements.txt

3. Run the Notebooks
Open the notebooks in Jupyter or Colab:
Sun's_model.ipynb for data preparation.
Model_CamiZheng.ipynb for machine learning models.
Execute the cells sequentially to reproduce the results.
Sample Dataset
Sample datasets are available in the data/ directory for testing. Larger datasets can be accessed through the links provided in the notebooks.

Results
Clustering: Startups were grouped based on their characteristics into well-defined clusters using MiniBatchKMeans.
Recommendations: The SVD model effectively aligned venture capitalists with suitable startups based on investment preferences.
Performance Metrics: The clustering and recommendation models achieved high silhouette scores and low Davies-Bouldin scores, indicating well-formed clusters.
Future Work
Expand dataset coverage by integrating more global VC databases.
Enhance models by incorporating additional NLP techniques for feature engineering.
Develop a user-friendly web interface for non-technical stakeholders.

License
This project is licensed under the Apache License 2.0. See the LICENSE file for details.

Feel free to adapt this README further with specific links, visuals, or additional sections to better suit your project! Let me know if you'd like help with customization.







