# Shooting Game -  Object Pooling Challenge

## Description

This Unity project showcases a player character that shoots bullets without utilizing the object pooling pattern. 
The challenge part of this project has been exported as a Unity package, allowing others to access and explore the game project directly.

## Prerequisites

Before setting up and running the project, ensure you have the following installed and configured:
- **Unity:**
  - **Version:** Unity 2022.3.30f1 LTS or later (recommend using the latest stable release)
  - **Scripting Runtime:** .NET 4.x Equivalent

- **Development Environment:**
  - **IDE:** 
    - **Visual Studio 2019/2022** with Unity workload
    - **Visual Studio Code** with C# extensions

- **.NET Framework:**
  - **Version:** Compatible with Unity's scripting runtime (typically .NET 4.x)
  - **Note:** Unity does not currently support .NET 8.0. Stick to the version recommended by your Unity installation.

## Libraries and Dependencies

### 1. **UnityEngine**
- **Description:** Core library for Unity game development.
- **Usage:** Provides access to Unity's engine features such as MonoBehaviour, GameObject, Transform, and more.
- **Included By:** Default in all Unity projects.

### 2. **System.Collections & System.Collections.Generic**
- **Description:** Provides interfaces and classes that define various collections of objects, such as lists, dictionaries, and arrays.
- **Usage:** Used for managing collections like arrays (`Bullet[] bullets`) and other data structures.
- **Included By:** Default in Unity projects.

### 3. **Unity-Specific Dependencies**
- **Bullet Class:**
  - **Description:** Custom class representing the bullet prefab.
  - **Usage:** Manages bullet behavior including shooting and lifecycle.

### 4. **External Libraries (If Applicable)**
- **Note:** The provided `Player.cs` script does not explicitly require external libraries beyond Unity's built-in libraries.

