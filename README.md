# Pirate Intelligent Agent

## Project Overview

For this project, I developed an intelligent pirate agent that could navigate through a maze to find a treasure. The goal was to apply reinforcement learning, neural networks, and deep Q-learning to a pathfinding problem.

Some of the code was provided as starter code, including the maze environment and supporting Python files used to run the game. My main responsibility was completing the Q-training algorithm in the Jupyter Notebook and training the intelligent agent. I implemented the reinforcement learning process that allowed the pirate to explore the environment, store experiences, learn from rewards and penalties, and eventually determine a successful path to the treasure.

During testing, I discovered that a high training win rate did not always mean that the agent had learned a reliable solution. At one point, the pirate became stuck repeatedly moving between two cells even though the training results showed a high win rate. I debugged this behavior and added a maximum step limit so that looping without reaching the treasure would be treated as an unsuccessful episode. After making these adjustments and retraining the model, the agent successfully completed the maze.

## What Do Computer Scientists Do and Why Does It Matter?

Computer scientists use technology, algorithms, and problem-solving skills to develop solutions to different types of problems. Their work matters because software is used throughout modern society to automate tasks, analyze information, improve efficiency, and solve problems that may be difficult to handle manually. This project showed me that computer science is not only about writing code. It also involves understanding how a system behaves, testing possible solutions, identifying problems, and improving a solution based on the results.

## How Do I Approach a Problem as a Computer Scientist?

I approach problems by first understanding what the program is expected to accomplish and then breaking the problem into smaller pieces. Instead of changing several things at once when something does not work, I have learned to test individual parts of the program and use the results to determine where the problem may be occurring.

This project was a good example of that process. When the pirate was not consistently reaching the treasure, I examined the agent's actions and Q-values instead of assuming the entire algorithm was incorrect. This helped identify a specific looping behavior and allowed me to make a targeted change to the training process. Breaking problems into smaller steps makes debugging more manageable and helps me understand why a solution works instead of only focusing on whether the program runs.

## What Are My Ethical Responsibilities to the End User and the Organization?

As a computer scientist, I have a responsibility to create software that is safe, reliable, fair, and respectful of the people who use it. Developers should consider issues such as privacy, security, bias, accessibility, and the possible consequences of automated decisions. This becomes especially important with artificial intelligence because an AI system can make decisions based on patterns it has learned rather than instructions for every individual situation.

I also have a responsibility to the organization to develop software that is dependable, maintainable, and appropriately tested. An AI system should not be considered successful simply because its performance statistics look good. Developers should test how the system behaves in realistic situations and identify unexpected behavior before it affects users. This project reinforced the importance of testing because the pirate initially showed a high training win rate while still having a problem with its learned behavior. Responsible development means looking beyond performance numbers and making sure that a system actually works as intended.
