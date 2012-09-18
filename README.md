# Perceptrons for Petra

Solution for labs in the Modern AI for Games class at the [IT University of
Copenhagen](http://www.itu.dk/) on Sep 18th 2012.

Given input either as `height` or `height,weight`, determine if Petra will find
a man attractive.

The program is a simple single perceptron network with a variable number of
inputs and one output. I cleaned up the code a bit and added the functionality
for the perceptron calculation.

The initial weights are set via `Random.nextFloat()`. The value for the
threshold input for the perceptron is set to `1`.

Matches the expected output for one input value in (less than) 10 iterations.
The expected output for two input values is found in aproximately 20 to 50
iterations. The number of iterations of course depend on the initial weights.

The program exits when the output matches the expected output or 1000
iterations has passed.
