# Pac-Man Movement Exercise

## Documentation

This README file is a companion to the Pac-Man Exercise completed during Week 4 of the Professional Certificate in Coding Cohort. This week's goal was to use setInterval() to control an Pac-Man image array so it appears to move across the screen. It starts with Pac-Man moving to the right until it reaches the edge of the browser window. Once that happens, Pac-Man appears to reverse direction then chomps across the screen to the left until it reaches the right page edge. Pac-Man flips again and the chomping process starts all over again.


### What were the steps to complete this assignment? 

Starter html, js, and image files were provided but the simulation of movement needed to be added to the JavaScript file. The steps to complete this project follow:
1. Add a JavaScript **setInterval()** method to call the **Run()** function every 200 milliseconds.
2. Add an extra argument to the **Run()** function to replace *null* with *pageWidth*.
3. Add conditions to the **checkPageBounds()** function to move Pac-Man one direction, then reverse direction once it hits the page width boundary.

### Takeaways from this exercise

Learning how to make Pac-Man move and chomp back and forth across the screen was fun. However, what I really learned was how to work through the exercise, carefully reading through the comments, picking up on nuances in the wording, googling all terms, and always, always use console.log() to check your code and to ensure anything you write works before moving onto the next step.


