# US Airline Social Media Presence Analysis

This project analyzes the social media presence of major US airlines by processing customer feedback from Twitter to identify sentiment trends and operational pain points.

## Key Findings & Insights

Based on the analysis of over 14,000 tweets, the following insights were identified regarding customer sentiment and airline performance:

### 1. Sentiment Distribution

**Dominant Negativity**: A significant majority of customer interactions are negative.

**Airline Specifics**: United, US Airways, and American Airlines receive the highest volume of negative feedback.

**Positive Outliers**: Virgin America and Southwest maintain a more balanced sentiment profile compared to their larger competitors.

### 2. Primary Pain Points

**Customer Service**: This is the leading cause of negative sentiment across almost all airlines.

**Operational Delays**: "Late Flight" and "Cancelled Flight" are the second and third most common reasons for customer complaints.

**Booking Frustrations**: After cancellations, issues with the booking process are a major driver of customer dissatisfaction.

### 3. Behavioral Trends
 
**Temporal Patterns**: Negative tweets peak during morning hours, suggesting higher customer stress or operational hurdles during early departures.
 
**Language Intensity**: The use of all-caps text in tweets is a strong indicator of high negative intensity and a higher probability of customer churn if not addressed.
 
**Sarcasm Detection**: High-intensity language is often used to convey sarcasm, which requires advanced NLP for accurate sentiment classification.

## Strategic Recommendations

The following evidence-based recommendations are proposed for airline stakeholders:

**Morning Staffing**: Increase the proportion of human customer service representatives (concierges) during morning hours to handle the surge in negative interactions.
 
**Targeted Troubleshooting**: Implement AI-driven chatbots specifically designed to handle FAQs and troubleshoot booking issues, which are a major source of "sadness" in sentiment.
 
**Operational Modeling**: Use data to model the causes and locations of flight cancellations to better adapt flight routes and refund policies to mitigate customer impact.
 
**Proactive Engagement**: Prioritize responding to high-intensity/all-caps tweets to prevent immediate customer loss.

## Features

**EDA**: Data cleaning and handling missing values in `negativereason` and `confidence` scores.
 
**Sentiment Analysis**: Advanced classification using NLTK and Transformer models.
 
**LLM Integration**: Utilizing OpenAI for nuanced text analysis and insight generation.
 
**Visualization**: Comparative analysis of sentiment and complaint types across airlines.

## Setup

1. **Dependencies**: Install via `pip install -r requirements.txt`.
2. 
**API Key**: Add your `OPENAI_API_KEY` to a `.env` file.


3. 
**Run**: Execute `airline_social_media_analysis.ipynb` to reproduce the findings.
