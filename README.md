# NLP Analysis of Hydra Marketplace Reviews

This project explores how sentiment is expressed in user reviews from the Hydra marketplace using exploratory NLP methods. The goal is not prediction, but understanding linguistic patterns in a domain-specific and informal communication environment.

The dataset contains anonymized Russian-language reviews labeled as positive or negative. Due to the presence of slang, shorthand expressions, and marketplace-specific terminology, the analysis focuses on interpretation and context-aware text processing rather than standard sentiment classification.

## Project Goals

- analyze how positive and negative experiences are communicated in reviews,
- identify distinctive vocabulary and phrase patterns,
- explore thematic structures in the corpus,
- examine domain-specific language and slang usage.

## Methods

The analysis combines several complementary approaches:

- text preprocessing and vocabulary exploration,
- TF–IDF analysis to identify sentiment-specific words,
- bigram analysis to capture phrase-level patterns,
- topic modeling (LDA) to identify recurring themes,
- log-odds and PMI analysis to detect domain-specific expressions.

## Key Findings

Results show that sentiment in this dataset is primarily expressed through descriptions of outcomes and processes rather than emotional language.

- Negative reviews typically describe problems, disputes, or attempts to resolve failed transactions.
- Positive reviews are shorter and function as confirmation, endorsement, or recommendation.
- Phrase-level analysis reveals recurring communication patterns that act as informal community conventions.

Overall, the project demonstrates how NLP methods can be used to understand communication structures in non-standard online environments where sentiment is embedded in transactional narratives rather than explicit emotional expression.

## Output

The full analysis is available in the HTML report included in this repository.
**[Open full analysis report](https://rin4ek.github.io/marketplace-review-text-analysis/)**
