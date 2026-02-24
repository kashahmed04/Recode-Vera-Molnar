# Personal Toolbox - Recode Vera Molnar

## How to Run the Program

Open the HTML file in a web browser.

- File: index.html
- The artwork will automatically generate inside the SVG canvas.

## Which Piece I Chose and Why

I chose the Interruptions piece because it shows how simple elements and randomness can create various visual patterns. 
I also chose this piece because I wanted to work with lines more since I never really worked with them before.

## Where to Find Transform Components

The transform functions are located near the top of the script.

- translate(x, y) — moves elements
- rotate(angle) — rotates elements
- compose(...transforms) — combines transform strings

These functions are designed to be reusable for SVG elements.

## Important Design Decisions

- Each line is placed inside a <g> element so each line and the transforms can be separated.
- Tried to structure the code in an experimental way so that it is easier to change line length and line segment number. 
  
## File

- index.html - Main program file.
