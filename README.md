# Arjun Janamatti - Senior Data Scientist

**Contact Information:**
- **Phone:** +91 8431849759
- **Location:** Bangalore, India
- **Email:** arjunjanamatti@gmail.com
- **Kaggle:** kaggle.com/arjunjanamatti
- **GitHub:** github.com/arjunjanamatti
- **LinkedIn:** linkedin.com/in/arjun-janamatti-b5b8789

## Summary
- Over 14 years of diverse experience in Data Science and Mechanical Engineering.
- Currently a Senior Data Scientist at Rockwell Automation, specializing in the CIAM domain.

## Technical Skills
- **Languages:** Python, R, SQL
- **Tech Stack:** Git, AWS, Azure, Jupyter Notebook, Pycharm, Visual Studio Code, LaTeX

## Technical Experience

### Senior Data Scientist, Rockwell Automation
**Jan 2024 - Present | Bangalore, India**
- Devised a data pipeline with Azure Data Factory for efficient data flow from SQL Server to Azure Data Lake Storage.
- Implemented data transformations in Azure Databricks, ensuring data integrity and consistency.
- Created a Power BI dashboard to visualize Key Performance Indicators for the IAM domain.

### DGM-Data Scientist, Schneider Electric
**June 2021 - Oct 2023 | Bangalore, India**
- Executed a POC for deploying open-source SLM on AWS.
- Streamlined safety stock calculations with feedback learning.
- Applied network modeling and a Genetic algorithm optimizer for Multi Echelon Inventory Optimization.
- Revamped Demand Forecasting with statistical methods, boosting forecasting accuracy by 5%.

### Python Developer, ScalingWeb
**Jan 2021 - May 2021 | Bangalore, India**
- Developed a Flask API for content moderation in a mobile app.
- Utilized 'deepspeech' models for audio analysis and OpenCV for image processing.

### Project Manager/Data Scientist, Biztechnosys Infotech Pvt Ltd
**Jan 2019 - Dec 2020 | Bangalore, India**
- Worked on data pre-processing, analysis, and visualization using Python and Microsoft Power BI.
- Managed projects related to CRM, web development, and mobile applications.

### Mechanical Engineer, Applus Velosi
**Aug 2007 - May 2016 | Muscat, Oman**
- Conducted inspections for NDE, Destructive testing, Hydrotesting, and FAT for Valves, Pipes, and fittings.

## Education
- **Master of Science in Petroleum Engineering**, University of Tulsa (Aug 2016 - Dec 2018)
- **Bachelor of Mechanical Engineering**, Visvesvaraya Technological University (Nov 2003 - July 2007)

## Special Achievements
- Crafted three Python packages for data analysis and processing, available on PyPI: `get-cov2`, `conPov`, and `simpleOutlierRemoval`.
- Led a 'Deep Dive on Transformers' session for Analytics India's Data Hour series.

## Projects

### Retrieval Augmented Generation (RAG) Projects

#### RAG_1
**Summary:** Developed a Retrieval Augmented Generation (RAG) system to enhance information retrieval and generation capabilities.

**Repository:** [RAG_1](https://github.com/arjunjanamatti/RAG_1/releases)

**Approach:** Implemented a pipeline to populate a database and retrieve relevant information using advanced NLP techniques.

**Tools:** Python, various NLP libraries

#### RAG_local
**Summary:** Built a local RAG system to ensure data privacy and reduce token costs, enabling efficient information retrieval and generation on local machines.

**Repository:** [RAG_local](https://github.com/arjunjanamatti/RAG_local)

**Approach:** Set up a local RAG pipeline using open-source tools to process and retrieve information from local data sources.

**Tools:** Python, local deployment tools

### Single Echelon Inventory Optimization
**Summary:** Optimized safety stock calculations using feedback learning, resulting in a reduction of 100 ME in the first year across 90% of factories and distribution centers.

**Requirement:** Previous safety stock calculations assumed normally distributed demand and no variation in lead time, leading to frequent stock outs.

**Solution:** Calculated optimal safety stock, right-sizing it for 80 distribution centers and 120 factories. Implemented a feedback loop to understand and learn from changes in safety stock recommendations.

**Approach:** Used convolution of demand series over lead time series with a joint probability approach.

**Inputs and Deployment:** Processed sales and purchase order data for approximately 1.3 million unique plant-material combinations, deployed in AWS with parallel processing in batch jobs.

**Techniques:**
- Joint probabilities
- Convolution of distribution objects

**Tools:** Python, AWS, Tableau, numpy, pandas, scipy, math, pygad

### Multi Echelon Inventory Optimization
**Summary:** Enhanced the single echelon solution using network modeling and a genetic algorithm optimizer.

**Requirement:** The single echelon approach only considered individual DCs or factories, without simulating SLA scenarios.

**Solution:** Enabled planners to simulate scenarios, maintaining regional SLA even when upstream SLAs were not met.

**Approach:** Used a genetic algorithm to simulate scenarios and optimize safety stock with the objective of minimizing stock levels.

**Techniques:**
- Joint probabilities
- Convolution of distribution objects
- Genetic algorithm

**Tools:** Python, AWS, Tableau, numpy, pandas, scipy, math, pygad

### Demand Forecasting
**Summary:** Improved demand forecasting accuracy by 5-10% using statistical approaches, regression models, DL models, and logical reasoning.

**Requirement:** Existing forecasting methods in Kinaxis achieved only 35% accuracy, necessitating improvement.

**Solution:** Applied the developed solution across all business units, significantly improving accuracy and reducing variance from actuals.

**Approach:** Treated outliers, clustered time series, and used an ensemble of models for demand forecasting.

**Techniques:**
- Time series modeling
- Hierarchical clustering
- Outlier treatment

**Tools:** Python, AWS, Tableau, numpy, pandas, scipy, math, darts, scikit-learn, tsfresh

### Production Planning
**Summary:** Optimized manual production planning processes using ML-based optimizers to fully utilize available resources.

**Requirement:** Planners needed to optimize production plans considering inventory and arriving stock, aiming for optimal resource utilization.

**Solution:** Developed an ML-based optimization for production end dates, considering constraints like capacity, queue, priority, efficiency, and material availability.

**Approach:** Used MIP to identify manufacturable orders and a genetic algorithm to optimize production line utilization and order completion times.

**Techniques:**
- Mixed integer linear programming
- Genetic algorithm

**Tools:** Python, AWS, numpy, pandas, scipy, math, pygad

### Video and Audio Classification
**Summary:** Built a Flask API for reviewing videos uploaded to a mobile app, identifying and flagging foul language and images using ML.

**Requirement:** The mobile app required ML to detect foul images or language in uploaded videos.

**Solution:** Developed a solution to identify acceptable videos, with flagged content reviewed by an administrator.

**Approach:** Used deepspeech for audio-to-text conversion and OpenCV for video detection.

**Techniques:**
- OpenCV for computer vision
- Deepspeech for audio
- Spacy for NLP

**Tools:** Python, AWS, Tableau, numpy, pandas, scipy, math, OpenCV, tensorflow, deepspeech
