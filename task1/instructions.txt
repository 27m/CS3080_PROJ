Task 1: Word Guess Game
• Write a Python program to web scrape the following website:
https://www.ef.edu/english-resources/english-vocabulary/top-1000-words/
• The goal of that web scraping is to obtain the 1000 most common words
in the English language.
• Once you have them, you should save them in an Excel spreadsheet file.
• After that, develop a word guess game.
• At the start of the game, the program will randomly select a word from
the Excel spreadsheet.
• The word characters will be displayed as underscores separated by spaces.
For example, if the word has 5 characters, then the word will be displayed
as 5 underscores separated by spaces.
• If the player (the guesser) guesses correctly a letter, the character will be
displayed in every place in the word.
a a
a a t
• The player can make any number of guesses, but can make 5 mistakes
only. For the fifth mistake, the program should do the following:
– displays the word (the actual characters, not the underscores).
– displays the message ”You Lost!”.
– terminates.
• If the player guessed the word correctly, the program should do the following:
– displays the word (the actual characters, not the underscores).
– displays the message ”You Won!”.
– terminates
