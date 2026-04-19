# 🖥️ 3D OpenGL Scene – Coffee Mug Environment

## 📌 Overview

This is the final project for CS 330 at SNHU

This project is a 3D graphics application developed using **C++ and OpenGL** that renders a fully interactive scene featuring a coffee mug placed on a textured surface. The purpose of this project is to demonstrate core computer graphics concepts such as transformations, lighting models, texture mapping, and camera systems.

The scene was designed to balance simplicity and realism while showcasing technical proficiency in building and rendering 3D objects from primitive shapes.

---

## 🎯 Features

* ✅ Interactive 3D camera (keyboard + mouse controls)
* ✅ Multiple 3D objects constructed from primitives
* ✅ Realistic lighting:

  * Ambient lighting
  * Diffuse lighting
  * Specular highlights
* ✅ Texture mapping using UV coordinates
* ✅ Material properties (shininess, reflectivity)
* ✅ Perspective and orthographic projection toggle
* ✅ Organized, modular C++ code structure

---

## 🧱 Scene Composition

The scene includes:

* A **textured table surface** (plane)
* A **coffee mug body** (cylinder)
* A **mug handle** (torus)
* A **mug base**

Each object is individually transformed using translation, rotation, and scaling to create a cohesive environment.

---

## 💡 Lighting Implementation

The lighting system combines:

* **Ambient lighting** for base illumination
* **Diffuse lighting** to simulate surface interaction with light
* **Specular lighting** for reflective highlights

Multiple light sources are used to enhance depth and realism, preventing the scene from appearing flat.

---

## 🧵 Texturing

* Textures are loaded using **stb_image**
* UV mapping ensures proper texture placement
* Texture scaling is applied to avoid distortion
* Different materials are used to contrast surfaces (e.g., table vs mug)

---

## 🎮 Controls

| Input         | Action                 |
| ------------- | ---------------------- |
| W / A / S / D | Move camera            |
| Q / E         | Move up / down         |
| Mouse         | Look around            |
| P             | Toggle projection mode |

---

## 🏗️ Project Structure

```
CS330Content/
└── Projects/
    └── 7-1_FinalProjectMilestones/
        ├── SceneManager.cpp
        ├── ShaderManager.cpp
        ├── ViewManager.cpp
        ├── ShapeMeshes.cpp
        ├── MainCode.cpp
        ├── shaders/
        └── textures/
```

* **SceneManager** → Builds and positions objects
* **ShaderManager** → Handles lighting and shaders
* **ViewManager** → Camera movement and projection
* **ShapeMeshes** → Mesh generation for primitives

---

## 🛠️ Technologies Used

* C++
* OpenGL
* GLSL (Shaders)
* GLM (Math library)
* stb_image (Texture loading)

---

## 🚀 How to Run

1. Open the project in your preferred C++ IDE (Visual Studio / VS Code / Codio)
2. Ensure OpenGL and required libraries are configured
3. Build and run `MainCode.cpp`
4. Use the controls to explore the scene

---

## 📸 Screenshots

<img width="919" height="631" alt="Coffee Mug" src="https://github.com/user-attachments/assets/af97b5f0-bfba-40dc-a42b-fc80d2f29a11" />

---

## 🧠 What I Learned

Through this project, I gained hands-on experience with:

* The OpenGL rendering pipeline
* Shader programming and lighting models
* Texture mapping and UV scaling
* Building complex objects from primitives
* Structuring a graphics application using modular C++ design

---

## 🔮 Future Improvements

* Add more objects to increase scene complexity
* Implement shadows for enhanced realism
* Introduce animation or physics
* Improve material realism with advanced shading techniques

---

## 👤 Author

**Tre Olson**
Computer Science – Software Engineering
YouTube Creator (Traizel)

---

## ⭐ Notes

This project was developed as part of a Computer Graphics course and refined for portfolio presentation.


