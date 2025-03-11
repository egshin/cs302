# CS 302 LAB 2 - ELLA SHIN - WINTER 2024

I created a function called create_random_robot in robot_config.py that takes in an input n and creates n boxes around a center boxes and connects each box with springs to the adjacent box and the center box. 

I also used the random library to create a random ratio between the outer springs and the inner springs (springs connected to the middle box) between 0.5 and 2. 

I changed rigid_body.py to take in 1 argument that corresponds to the number of boxes. setup_robot calls create_random_robot with this input. 