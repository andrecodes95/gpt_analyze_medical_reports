# gpt_analyze_medical_reports
This is a brief exporation of using an LLM to analyze medical reports for a specific patient. 

## LLM
Open AI's GPT API was used for this project 

## Outline
- Prompt GPT for a database of example patients and store their information in a dictionary. 
- Prompt GPT to access a random patient from the database using an internal function. 
- Once patient information is retrieved, direct GPT to create medical documents for the user. 
- Prompt GPT to aummarize and analyze patient history.