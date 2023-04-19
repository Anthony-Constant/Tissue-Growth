<h1>Modelling and Analyzing the Growth of a Network</h1>

<h2>What is it?</h2>

<p>This program models and analyzes the growth of a network based on the biological concept of cell growth and structure formation. In this model, a cell with a nucleus reproduces by splitting off daughter cells, which are formed at defined positions (lower left and lower right of the parent cell). After this, the daughter cells repeat the cycle of separation and positioning. However, daughter cells that end up at the same location experience competition for space and resources and as a result become infertile. The outcome of the process is a tree-shaped "tissue" of green and red patches (respectively reproducing and non-reproducing cells).</p>

<h2>How it works</h2>

<p>This program starts by creating a cell in the center of the top row of the canvas. The cell is colored green, indicating it is a reproducing cell. The program then proceeds to create daughter cells at the defined positions (lower left and lower right) of the parent cell, which are also colored green. These daughter cells also repeat the process, forming new cells at defined positions, which are also colored green. However, if two daughter cells end up at the same position, they compete for space and resources and become infertile. Infertile cells are colored red, indicating they are not reproducing cells.</p>

<h2>How to use it</h2>

<p>To use this program:</p>

<ul>
	<li>Click the "Set-up" button to set up the initial agent.</li>
	<li>Click the "go-once" button to run the program incrementally (+1).</li>
	<li>Click the "go" button to run the program continuously.</li>
	<li>Move the "#generations" slider to specify the number of generations outputted.</li>
	<li>The "show-patch-color" switch clears the patches by setting their color to black.</li>
	<li>The "show-circle?" switch arranges the nodes of the network as a circle.</li>
</ul>

<p>Note: The program stops after it has been checked if generationstep = #generations.</p>

<h2>Things to notice</h2>

<ul>
	<li>The growth of the network over time.</li>
	<li>The change in color of each cell indicating whether it is a reproducing cell (green) or a non-reproducing cell (red).</li>
</ul>

<h2>Things to try</h2>

<ul>
	<li>Experiment with changing the number of generations and analyze the output using the tables provided.</li>
	<li>Turn the "show-circle?" switch on and off to see the difference in the arrangement of nodes in the network.</li>
</ul>

<h2>Credits</h2>

<p>This script was created by Anthony Constant (AC). If you have any questions or suggestions, you can contact him at <a href="http://www.anthonyconstant.co.uk/">anthonyconstant.co.uk</a>.</p>

<h2>License</h2>

<p>This script is released under the MIT License. See the LICENSE file for more details.</p>
