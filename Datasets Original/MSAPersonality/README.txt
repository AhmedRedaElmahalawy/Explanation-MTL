***********************************MSAPersonality Dataset***********************************

Title: MSAPersonality Dataset: A Modern Standard Arabic Resource for Personality Recognition
Version: 1.0
Creation Date: 2021
Release Date: 2024
_______________________________________________________________________________________________

1. General Information
----------------------
- Description:
The MSAPersonality Dataset contains 267 texts written in Modern Standard Arabic, annotated with the Big Five personality traits (Openness, Conscientiousness, Extraversion, Agreeableness, and Neuroticism).
This dataset was designed for Automatic Personality Recognition (APR), a computational task that infers personality traits from textual data.

- Purpose:
To provide a benchmark resource for researchers working on personality prediction using Arabic text.

- Creators:
Khaoula Chraibi, Ilham Chaker, And Azeddine Zahi
Department of Computer Science, Faculty of Sciences and Technology, University of Sidi Mohamed Ben Abdellah, Fez, Morocco

- Associated Publication:
This dataset is described in detail in the journal article:
Chraibi, K., Chaker, I., Dhassi, Y., & Zahi, A. (2024). MSAPersonality: a modern standard Arabic dataset for personality recognition. International Journal of Electrical & Computer Engineering (2088-8708), 14(4).
Please refer to the paper for methodological details and validation.
_______________________________________________________________________________________________

2. Dataset Contents
-------------------
- File Structure:

MSAPersonality_V1_267.csv: Contains the dataset (267 rows, 11 columns).
README.txt: This file.

- Data Format:
The dataset is provided as a CSV file with the following columns:

text: The text entry in Modern Standard Arabic.

sAGR: agreeableness score.
sCON: conscientiousness score.
sEXT: extraversion score.
sNEU: neuroticism score.
sOPN: openness score.

cAGR: agreeableness class (1:High/Yes - 0:Low/No).
cCON: conscientiousness class (1:High/Yes - 0:Low/No).
cEXT: extraversion class (1:High/Yes - 0:Low/No).
cNEU: neuroticism class (1:High/Yes - 0:Low/No).
cOPN: openness class (1:High/Yes - 0:Low/No).
_______________________________________________________________________________________________

3. Usage Instructions
---------------------
- License:
This dataset is licensed under the CC BY-NC-SA 4.0.
You are free to use, share, and adapt this dataset for non-commercial purposes, provided you attribute the authors and share derived works under the same license.

- Citation:
If you use this dataset, please cite:

Dataset:
Chraibi, Khaoula; Chaker, Ilham; Zahi, Azeddine (2024), “MSAPersonality Dataset: A Modern Standard Arabic Resource for Personality Recognition”, Mendeley Data, V1, doi: 10.17632/k9b68trxj5.1.

Paper:
Chraibi, K., Chaker, I., Dhassi, Y., & Zahi, A. (2024). MSAPersonality: a modern standard Arabic dataset for personality recognition. International Journal of Electrical & Computer Engineering (2088-8708), 14(4).

- How to Use:
Load MSAPersonality_V1_267.csv using Python, R, or any preferred software. 
_______________________________________________________________________________________________

5. Contact Information
----------------------
For questions, issues, or collaboration inquiries, contact:
Khaoula Chraibi
Email: khaoula.chraibi@usmba.ac.ma
Affiliation: University of Sidi Mohamed Ben Abdellah, Fez, Morocco


