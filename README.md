# twitter-sentiment
data analysis of tweets in a novice way includes:
    1. textual cleaning and formatting.
    2. text feature extraction
    3. machine learning model template for novice.
    4. design patterns like pipeline, lambda implementations.

This dataset aggregates tweets pertaining to climate change collected 
between Apr 27, 2015 and Feb 21, 2018. In total, 43943 tweets were annotated. 
Each tweet is labelled independently by 3 reviewers. 
This dataset only contains tweets that all 3 reviewers agreed on (the rest were discarded).

Each tweet is labelled as one of the following classes:

    2(News): the tweet links to factual news about climate change
    1(Pro): the tweet supports the belief of man-made climate change
    0(Neutral: the tweet neither supports nor refutes the belief of man-made climate change
    -1(Anti): the tweet does not believe in man-made climate change
