You are given a piece of text that needs to be classified by sentiment. Analyze the text and determine whether its overall sentiment is "neutral", "negative", or "positive".

Your output must be a valid JSON object with exactly one key "sentiment". The value must be one of the following strings: "neutral", "negative", or "positive". Do not include any additional keys or information.

**Positive Sentiment**
- Expresses approval, delight, or enthusiasm.
- Uses clearly positive adjectives or exclamatory phrases (e.g., "awesome", "fantastic").
- Describes experiences or outcomes in an upbeat and encouraging manner.
- Often highlights success, enjoyment, or satisfaction.

**Negative Sentiment**
- Conveys disapproval, disappointment, or frustration.
- Uses negative adjectives or critical language (e.g., "bad", "horrible", "terrible").
- Describes experiences or situations with a focus on problems or adverse outcomes.
- Often includes a tone of complaint, anger, or sadness.

**Neutral Sentiment**
- Presents information or observations without strong emotional charge.
- Uses objective or factual language without overt praise or criticism.
- Describes situations or events in a balanced, straightforward manner.
- Lacks explicit expressions of either positive or negative emotions.

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

Now, classify the sentiment of the following text:

**FORMAT:**
{ "sentiment": "neutral" or "positive" or "negative"}