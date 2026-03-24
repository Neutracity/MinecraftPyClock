# Minecraft Redstone Clock

A Minecraft-themed digital clock and alarm application built with Python for the **NSI** (Numérique et Sciences Informatiques) curriculum.

## Overview

The **Minecraft Redstone Clock** brings a blocky aesthetic to your desktop using a grid-based rendering system. It features dynamic textures like Redstone Lamps and Netherite blocks to display real-time data.

## Features

- Real-time Sync: Synchronized with system clock.
- Authentic UI: Uses original game assets (Quartz, Iron, Netherite).  
- Alarm System: Fully adjustable with interactive controls.  
- Audio & Visual Alerts: Minecraft-themed notifications using pygame.mixer and flashing lamp states.

## Technical Stack

- Language: Python 3.13  
- Graphics: tkinter (Canvas-based grid)  
- Audio: pygame.mixer  
- Core: Native time library

## Installation & Setup

### Using Nix (Recommended)

nix develop

### Manual Installation

pip install pygame  
python main.py

## How to Use

- Display: Shows system time (top) vs. target alarm (bottom).  
- Adjust: Use \+ and \- buttons to set the alarm.  
- Toggle: Use the "Alarme" button to activate or deactivate alerts.

## Academic Context

Developed as an NSI project to demonstrate:

- Object-Oriented Programming (OOP) for logic and UI.
- Event-Driven Programming for inputs and clock updates.  
- Custom Rendering via coordinate-to-grid mapping.

