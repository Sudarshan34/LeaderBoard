https://sudarshan34.github.io/LeaderBoard/

Dear Team,
I have used html,css, js to complete this project. In HTML for tags and css to apply some styling, below are the things explaining the js code

leaderboardData: This array holds the initial data for the leaderboard, including players' first names, last names, countries, and scores.
updateLeaderboard(): This function updates the leaderboard based on the data in the leaderboardData array. It sorts the data by player score in descending order and then dynamically creates table rows for each player,
including their information and a "Delete" button.
deletePlayer(id): This function allows the deletion of a player from the leaderboard by their unique ID. It finds the player in the leaderboardData array, removes them, and then calls updateLeaderboard() to 
refresh the leaderboard without the deleted player.
addPlayerButton.addEventListener(): This event listener is attached to the "Add Player" button. When the button is clicked, it retrieves the values entered in the input fields (first name, last name, country, 
and player score), 
creates a new player object with a unique ID, and adds them to the leaderboardData array. Then, it calls updateLeaderboard() to display the updated leaderboard.
updateLeaderboard(): Finally, updateLeaderboard() is called once to initialize the leaderboard with the initial data, and it's called again whenever a player is added or deleted to keep the leaderboard up-to-date.
