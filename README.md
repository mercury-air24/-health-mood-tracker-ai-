# Health-Mood-Tracker-AI (Building AI course project)

An AI system that analyzes and predicts mood changes based on diary entries. This is my project for an artificial intelligence course.

## Summary

A simple AI that analyzes short daily journal notes and predicts the user’s emotional state. The goal is to help people identify patterns in their mental health and prevent burnout before it sets in.

## Background

Mental health issues are increasingly common, especially 
among students and young professionals. Many people don't 
notice gradual changes in their mood until it's too late.

* Stress and burnout are hard to detect early
* People often ignore small signs of emotional decline
* There are a few simple, private tools for mood tracking

My personal motivation is that I believe small daily reflections can make a big difference in mental wellbeing.

## How is it used?

Every day, the user writes 2–3 sentences describing how they feel. The AI analyzes the text and classifies the mood as positive, neutral, or negative. Over time, it identifies patterns and warns the user if their mood remains negative for several days in a row.
The solution is useful for:
* Students during exam periods
* People going through stressful life changes
* Anyone who wants to understand their emotional patterns
  
## Data sources

The system will be trained on the GoEmotions dataset by 
Google, which contains 58,000 real text examples labeled 
with emotions such as joy, sadness, anger, and stress.
[GoEmotions by Google](https://research.google/blog/goemotions-a-dataset-for-fine-grained-emotion-classification/)

## AI methods

The system uses two main techniques:

| Method | How it works |
| ------ | ------------ |
| Bag of Words | Converts text into numbers by counting word frequencies |
| Naive Bayes | Calculates the probability of each mood based on the words used |

For example, the entry *"I feel sad and exhausted"* would 
be converted into word frequencies, and the Naive Bayes 
classifier would recognize that words like "sad" and 
"exhausted" appear most often in negative examples — 
and classify the mood accordingly.

## Challenges

* The system cannot replace professional mental health care
* Text alone may not capture full emotional context
* Privacy is critical — diary entries are very personal
* Cultural and language differences affect word meaning
* The model may misclassify sarcasm or irony

## What next?

The project could grow into a mobile app with:
* Multilingual support
* Voice input instead of typing
* Integration with a therapist platform
* Personalized suggestions based on mood patterns

To move forward I would need skills in:
* Natural language processing
* Mobile app development
* Data privacy and security

## Acknowledgments

* Building AI course by Reaktor and University of Helsinki
* [GoEmotions Dataset by Google](https://research.google/blog/goemotions-a-dataset-for-fine-grained-emotion-classification/)
* [Bag of Words model explanation](https://www.geeksforgeeks.org/nlp/bag-of-words-bow-model-in-nlp/)
* [Naive Bayes classifier documentation](https://scikit-learn.org/stable/modules/naive_bayes.html)
* [Mental health and AI research](https://ieeexplore.ieee.org/document/11063603)
