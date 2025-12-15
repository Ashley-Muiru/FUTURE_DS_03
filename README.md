Project Overview
The dataset was compiled from reliable travel platforms such as MakeMyTrip and Holidify, containing:
- City-level ratings (numeric scale: 4.0–4.9)
- Text-based feedback and descriptions
- Metadata on destinations (location, type, etc.)
The analysis combined numeric ratings with sentiment insights to provide a holistic view of traveler perceptions

Tools & Techniques
- Python for data cleaning and analysis
- NLP (Natural Language Processing) for text feedback exploration
- VADER Sentiment Analysis for sentiment classification
- Visualization libraries: Seaborn, Matplotlib for histograms, KDE plots, pie charts, bar charts, and wordcloud.

Key Insights
Top Rated Cities
- Agra (4.9) – Iconic attractions like the Taj Mahal
- Goa (4.9) – Beaches and nightlife
- Manali, Varanasi, Darjeeling (4.8) – Nature, spirituality, and scenic landscapes
Lowest Rated Cities
- Kodaikanal, Lakshadweep, Pahalgam (4.0) – Lower satisfaction, possibly due to accessibility or infrastructure
- Matheran (4.1) and Lucknow (4.1) – Slightly higher but still among the least favored.
Sentiment Distribution
- Positive: ~79%
- Neutral: ~20%
- Negative: ~1%
- Feedback is overwhelmingly positive, with minimal dissatisfaction.
Word Cloud Themes
- Frequent mentions of "city", "hill", "station", "valley", "beaches" highlight geography and scenic appeal.
- Positive descriptors like "beautiful", "popular", "known" emphasize admiration.
- Cultural landmarks such as "temple" suggest diverse attractions.
Average Rating by Sentiment
- Counterintuitively, negative sentiment reviews had the highest average rating (~4.6).
- Indicates a disconnect between textual sentiment and numeric ratings.
VADER Sentiment Analysis
- Positive: 63 entries (≈88%)
- Neutral: 5 entries (≈7%)
- Negative: 3 entries (≈4%)
- Confirms strong positivity bias in the dataset

Takeaways
- Indian tourist destinations are perceived very favorably, with ratings rarely dropping below 4.0.
- Combining numeric ratings with sentiment analysis provides deeper insights into traveler perceptions.
- Highlights standout destinations, uncovers subtle complaints, and identifies areas for improvement.
