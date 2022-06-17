# Code Dojo of Conway's Game of Life with MCreator

## First Objective

The goal is to implement Jon Conway's Game of Life using only the Scratch editor - the visual programming - of MCreator.

## Rules

Here a a few rules you have to follow in order to complete this Code Dojo.

- Choose a block to represent a living cell.
- Choose a other block to represent a dead cell.
- Avoid naturally spawning blocks to avoid issues.
- Test your mod in a flat world without structures, in creative mode.
- Any block that is not a living cell is considered to be a dead cell by the simulation, except air.
- The grid only takes into account the __x__ __z__ axes.
- Create a __simulation controller__ that allows you to start and pause the simulation, so you can place a few cells without worry.
- Limit the simulation to a square around the player of 100 x 100. You may make that bigger if you feel like it, but beware of performance issues !
- Set the speed to one generation per 20 ticks - one second. You may make it faster, but again, performance issues !

## Bonus challenges

- Allow to change the speed of the simulation in the game, somehow.
- Allow to change the size of the simulation in the game, somehow.
- Allow to reset the simulation - replacing all licing cells by dead cells.
- Make the zone of the simulation as big as you can without lag.
- Use different colors for living cells, depending on the number of living neighbors.
- Try using empty space for dead cells and flowers for living cells instead of blocks.
- Go ahead and cosider air as being a dead cell, or use air

## Conclusion

Start by cloning this repository and create a new workspace in a directory.

You may create different variations by cloning the workspace into another directory so you can go back and forth easily.
