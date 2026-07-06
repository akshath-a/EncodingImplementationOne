# EncodingImplementationOne
# Flipkart Review Sentiment & Feature Analysis

## Project Overview
This project provides a comprehensive end-to-end NLP (Natural Language Processing) pipeline designed to scrape, clean, and extract actionable insights from Flipkart product reviews. By evaluating user sentiment and text structures, the pipeline surfaces critical product strengths and engineering pain points.

---

## Key Features & Insights

* **High-Efficiency Text Preprocessing:** Implements a 5-step NLP pipeline (lowercasing, punctuation removal, tokenization, stopword filtering, and lemmatization) that compresses text down to a clean semantic footprint.
* **Statistical Sentiment Profiling:** Segregates reviews into Positive, Neutral, and Negative classes, tracking core metrics like average rating and distribution.
* **Feature Extraction (TF vs. TF-IDF):**
  * Uses term frequency to identify highly discussed features (*Quality*, *Camera*, *Performance*, *Battery*).
  * Leverages TF-IDF vectorization to isolate high-importance diagnostic terms that signal critical user complaints like *drain* and *charge*.

---
