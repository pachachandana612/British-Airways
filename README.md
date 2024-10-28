# British Airways Virtual Internship Project

This repository contains my work on the British Airways virtual internship, completed through Forage. The project focuses on understanding customer reviews and predicting customer booking behavior, leveraging data scraping, text analysis, and machine learning.

## Project Overview

### Task 1: Customer Review Sentiment Analysis
In Task 1, the goal was to scrape, clean, and analyze customer reviews from the Skytrax website. This task involved text processing, sentiment analysis, and summarizing insights in a presentation slide.

#### Steps:
1. **Data Scraping**: Used Python and Jupyter Notebook to collect 1,000 customer reviews focused on British Airways' services.
2. **Data Cleaning**: Processed raw text data to prepare it for analysis, removing unnecessary characters and formatting.
3. **Sentiment Analysis**: Performed sentiment analysis, categorizing reviews into Positive, Negative, and Neutral.
4. **Data Visualization**: Created visualizations such as word clouds and sentiment distributions to summarize key insights.
5. **Presentation**: Key findings were summarized in a PowerPoint slide, showing sentiment distribution as:
   - Positive Reviews: 507
   - Negative Reviews: 393
   - Neutral Reviews: 100

#### Files for Task 1:
- `BritishAirways Task1.ipynb`: Jupyter Notebook with data scraping, cleaning, and sentiment analysis code.
- `Presentation - Task 1.pptx`: Summary slide with visualizations and insights.

### Task 2: Predicting Customer Buying Behavior
In Task 2, the objective was to predict customer bookings using machine learning. This involved feature engineering, model training, and performance evaluation.

#### Steps:
1. **Data Exploration**: Explored and preprocessed the `customer_booking.csv` dataset, analyzing key features.
2. **Feature Engineering**: Created new features based on existing data to improve model accuracy.
3. **Model Training**: Trained a Random Forest Classifier and Logistic Regression model to predict the likelihood of booking.
4. **Model Evaluation**: Evaluated model performance using cross-validation, accuracy, and feature importance metrics.
5. **Presentation**: Summarized model findings in a PowerPoint slide, highlighting the most correlated features:
   - Wants Extra Baggage
   - Wants Preferred Seat
   - Wants In-Flight Meals
   - Number of Passengers
   - Flight Hour

#### Files for Task 2:
- `Task2Code.ipynb`: Jupyter Notebook for data preparation, feature engineering, model training, and evaluation.
- `customer_booking.csv`: Dataset containing customer booking data.
- `Task2_Presentation.pptx`: Presentation slide summarizing model results and insights.

## Key Findings
- **Task 1**: Sentiment analysis showed a majority of positive reviews, with some negative feedback, offering insights into customer satisfaction trends.
- **Task 2**: Random Forest Classifier outperformed Logistic Regression in predicting booking likelihood. Key features related to extra services and flight details influenced booking behavior.

## Tools and Technologies
- **Python**: Data scraping, cleaning, analysis, and model training
- **Libraries**: Pandas, BeautifulSoup, Scikit-learn, Matplotlib, and Seaborn
- **PowerPoint**: Presentation slides summarizing findings for each task
- **Jupyter Notebook**: Main environment for code execution and analysis

## Conclusion
This project provided hands-on experience in web scraping, text analysis, feature engineering, and machine learning model development. The insights gathered here can help British Airways optimize customer engagement strategies and improve booking prediction accuracy.

---

For more details on each task, please refer to the respective files and presentations in this repository.
