#  Monetary Policy Analysis with NLP Techniques

This repository contains Python code that performs Natural Language Processing (NLP) techniques to analyze monetary policy documents, specifically the summary of the Monetary Policy Committee (MPC) meetings from the Central Bank of Turkey (CBRT).

The main goal of this project is to extract meaningful insights from the CBRT's meeting summaries by using web scraping, employing various NLP techniques,  text cleaning, lemmatization, part-of-speech tagging, and creating visualizations like word clouds and frequency bar plots.

The script will fetch the meeting summary, clean the text, apply lemmatization, perform part-of-speech tagging to retain only adjectives and nouns, and then create a word cloud and a frequency bar plot of the top words.

The generated word cloud and bar plot will be displayed.

To analyze a different meeting summary, modify the url variable in the script with the desired URL.
You can adjust the number of top words to be included in the frequency bar plot by changing the n parameter in the freq_bar_plot function.
