<h1>Number Guessing Game</h1>
 <p>A number guessing game implemented by Android Studio and Java.</p>

<h2>Extra Features</h2>
 <p>
  <ul>
 <li>Play button</li>
 <li>Enter your name blank</li>
 <li>Clean user interface</li>
 <li>The game has 3 rounds: player has to pass each round to another higher round</li>
 <li>Open source and object oriented design</li>
  </ul>
 </p>

<h2>How to Play</h2>
 <ul>
  <li> Regard to this website to open the app on terminal: https://pub.towardsai.net/how-to-run-an-android-application-from-command-line-e139eda62867
</li>    
  <li>On a machine with target API 22 and Gradle version 7.4</li>  
  <li>Press the start button and enter your name to enter the first round. Your name will be stored with your final scores</li>
  <li>Find the hidden number to win the game, best moves will be counted as your high score toward the end of each round. The lesser the attempts, the higher your score</li>
  <li>Click guess to start choosing the number</li>
  <li>To play again, exit the game and repeat steps 2 through 7.</li>
 </ul>

<h2>Game Logic</h2>
<h3>Multiple players</h3>
 <p>Each user will be prompted to enter their name, and their name, scores will be stored in an ArrayList. However, when the app is closed, it will also disappear. When they start the new game, even though they use their old name, it still counts as a new player.</p>

<h3>Guessing hidden number</h3>
 <p>When the client clicks the number button, the button id will be compared with the hidden result and return a notiification whether if the number they chose is higher, lower or correct. If it's not correct then their attempt will be decreased by 1. If they've used all of 3 attempts and not guessing the right number, the game will end.</p>

<h3>Generate random hidden number between buttons</h3>
<p>Use Java random built-in function to get the hidden number</p>

<h2>GUI</h2>
<h3>Start Menu</h3>
<p>The XML contains Start and name fill with onClick function</P>

<h3>Scores and ranking</h3>
<p>Player's best score will be displayed when they finished the game either lose or win and will show in a leaderboard. The higher the score, the higher rank they will have</p>

<h3>End Screen, Congratulations screen and Leaderboard</h3>
<p>End screen will appear if the user loses and congratulation screen will appear otherwise. After that, it will transit to the leaderboard.</p>
<p>For the leaderboard, I used built-in Collections in Java to sort the scores and print out the user's name and score respectively from high to low</p>
