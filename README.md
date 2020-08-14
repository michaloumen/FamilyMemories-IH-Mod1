![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Project #1 | Family Memories

## Game rules

1. Cards will be mixed up
2. All cards face down
3. Player turn over any two cards
   * If the two cards match we keep them
   * If they don't match, we turn them back over
4. Remember what was on each card and where it was
5. Watch and remember during the other player's turn
6. The game is over when all the cards have been matched
7. The player with the most matches wins

## Instructions

### Iteration 1: Draw the game board

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_ab5a6ba28003829bd3d8d485feeee649.png)

The first thing we need is to create our board. The left side of the image is already on the HTML file, but when we click on the **Start Game** button, we need to create the canvas and display the road.

The canvas HTML element is already part of the HTML starter code provided in the `index.html` file. In the `images` folder, you can find the image of the raod.

### Iteration 2: Draw the car

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_9a8f35a079a1343f39cee4028ab8a081.png)

Once we have our road, we need the player's car. The same as for the raod, in the `images` folder, you will find a `.png` file you should use.

### Iteration 3: Make the car move right and left

In our game, the player will only be able to move the car to the right and left. Using `left` and `right` arrows, the player should be able to move the car.

:bulb: Remember the boundaries!

### Iteration 4: Create obstacles

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_618fa6bbeed08f1e74b9457af1ecaf4c.png)

Now let's make this interesting. We should create obstacles that show up every specific amount of time.

They will always start in the position **0** of the `y` axis (the obstacles will be coming from the top of the canvas), but you should make them appear in a random place of the `x` axis.

### Iteration 5: Move the obstacles

For moving the obstacles, we need to update our `canvas` continuously. In this iteration, you need to continually change the position of the obstacles in every update, making them move down the road.

### Iteration 6: Points, points, points

Oh! If we want to challenge somebody, we need to quantify who is making it better. So we need to add a **score**. Go ahead and add a method to count points while you keep the car avoiding obstacles.

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_e4b1a09cee1b1a827a2c68023d0d2b1f.png)

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_4e64a09180fd0add2766f7e28ebce6bf.png)

<br>

**Happy coding!** :heart:
