# DS4002Project1
## Section 1: Software and Platforms
Software: We used Google Colab to create our Python scripts for cleaning, exploratory data analysis, and final analysis

Packages used: the PyPDF2 package was used to extract text from pdfs, the VADER package was used for sentiment analysis, the Natural Language Toolkit package was used for natural language processing, and the pandas package was used for data manipulation and analysis

Platform: All members used Macs

## Section 2: Map of Our Documentation
* DATA folder
  * Our sentiment scores final dataset
    * all_sentiment_scores.xlsx
  * 20 PDF files of scripts used in VADER analysis
    * BREAKING_BAD_-_PILOT.pdf
    * Baby_Reindeer_1x01.pdf
    * Barry_1x01.pdf
    * Cruel_Intentions_1x01_-_I.pdf
    * Dead_to_Me_1x01_-_Pilot.pdf
    * Dexter_-_Pilot.pdf
    * Game_of_Thrones_Pilot_Script_.pdf
    * Ghosted_1x01_-_Pilot.pdf
    * Girlboss_1x01_-_Pilot.pdf
    * Gossip_Girl_1x01_-Pilot.pdf
    * How_I_Met_Your_Mother_-_Pilot.pdf
    * Jane_the_Virgin_1x01_-_Pilot.pdf
    * Lost_1x01_-_Pilot.pdf
    * Mad_Men_-_Pilot.pdf
    * Mindhunter_1x01_-_Pilot.pdf
    * Peaky_Blinders.pdf
    * Station_Eleven_1x01_-_Wheel_of_Fire.pdf
    * Stranger_Things_-_Pilot.pdf
    * The_Office_U_S_Pilot.pdf
    * The_Sopranos_-_Pilot.pdf
    * the-good-place-101-everything-is-great-2017.pdf
* OUTPUT folder
  * Data dictionary, graphs from EDA, and final analysis visualization
    * Data Appendix.pdf
* SCRIPTS folder
  * Code to prepare scripts to be run through VADER, our exploratory data analysis, and final analysis
    * DS_4002_Project_1.ipynb
* LICENSE
* README.md
* REFERENCES file
  * References used in MI3

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
