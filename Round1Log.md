# 100 Days Of Code, Round 1 - Log

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
