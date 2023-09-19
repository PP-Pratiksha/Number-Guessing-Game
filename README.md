ALGORITHM FOR NUMBER GUESSING GAME<br>
Step 1: Generate a random number between 1 and 100.<br>
Step 2: Record the turn number the player is on. Start it on 1.<br>
Step 3: Provide the player with a way to guess what the number is.<br>
Step 4: Once a guess has been submitted first record it somewhere so the user can see their previous guesses.<br>
Step 5: Next, check whether it is the correct number.<br>
Step 6: If it is correct:<br>
        1.	Display You guessed Correctly message.<br>
        2.	Stop the player from being able to enter more guesses (this would mess the game up).<br>
        3.	Display control allowing the player to restart the game.<br>
Step 8: If it is wrong and the player has turns left:<br>
        1.	Tell the player they are wrong and whether their guess was too high or too low.<br>
        2.	Allow them to enter another guess.<br>
        3.	Increment the turn number by 1.<br>
Step 9: If it is wrong and the player has no turns left:<br>
        1.	Tell the player it is game over.<br>
        2.	Stop the player from being able to enter more guesses (this would mess the game up).<br>
        3.	Display control allowing the player to restart the game.<br>
Step 10: Once the game restarts, make sure the game logic and GUI are completely reset, then go back.<br>
