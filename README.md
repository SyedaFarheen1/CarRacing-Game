# 🏎️ Mario Kart Themed Car Racing Game (8086 Assembly)

**Computer Organisation & Assembly Language – Final Project (3rd Semester)**

This project is a **Mario Kart–inspired car racing game developed using 8086 Assembly Language**.  
The game challenges players to maneuver their kart between lanes, avoid obstacles, and collect stars to maintain fuel and increase their score.

The game runs inside a **DOS environment using DOSBox**, demonstrating how Assembly programs can be executed and interacted with within an emulated system.


# 👩‍💻 Developers

- **Syeda Farheen** – [GitHub Profile](https://github.com/SyedaFarheen1)
- **Mariyam Iqbal** - [GitHub Profile](https://github.com/marzipanmomo)

# 🎮 Game Description

In this **lane-based racing game**, the player controls a kart that must avoid obstacles while collecting stars to survive as long as possible.

The gameplay focuses on **quick reactions and strategic movement** between lanes while managing a **fuel system that continuously decreases over time**.

# 🎯 Gameplay Mechanics

### Player Controls

| Key | Action |
|-----|------|
| ⬅ **Left Arrow** | Move kart to the **left lane** |
| ➡ **Right Arrow** | Move kart to the **right lane** |

The player must continuously switch lanes to **avoid obstacles and collect stars**.

# ⚠️ Obstacles

The player must avoid the following obstacles:

- 🍌 **Banana Peel**
- 🚗 **Enemy Car Type 1**
- 🚗 **Enemy Car Type 2**

Colliding with obstacles negatively impacts gameplay and may result in losing the game.

# ⭐ Power-Ups

**Stars** appear during the game and provide the player with benefits.

Each collected star:

- **Refills the fuel bar**
- **Adds +10 points to the score**

Collecting stars is essential for surviving longer in the game.

# ⛽ Fuel System

The game includes a **fuel bar that gradually decreases over time**.

If the player does not collect stars to replenish fuel, the fuel bar will eventually **run out and the game will end**.

# 🛠 Technologies Used

- **8086 Assembly Language**
- **NASM Assembler**
- **DOSBox Emulator**
- **Notepad++ (for editing and executing the assembly code)**

---

# ▶️ How to Run the Game

Follow the steps below to run the game on your system.

## 1️⃣ Download Required Files

Download the following files from this repository:

- `DOSBoxPortable.zip`
- `Notepad++Portable.zip`
- `MarioKart.asm`

---

## 2️⃣ Extract the Files

Unzip both portable folders.

After extraction you should have:

```
DOSBoxPortable
Notepad++Portable
```

## 3️⃣ Create a Main Project Folder

Create a folder (for example):

```
MarioKartGame
```

Place the following files inside it:

```
MarioKartGame
│
├── DOSBoxPortable
├── Notepad++Portable
└── MarioKart.asm
```

## 4️⃣ Open the Assembly File

1. Open the **Notepad++Portable** folder  
2. Run **Notepad++.exe**  
3. Open the file **MarioKart.asm**

## 5️⃣ Run the Game

Press the following key combination inside **Notepad++**:

```
ALT + R
```

This will assemble and execute the program, launching the game inside **DOSBox**.

# 📚 Academic Context

This project was developed as part of the **Computer Organisation & Assembly Language** course during the **3rd semester**.

The project demonstrates practical implementation of:

- Low-level programming
- Keyboard input handling
- Memory manipulation
- Basic graphics logic
- Game loop implementation
- DOS-based program execution
