# Online-Music-Reviews-System

An AI-powered music review chatbot built using **Python** and **Google Gemini AI** that analyzes music reviews, generates summaries, performs sentiment analysis, and recommends similar artists. This project demonstrates the integration of Generative AI and NLP techniques to deliver intelligent music insights through an interactive chatbot interface.

## Features

- Generate concise music review summaries
- Perform sentiment analysis (Positive, Neutral, Negative)
- Recommend similar artists based on review content
- Interactive chatbot experience
- Powered by Google Gemini API

## Tech Stack

- Python
- Google Gemini API
- Jupyter Notebook
- Natural Language Processing (NLP)

## Project Structure

```text
Online-Music-Review-System/
│
├── Online Music Review System.ipynb
├── README.md
└── requirements.txt
```

## Installation

1. Clone the repository

```bash
git clone https://github.com/your-username/Online-Music-Review-System.git
cd Online-Music-Review-System
```

2. Install dependencies

```bash
pip install google-generativeai requests
```

3. Configure your Gemini API key

```python
import google.generativeai as genai

genai.configure(api_key="YOUR_API_KEY")
```

## Usage

Run the Jupyter Notebook and enter an artist or album name.

Example:

```text
Input: Taylor Swift

Output:
✔ Summary of the review
✔ Sentiment Analysis: Positive
✔ Similar Artist Recommendations
```

## Learning Outcomes

- Generative AI Integration
- Prompt Engineering
- API Integration
- Sentiment Analysis
- NLP Applications
- Python Development

## Future Enhancements

- Spotify API Integration
- Real-time Review Fetching
- Genre Classification
- Streamlit/Flask Web Application
- Personalized Recommendations

## Author

**Durgesh Mitha**


---

⭐ If you found this project helpful, consider giving it a star!
