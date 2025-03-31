# FantasyPremierLeague
C++ Command Line Soccer Premier League Simulator. Uses multiple data structures(Vectors, Unordered Maps), classes.

To use the program, first download the zip file and unzip it. Ensure that the
muchmoreexpanded.csv is inside of the folder. Build using

`g++ -o main fpl.cpp`

Run using

`./main`

You will see a number of options. Type the respective number and hit enter to do each.
Brief description of each of the numbers
1. Buy player allows you to manually buy a player. Type the player’s team name,
position, and last name to draft him to your team
2. Sell player pulls up a list of your current squad. Select a number to sell
3. Simulates a week and gives you points based on your players/red cards
4. Drafts/autofills a squad with remaining players from the database. If you can’t get a
full squad of 15, it won’t fill your team up, and you will need to fill it yourself
5. Clears your entire squad and returns to database
6. Shows your full squad
7. Shows the bot rival’s squad
8. Exits the program
