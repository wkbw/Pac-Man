# Pac-Man
Pac-Man Movement Exercise

## Documentation

This README file is a companion to the PacMan Exercise completed during Week 4 of the Professional Certificate in Coding Cohort. This week's goal was to use setInterval() to control an PacMan image array so it appears to move across the screen. It starts with PacMan moving to the right until it reaches the edge of the browser window. Once that happens, PacMan appears to reverse direction then chomps across the screen to the left until it reaches the right page edge. PacMan flips again and the chomping process starts all over again.


### What were the steps to complete this assignment? 

Starter html, js, and image files were provided but the simulation of movement needed to be added to the JavaScript file. The steps to complete this project follow:
1. Add a Javascript **setInterval()** method to call the **Run()** function every 200 milliseconds.
2. Add an extra argument to the **Run()** function to replace *null* with *pageWidth*.
3. Add conditions to the **checkPageBounds()** function to move PacMan one direction, then reverse direction once it hits the page width boundary.

### Takeaways from this exercise

Learning how to make PacMan move and chomp back and forth acress the screen was fun. However, what I really learned was how to work through the exercise, carefully reading through the comments, picking up on nuances in the wording, googling all terms, and always, always use console.log() to check your code and to ensure anything you write works before moving onto the next step.


