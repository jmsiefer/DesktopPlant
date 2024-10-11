# DesktopPlant

A Python script using `pygame` to animate a plant GIF. It allows dragging the animation window across the desktop while playing the animated frames in a transparent window.

## Features

- **Animated GIF Display**: Uses `pygame` and `PIL` to load and display an animated plant GIF with transparency.
- **Draggable Window**: Allows dragging the animation window across the screen.
- **Transparency**: Displays the animation with a transparent background for a clean overlay on the desktop.

## Requirements

- Python 3.x
- `pygame` library for displaying the animation.
- `PIL` (Python Imaging Library) for handling GIF frames.
- `pywin32` library for window manipulation on Windows.
- `Plant.gif`: Animated GIF file of the plant.

To install the required libraries, run:
```bash
pip install pygame pillow pywin32
```

## Usage

1. **Update File Paths**: Modify the `gif_path` in the script to the location of `Plant.gif` on your system:
   ```python
   gif_path = r'C:\path\to\Plant.gif'
   ```

2. **Run the Script**:
   ```bash
   python Plant.py
   ```

3. **Interaction**:
   - Click and drag the animation window to move it around the screen.
   - The animation will loop through the frames of the plant GIF.

## Notes

- Ensure the path to `Plant.gif` is correctly set in the script.
- The window will be transparent and frameless, suitable for overlaying on the desktop.
- Adjust the `animation_speed` variable to change the speed of the GIF animation.
- This script is designed for Windows due to the use of `pywin32` for window transparency and dragging.

## License

This project is licensed under the MIT License. See the `LICENSE` file for details.

## Author

Josh

---

Feel free to contribute or report any issues you encounter!
