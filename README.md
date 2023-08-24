# openai-costs-tracking
Python script to run openai costs extraction by user, model, day.

The script has a time sleeper due to API request limit of 5 requests per minute.

After running the script will save a json file with the current extraction + the past extraction.

New runs will start from the last date you have extracted the costs (no need to run the entire history everytime).
