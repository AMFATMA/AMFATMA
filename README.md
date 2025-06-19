<h1 align="center">Hi 👋, I'm Fatma Amor</h1>
<h3 align="center">A Passionate Data Analyst</h3>

- 📫 How to reach me **fatma.amor@gmail.com**

# 📄 Know about my experiences

Having studied Computer Science, I recently specialized in Data Analytics. Professional, with strong organizational skills and effective communication abilities developed during my teaching experience, I am eager to seize an opportunity in the data field. I aim to leverage my technical skills and organizational abilities to contribute to innovative projects and data analysis, providing relevant solutions to the strategic challenges of businesses.

---

## ⚡ Fun fact

**I get excited about learning new tools – the more complex, the better! It’s like collecting superpowers for my work.**

---

## 🚀 Projects
![Texte alternatif](images/image2.png)



🔍 Project Overview
Goal:
Predict the risk of chronic respiratory diseases (such as asthma, COPD) based on individual lifestyle factors and environmental pollution indicators.

🧾 Data Sources
Lifestyle & Health Data

ANSES (anses.fr): For food, toxicological, and environmental exposure assessments.

AMELI (ameli.fr): For health system data, reimbursement statistics, chronic disease stats, etc.

Pollution Data

Open-Météo: Scraped for air quality indicators like PM2.5, NO₂, O₃, and general weather conditions that influence respiratory risk.


🔧 Features Considered
You might be including:
Age, sex, smoking status
Physical activity level
Air pollution levels (daily/weekly averages)
Temperature/humidity (as respiratory stressors)
Geographic location (urban vs. rural exposure)

The project workflow follows a structured pipeline consisting of several key stages:

Data Collection
The process begins with gathering raw data from three distinct sources: Ameli, ANSES, and OpenMétéo. These datasets form the foundation for the entire pipeline

ETL Process
The Extraction, Transformation, and Loading (ETL) process manages the flow of data across the pipeline:

[**Extraction from MongoDB**](https://github.com/AMFATMA/AMFATMA/blob/main/notebooks/Bloc%201/ETL/connexion_mongo.py)
: Data is retrieved from a data lake stored in MongoDB.

Transformation: This step involves cleaning and structuring the data. Specifically, [**air quality**](https://github.com/AMFATMA/AMFATMA/blob/main/notebooks/Bloc%201/ETL/air_trait.py) data is transformed and [**joined**](https://github.com/AMFATMA/AMFATMA/blob/main/notebooks/Bloc%201/ETL/jointure.py) with lifestyle and respiratory disease datasets to form a unified and enriched dataset.

[**Loading to supabase](https://github.com/AMFATMA/AMFATMA/blob/main/notebooks/Bloc%201/ETL/connexion_supabase.py): The final dataset is loaded into a structured relational database using Supabase for further analysis and modeling.

The data is cleaned, joined, and transformed to create a consistent, high-quality dataset ready for analysis.

[**Preprocessing & Analysis**](https://github.com/AMFATMA/AMFATMA/blob/main/notebooks/Bloc%202/analyse_preprocessing.ipynb)
The prepared dataset undergoes exploratory data analysis (EDA) and preprocessing steps such as handling missing values, normalization, and feature engineering to ensure the data is optimized for modeling.

[**Machine Learning (ML)**] (https://github.com/AMFATMA/AMFATMA/blob/main/notebooks/Bloc%203/machine_learning.ipynb)
Various machine learning models are developed and trained on the processed data to make predictions or classifications.

[**Deep Learning (DL)**] (https://github.com/AMFATMA/AMFATMA/blob/main/notebooks/Bloc%204/Deep_learning.ipynb)
For more complex patterns and higher accuracy, deep learning models are designed and trained, leveraging neural networks.

[**Deployment (Industrialization)**](https://pmc-frontend-gvo6.onrender.com/)
Finally, the validated models are deployed into a production environment to be used in real-world applications, ensuring scalability and maintainability.



---

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://www.arduino.cc/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/arduino-1.svg" alt="arduino" width="40" height="40"/> </a> <a href="https://www.docker.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original-wordmark.svg" alt="docker" width="40" height="40"/> </a> <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> </a> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>
