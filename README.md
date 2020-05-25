# Tetris! 

This project follows the excellent tutorial by Ania Kubow, which 
I found via freeCodeCamp.org. 

https://youtu.be/rAUn1Lom6dw

### Description
- An in-browser simple version of Tetris
- Majority of the code is in app.js; 
- index.html is super simple; 
- style.css is what you'd expect

### Self-goals:
- get more comfortable with Atom
- utilze Git and GitHub more
- increase JS knowledge
- understand connectivity between JS, HTML, CSS

### Changelog 
###### Version 1
- .html, .js. and .css all created and working functionally. 
- about 2/3 through tutorial.
- pieces are randomly generated, fall, and re-generate
- next-up piece is displayed
- controls include left and right (with limits) and up (rotate)
###### Version 2
- tutorial complete!
- colors added to each unique tetromino
- complete lines disappear 
- Start and Pause button added

### Next up:
- Add: 'drop' control
- Add: 'hurry down' control
- Add: moment on last 'final' row before starting next piece
- Add: speed increase with new levels
- Bug: when rotating, pieces will switch to next row (switch sides of game board)
- Bug: when deleting a row, column 2 (array[1]*) will remain colored at top of game board
- Bug: can still move L/R while paused?
- Bug: some lines clear with one piece missing?
- Bug: every time pause is hit, the upcoming piece resets/respawns
- Design: improve color scheme
- Design: add grid to <div> elements
- Design: center, make more visually appealing 
- Design: add shadow to tetrominos 