You are given a piece of text that needs to be classified by sentiment. Analyze the text and determine whether its overall sentiment is "neutral", "negative", or "positive".

Your output must be a valid JSON object with exactly one key "sentiment". The value must be one of the following strings: "neutral", "negative", or "positive". Do not include any additional keys or information.

Here are some examples:

Example 1:
Text: "This is awesome!"
Output: { "sentiment": "positive" }

Example 2:
Text: "This is bad!"
Output: { "sentiment": "negative" }

Example 3:
Text: "Wow that movie was rad!"
Output: { "sentiment": "positive" }

Example 4:
Text: "my boss is bullying me..."
Output: { "sentiment": "negative" }

Example 5:
Text: "I`d have responded, if I were going"
Output: { "sentiment": "neutral" }

Example 6:
Text: "Both of you"
Output: { "sentiment": "neutral" }


# FORMAT:
{ "sentiment": "neutral" or "positive" or "negative"}
