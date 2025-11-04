**🧠 Student Feedback Analysis using NLP**



**📘 Overview**



This project analyzes student feedback collected through Google Forms after campus events.

It uses Python and basic Natural Language Processing (NLP) techniques to understand satisfaction levels and identify key areas for improvement.



By combining text-based feedback and numerical ratings, the analysis provides actionable insights to improve future event planning and engagement.





**🎯 Objectives**



* Analyze student satisfaction levels using textual and rating-based feedback



* Perform text preprocessing and sentiment analysis



* Visualize patterns, word clouds, and common themes in student responses



* Identify key improvement areas and positive highlights





**📂 Dataset**



* File Name: student\_feedback.csv



* Source: Google Forms (manually exported as CSV)



* **Typical Columns:**\
   ⦁	Timestamp – When the feedback was submitted\
   ⦁	Event Name – The event attended \
   ⦁	Rating – Numeric rating (e.g., 1–5)\
   ⦁	 Feedback – Text-based comments from students\



**🧰 Tools \& Libraries**



* Google Colab – For running the notebook



* Python 3.x



* Libraries Used:



* pandas – Data manipulation and analysis



* matplotlib, seaborn – Data visualization



* wordcloud – Generate word clouds



* nltk / textblob – Sentiment analysis



* re – Text preprocessing



⚙️ **Workflow**



1\. Load and clean the dataset



* Handle missing values
  
* Standardize text feedback
  

2\. Exploratory Data Analysis (EDA)



* Distribution of ratings



* Event-wise average satisfaction



* Frequency of positive/negative words



3\. Text Preprocessing



* Tokenization



* Stopword removal



* Lemmatization



4\. Sentiment Analysis



* Determine polarity (positive, negative, neutral)



* Correlate sentiment with numeric ratings



5\. Visualization



* Word clouds of common phrases



* Bar charts for sentiment vs rating



* Insights by event or category



**📊 Example Insights**



* Students rated technical workshops higher than cultural events



* Common positive words: “helpful”, “interactive”, “well-organized”



* Improvement areas: “timing”, “venue”, “duration”



**🚀 How to Run**



1. Open the project in Google Colab or any Python IDE.
   
2. Upload the student\_feedback.csv file.
   
3. Install required libraries:\
   pip install pandas matplotlib seaborn wordcloud nltk textblob
   
5. Run all cells to generate the visualizations and insights.



**🧩 Project Structure**


📁 Student_Feedback_Analysis/\
│\
├── feedback_analysis.ipynb\
├── README.md\
└── requirements.txt




**📈 Future Enhancements**



* Deploy as a Streamlit dashboard for interactive insights



* Integrate machine learning models for deeper sentiment scoring



* Automate data collection directly from Google Forms API



**✍️ Author**



Developed by Manoj Shanigaram



📧 For collaboration or suggestions: your- manojshanigaram143@email.com

