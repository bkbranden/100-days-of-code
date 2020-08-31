# 100 Days Of Code, Round 1 - Log

### Day 14: August 30, 2020 

**Today's Progress**: Today I finished routing up the API to work with Firestore and got it add new database items using a POST request and testing it out in Postman. Also, I was able to write up a deployment script to push the production files up to Glitch, but I am running into memory issues in Glitch so I might have to opt for creating a minified production version.
   
**Thoughts:** This wasn't too difficult in terms of thinking and problem solving, but was rather something that I just had to brute force to get done. However, I figured out and mapped some ways to learn better practices when completing something that I already know how to do... its open source!

### Day 13: August 25, 2020 

**Today's Progress**: Today was learning about shell scripting as well as the difference between mac os and windows ntfs filesystems. I learned about best practices in keeping credentials within environment variables in Jenkinsfiles as well as how to shell script for different environments based on conditionals. Furthermore, I worked more on completing my desktop setup and worked on the differences of filesystems in mac os and windows as well as installing drivers for hardware. I also went through mounting iso files and external drives to set up windows 10 on my desktop.
   
**Thoughts:** Again this is the first time that things within shell scripting, DevOps, and building a pc started to make more sense to me as well as seeing the steps that are involved.

### Day 12: August 24, 2020 

**Today's Progress**: Today was a lot of learning about CI/CD software systems as well as learning about creating pipelines with Jenkins. I learned about what DevOps generally is as well as what typical CD pipelines look like and what stages it is made up of. Furthermore, I created some basic pipelines using Jenkinsfiles to learn how to use Jenkins.
   
**Thoughts:** This is something new to me entirely since I have never really focused on the DevOps side of things. I think it is super interesting however that there is a set paradigm to set up CI/CD pipelines for software systems and is the first time that I felt I was able to narrow down what goes into DevOps.

### Day 11: August 21, 2020 

**Today's Progress**: Its been a while since I had just started work and was trying to get into the swing of things. I have switched up my schedule to fit in more on-hands experience rather than theoretical learning. Today I worked a lot on my new open source productivity animation app and got more deployment strategies with babel and bundling figured out and will have to add in webpack later. 
Also, I tried abstracting out the express app's listen method to using node's http package with `createServer` Furthermore, I got the backend server hooked up to Firebase's firestore to store data information on the user.
   
**Thoughts:** This is definitely something that I am not used to since most of the times when coding or learning, it has been on a tangible side but the deployment side of things seems like its less structured to learn. I might need to buy a book on it.

**Link to work:** [Repo](https://github.com/bkbranden/ProductivityAnimation/tree/3e487aa67485c0be830398d2e77562360da7b763)


### Day 10: August 3, 2020 

**Today's Progress**: I wanted to start on a mobile app on iOS and learn about Flutter. Decided to start a project on Flutter to create a productivity animation app that animates how the day is spent in a circular pie graph. Today, I learned how the widget system sort of works in Flutter, completed the infinite list tutorial, and figured out how to deploy a development app to my phone.

**Thoughts:** This was super interesting as I did not really know what the deployment was like and how it worked. Flutter is interesting in its own right, but is very similar to React so it might not be too bad. The deployment is very interesting as Flutter seems to take of the configurations and I am curious how XCode handles things. 

**Link to work:** [Repo](https://github.com/bkbranden/ProductivityAnimation/tree/bf75bcb1b6abe4e0d1de0f77d899a7c7c339714c)

### Day 9: July 19, 2020 

**Today's Progress**: Finished customizing the Slate docs template that I utilized to have a static-site generator to output my notes. I configured so that it will be directly portable to the syntax and way that I write my notes in markdown so that I don't have to change anything syntax or file related in my markdown files when I am taking notes without a server. Also, I got through several hours of competitive coding practice as well as understanding one of the Codeforces problems which was on maximizing the min and max weights given to k people out of n integers. Also, I got started on Project Euler. Currently, trying to figure out a good and time efficient way to personalize the coding practice I do and make real-world applications.

**Thoughts:** This was not something that I planned to work on but I got distracted and had to make some progress on this since I think it will help me in the long run. Also, I am excited to grind on the competitive programming daily since I think it will be very useful to me in the long-run. I was thinking about a good way to personalize the problems that I solve and common patterns. Upon further thinking, it might be better to not find applications of a coding problem but rather dive deeper into the core algorithm and principles utilized within the algorithm as that is what translate to other problems most of the time.

### Day 8: July 13, 2020 

**Today's Progress**: Today, switched it up to learn and practice more machine learning. I got a dataset from the UCI ML database. Using one of their datasets designed for classification, I classified the type of wine based on parameters utilizing the K-Nearest-Neighbors algorithm that I learned previously. Probably because the dataset was designed for classification, the results were very accurate with over 90% accuracy.

**Thoughts:** This was super interesting because it was one of the first projects that I tried to utilize what I learned in ML without having to look at a guide or tutorial. This helped me understand what type of datasets and problems are solved with KNN as well as how to clean up datasets and convert them in a format that you need.

**Link to work:** [DataSets](http://archive.ics.uci.edu/ml/datasets/Wine)

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
