# anki_verb_conjugation_trainer
 
Simple verb conjugation deck for Anki which makes use of ChatGPT to generate its cards. Initially created to train Brazilian Portuguese verb conjugations but is easily changed to whatever language. Would like to automate the process using Python, but the openai api is locked behind a paywall which makes it useless for many. 

1. Simply copy the prompt to ChatGPT to create new sentences. Change to whatever suits your needs.

2. Copy the output to the UTF8 .csv database.

3. Import the database file to a new or existing deck, make sure you put both the "Tag" and the "Tenses" fields to column 4 under Field Mapping!

4. Train those conjugations!