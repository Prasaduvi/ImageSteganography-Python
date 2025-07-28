# ImageSteganography-Python
A Python project for image steganography using Tkinter
## 🎨 Project Overview

This is a simple Image Steganography tool built using Python's Tkinter for the graphical user interface and the Pillow library for image manipulation. Steganography is the art and science of writing hidden messages in such a way that no one, apart from the sender and intended recipient, suspects the existence of the message. This project allows you to:

* **Encode**: Hide secret text messages within an image.
* **Decode**: Extract hidden text messages from an image.

## ✨ Features

* User-friendly graphical interface powered by Tkinter.
* Ability to select image files (PNG, JPEG, JPG).
* Encodes text data into the least significant bits of image pixels.
* Decodes hidden messages from steganographically altered images.
* Displays original and decoded image information (size, dimensions).

## 🚀 Getting Started

### Prerequisites

Before you run the application, make sure you have Python installed on your system. This project requires the `Pillow` library.

You can install `Pillow` using pip:

```bash
pip install Pillow
````

### How to Run

1.  **Clone the repository (or download `ImageS.py`):**

    ```bash
    git clone [https://github.com/YourUsername/ImageSteganography-Python.git](https://github.com/YourUsername/ImageSteganography-Python.git)
    cd ImageSteganography-Python
    ```

    (Replace `YourUsername` with your GitHub username and `ImageSteganography-Python` with your repository name if you changed it).

2.  **Run the Python script:**

    ```bash
    python ImageS.py
    ```

### Usage

1.  **Encode a message:**

      * Click on the "Encode" button.
      * Select an image file you wish to use for hiding your message.
      * Enter your secret message in the provided text area.
      * Click "Encode" to save the new image with the hidden message (it will be saved as a `.png` file).

2.  **Decode a message:**

      * Click on the "Decode" button.
      * Select an image file that contains a hidden message.
      * The hidden message will be displayed in a text area.

## 🛠 Technologies Used

  * **Python 3.x**
  * **Tkinter**: Standard Python interface to the Tcl/Tk GUI toolkit.
  * **Pillow (PIL)**: Python Imaging Library, used for image processing functionalities.
