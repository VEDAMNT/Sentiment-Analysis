## TextBlob Sentiment Analysis

This Python script utilizes TextBlob for basic sentiment analysis of user-provided text.

### Function

The `sentiment_analysis(text)` function takes a text string as input and classifies its sentiment as positive, negative, or neutral. It achieves this by:

1. Creating a TextBlob object from the text.
2. Extracting the polarity score, a value between -1 (most negative) and 1 (most positive).
3. Classifying the sentiment based on the polarity score.

**Note:** The script includes a commented-out section demonstrating an alternative approach using the `sentiment` property of TextBlob.

### Usage

1. Clone or download the repository.
2. Install required libraries (`textblob`): `pip install textblob`
3. Run the script (e.g., `python sentiment_analysis.py`).
4. Enter a review or sentence when prompted.
5. The script will analyze the sentiment and print the result (positive, negative, or neutral).

###  Example

Input: "This movie was fantastic!"

Output: "The sentiment of the text is: positive"

### Contribution

Feel free to contribute by forking the repository and submitting pull requests.

