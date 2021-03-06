# Staff solutions to 6.141 labs

- **[ta_lab3](/ta_lab3):** Wall following
- **[ta_lab4](/ta_lab4):** Visual servoing
- **[ta_lab5](/ta_lab5):** Particle filter localization
- **[ta_lab6](/ta_lab6):** Pure Pursuit + A* Trajectory Planning

Feel free to use these packages in future labs as long as you report which nodes you used were provided by the TAs.
 
For future labs, TA examples will be released to this repo using wstool after the due date of the labs.
 
## Installation Steps
```bash
cd ~/racecar-ws/
# Add upstream TA repo
wstool set src/ta_examples_public --git "https://github.com/mit-racecar/TA_example_labs.git"
# Pull in new code from TA repo
wstool update
# Install ros deps
rosdep install -r --from-paths src --rosdistro kinetic -y
# build workspace
catkin_make
```

See the readme for each package for additional installation and/or usage instructions.

## Using the example packages
```bash
roslaunch ta_lab3 example.launch
``` 