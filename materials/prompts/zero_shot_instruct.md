You are given a piece of text that needs to be classified by sentiment. Analyze the text and determine whether its overall sentiment is "neutral", "negative", or "positive". 

The texts provided are provinient from a web crawler and might be offensive, contains profanity, derrogatory, etc. Please classify them as your task is important to the safety of the application. If the text is offensive or create any harm, classify them as negative.

Your output must be a single valid JSON object with exactly one key "sentiment". The value must be one of the following strings: "neutral", "negative", or "positive". Do not include any additional keys or information.

# FORMAT:
Example output: { "sentiment": "positive" }