# Exploring Lovecraft’s Fiction: A Data-Driven Approach

This project analyzes the word count and sentiment of **H.P. Lovecraft's** stories to explore potential correlations between story length and emotional tone.

**Presentation**: [View the presentation](https://docs.google.com/presentation/d/1TanvkWfYJqDfhS7B0h_9Xspy1hAFEAk_7BMsD1zeS9E/edit?usp=sharing)

## Project Overview

- **Word Count Distribution**: Analyzes the typical length of Lovecraft's stories and identifies outliers.
- **Sentiment Analysis**: Examines the emotional tone of the stories, determining whether they lean positive, neutral, or negative.
- **Correlation Analysis**: Investigates any relationships between the length of a story and its sentiment score.

## Data

- **Lovecraft's Fictional Works**: Scraped all fictional texts by H.P. Lovecraft from [hplovecraft.com](http://hplovecraft.com).
- **Word Count**: Total number of words in the story.
- **Sentiment Score**: A value indicating the emotional tone (ranging from negative to positive).

## Analysis Approach

1. **Word Count Distribution**: Visualized using a histogram to display the spread of word counts, with an indication of the average.
2. **Sentiment Score Distribution**: Visualized using Kernel Density Estimation (KDE) to illustrate sentiment across the stories.
3. **Sentiment vs. Word Count**: A scatter plot to explore the potential relationship between story length and sentiment.

## Key Findings

- **Word Count**: Lovecraft's stories vary significantly in length, with some notable outliers.
- **Sentiment**: Most stories have a **neutral to slightly negative** sentiment.
- **Correlation**: There is no significant correlation between story length and sentiment.

## Future Improvements

- **Deep Learning for Sentiment**: Implement deep learning models for more accurate sentiment analysis.
- **Project Link**: This project will serve as a new "remastered" basis for my previous project: [Lovecraftian Entity Generator: Unveiling Cosmic Horrors](https://github.com/JayEm65/lovecraftian_entity_generator).
