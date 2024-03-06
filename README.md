## Artificial Intelligence Projects
#### Here is a respository of my code created from the CAP6635 Artificial Intelligence Course from FAU.

#### For homework 1, We had to take a 5x5 matrix board and expand it to a 6x6 matrix board to have three types of agents navigate the board to clean any spots that are dirty (which are the white spots). The three types of agents are:

### 1. Simple Reflex Agent

- These types of agents are based on condition-action rules and are stateless devices.
- They have no memory of past world states and have no specific objective/goal.

### 2. Model-Based Reflex Agent

- These agents have internal states that are used to keep track of past states of the world.

### 3. Goal-Based Agent

- In addition to state information, the agent also has goal information that describes situations that the agent wants to carry out.
- Agents can take future events into consideration.

#### I created a folder called Homework 1 that contains three separate source code files for all three of the agents. Now here is a description of what each of the three seprate source code files do once you run them:

- Once you run the simple-reflex agent file, the agent in the form of a red star is shown on the board that starts at the location [1, 1] in the matrix. The simple-reflex agent starts off by moving and the agent does not know where it is on the board. The agent travels to any place it can go and if the agent reaches to a place on the board where it has to make a decision on where to go next, it will randomly choose a location to move to next. When the agent gets to a location where there is a white spot (Dirt), the agent cleans it up by moving to the location of the white spot. Since this agent has no goal and no memory of past states it has been too, the agent continues to randomly choose a location to go even when all of the dirt is removed from the board.

- Once you run the model-based reflex agent, the agent in the form of a red star is shown on the board that starts at the location [1, 1] in the matrix. The agent now has memory to remember the states the agent has been to. Since the agent has knowledge of the states it has been to, this agent now has a path to follow that will allow the agent to move through the whole board to make sure that all of the dirt is removed from the board. Once the agent has reached it's final position on the board, which is [6, 6], the program will end.

- Once you run the goal-based agent, the agent in the form of a red star is shown on the board that starts at the location [1, 1] in the matrix. This agent now has a goal to follow which is to clean all of the dirt that is present on the board. When the agent has finished cleaning all of the white spots from the board, the program terminates. There is a Node file that represents a location in the matrix array that needs to be in the same directory as the goal-based agent source code file to be able to run the code. 









