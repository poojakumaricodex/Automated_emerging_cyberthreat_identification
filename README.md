Automated Emerging Cyber Threat Identification using NLP


This project focuses on the intelligent identification and profiling of emerging cyber threats by analyzing unstructured textual data using Natural Language Processing (NLP). With the growing volume of cyber threat intelligence shared through articles, blogs, and reports, manual analysis becomes time-consuming and inefficient. This system automates the process, enabling faster and more accurate threat detection to support cybersecurity operations.

Key Features:
Data Collection: Scraped and aggregated cyber threat reports, security blogs, and news feeds to create a real-time corpus of threat intelligence.

Text Preprocessing: Applied NLP techniques such as tokenization, lemmatization, stopword removal, and POS tagging for clean and structured text.

Named Entity Recognition (NER): Used spaCy to extract entities such as malware names, attack types, vulnerabilities (e.g., CVEs), and affected organizations.

Topic Modeling: Implemented Latent Dirichlet Allocation (LDA) to uncover hidden themes and evolving threat patterns across the dataset.

Clustering & Classification: Used unsupervised learning (K-Means) to group similar threat narratives and supervised models to classify threat types.

Threat Trend Analysis: Temporal analysis of identified entities and topics to monitor the rise or decline of specific threats over time.

Visualization: Plotted entity frequency, word clouds, cluster patterns, and timeline trends for better threat understanding.

Technologies & Libraries Used:
Languages: Python

NLP Libraries: spaCy, NLTK, Gensim

ML Libraries: Scikit-learn, XGBoost

Visualization: Matplotlib, Seaborn, WordCloud

Development Tools: Jupyter Notebook, Pandas, NumPy

Outcomes:
Automated extraction of actionable threat intelligence

Visualization of emerging cyber trends for proactive decision-making

Foundation for building a real-time cyber threat intelligence dashboard or alerting system

Setup and Installation
Follow these steps to set up the project in your local environment:

1. Clone the Repository
git clone https://github.com/yourusername/automated-cyber-threat-nlp.git
cd automated-cyber-threat-nlp

2. Create a Virtual Environment
It's recommended to use a virtual environment to avoid conflicts with other packages.
python -m venv venv
source venv/bin/activate   
venv\Scripts\activate

3. Install Dependencies
Install all required libraries from the requirements.txt file:

bash
Copy
Edit
pip install -r requirements.txt
If you haven’t generated a requirements.txt file yet, here’s an example of what to include:

text
Copy
Edit
spacy
nltk
scikit-learn
gensim
pandas
matplotlib
seaborn
wordcloud
xgboost
jupyter
📌 Note: You may need to download NLP models for spaCy and NLTK:


python -m spacy download en_core_web_sm

import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')

4. Run the Jupyter Notebook
jupyter notebook
Open the notebook and run the cells to execute the pipeline.

Screenshots


![Screenshot 2025-05-14 210348](https://github.com/user-attachments/assets/1d12eac7-067d-4266-afb6-d4ebace38aeb)
![Screenshot 2025-05-14 210403](https://github.com/user-attachments/assets/4db24a81-2b1a-4306-99b8-de38239a4196)
![Screenshot 2025-05-14 210416](https://github.com/user-attachments/assets/53f50453-613e-47db-8d5a-39a7e1623d45)






