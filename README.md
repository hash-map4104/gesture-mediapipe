# 🎨 Air Canvas: Hand Gesture Drawing

An interactive computer vision application that lets you draw on your screen in real-time using just your hand gestures. Built with Python, OpenCV, and Google's MediaPipe.

## ✨ Features

* **Gesture-Based Controls:** Draw, erase, select colors, and clear the canvas using intuitive hand shapes.
* **Cursor Smoothing:** Built-in coordinate smoothing ensures your drawing lines are fluid and natural, not jagged or jumpy.
* **Adjustable Brush Size:** Easily scale the thickness of your drawing brush up or down using your keyboard.
* **Dynamic UI:** Features a sleek, semi-transparent header bar with selectable color swatches and active status indicators.
* **On-Screen Feedback:** Real-time toast notifications for saving files, along with an active mode/status display.

## 🛠️ Requirements

Ensure you have Python 3.7+ installed. You will need the following libraries to run this project:

```bash
pip install opencv-python mediapipe numpy

## 🎮 Quick Start: How to Use It

1. **Launch the App:** Run the script in your terminal (`python your_script_name.py`). Your webcam will activate, and a window will appear.
2. **Show Your Hand:** Hold your hand up to the camera. The app tracks a single hand at a time.
3. **Select a Color:** * Hold up **2 fingers** (Index and Middle finger).
   * Move your hand so the on-screen cursor hovers over the color palette at the top of the screen.
   * Hover over a color block to select it, or hover over the **ERASE** block to switch to the eraser.
4. **Start Drawing:** * Hold up **1 finger** (Index finger only).
   * Move your finger around the screen to paint!
5. **Clear the Screen:**
   * Close your hand into a **Fist** (0 fingers). The entire canvas will wipe clean instantly.
6. **Pause/Hover:**
   * If you hold up 3 or 4 fingers, the app will pause drawing and just let you move your cursor around the screen without leaving a mark.

---

## ⌨️ Keyboard Shortcuts & Sizing

While the application window is active and in focus, use your keyboard to control the brush size and save your work:

| Key | Action | Description |
| :--- | :--- | :--- |
| **`+`** or **`=`** | **Increase Size** | Makes the drawing brush thicker (Max: 40px). |
| **`-`** | **Decrease Size** | Makes the drawing brush thinner (Min: 2px). |
| **`s`** | **Save Image** | Saves your current masterpiece as a `.png` file in your project folder. |
| **`q`** | **Quit** | Safely closes the application and turns off your webcam. |

*(Note: The eraser size is currently fixed to a large radius for quick and easy mistake clearing!)*


