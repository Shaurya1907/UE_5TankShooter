🪖 Battle Blaster (UE5 Tank Shooter)
A 3D Tank Shooter built with Unreal Engine 5 and C++

A real-time combat game focused on implementing core gameplay systems such as movement, shooting mechanics, AI behavior, and game state management using Unreal Engine’s C++ framework.

This project demonstrates how fundamental game development concepts come together to form a complete playable experience.

🎮 Overview

Control a tank in an arena filled with AI-controlled towers and survive while eliminating all enemies.

Destroy all enemy towers before they eliminate you
Avoid incoming projectiles using movement and positioning
Aim precisely and manage combat situations strategically

The game emphasizes clean architecture, modular design, and reusable systems.

⚙️ Features
🚗 Player-controlled tank movement
🎯 Turret rotation and aiming system
💣 Projectile-based combat
❤️ Health and damage system
🤖 AI-controlled enemy towers
🧠 Game mode with win/lose conditions
📢 On-screen debug messaging
🏗️ Project Structure
Source/
│
├── BasePawn
├── Tank
├── Tower
├── Projectile
├── HealthComponent
├── BattleBlasterGameMode
├── BattleBlasterGameInstance
├── ScreenMessage
└── BattleBlaster
🧩 System Overview
🔹 BasePawn

Handles shared functionality such as mesh setup, turret rotation, and firing logic. Acts as the foundation for both player and enemy entities.

🔹 Tank

Player-controlled pawn responsible for movement, input handling, and camera control. Implements user interaction with the game world.

🔹 Tower

Enemy AI unit that continuously tracks the player, rotates its turret, and fires projectiles automatically.

🔹 Projectile

Handles movement, collision detection, and damage application upon impact.

🔹 HealthComponent

A reusable component that manages damage intake, health tracking, and destruction behavior.

🔹 GameMode

Controls overall game flow, including initialization, win conditions, and loss conditions.

## 📸 Screenshots

### 🎮 Gameplay Overview
![Gameplay](Images/demo1.png)

### 💥 Combat System
![Combat](Images/demo3.png)

### 🤖 Enemy Towers
![Towers](Images/demo4.png)

### 🏆 Victory State
![Victory](Images/demo2.png)

🎮 Controls
Action	Key
Move Forward	W
Move Backward	S
Turn Left	A
Turn Right	D
Aim	Mouse
Fire	Left Click
⚙️ Setup Instructions
1. Clone the repository
git clone https://github.com/Shaurya1907/UE_5TankShooter.git
2. Open the project

Open the .uproject file in Unreal Engine 5

3. Build

Compile the project inside the editor

4. Run

Press Play to start the game

This project is licensed under the MIT License. See the Licence.txt file for details.

🧠 Notes

This project was developed to strengthen understanding of:

Object-oriented programming in C++
Unreal Engine gameplay architecture (Actors, Pawns, Components)
AI behavior and interaction systems
Collision detection and physics handling
Game loop design and state management