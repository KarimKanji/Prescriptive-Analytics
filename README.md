# Prescriptive-Analytics
Course Code: IA‑2‑019 (0), Prescriptive Analytics, 13.10.2020 (Course in Prescriptive Analytics during my first year of studies)

-------------------------

## Assignment 1: 

The homework assignment is to use the same code_lesson01.ipynb that we used during the lesson (and Hands-on 01) with the provided agent and labyrinth. Modify the code as needed to solve the tasks. Homework can be done in groups of up to 2.

Modify the original 6x6 labyrinth to create 2 new labyrinths:

A 10x10 labyrinth
A 20x20 labyrinth
Increase the complexity of the labyrinths randomly, manually, or using your own algorithm so that the labyrinth walls correspond to:
10% of its area
20% of its area
50% of its area
Note! Ensure that the labyrinth doesn't close off and become unsolvable!
P.S. So, there will be a total of 6 different labyrinths.

Evaluate how many steps the agent needs at a minimum to exit each individual labyrinth.
Let the agent solve the labyrinths and determine its best results. Does it match?

Note! If your labyrinth becomes too difficult, it's possible that the agent may never solve it. Plot the labyrinth using tools like Seaborn to check if it's appropriate or increase the number of actions the agent can perform. Write down your observations and reflections if nothing works!

Hyperparameter tuning: Find the best Alpha and randomFactor values possible for an agent to solve the 10x10 labyrinth with 20% area coverage in as few steps as possible.
Tips: Use 'for loops' for this task.


-------------------------

## Assignment 2:

In the assignment, you will continue working on the code we used during the lesson, which is also available on itslearning (lesson_02_code_bandit_class.ipynb).

Modify the code as needed to solve the tasks.
Homework can be done in groups of up to 2.

Note: All tasks should be plotted!

Compare the results for 𝜖 = 0, 𝑄1 (𝑎) = 1, 5, and 10.
How does the result from task 2 change if we instead use 𝜖 = 0.1?
Compare the results in the optimistic problem with:
𝜖-greedy; 𝜖 = 0.1, 𝑄1 (𝑎) = 0
Optimistic with 𝑄1 (𝑎) = 10 and 𝜖 = 0.1
UCB with 𝑄1 (𝑎) = 0 and c = 2 (UCB)
Show how the results change when UCB has 𝜖 = 0.1.

-------------------------

## Assignment 3:

Make FrozenLake 8x8 in size and solve it with a manual policy (as in Hands-on).

Train an agent to solve the 8x8 FrozenLake with slippery=True and extract a policy. Q-learning is a popular method, please describe why you are using a different one if applicable.

How did it go? Describe the results.

Reflect on your manual policy, did it improve or worsen?

Refer to the "Additional Material" page for solution suggestions and materials if needed.

-------------------------

## Assignment 4:

Find the optimal policy to solve the Tower of Hanoi with 3 rings. Code your problem in Python and Jupyter Notebook. Remember to print or visualize the policy!

Below are all the stages for the Tower of Hanoi with 3 rings.

Tips:

One way to start is by coding all the states and actions.

For example, from the initial state A123 B0 C0, the next state (state) can only be A23 B1 C0 or A23 B0 C1.

-------------------------

