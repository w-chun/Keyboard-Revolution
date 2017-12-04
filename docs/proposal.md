# Keyboard Revolution

### Background

Keyboard Revolution is inspired by Dance Dance Revolution. The game involves directional arrows rising from the bottom. To score points, the player has to hit the correct arrow key(s) when the rising arrow(s) cross the line.

### Functionality & MVP

- [ ] Start and pause game
- [ ] Arrow(s) are rising
- [ ] Press arrow key when rising arrow crosses line
- [ ] Animations when arrow key is pressed
- [ ] Points are added when player hits the key on time

In addition, this project will include:

- [ ] A production Readme

### Wireframes

![wireframe](https://github.com/w-chun/Keyboard-Revolution/blob/master/wireframe.png)

### Architecture and Technologies

This project will be implemented with the following technologies:

- Vanilla JavaScript and jquery for overall structure and game logic,
- HTML5 Canvas for DOM manipulation and rendering,
- Webpack to bundle and serve up the various scripts.

In addition to the webpack entry file, there will be multiple scripts involved in this project:

- TBD

### Implementation Timeline

Day 1: Webpack and Entry File

- [ ] Get `webpack` serving files and frame out index.html
- [ ] Render an object to the Canvas element
- [ ] Create animations and key press

Day 2: Create rising arrows  

- [ ] Complete the `arrow.js` module (constructor, update functions)

Day 3: Scoring is implemented

- [ ] Build interaction between the arrows and key pressed
- [ ] Score is added for the correct action

Day 4: Controls and Styling

- [ ] Create controls for start and pause
- [ ] Have a styled `Canvas`, nice looking controls and title

### Bonus Features

- [ ] Difficulty levels
