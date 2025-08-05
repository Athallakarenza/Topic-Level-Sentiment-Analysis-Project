# [NLP Project] Topic-Level-Sentiment-Analysis-Project

Topic-level sentiment analysis on TIX ID reviews using BERT (94.3% accuracy) to classify sentiment, extract key topics, and generate insights. Helps identify user pain points and strengths to support product improvement.

### Projects Objective
Create a BERT model to perform sentiment analysis, model the topics, and evaluate the model using accuracy, classification report, F1-score, recall, and precision. Apply the sentiment model to each topic to determine topic-wise sentiment and provide insights for decision makers.

### Methods Used
- Deep Learning  
- Sentiment Analysis  
- Topic Modelling  

### Language
- Python  

### Module/Library
- pandas  
- numpy  
- matplotlib  
- seaborn  
- torch  
- re  
- transformers  
- bertopic  
- nltk  
- scikit-learn  

### Step By Step
1. **Dataset Analysis**
2. **Cleaning Data**
   - Checking missing values  
   - Checking duplicate data  
3. **Data Visualization**
4. **Text Pre-Processing**
   - Text Cleaning  
   - Label Encoding  
   - Tokenization  
5. **Tuning Hyperparameters**
6. **Build Model**
   - Sentiment Analysis Model  
   - Topic Modelling Analysis  
7. **Model Evaluation**
   - Model achieved overall accuracy of **94.3%**
   - Positive class: Precision **96%**, Recall **98%**
   - Non-positive class: Precision **83%**, Recall **72%**
   - Extracted **9 main topics** from user reviews  
8. **Insight Analysis**

Based on the Topic-Level Sentiment Analysis, several key issues were consistently highlighted by users. The most prominent complaints include technical problems and login access issues (87.1% non-positive sentiment), overly frequent app updates (87.9%), and disappointment with promotional offers perceived as misleading (95.2%). These recurring themes indicate areas that significantly impact user trust and satisfaction. Addressing these issues could lead to improved user experience, reduced churn, and stronger customer loyalty for the TIX ID platform.

