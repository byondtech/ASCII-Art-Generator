# ASCII Art Generator

This is a Python program that generates ASCII art from an input image. The program uses the Pillow library to resize the image, convert it to grayscale, and convert each pixel to a string of ASCII characters.

## Getting Started

### Prerequisites

This program requires Python 3.x and the Pillow library to be installed.

### Installation

1. Clone the repository to your local machine.
2. Install the required dependencies by running **pip install -r requirements.txt** in the command line

### Usage

1.Run the program by executing the **ascii_art.py** file in the command line.
2. Enter a valid pathname to an image when prompted.
3. The program will generate an ASCII art representation of the image and display it in the console.
4. The program will also save the output to a file named **ascii_image.txt** in the current directory.

### Customization
The program provides options for customizing the output.

### Width

You can specify a custom width for the output by passing a **new_width** argument to the **main()** function. The default value is 100.
```
def main(new_width=100):
    # ...

```
### Characters

You can modify the list of ASCII characters used to generate the output by modifying the **ASCII_CHARS** list at the beginning of the script.
```
ASCII_CHARS = ["@", "#", "S", "%", "?", "*", "+", ";", ":", ",", "."]

```
## Acknowledgements
This program is based on a tutorial by <a href="https://www.youtube.com/channel/UC4JX40jDee_tINbkjycV4Sg">Murtaza's Workshop - Robotics and AI</a> on YouTube.
