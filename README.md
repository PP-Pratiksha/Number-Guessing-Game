ALGORITHM FOR NUMBER GUESSING GAME
Step 1: Generate a random number between 1 and 100.
Step 2: Record the turn number the player is on. Start it on 1.
Step 3: Provide the player with a way to guess what the number is.
Step 4: Once a guess has been submitted first record it somewhere so the user can see their previous guesses.
Step 5: Next, check whether it is the correct number.
Step 6: If it is correct:
        1.	Display You guessed Correctly message.
        2.	Stop the player from being able to enter more guesses (this would mess the game up).
        3.	Display control allowing the player to restart the game.
Step 8: If it is wrong and the player has turns left:
        1.	Tell the player they are wrong and whether their guess was too high or too low.
        2.	Allow them to enter another guess.
        3.	Increment the turn number by 1.
Step 9: If it is wrong and the player has no turns left:
        1.	Tell the player it is game over.
        2.	Stop the player from being able to enter more guesses (this would mess the game up).
        3.	Display control allowing the player to restart the game.
Step 10: Once the game restarts, make sure the game logic and GUI are completely reset, then go back.
