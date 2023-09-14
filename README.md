# Flashcard-Application
This project leverages the Tkinter library in Python to create a vibrant and interactive flashcard app to assist individuals in learning new English words along with their Polish translations. </br>
The words used in the data are the most common in spoken language.

## Features

- **Dynamic Flashcards**: Display English words on one side and their Polish translations on the flip side.
- **Data Persistence**: Maintains a list of words to learn in a CSV file.
- **Progress Tracking**: Allows users to mark words they have learned, removing them from the list of words to learn.
- **Randomized Learning**: Randomly selects words from the learning list.
- **Automatic Flip**: Automatically flips the card to reveal the translation after a set period (3 seconds).

## How to Use
1) Launch the application.
2) The application initially loads words from data/words_to_learn.csv if available; otherwise, it loads from data/english_words.csv.
3) Flashcards will automatically flip after 3 seconds to reveal the Polish translation of the displayed English word.
4) If you know the word, click the checkmark button, and the word will be removed from the learning list, and the next word will be displayed.
5) If you don't know the word, click the cross button to move to the next word without removing it from the learning list.

![f1](https://github.com/maxyymmm/Flashcard-Application/assets/120425774/8a8e4886-33ab-44f1-a131-e8e88d5a5e0e) </br>
![f2](https://github.com/maxyymmm/Flashcard-Application/assets/120425774/c7dd488e-8e31-4bb8-b551-80d53df7d3eb)
