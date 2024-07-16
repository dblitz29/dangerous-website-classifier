# 🌐 Website Classification AI Model

In this notebook, we implement the creation of an AI model used for classifying websites based on their content. The steps for creating this AI model are as follows:

## 🚀 Steps to Build the AI Model

1. **Data Collection** - Collecting the dataset as a reference for training data.
2. **Data Preparation** - Creating EDA (Explanatory Data Analysis).
3. **Feature Extraction** - Analyzing data patterns used.
4. **Model Training & Selection** - Comparing classification algorithms (Linear SVC (Support Vector Classifier), XGBoost, Decision Tree).
5. **Model Evaluation** - Evaluating the results of the chosen algorithm.
6. **Model Deployment** - Deploying the trained AI model.

## 🎮 Demo

The results of the AI training can be simulated by inputting a new website URL and obtaining its classification. Website content is extracted using web scraping technology.

### 📊 Data Information

In this AI model creation demo, we use a sample `website_classification` dataset from Kaggle, which contains 3 fields:
- `website_url` (string): URL of the website using the format https://
- `cleaned_website_url` (string): Content from the website obtained through web scraping
- `category` (string): Category of the website

### 📁 Website Categories

In this demo, we classify websites into the following 15 categories:
- 🌍 Travel
- 💬 Social Networking and Messaging
- 📰 News
- 📺 Streaming Services
- ⚽ Sports
- 📷 Photography
- 🏛️ Law and Government
- 🏋️ Health and Fitness
- 🎮 Games
- 🛒 E-Commerce
- 💬 Forums
- 🍲 Food
- 🎓 Education
- 💻 Computers and Technology
- 🏢 Business/Corporate, Adult
