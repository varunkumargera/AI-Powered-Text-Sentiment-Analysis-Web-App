# AI-Powered-Text-Sentiment-Analysis-Web-App
# Sentiment Analysis Web App

A web-based sentiment analysis application that allows users to analyze the sentiment of text input in various formats and provides visualizations of the results. The application supports multiple features including sentiment classification, sentiment over time, and sentiment visualization.

## Features
1. **Sentiment with Confidence**: Classifies the sentiment of the text (Positive, Negative, or Neutral) with the confidence score.
2. **Sentiment with Emoji**: Adds an emoji to the sentiment classification based on the result (😊 for Positive, 😢 for Negative, 😐 for Neutral).
3. **Sentiment Multilingual**: Supports sentiment analysis for text in different languages.
4. **Sentiment Over Time**: Analyzes the sentiment of each line in a paragraph and provides a count of positive, negative, and neutral sentiments.
5. **Sentiment Visualization**: Provides a bar chart visualization of sentiment distribution (Positive, Negative, Neutral) for the given input.
6. **Sentiment File Upload**: Allows users to upload a `.txt` file for sentiment analysis.

## Tech Stack
- **Gradio**: For building the interactive user interface.
- **Hugging Face Transformers**: For leveraging pre-trained models for sentiment classification.
- **Matplotlib**: For creating sentiment distribution visualizations.

## Requirements
To run this app locally, you'll need to install the following Python libraries:
- `gradio`
- `transformers`
- `torch`
- `matplotlib`

You can install these dependencies using the following command:
```bash
pip install -r requirements.txt
