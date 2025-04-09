## 🎨 Color Detection with OpenCV

This project uses OpenCV to build a simple yet effective color detection tool that detects and displays the name and RGB values of the color where the user double-clicks on an image. It’s built using Python and powered by a CSV color dataset.

---

### 📁 Files

- `color_detection.py`: Main script to run the color detection app.
- `colorpic.jpg`: The image on which colors will be detected (replaceable with any image).
- `colors.csv`: CSV file containing over 800 color names and their RGB/hex values.

---

### 🔍 Project Overview

#### Features:
- Detect color from any pixel in the image using mouse click.
- Display the name of the closest color based on RGB distance.
- Show RGB values of the selected pixel in real-time.
- Dynamically adjust text color for readability on light/dark backgrounds.

---

### 🖼️ How it Works

1. Load the image and CSV file of colors.
2. Display the image in a window.
3. On double-click, detect the pixel RGB value.
4. Match the RGB value to the closest one in the CSV using a distance function.
5. Display the color name and RGB values on top of the image.

---

### 🛠️ Technologies Used

- Python
- OpenCV
- Pandas

---


### 📦 Future Improvements

- Add GUI interface for image selection.
- Improve color-matching algorithm using Euclidean distance or LAB color space.
- Display HEX codes and copy to clipboard.
