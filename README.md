# 🎮 Java Platformer Game (Tutorial-Based Project)

![Game Poster](https://github.com/thecloudwalkerx/platformerGame/blob/main/Game%20Poster.png)

This repository contains a **2D platformer game** built in **Java**, following the *Platformer Tutorial Series* by [**Kaarin Gaming**](https://www.kaaringaming.com/).  
The purpose of this project is **educational** — to learn the fundamentals of Java game development through hands-on replication, code exploration, and experimentation.

---

## 🧩 Project Overview

This project implements the core systems of a classic 2D platformer, including:

* Game window and rendering pipeline  
* Fixed-time-step **game loop**  
* Keyboard input handling  
* Player **movement, jumping, and gravity**  
* Level loading and **collision detection**  
* Game state management (Menu, Playing, Paused, etc.)  
* Basic **enemy AI**, objects, and interactive items  
* **Animations**, **parallax backgrounds**, and **sound effects**

All assets and logic are structured in a modular format, making it easy to extend or customize for future projects.

---

## 🎥 Gameplay Preview

https://github.com/thecloudwalkerx/platformerGame/blob/main/Gameplay%20Video.mp4

---

## 🧠 Learning Goals

This repository serves as a learning notebook rather than an original game.  
Through this build, I aimed to understand:

1. How low-level Java rendering works using **BufferedImage**, **Graphics2D**, and **JFrame**.  
2. How to manage timing, FPS, and delta updates in a real-time loop.  
3. How collision detection and tile-based movement systems operate.  
4. How to structure reusable game states and event systems.  
5. How animations and sprite sheets are parsed and rendered.  
6. How to handle simple physics like jumping and gravity.  

---

## 🛠️ Technologies & Tools

* **Language:** Java (JDK 17+)  
* **Frameworks / Libraries:** Native Java AWT & Swing  
* **IDE:** IntelliJ IDEA / Eclipse  
* **Assets:** Pixel art from [Pixel Frog](https://pixelfrog-assets.itch.io/)  
* **Tutorial Source:** [Kaarin Gaming YouTube Channel](https://www.youtube.com/@KaarinGaming)

---

## 🚀 How to Run

### 1. Clone this repository
```bash
git clone https://github.com/[your-username]/JavaPlatformerTutorial.git
cd JavaPlatformerTutorial
```

### 2. Open in your IDE
Open the project folder in IntelliJ IDEA or Eclipse.

### 3. Run the Main Class
Navigate to `main/java/Game.java` or the primary entry file used for your setup, and run it as a Java Application.

---

## 📦 Features Implemented

| Feature | Description |
|----------|-------------|
| **Game Window & Loop** | Custom rendering window and stable delta-time loop |
| **Input System** | Keyboard controls for player movement |
| **Sprites & Animations** | Player and enemy animations from sprite sheets |
| **Tile Collision** | Prevents player from walking through objects |
| **Gravity & Jump** | Realistic falling and jumping mechanics |
| **Game States** | Menu, Playing, Paused, Options |
| **Objects & Items** | Collectibles, traps, and power-ups |
| **Sound System** | Background music and sound effects |
| **Multiple Levels** | Load level data and transitions dynamically |

---

## 📂 Folder Structure

```
src/
 ├── entities/
 │    ├── Player.java
 │    ├── Enemy.java
 │    └── ...
 ├── levels/
 │    ├── Level.java
 │    ├── LevelManager.java
 │    └── ...
 ├── main/
 │    ├── Game.java
 │    ├── GameWindow.java
 │    ├── GamePanel.java
 │    └── ...
 ├── ui/
 │    ├── Menu.java
 │    ├── PauseOverlay.java
 │    └── ...
 ├── util/
 │    ├── Constants.java
 │    └── LoadSave.java
 └── audio/
      ├── SoundPlayer.java
      └── ...
```

---

## 📚 Reference Tutorial Series

This project follows the full *Java Platformer Tutorial Series* by **Kaarin Gaming**:

📺 **YouTube Playlist:** [@KaarinGaming - Platformer Series](https://www.youtube.com/@KaarinGaming)  
🌐 **Website:** [https://www.kaaringaming.com/](https://www.kaaringaming.com/)  
💻 **GitHub (Original Source):** [KaarinGaming/PlatformerTutorial](https://github.com/KaarinGaming/PlatformerTutorial)

---

## ☕ Credits & Acknowledgment

This repository is **not an original creation** — it is a **learning-based recreation** of Kaarin Gaming’s tutorial.  
All foundational code and logic concepts belong to the original author.

If you found their tutorials helpful, please consider supporting them:

**Buy Kaarin Gaming a Coffee:**  
👉 [https://www.kaaringaming.com/](https://www.kaaringaming.com/)  
👉 [YouTube: @KaarinGaming](https://www.youtube.com/@KaarinGaming)

*Special thanks to Kaarin Gaming for providing in-depth, beginner-friendly tutorials that inspire others to learn game development from the ground up.*

---
