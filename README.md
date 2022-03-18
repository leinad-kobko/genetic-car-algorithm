# Installs
Required installs to run:
- Pygame
- Box2D
Note: You may need to install Anaconda and install swig before trying to install.

# Running the code
Running the code is relatively simple. When pulled the code will run 1 point crossover with a 5% mutation rate.
To switch to either 2 point, or uniform crossover, comment out 1 point crossover and comment the preferred one in.
The lines to comment out can be found from lines 994-997.
```console
python genetic_car_sim.py
```