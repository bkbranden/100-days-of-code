# 100 Days Of Code, Round 1 - Log

### Day 7: July 10, 2020

**Today's Progress**: Started tackling adding more features into the frontend. Because I want the frontend architecture to be up to date and simple, I decided to utilize the React-Router for navigation as well as Redux for state management of trhings that exist throughout the whole app such as admin and login functionality. I integrated React Router, but right now I am writing the basics for the Redux integration. So far, I have only written the action types and creators, but am going to tackle the reducers and then the store so that I can hook it up with the React router

**Thoughts:** Hooking up the React Router and the Redux was much easier this time around than before. One main problem that I ran into was how to best organize the code. Because there isn't any guides organizing was something that took some time for me to figure out how I best wanted it. Furthermore, because this time around I am utilizing Typescript, the type definitions are definitely something to get used to.

**Link to work:** [Current Commit](https://github.com/bkbranden/CrystariumTree/tree/c99163c955e0683d773f35052223d9c92e83a809)

### Day 6: June 25, 2020

**Today's Progress**: Today I added the draw logic to the game as well as keeping track of the different states throughout the game and then allowing for resetting back to a previous state. Also, updated some styles on the buttons and the board.

**Thoughts:** The keeping track of the state logic actually had a small problem where I would arrays and matricies would be passed by reference when assigned to another variable so when a state was updated, it would override all of the previous states. The workaround was to create copies of the state everytime that I needed it. Also, styling proved to be very limiting. Trying to style having an element in the center with a column to the right of it proved impossible in flexbox. Also, trying to style bottom borders with elements with padding also was impossible to do.

**Link to work:** [Current Commit](https://github.com/bkbranden/CrystariumTree/tree/2bf9c8159df2a5bcb60172687952cc28a4b5bb40)

### Day 5: June 24, 2020

**Today's Progress**: Today I added the gameover logic to check if the game is over and also a conditional to prevent any further play when the game is over. Also added the "reset" functionality and "game-over" text!

**Thoughts:** These features weren't the hardest to code up, but I could not think of the best way to check if the game is over other than hard-iterating through each row, each column, and each diagonal. Is there a better way to do this or is it not worth spending time thinking over?

**Link to work:** [Current Commit](https://github.com/bkbranden/CrystariumTree/tree/43696a3040c663ac99b26f9ad66548aa32f0fc60)

### Day 4: June 23, 2020

**Today's Progress**: Today, I added to logic of being able to click "X" and "O" on the tic tac toe board and adding the player 1's turn and player 2's turn. Also, I added the logic of putting in the text for displaying who's turn it was.

**Thoughts:** This was pretty rewarding to code up as it is the main logic within the tic-tac-toe game. One thing that took a little bit of thinking to figure out was how to change the board state on-click. I think the best way was to get the row and column index and then mutate a copy and call setState(), but there might be cleaner ways such as using the MouseEvent cursor position with respect to the square position.

**Link to work:** [Current Commit](https://github.com/bkbranden/CrystariumTree/tree/43696a3040c663ac99b26f9ad66548aa32f0fc60)


### Day 3: June 22, 2020

**Today's Progress**: Today I started reverse engineering the tic-tac-toe React tutorial available [here](https://reactjs.org/tutorial/tutorial.html). I thought this would be a good project exercise to solidfy my React skills especially with Typescript as well as I am going to use this as a base when I set up my router and different parts of my website later. Later I envision having a games projects tab that takes the user to all of the games that I have worked on and made.

**Thoughts:** I actually messed up the CSS modules paradigm that I mentioned in the last log as the file naming convention requires ".module" where you can import the styles as an object. Working with typescript interfaces for the proptypes and statetypes was something I had to brush up on again. Overall, I think I made significant progress and it was very fun!

**Link to work:** [Current Commit](https://github.com/bkbranden/CrystariumTree/tree/807a32205a01e3da170b931ce723dfa77d21485e)

### Day 2: June 21, 2020

**Today's Progress**: Created a basic navbar styled with CSS. Downloaded node-sass to integrate SCSS with my React project. Utilizing the CSS modules paradigm for better code organization. Included fonts using webfontloader package (works really well).

**Thoughts:** I struggled with the different syntax with SCSS. It was a very slight difference from traditional CSS which made it harder to debug (strings don't exist in scss files). The webfontloader package that I utilized for the Roboto Mono font works super well and was integrated very easily.

**Link to work:** [Current Commit](https://github.com/bkbranden/CrystariumTree/tree/d317f4d92f53facc9d1b044b03fc480aea82d20e)

### Day 1: June 20, 2020

**Today's Progress**: Created the Frontend and APIservice containers and linked them together using docker-compose. Created a basic proof of concept of being able to download npm packages by using React-D3-Tree. Started linking the frontend together and will handle the basic homepage.

**Thoughts:** Struggled with containerizing the react application because of a bug in the latest version of react-scripts (3.4.1). Also, tried to find some free mock-up resources on sketchappresources but it seems difficult to find some that are minimal but modern.
