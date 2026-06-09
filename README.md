
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

---

## Key findings

- Sentiment shifted significantly in the hours following the car attack, with a marked increase in negative and grief/anger-coded tweets
- LDA revealed distinct topic clusters: [**update with your actual topics — e.g., condemnation/solidarity, political framing, media coverage, counter-protest**]
- [Add 1–2 more findings from your actual analysis]

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
