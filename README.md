# Vacuum-Cleaner-Agent
Vacuum Cleaner Agent in pyhton


Task 1: Marks: 5
Design a simple reflex agent, that waters plants efficiently in a greenhouse.
Task Description:
• Environment:
▪ A 3x3 grid where each cell contains plants (Dry/Wet).
• Percepts:
▪ The agent senses the soil moisture level of the cell it is currently in.
• Actions:
▪ Move in four directions: Up, Down, Left, Right.
▪ Water the plant in its current cell if the soil is Dry.
• Goal.
▪ Make each plant Wet.

Model Based Agents

Task 2: Marks: 5

Implement a model-based agent for an autonomous cleaning robot that navigates a 5×5 room,
cleans dirt, and avoids obstacles. The robot maintains an internal model of the environment,
updates its knowledge dynamically, and optimizes its cleaning path.
Task Description:
• Environment:
▪ The warehouse is represented as a 5×5 grid, containing:
• Dirt (D): Locations that need to be cleaned.
• Obstacles (#): Fixed furniture that the robot must avoid.
• Empty Spaces (.): Areas where the robot can move freely.
• Robot (R): The agent navigating the room.
▪ Dynamic Changes in the Environment:
• The robot remembers which locations have been cleaned.
• The internal model updates after each cleaning action.
• Percepts:
▪ The grid layout (Dirt, Obstacles, Free Spaces).
▪ The current location of dirt (dirty or already cleaned).
▪ The robot’s current position in the room.
• Actions:
▪ Move (Up, Down, Left, Right): Navigate through empty spaces.
▪ Clean (C): Remove dirt from the current position.
▪ Update Internal Model: Mark cleaned areas to avoid unnecessary revisits.
• Goal:
▪ Maintain an Internal Model:
• Store the room layout, including dirt, obstacles, and empty spaces.
• Update the model when a dirt spot is cleaned.
▪ Adapt to Changes:
• Avoid revisiting already cleaned areas.
• Optimize movement using BFS for efficiency.
▪ Complete All Deliveries:

• Navigate to all dirt locations using the shortest path.
• Clean all dirty spots and update the internal model dynamically.
