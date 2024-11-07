Pong Game in Assembly
Overview
This project is a classic Pong game implemented in assembly language. The aim was to challenge ourselves by diving deep into low-level programming and understanding the intricacies of hardware interactions.

Logic
The game logic for our Pong game includes:

1. Initial Setup: Setting up the display, initializing the ball and paddles, and preparing the game environment.

2. Game Loop: The core of the game, which includes:
    Input Handling: Capturing user inputs to move the paddles.
    Ball Movement: Updating the ball's position based on its current trajectory.
    Collision Detection: Checking for collisions between the ball and the paddles, walls, and scoring zones.
    Score Keeping: Updating the score when the ball passes a paddle.
    Rendering: Drawing the paddles, ball, and scores on the screen.

Challenges Faced
1. Low-Level Hardware Interactions
    Understanding Hardware Registers: We had to learn how to manipulate hardware registers directly for display output and input handling.
    Assembly Syntax: The syntax and structure of assembly language are quite different from high-level languages, requiring a steep learning curve.

2. Memory Management
    Manual Memory Allocation: Unlike high-level languages, we had to manage memory manually, keeping track of variable addresses and ensuring there were no conflicts.
    Stack Management: Properly using the stack for function calls and interrupts was crucial to maintain the game state.

3. Timing and Synchronization
    Precise Timing: Implementing precise timing mechanisms for smooth ball movement and paddle response required careful use of timers and interrupts.
    Synchronization: Ensuring that input handling, game logic, and rendering were perfectly synchronized to avoid glitches and provide a smooth gaming experience.

4. Debugging and Testing
    Limited Debugging Tools: Debugging assembly code can be challenging due to limited debugging tools and the complexity of low-level operations.
    Testing: Ensuring all game scenarios were tested thoroughly, especially edge cases involving ball and paddle collisions.

Conclusion
Creating a Pong game in assembly language was a challenging yet rewarding experience. It provided deep insights into how computers work at the hardware level and sharpened our problem-solving skills. Despite the hardships, successfully implementing this project brought immense satisfaction and a sense of accomplishment.

Thank you for checking out our Pong game in assembly! If you have any questions or suggestions, feel free to reach out. Happy gaming!
