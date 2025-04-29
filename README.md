# LSTM-Experiments
Experiment 5.1: Time Series Forecasting with LSTM
Dataset
Daily Minimum Temperatures in Melbourne
Kaggle Dataset Link

Alternative Datasets (Kaggle Links):
COVID-19 Daily Cases

Airline Passengers

Electricity Consumption

Tesla Stock Prices

Seattle Weather Data

Sunspot Activity

PJM Energy Consumption

Bitcoin Price

Walmart Sales

Experiment 5.2: Sequence Text Prediction with LSTM
Dataset
Shakespeare Text
Kaggle Dataset Link

Alternative Datasets (Kaggle Links):
Pride and Prejudice

Harry Potter Books

Movie Dialogues

Reddit Jokes

Taylor Swift Lyrics

Wikipedia Articles

News Headlines

Quora Questions

English Proverbs

Experiment 5.3: Sequence Text Classification with LSTM
Dataset
IMDb Movie Reviews
Kaggle Dataset Link

Alternative Datasets (Kaggle Links):
SMS Spam Collection

Amazon Product Reviews

Yelp Reviews

Twitter Sentiment

Toxic Comments

Sarcasm Detection

BBC News

Disaster Tweets

Fake News

Repository Structure
LSTM-Experiments/
│
├── Experiment_5.1_Time_Series_Forecasting/
│   ├── temperature_forecasting.ipynb
│   ├── data/
│   │   └── daily-min-temperatures.csv
│   ├── outputs/
│   │   ├── predictions.png
│   │   └── metrics.txt
│   └── README.md
│
├── Experiment_5.2_Text_Generation/
│   ├── text_generation.ipynb
│   ├── data/
│   │   └── shakespeare.txt
│   ├── outputs/
│   │   ├── generated_text.txt
│   │   └── training_curves.png
│   └── README.md
│
├── Experiment_5.3_Text_Classification/
│   ├── sentiment_analysis.ipynb
│   ├── data/
│   │   └── imdb_reviews.csv
│   ├── outputs/
│   │   ├── confusion_matrix.png
│   │   └── classification_report.txt
│   └── README.md
│
├── requirements.txt
└── README.md (this file)
Setup Instructions
Clone the repository:

bash
git clone https://github.com/Rushii2002-lab/LSTM-Experiments.git
cd LSTM-Experiments
Install dependencies:

bash
pip install -r requirements.txt
Download datasets (or use provided sample data):

For each experiment, download the dataset from the Kaggle links above

Place in the respective data/ directory

Running the Experiments
Each experiment has its own Jupyter notebook with detailed instructions:

Time Series Forecasting: Experiment_5.1_Time_Series_Forecasting/temperature_forecasting.ipynb

Text Generation: Experiment_5.2_Text_Generation/text_generation.ipynb

Text Classification: Experiment_5.3_Text_Classification/sentiment_analysis.ipynb

Results Summary
Experiment	Best Model	Key Metric	Value
5.1	LSTM with Dropout	Test RMSE	1.87°C
5.2	2-Layer LSTM	Training Accuracy	72.4%
5.3	Bidirectional LSTM	Test Accuracy	87.6%
License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For questions or suggestions, please contact:
Rushikesh Sawant
ty btech 
MIT AOE Pune

Declaration
I, Rushikesh Sawant, confirm that the work submitted in this assignment is my own and has been completed following academic integrity guidelines. The code is uploaded on my GitHub repository account:

GitHub Repository Link: https://github.com/Rushii2002-lab/LSTM-Experiments.git

Signature: Rushikesh Sawant
Date: 27-04-2025
