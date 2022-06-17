# [`TheG0ATS`](https://theg0ats.github.io/Project-Prep/)
> Code Fellows Python 401

# Pitch Ideas:

## Brainstorming Ideas
  * `Nonogram/Picross Web Game`: Picross is a type of puzzle where you start with a blank grid, and fill in grid spaces based on the number hints on the sides of the puzzle.
  * `Coop web game`: A game that requires 2 users to work together to solve puzzles
  * `Pykemon`: A pocket monster type game.
  * `Pynopoly`: A Board game built with python.

# Top 2:

## Pitch: `Nonogram/Picross Web Game`

[What is a Nonogram?](https://en.wikipedia.org/wiki/Nonogra)

### Summary of idea

Picross is a type of puzzle where you start with a blank grid, and fill in grid spaces based on the number hints on the sides of the puzzle. We could implement this in a web-based Next.js project, with React for the frontend and TailwindCSS to style the grid nicely, and an API to get puzzle layout from the server. 

### Problem Domain

### Advantages of this project

- Clear problem domain
- Other people have made open-source picross projects, so we'd have something to reference if we feel lost
- Most picross websites I'm seeing on a quick Google are either ugly or clunky, so we could actually bring something new with a nice looking and streamlined website

### Minimum Viable Product (MVP)

- Web project that presents a picross grid 
- Grid numbers layout is loaded from database, via API
- Users can fill in cells or mark them with an X
- Users can hit a "verify" button to check if they've solved it correctly, if it is:
- Another puzzle is then served up

### Stretch:

- Optional login system to track which puzzles have been solved
- Different puzzle sizes (8x8, 10x10, 15x15, 20x20, etc)
- A "hint" system or maybe a "fill in a correct square for me" freebie thing?

[An example of a JavaScript implementation.](https://courses.cs.washington.edu/courses/cse154/19sp/sections/extra/nonograms/slides/index.html#/13)

## Pitch: `Coop game`

### Summary of idea

Multiplayer coop game where each player must help others by completing puzzles to reach their specific destinations. We can use python Arcade.and host on digitalOcean.

### Problem Domain

People now more than ever need to work together. Promotes teamwork. Have fun!

### Pros:

- Lots of tutorials 
- Well documented libraries 
- Learn new libraries 

### Cons:

- Unfamiliar libraries
- Hosting

### Minimum Viable Product (MVP)

- Two player web game
- Can interact with assets 
- Can move to next level