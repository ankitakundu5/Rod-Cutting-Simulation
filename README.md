# Rod Cutting Simulation
This project is a HTML and Javascript application that simulates the Rod Cutting Problem using Dynamic Programming, visualizing the optimal way to cut a rod to maximize profit.

# Problem Statement
Given a rod of length n and an array of prices that contains prices of all pieces smaller than n, determine the maximum value obtainable by cutting up the rod and selling the pieces.

# Input
Input: User can enter space-separated prices for lengths 1 to n.

Rod Length: User inputs total rod length to cut.

# Output
Maximum profit that can be obtained.
List of cut sizes to achieve that profit.

# Visual Representation
Colorful blocks representing different cut lengths on a canvas.

# Logic and Approach
The program uses Dynamic Programming (Bottom-Up) to solve the rod cutting problem:

1. Create a DP table dp[] where dp[i] stores the maximum profit for a rod of length i.
2. For every length i, iterate over all possible first cuts j (from 1 to i).
3. Update the maximum profit.
   
# The app will display
Max profit

List of optimal cuts

A visual breakdown of the rod with color-coded segments


# Output
![image](https://github.com/user-attachments/assets/71ae520a-29a0-4e5e-9f78-08130032a22b)
