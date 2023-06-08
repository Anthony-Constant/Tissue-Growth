# Modelling and Analyzing the Growth of a Network

## What is it?

This program models and analyzes the growth of a network based on the biological concept of cell growth and structure formation. In this model, a cell with a nucleus reproduces by splitting off daughter cells, which are formed at defined positions (lower left and lower right of the parent cell). After this, the daughter cells repeat the cycle of separation and positioning. However, daughter cells that end up at the same location experience competition for space and resources and as a result become infertile. The outcome of the process is a tree-shaped "tissue" of green and red patches (respectively reproducing and non-reproducing cells).

## How it works

This program starts by creating a cell in the center of the top row of the canvas. The cell is colored green, indicating it is a reproducing cell. The program then proceeds to create daughter cells at the defined positions (lower left and lower right) of the parent cell, which are also colored green. These daughter cells also repeat the process, forming new cells at defined positions, which are also colored green. However, if two daughter cells end up at the same position, they compete for space and resources and become infertile. Infertile cells are colored red, indicating they are not reproducing cells.

## How to use it

To use this program:

- Click the "Set-up" button to set up the initial agent.
- Click the "go-once" button to run the program incrementally (+1).
- Click the "go" button to run the program continuously.
- Move the "#generations" slider to specify the number of generations outputted.
- The "show-patch-color" switch clears the patches by setting their color to black.
- The "show-circle?" switch arranges the nodes of the network as a circle.

Note: The program stops after it has been checked if generationstep = #generations.

## Things to notice

- The growth of the network over time.
- The change in color of each cell indicating whether it is a reproducing cell (green) or a non-reproducing cell (red).

## Things to try

- Experiment with changing the number of generations and analyze the output using the tables provided.
- Turn the "show-circle?" switch on and off to see the difference in the arrangement of nodes in the network.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

This script was developed by [Anthony Constant](https://anthonyconstant.co.uk/).

## Support My Work

If you like this repository or have used any of the code, please consider showing your support:

- Give it a star ⭐️ to acknowledge its value.
- You can also support me by [buying me a coffee ☕️](https://ko-fi.com/W7W144CAO).

