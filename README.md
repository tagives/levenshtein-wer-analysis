# Levenshtein Distance & Word Error Rate (WER) Analysis

This project explores the application of **Levenshtein Distance** for calculating the **Word Error Rate (WER)** — a critical metric in evaluating the performance of Automatic Speech Recognition (ASR) systems.

##  Overview

- Dataset: [TED-LIUM Release 3](http://www.openslr.org/19/)
- ASR Models compared:  
  - Google Speech-to-Text API  
  - Whisper AI (OpenAI)

##  Key Features

- Implemented multiple WER calculation methods in Python using the `jiwer` library.
- Theoretical review of edit distance algorithms (Levenshtein, Damerau-Levenshtein, Jaro-Winkler).
- Efficiency comparison between naive recursive and dynamic programming approaches.
- Visual analysis of model performance based on WER.

## Results

| Model              | Word Error Rate (WER) |
|-------------------|------------------------|
| Google STT        | 11.34%                 |
| Whisper AI        | 6.02%                  |

## Files

- `notebook/`: Python notebook implementing Levenshtein & WER
- `report/`: Final report and presentation (PDF)
- `references/`: `.bib` file with citations used in the report

 
