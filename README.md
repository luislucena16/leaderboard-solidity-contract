# Readme
Leaderboard create to manage user scores through smart contracts

# Structure
1. Events
2. Nothing to do here
3. This modifier is used to avoid non players to try to withdraw rewards
4. This function is used to create a board
5. This is done by instantiating a game and pushing into the games list
6. This function is used to retrieve data from the game contract and update the board positions
7. Get the game by its id
8. The board cannot be updated if timestampend has passed
9. Get the players list from game contract
10. Iterate over players list to get their scores.
11. Sort the lists of players and scores and get the top 10.
12. Update game data
13. This function is used to withdraw rewards according to the board results
14. Get player score and amount of total players
15. Internal function used to quicksort players and scores
16. This function is used to get the top N players and its scores
