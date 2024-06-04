# Snowman Artificial Intelligence Chatbot Guide

This readme.md demonstrates how to train and load the models and discord bot.

## Overview

**_Step 3 to 14 is only ran once to get your pickle files. To host your bot, only step 15 to 17 is needed for the subsequent times._**

`snowman.ipynb` is split into 4 main sections (song classifier model, category model, fuzzy, discord).

### _Song Classifier Model_

1. Run block 1 to load the libraries.
2. Run block 2-8.
3. Choose an algorithm from block 9-11. (Run only one of them but in our case will be block 9 for Naive Bayes).
4. Run block 12-13.
5. You should have `song_classifier_model.pkl` and `year_columns.pkl`.
6. Restart your kernel to clear all variables.

### _Category Model_

7. Run block 1 to load the libraries.
8. Run block 15-18.
9. Choose an algorithm from block 19-21. (Run only one of them but in our case will be block 19 for Naive Bayes).
10. Run block 22-23.
11. You should have `category_classifier.pkl` and `vectorizer.pkl`.

### _Fuzzy_

12. Run block 1 to load the libraries.
13. Run block 25-27.
14. You should have `weather_system.pkl`
15. Restart your kernel to clear all variables.

### _Discord_

16. Run block 1 to load the libraries.
17. Replace your API token for OpenWeatherMap in block 28.
18. Run block 28 to import all necessary functions.
19. Replace the token in block 29 with your own bot token and run block 29.
20. Run block 30 to start hosting your bot.
