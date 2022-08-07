# theneuralbot

This is a Python Twitter bot that focuses more on analysis and replying to mentioned users. Note: this is intented to run every minute with crontab, so depending on one's Twitter API limits limits and where one hosts this code, the count in the mentions timeline may be allowed to vary. Additionally, common words are eliminated in the script itself, and you will see a list containing these words in the script.  

To eliminate repetitions in neuralmentions, a dot.txt file is created to log the Tweet IDs of the mentions, and the script will scan this file to avoid duplications.

When logging top words in neuralanalysis, the results will show up in a list.  
