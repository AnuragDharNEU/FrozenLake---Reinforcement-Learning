The purpose of this project is to train an agent to play the game called Frozen Lake using Q-Learning and we will get a play back of how the agent plays the game after it is trained.

#### The story of Frozen Lake 

##### Winter is here. You and your friends were tossing around a frisbee at the park when you made a wild throw that left the frisbee out in the middle of the lake. The water is mostly frozen, but there are a few holes where the ice has melted. If you step into one of those holes, you'll fall into the freezing water. At this time, there's an international frisbee shortage, so it's absolutely imperative that you navigate across the lake and retrieve the disc. However, the ice is slippery, so you won't always move in the direction you intend. The surface is described using a grid like the following

<h5> SFFF<br>
FHFH <br>
FFFH <br>
HFFG</h5>

This grid is our environment where S is the agent’s starting point, and it’s safe. F represents the frozen surface and is also safe. H represents a hole, and if our agent steps in a hole in the middle of a frozen lake, well, that’s not good. Finally, G represents the goal, which is the space on the grid where the prized frisbee is located.

The agent can navigate left, right, up, and down, and the episode ends when the agent reaches the goal or falls in a hole. It receives a reward of one if it reaches the goal, and zero otherwise.

### How to run this file

To run the file we have to install the packages that we are using in this project <br>
gym -->  pip install gym

Then we can run the python file.

In the last step we can see that the agent plays the Frozen Lake game and gets to the goal.
