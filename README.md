📊 Sentiment Analysis on Product Reviews
📝 Project Description

This project performs Sentiment Analysis on customer product reviews from the Amazon Fine Food Reviews dataset.
Using Natural Language Processing (NLP) techniques and the TextBlob library, the system automatically classifies reviews into:

😊 Positive
😐 Neutral
😞 Negative

The project also generates visual insights using charts and summarizes customer feedback trends.

🎯 Objectives
Analyze customer reviews automatically
Identify customer satisfaction levels
Classify sentiments using polarity scores
Visualize review sentiment distribution
Generate business insights from customer feedback
📂 Dataset

Dataset Source:
Amazon Fine Food Reviews Dataset

Dataset Used
File: Reviews.csv
Rows Used: First 5,000 rows
Important Columns:
Text → Customer Review
Score → Product Rating
🛠️ Technologies Used
Technology	Purpose
Python	Programming Language
Jupyter Notebook	Development Environment
Pandas	Data Handling
TextBlob	Sentiment Analysis
Matplotlib	Visualization
Seaborn	Data Visualization
✅ Features
Data loading and preprocessing
Removal of null and duplicate reviews
Sentiment polarity calculation
Sentiment classification
Data visualization using charts
Insight generation from reviews
⚙️ Installation
1️⃣ Clone the Repository
git clone https://github.com/your-username/sentiment-analysis-product-reviews.git
2️⃣ Navigate to Project Folder
cd sentiment-analysis-product-reviews
3️⃣ Install Required Libraries
pip install pandas textblob matplotlib seaborn
4️⃣ Run Jupyter Notebook
jupyter notebook

Open:

analysis.ipynb
📊 Sentiment Classification Logic
if polarity > 0:
    sentiment = "Positive"
elif polarity < 0:
    sentiment = "Negative"
else:
    sentiment = "Neutral"
📈 Visualizations Included
Bar Chart of Sentiment Counts
Pie Chart of Sentiment Distribution
Custom Analysis Chart
Rating vs Sentiment Comparison
OR Most Common Negative Words
📁 Project Structure
SentimentAnalysis/
│
├── analysis.ipynb
├── Reviews.csv
├── README.md
├── summary.pdf
│
├── charts/
│   ├── sentiment_bar_chart.png
│   ├── sentiment_pie_chart.png
│   └── custom_chart.png
💡 Key Insights
Majority of reviews are generally positive
Negative reviews commonly mention:
product quality
packaging issues
delayed delivery
Sentiment analysis helps businesses improve customer experience
🚀 Future Improvements
Use advanced NLP models like BERT
Deploy as a web application
Add real-time sentiment prediction
Create an interactive dashboard
