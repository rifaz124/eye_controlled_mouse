# eye_controlled_mouse

This project is a Python-based eye-controlled mouse using OpenCV library.

## Table of Contents

- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Description

The aim of this project is to control the mouse pointer using eye movement. It uses OpenCV library to detect the eyes and pupil. Then, it calculates the position of the pupil and maps it to the movement of the mouse pointer.

## Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/rifaz124/eye_controlled_mouse.git
   ```
   
2. Install the required dependencies:

   ```sh
   pip install -r requirements.txt
   ```
   
## Usage

1. Run the main.py script:

   ```sh
   python main.py
   ```  
2. Place your head in front of the camera and adjust the camera position so that your eyes are visible.
3. Look at the edges of your screen to move the mouse pointer in that direction.
4. Blink your eyes to perform a mouse click.

## Contributing
#Contributions are welcome! Here are the steps to contribute:

1. Fork the repository.
2. Create a new branch:
```sh
git checkout -b my-feature-branch

```
3. Make your changes and commit them:
```sh
git commit -am 'Add some feature'

```
4. Push your changes to your fork:
```sh
git push origin my-feature-branch

```

5. Create a pull request.
