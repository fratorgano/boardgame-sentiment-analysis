# What do you like in boardgames
This is the repo for the project for the Natural Language Processing course for the master's degree at UNIMI

The goal of this project is to analyze the reviews/comment left on various board games available on BoardGameGeek and extract some information regarding the sentiment towards some aspects of the games that could be used for various other tasks.

This project focused specifically on:
* Analyzing a predefined list of aspects and obtain a score for how good or bad each is
* Extract aspects directly from the reviews, analyze if the aspect is positive or negative and generate a list of the best and worst aspects for each game considered.

This was done using two models based on the Local Context Mechanism that is finetuned for the Aspect Polarity Classification task to give more importante to closer tokens that should allow for improved performance in that specific task.
