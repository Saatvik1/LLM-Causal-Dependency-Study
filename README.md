# LLM-Causal-Dependency-Study
A study on plan completion, specifically studying if LLMs such as Gemini's Flash model and DistilBERT understand the underlying aspects of plans such as temporal and state dependencies of entities in plans.

# File Explanations
* 1_0_FinalProjNLP_DS -> Gemini Workflow and Testing
* 1_0_FinalProjNLP_DS_2 -> DistilBERT Workflow and Testing
* Modified_Test/Train -> Modified CaT-Bench plans
* Gemini_Prediction_Results -> Raw data of Gemini's test results
* prompt.txt -> Text file of prompts used in testing (Idea 2 and Idea 3)

# Modifications 
* cat-bench within python dataframes, using pandas, did not save to the files. Saved the changes to csv's in between like rds_train rds_test

# Commands
* Used Gemini API functions to test model (generate_content())
* Used Google AI Studio to fine-tune Gemini Flash Model

# Link to dataset (CAT-Bench) :
https://drive.google.com/file/d/1UjFwv-BKU0Q7CRAFFEFsMX2AUtoT5Wud/view?usp=sharing 

# Software Requirements 
* datasets==3.0.0
* transformers==4.31.0
* matplotlib==3.7.1
* git-lfs
* google-generativeai
* jsonlines
* python-dotenv
* sklearn
* scipy
