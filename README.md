# DS4002Project1
## Section 1: Software and Platforms
Software: We used Google Colab to create our Python scripts for cleaning, exploratory data analysis, and final analysis

Packages used: the PyPDF2 package was used to extract text from pdfs, the VADER package was used for sentiment analysis, the Natural Language Toolkit package was used for natural language processing, and the pandas package was used for data manipulation and analysis

Platform: All members used Macs

## Section 2: Map of Our Documentation

## Section 3: Instructions for Reproducing Our Results
1. Open a “DS 4002 - Project 1.ipynb” script in Google Colab (file found in SCRIPTS folder in Gtihub)
2. Import all 20 pilot show script pdfs into Google Colab (files found in DATA folder in Github)
3. Run “PART 1: Prepare data” in Python script
* Import any necessary packages (install PyPDF2 and SentimentIntensityAnalyzer)
* Extract text from PDF and save as a new Pandas data frame 
* Install and define VADER
4. Run “PART 2: EDA plot” in Python script
* For accessibility, save dataframe of produced sentiment scores as an .xlsx file (this has already been provided to you in the SCRIPTS folder and is called "all_sentiment_scores.xlsx"). This is the final data used for analysis.
* Run the three EDA plots
5. Run “PART 3: Multiple Linear Regression Analysis” in Python code
* Read in excel ("all_sentiment_scores.xlsx") and print df
* Run Multiple Linear Regression on data
* Run plot 4
