# Connect Four – Blazor Web App 🎮

This project is a **Connect Four game** built using **Blazor (.NET 8)** as part of the Microsoft Learn module:

> **Build a Connect Four game with .NET and Blazor**  
> https://learn.microsoft.com/en-us/training/modules/dotnet-connect-four/

The goal of this project is to learn how to:
- Build reusable Blazor components
- Separate game logic from UI
- Use dependency injection for shared state
- Handle user interaction and UI updates in Blazor

---

## 🚀 Features

- Interactive Connect Four board
- Two-player turn-based gameplay
- Automatic piece drop with animation
- Win detection (horizontal, vertical, diagonal)
- Tie detection
- Error handling (column full, game over)
- Reset game without page refresh
- Server-side interactivity using Blazor Server

---

## 🧠 Architecture Overview

The application follows a **clean separation of concerns**:

GameState.cs → Game logic & rules
Board.razor → UI + user interaction
Home.razor → Hosts the board component
Program.cs → Dependency injection setup



### Key Concepts Used
- Razor Components
- Dependency Injection (`AddSingleton`)
- Component lifecycle (`OnInitialized`)
- Event handling (`@onclick`)
- CSS-based animation
- Blazor Interactive Server render mode

---

## Prerequisites
- .NET 8 SDK
- VS Code or Visual Studio 2022+

---
