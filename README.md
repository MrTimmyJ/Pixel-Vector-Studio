# Pixel-Vector-Studio
Create pixel-perfect vector designs with this advanced editor

Author: Timothy Johnson <br>
Date: February 2025 to April 2025


### 🔗 Live Demo

[Pixel Vector Studio](https://vec-art.netlify.app/)

## Overview

&nbsp;&nbsp;&nbsp;&nbsp;An interactive, canvas-based vector editor for pixel-precise drawing.
Built with vanilla JavaScript and HTML5, this app supports multiple layers, ruler guides, zoom/pan controls, and a customizable toolset.
Ideal for retro-style art, tilemaps, and creative prototyping.

&nbsp;&nbsp;&nbsp;&nbsp;PixelVector Studio is a fully client-side vector-style editor focused on pixel precision.
It offers multi-layer editing, tool-based drawing, grid customization, and user-friendly interactions like drag-to-pan and zooming.

Whether you're creating retro art or building a pixel-based tile system, this app makes it intuitive and fast to sketch, plan, and iterate.

🧩 Features

    🖼️ Canvas grid with customizable size and cell dimensions

    ✏️ Tools: select, draw lines, draw squares, eraser

    🧭 Rulers, zoom, and panning

    🎚️ Adjustable color presets (save, load, and clear)

    🧱 Multi-layer editing support

    🧰 Grid history with undo/redo

    📌 Click+drag selection & move

    🧠 Smart clipboard system

    ✅ Interactive UI and shortcut support

🔄 User Workflow

    Launch the web app (no install needed)

    Use the toolbar to select tools, pick colors, and adjust the grid

    Draw on the canvas and manage layers

    Save or export your creation (coming soon)

    Continue editing with full undo/redo support

⚙️ How It Works

🧠 Canvas System

    Uses an HTML5 canvas with p5.js integration (optional)

    Supports zooming and panning with mouse or touch

    Grid cells are stored in a 2D array with state tracking

    Layers stored as individual grid states with visibility toggles

🧰 Tool Handling

    Select, lines, squares, and eraser tools implemented using event listeners

    Color picker and presets update penColor in real-time

    Clipboard functionality allows copy/paste of selected areas

💾 State Management

    Layer-based drawing grid stored in layers[]

    Selection stored with start/end coordinates and offsets

    Undo/redo tracked in gridHistory[] and redoHistory[]

    Project name, path, and changes tracked for potential file operations

🖼️ Screenshots / Visuals

![pixelvectorstudio](https://github.com/user-attachments/assets/91b34ee6-0fab-47d6-b547-8bf334ab266b)

🧰 Technologies Used
    
    🐍 JavaScript	Main programming language
    
    🖼️ HTML5 Canvas	Drawing surface and rendering logic
    
    🎨 CSS	Interface styling and layout
    
    🔧 p5.js Simplified drawing and transformations
    
    🧠 DOM Events	For user input, tool usage, UI interactivity

🚀 Getting Started

    To run this app:

      git clone https://github.com/MrTimmyJ/PixelVector-Studio.git
      cd PixelVector-Studio
      open index.html

🌱 Upcoming Features

    🧱 Snap-to-grid enhancements

    🧮 Measurement tools for prototyping

    🎨 Add fill tool and ellipse tool

    💬 Interactive tutorial or guide overlay

🪪 License

This open-source project is available under the [MIT License](https://opensource.org/license/mit).
