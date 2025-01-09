Sheephish is a fun and interactive OpenGL-based game where players immerse themselves in an exciting challenge. The game combines visually appealing graphics with engaging mechanics, showcasing the capabilities of OpenGL.

**Features:**
🐑 Dynamic Gameplay: Engage with unique levels and challenges.
🎮 OpenGL Graphics: High-quality 2D/3D visuals rendered using OpenGL.
🕹️ Custom Controls: Intuitive input system for smooth gameplay.
🚀 Cross-Platform: Runs on Windows, Linux, and macOS.

**Installation**
Clone the Repository:

git clone [https://github.com/your-repo-url/Sheephish.git](https://github.com/noureen-aslam/Sheepish-Game.git)
cd Sheephish


Install Dependencies: Ensure you have the necessary libraries for OpenGL development:

GLUT
GLEW
Any additional frameworks required for your system.
Use your package manager:
Ubuntu/Debian:
sudo apt-get install freeglut3-dev glew-utils

macOS (with Homebrew):
brew install glew freeglut

Compile the Code: Use the provided Makefile (if available) or compile manually:
g++ -o sheephish main.cpp -lGL -lGLU -lglut

Run the Game:
./sheephish

**How to Play**
Objective: Guide the sheep through various obstacles to safety.
Controls:
Arrow keys for movement
Spacebar to jump
Tips: Avoid traps and collect power-ups to score higher!
Development
This project was built using:

Programming Language: C++
Graphics API: OpenGL
IDE: Visual Studio Code (or your preferred IDE)
Feel free to contribute! Submit a pull request or report issues via the issue tracker.
