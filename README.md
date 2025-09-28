# 🧱 MineJava

UNITY game like other sandbox block games

## 🚀 Features

- First-person movement and jumping
- Left-click to place blocks
- Right-click to destroy blocks
- Simple physics-based player controller
- Easy-to-expand block system

## 🛠 Requirements

- Unity 2021 or newer
- A basic cube prefab named `Block` with a collider and material
- A player object with a Rigidbody and Collider
- Main Camera tagged as `MainCamera`

## 📦 Setup Instructions

1. Clone or download the project.
2. Open in Unity.
3. Create a cube prefab:
   - GameObject → 3D Object → Cube
   - Add a material (e.g., grass, dirt)
   - Drag into `Prefabs` folder and name it `Block`
4. Add the `MiniMinecraft.cs` script to your Main Camera.
5. Assign the `Block` prefab to the script in the Inspector.
6. Add a Rigidbody to your player object.
7. Press Play and start building!

## 🎮 Controls

| Action           | Key / Mouse        |
|------------------|--------------------|
| Move             | WASD               |
| Jump             | Space              |
| Place Block      | Left Click         |
| Destroy Block    | Right Click        |

## 📌 Notes

- Blocks are placed at rounded positions for grid alignment.
- You can expand this by adding terrain generation, inventory, crafting, and multiplayer.

## 📄 License

This project is open-source and free to use for learning and experimentation. No commercial use without permission.


