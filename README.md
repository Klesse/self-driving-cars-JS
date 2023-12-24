# 🚗 Self-driving cars

This project was made as learning neural networks and genetic algorithms with 
professor [Radu Mariescu-Istodor](https://radufromfinland.com/) in his free
youtube course.

This consists as a learning approach algorithm to simulated self-driving cars.

Using genetic algorithms, we can set a fitness function to determine if the 
neural network weights are good or not, and then evolve this each generation.

# Topics approached

* Car mechanics
* Road creation and definition
* Artificial sensor
* Collision detection
* Traffic simulation
* Neural network
* Visualization of the neural network
* Genetic algorithm


# How to run

1. Open the index.html file.
2. Use the save button (between the road and the network) to save the weights 
of the best car (in this case, set as the furthest one). So the next generation 
(refreshing the page) will start the best car of the prior and others with 
mutation.
3. Refresh the page and repeat steps 2 and 3 until the car pass the obstacles.

# TODOs

* Develop some sprite for the cars.
* Define a better fitness function.
* Multithreading to get best performance.
* Do NN Tuning.
