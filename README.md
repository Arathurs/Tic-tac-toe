## Tic-Tac-Toe/React

### Screenshot:
  ![Screenshot](public/img/homepage.png)
  
  ![Screenshot](public/img/homepage1.png)
  
  ![Screenshot](public/img/homepage2.png)
  
  ![Screenshot](public/img/homepage-white.png)
  
  ![Screenshot](public/img/homepage-betterer.png)
  
  ![Screenshot](public/img/homepage-better.png)
  
#### [Link to Live Site](http://pinnock-roadside.epizy.com/)  
#### [Link to Repo](https://github.com/Arathurs/Roadside_Assistance_Site.git/)  

### About the Project
Simple tic-tac-toe web application game, created with React.

### Fixes v4
- Improved the visual design of the app using CSS5.
- Refactored code to enhance performance, efficiency and readability.
- Refactored code to follow best practices in clearly separating containter elements from presentational elements.
- Fixed tiny design and performance bug fixes in previous verson.


### To Do

- Make computer player smarter
- Instead of making random moves have the computer survey the current tic-tac-toe board to decide an optimal move.
- Implement a function that gives the computer player the cabapility to detect and act on instant wins. For example, Computer player is 'O' and it's the Computer's turn. If there are any rows with at least two 'O's, the computer will find it and place an 'O' there to automatically win.
- Implement a function that allows the computer to plan multiple optimal moves ahead, depending on the current board, at least 2-3 actions ahead.
- Implement a feature that would allow the player to choose the difficulty of the game. Difficulty can be controlled by simulating human error by using Math.random() to give the computer specific odds of picking the optimal move. The harder the difficulty chosen, the more likely the computer is to not make "mistakes".
- Refactor isThereAWinner(), which check if the most recent move resulted in a win. Currently it is highly inefficient, utilizing a brute force method which checks all 8 rows for a possible win. It only needs to check the***affected***rows of a recent move, which at most can be four.