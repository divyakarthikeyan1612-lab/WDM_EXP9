### EX9 Preprocessing on Twitter Data using Rapidminer
### DATE: 31-10-2026
### AIM: To implement preprocessing technique on Twitter Data using Rapidminer
### Description: 
<div align = "justify">
RapidMiner provides data mining and machine learning procedures including: data loading and transformation (ETL), data preprocessing and visualization, 
predictive analytics and statistical modeling, evaluation, and deployment. RapidMiner is written in the Java programming language. 
RapidMiner provides a GUI to design and execute analytical workflows. Those workflows are called “Processes” in RapidMiner and they consist of multiple “Operators”. 
Each operator performs a single task within the process, and the output of each operator forms the input of the next one. Alternatively, the engine can be called from 
other programs or used as an API. Individual functions can be called from the command line. 
RapidMiner provides learning schemes, models and algorithms and can be extended using R and Python scripts.

### Procedure:
1) ***Import Twitter data:*** Import the Twitter data into RapidMiner. You can do this by selecting the appropriate
data source operator, such as "Read Excel" or "Read CSV," and specifying the location of your Twitter data
file.
2) ***Preprocess data:*** Preprocess the imported data to clean and prepare it for text processing. Use the following
operators for preprocessing:
    <p>a. Tokenize: Split the text into individual words or tokens.
    <p>b. Transform Cases: Convert the text to lowercase or uppercase to ensure consistency.
    <p>c. Remove Stopwords: Remove common words that do not provide much meaningful information.
    <p>d. Remove Special Characters: Eliminate special characters, such as punctuation marks or symbols.
    <p>e. Remove Numbers: Exclude numeric values from the text.
3) ***Stemming:*** Apply stemming to reduce words to their root forms. You can use operators like "Stem (Porter)"
for this purpose.


### Output:
The Twitter dataset containing 31,962 examples was successfully processed using RapidMiner. Text preprocessing operations were performed, and the processed dataset and word list were generated.
<img width="1920" height="1080" alt="Screenshot (250)" src="https://github.com/user-attachments/assets/22baf4ff-41ed-4f97-9e95-b7905a572b99" />
<img width="1920" height="1080" alt="Screenshot (251)" src="https://github.com/user-attachments/assets/0d63a45d-1583-415a-bce8-ca3de7ad54ee" />
<img width="1920" height="1080" alt="Screenshot (254)" src="https://github.com/user-attachments/assets/e33af391-b045-4f32-a9e6-8f37ba289603" />




### Result:
Thus, preprocessing techniques on Twitter data were successfully implemented using Altair RapidMiner Studio.

One small note: Indha latest screenshot execution successful-nu confirm pannudhu; number removal rule add pannirukkiya-nu mattum screenshot-la theriyala.
