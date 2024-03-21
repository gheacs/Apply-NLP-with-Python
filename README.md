# Analyze Taylor Swift Lyrics with Python

## Overview
On October 21, 2022, at midnight, Taylor Swift released her new album, Midnights. To uncover any potential hints dropped before its release, this project dives deep into the analysis of Taylor Swift's lyrics, focusing on her references to ‘midnight’. You will explore how frequently ‘midnight’ and related terms like day, night, and time are mentioned across her discography.

Further, the project employs sentiment analysis to examine the tone and vibe of Taylor Swift's lyrical content over her career, aiming to decipher her narrative inclination towards day or night. This offers a practical application of natural language processing (NLP) and text analysis skills on a real-world dataset.

## Dataset
The dataset, curated by Jan Llenzl Dagohoy and available on kaggle.com, encompasses the complete discography of Taylor Swift as of October 20, 2022, including the albums:

- Taylor Swift
- Fearless
- Speak Now
- Red
- 1989
- reputation
- Folklore
- evermore

## Installation and Setup
1. Ensure Python is installed on your system and follow these steps:
2. Clone this repository to your local machine.
3. Install the required Python libraries:
```bash
pip install pandas scikit-learn matplotlib numpy nltk
```

4. Download the necessary NLTK data:
```bash
import nltk
nltk.download('punkt')
nltk.download('vader_lexicon')
```

## Usage
Run the script to analyze the lyrics:
```bash
python analyze_lyrics.py
Replace analyze_lyrics.py with the actual script name if different.
```
## Resources
Apply Natural Language Processing with Python
Kaggle Dataset by Jan Llenzl Dagohoy

## License
Specify the license under which the project is released, such as MIT, GPL, Apache, etc.
