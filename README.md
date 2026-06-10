
# Sentiment & Topic Analysis of #Charlottesville Twitter Data

> Computational text analysis of Twitter reactions to the 2017 Unite the Right rally, examining public sentiment patterns and discourse framing around a domestic extremism event.

Presented at the **Grace Hopper Celebration (Women in Computing), Orlando 2019** and the **American Society of Criminology Annual Meeting, San Francisco 2019**.

---

## Overview

The August 2017 Unite the Right rally in Charlottesville, VA, was a major domestic extremism event that generated a large volume of public reaction on social media. This project applies NLP methods to a corpus of tweets using the `#Charlottesville` hashtag to:

- Measure **sentiment polarity** (positive, negative, neutral) of public responses over time
- Identify dominant **topics and discourse frames** using LDA topic modeling
- Examine how Twitter users engaged with, challenged, or amplified extremist narratives

This type of analysis has direct applications in **cyber threat intelligence** and **counter-extremism research** — understanding how extremist events propagate on social platforms informs both law enforcement response and platform moderation policy.

---

## Methods

| Step | Method | Library |
|---|---|---|
| Data collection | Twitter API (hashtag search) | `tweepy` |
| Preprocessing | Tokenization, stopword removal, normalization | `nltk`, `re` |
| Sentiment analysis | VADER (Valence Aware Dictionary and sEntiment Reasoner) | `vaderSentiment` |
| Topic modeling | Latent Dirichlet Allocation (LDA) | `gensim` |
| Visualization | Word clouds, sentiment over time, topic distributions | `matplotlib`, `wordcloud` |


<img width="1393" height="633" alt="image" src="https://github.com/user-attachments/assets/f489374c-4a0b-46a7-8504-931ce4920c99" />

---

## Key findings

- Sentiment shifted significantly in the hours following the car attack, with a marked increase in negative and grief/anger-coded tweets
- The NRC lexicon from Saif Mohammad and Peter Turney categorizes words in a binary fashion into categories of positive, negative, anger, anticipation, disgust, fear, joy, sadness, surprise, and trust. 
- LDA revealed distinct topic clusters: e.g., condemnation/solidarity, political framing, media coverage, counter-protest. The most common words are Trump, white, violence, nazis, vice, killed, hate, attack, racist, and were flagged as negative; surprisingly, protest and protesting are also considered negative terms. 

<img width="504" height="360" alt="image" src="https://github.com/user-attachments/assets/68ab2076-4fd8-4ede-acd2-7468f1f1828a" />

<img width="504" height="371" alt="image" src="https://github.com/user-attachments/assets/306212f1-cdfe-4bf2-adf5-363740008524" />

---


> ⚠️ **Data note:** Raw tweet data is not included in this repository in compliance with Twitter/X's developer terms of service, which prohibit redistribution of tweet content. The notebook documents the collection methodology. Contact [vguetler@gmail.com](mailto:vguetler@gmail.com) for information about replicating the dataset.

---

## Related work

This analysis is part of a broader research program on computational methods for violent extremism and cybercrime research:

- **Dissertation:** *Exploring Cyberterrorism, Topic Models & Social Networks of Jihadist Dark Web Forums* — West Virginia University, 2022
- **In progress:** *Cyber Threat Analysis from Hacker Forums Using Qualitative Computational Techniques*
- **In progress:** *Examining the Dark Web: Research Design and Methods of Textual Analysis for Detecting Online Extremism*

---

## Citation

```bibtex
@misc{guetler2019charlottesville,
  author    = {Guetler, Vivian F.},
  title     = {Sentiment and Topic Analysis of \#Charlottesville Twitter Data},
  year      = {2019},
  publisher = {GitHub},
  url       = {https://github.com/vguetler/charlottesvillenlp}
}
```

---

## Contact

**Vivian F. Guetler, PhD** — Computational Social Scientist & Cybersecurity Researcher  
[vguetler.github.io](https://vguetler.github.io) · [linkedin.com/in/vguetler](https://linkedin.com/in/vguetler) · vguetler@gmail.com
