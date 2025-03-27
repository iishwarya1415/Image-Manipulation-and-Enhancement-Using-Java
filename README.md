# GRIME: Graphical Image Manipulation and Enhancement

> **📌 Code available upon request.**

GRIME is a Java-based image processing application that provides both **graphical** and **command-line** interfaces for performing advanced image manipulation. It was developed as part of the **Programming Design Paradigm (PDP)** course in the Master’s in Computer Science program.

---

## 🧠 Project Overview

GRIME offers a wide range of image enhancement and manipulation capabilities through a dual-interface system:

- **Graphical User Interface (GUI)** built with Java Swing
- **Command-Line Interface (CLI)** for batch processing and scripting

Users can load images in formats such as PNG, JPG, etc., apply a series of transformations, preview the results, and save the final image. Whether you're a developer automating image workflows or an end-user looking to enhance photos, GRIME provides a flexible and modular toolset.

---

## 🎯 Goals

- Demonstrate **clean software design** using **Model-View-Controller (MVC)**
- Provide both GUI and CLI usage options
- Support a wide range of **image operations**
- Allow **custom scripting** for complex workflows (CLI mode)
- Focus on **modularity**, **extensibility**, and **testability**

---

## 🧱 Architecture

### MVC Breakdown:

- **Model**: Handles the image data and processing logic.
- **View**: Displays the interface—either via GUI components or CLI output.
- **Controller**: Bridges user actions with model operations.

### Packages:
- Controller
- Model
- View
- Utils

  
Each component follows the **Single Responsibility Principle**, making it easy to maintain and expand.

---

## ✨ Features

### ✅ Common (GUI & CLI)
- Load and save images
- Apply blur, sharpen, sepia, and color-correction filters
- Extract red, green, blue, luma, and value channels
- Resize image (downscaling)
- Compress image using lossy compression
- Generate image histograms
- Adjust brightness and contrast levels

### 🖼️ GUI-Only
- Manual resizing via input fields
- Preview before/after effects in real time

### 💻 CLI-Only
- Intensity component extraction
- RGB channel split and combine
- Brightness adjustments using numerical input
- Split view rendering of effects

---

## 🔧 How to Run

### 🟢 Run via IntelliJ / Any Java IDE
1. Open `Main.java`
2. Run the application
3. GUI will launch; use "Load" to import an image
4. Apply filters or transformations
5. Use "Save" to export the image

### 🟡 Run via JAR

To launch GUI:
```bash
java -jar Program.jar
