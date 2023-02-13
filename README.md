# Scrabble

This code defines two lists: `letters` and `points`, which represent the point values for each letter in the game Scrabble. It then creates a dictionary `letters_to_points` which maps each letter to its corresponding point value, and adds a key-value pair for a space character with a point value of 0. 

Next, a function `score_word` is defined that takes a `word` as input and calculates its point value by iterating through each letter in the word and looking up its point value in the `letters_to_points` dictionary. 

Finally, a dictionary `player_to_words` is defined, which maps each player to a list of words that they played in a game. The code then creates an empty dictionary `player_to_points` and iterates through the `player_to_words` dictionary, calculating the point value of each player's words using the `score_word` function and storing the results in `player_to_points`. The final result is printed to the console.
