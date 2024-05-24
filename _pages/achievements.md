---
layout: archive
title: "Achievements"
permalink: /achievements/
author_profile: true
---

## Organizer of VITD shared task (Task 1) endorsed by [BLP Workshop @ EMNLP 2023](https://blp-workshop.github.io/)
I had the honor of organizing the VITD shared task, endorsed by the first Bangla Language Processing (BLP) Workshop at EMNLP 2023. This shared task presents a challenge to NLP enthusiasts who wish to participate in a violence inciting text classification task. The VITD shared task saw enthusiastic participation from 27 teams, comprising 88 individuals, including undergraduate students, graduate students, and university faculty. <br>

You can see the task details [here](https://github.com/blp-workshop/blp_task1)

To see the task overview paper, [click here](https://aclanthology.org/2023.banglalp-1.33.pdf)

## Ranked 5th in SemEval 2024: Numeral-Aware Headline Generation
Our team, **NumDecoders**, participated in NumEval shared task, which focused on numerical reasoning. The task required models to compute the correct number to fill in blanks in news headlines.

Here, we introduced a Chain-of-Thought enhanced solution for large language models, including flanT5 and GPT 3.5 Turbo, aimed at solving mathematical problems to fill in blanks from news headlines. Our approach built on a data augmentation strategy that incorporated additional mathematical reasoning observations into the original dataset sourced from another mathematical corpus. Both automatic and manual annotations were applied to explicitly describe the reasoning steps required for models to reach the target answer. We employed an ensemble majority voting method to generate final predictions across our best-performing models. 

We are proud to have ranked 5th in this task.

You can find the leaderboard [here](https://www.kaggle.com/competitions/numeval/leaderboard?)

## Top 10 in 10 language tracks, SemEval 2023: Multilingual Complex Named Entity Recognition
Our team, **garNER**, participated in MultiCoNER shared task focused on detecting semantically ambiguous and complex entities in short, low-context settings. We developed a knowledge augmentation approach. By querying the Wikipedia API, we appended summaries of relevant entities directly to the input sentences. These entities were either retrieved from the labeled training set (Gold Entity) or identified using off-the-shelf entity taggers (Entity Extractor). To enhance accuracy, we employed ensemble methods across multiple models for the final predictions.

This competition included 13 tracks: 12 language-specific tracks and 1 multilingual track. I'm proud to share that we secured a spot in the top 10 for 10 of the language tracks.

You can find the leaderboard of each track [here](https://multiconer.github.io/results) 