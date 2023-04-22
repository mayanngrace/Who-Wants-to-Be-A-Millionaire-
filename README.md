# Who-Wants-to-Be-A-Millionaire-
A console program adaptation of the trivia game show entitled "Who Wants to Be A Millionaire?" programmed using Python. It is a free and open-source game where the player can put their knowledge into test by answering a series of multiple choice questions correctly in order to win a virtual million dollars.

## Project Specifications
At the start of the program, there are three choices for the user: (a) Play Game, (b) View High scores, (c) Quit Game
<ol type="1">
  <h3><li>Play Game:</h3>
  <ol type= "a">
    <li>When the user plays the game, the program first asks the user of his/her name. This will be used for the entirety of the game
    <li>Each game has 15 questions which you will get from question banks. Each question has 4 choices.
    <li>Question banks:  1 for easy questions, 1 for average questions, and 1 for difficult questions (10 questions each)
    <li>At the start of each round, the question will be flashed/displayed along with the choices. The current earnings and the prize of the round should also be displayed. (Example: If the user is at round 5, the current earnings is 8,000 while the round prize is 15,000). The user has three options: (1) answer the question, (2) Choose a lifeline, (3) Walk away with earnings.
   <li>Answer the question: The user should input the letter corresponding to his/her answer. For average and difficult questions, after the user types in his/heranswer, the program must confirm the choice of the user (Yes/No). If it is not his/her final answer, then the user can change his/her final answer. Otherwise, if the answer is correct, the user proceeds to the next round/question. If not, then the user walks away with the prize of the last earned checkpoint (If the user is in a checkpoint round, e.g. Round 10, and fails to answer correctly, he earns the previous checkpoint, not the current one. In this case, 20,000 not 150,000). (See table below for the different checkpoints).
    <li>Choose a lifeline: There are two lifelines available: Call-a-friend and 50/50.
    <ol type="i">
        <li> Call-a-friend: There are 3 types of friends and each friend can only be called once for the whole game:
          <ul>
            <li> Smart friend. A friend with a humble tone and has a 90% chance of providing the correct answer.
            <li> Unsure friend. A friend that is confused and has a 50% chance of providing the correct answer.
            <li> Arrogant friend. A very, very arrogant friend with a 20% chance of providing the correct answer.
          </ul>
        <li>50/50: Remove two incorrect answers
        <li>Lifelines cannot be used in the final question.
    </ol>
  <li> Walk away with Earnings: The user gets his current earnings and the game ends.
 </ol>
<h3><li>View High Scores:</h3> The top 5 players with the highest earnings will be displayed.
<h3><li>Quit Game:</h3> The programs stops executing and closes.
<h3><li>Game Rounds and Checkpoints:</h3>
</ol>

![image](https://user-images.githubusercontent.com/102021376/233771311-efc3de6f-f76b-44a1-9a42-ddb21ed35afa.png)
![image](https://user-images.githubusercontent.com/102021376/233770500-7862a86a-c444-4249-a872-17a640bdda2e.png)


