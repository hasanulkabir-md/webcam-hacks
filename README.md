
# Webcam Hacks

This project allows you to control your social media using webcam gestures. By detecting a yellow color on the screen, it triggers actions like pressing the spacebar.

## Installation

To install the required dependencies, create a virtual environment and install the packages by running:

```bash
pip install -r requirements.txt
````

Make sure you have `opencv-python`, `numpy`, and `pyautogui` listed in your `requirements.txt` file. To generate the `requirements.txt` file, use:

```bash
pip freeze > requirements.txt
```

## Usage

To run the webcam control script:

```bash
python src/webcam_control.py
```

Ensure your webcam is connected and functional before starting the program. The script will detect yellow color in the video feed and perform actions like pressing the spacebar based on the position of the detected color.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

````

### `.gitignore`

```bash
# Python bytecode
__pycache__/
*.pyc
*.pyo

# Virtual environments
.venv/
env/

# IDE or editor files
.idea/
.vscode/

# MacOS specific files
.DS_Store

# Windows specific files
Thumbs.db
````

---
