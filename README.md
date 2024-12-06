# ACAI | RGB LED Matrix Persistence of Vision Display

Welcome to the RGB LED Matrix Persistence of Vision Display project! This project involves spinning an RGB LED matrix to create a persistence of vision (POV) display.

## Description

This project demonstrates how to use an RGB LED matrix to create a POV display. By spinning the LED matrix at a high speed and controlling the LEDs, you can create the illusion of a stable image in mid-air. The project uses PlatformIO running on a Metro M4 Airlift Lite. It uses a web server to allow remote control of the display while it is in motion.

## Basics

Installing Visual Studio Code is heavily recommended, but not required. Feel free to use an IDE of your choice. The remainder of this documentation will assume that you are using Visual Studio Code. 
You can download VSCode [here](https://code.visualstudio.com/Download).

If you are using windows, please make sure you have C and C++ compilers availible and working on your machine.

Some great resources for doing this are included here:

1. [C++ Programming With VSCode](https://code.visualstudio.com/docs/languages/cpp)

2. [Install GCC Compiler & GDB Debugger for C/C++ on Windows (with Visual Studio Code) using MSYS2](https://www.youtube.com/watch?v=-gLsB2ZZXLs)

On Linux, you can install C/C++ dependencies by running the following commands:
```
sudo apt-get update
sudo apt-get install build-essential
```
This package includes the compilers to run the project.

If you don't already have it, the latest version of python is required to use PlatformIO
Their installation guide can be found [here](https://docs.platformio.org/en/latest/integration/ide/vscode.html#installation).

You can find python3 [here](https://www.python.org/downloads/).

It is important to note that linux requires you to install the python3-venv package as well, which can be installed using
```
sudo apt-get install python3-venv
```

## Installation

To get started with this project, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/Cole1111111/ACAI.git
    ```
2. Navigate to the project directory:
    ```sh
    cd ACAI
    ```
3. Install PlatformIO:
    ```sh
    pip install platformio
    ```
   Or install the PlatformIO Visual Studio Code Extension (Recommended)
   You can check out their documentation for the extension [here](https://platformio.org/install/ide?install=vscode).

## Usage

To run the project on the Arduino Uno, follow these steps:

1. Connect your Arduino Uno to your computer via USB.
2. Upload the code to the Arduino Uno using PlatformIO:
    ```sh
    pio run --target upload
    ```
    Or use Visual Studio Code extension to call the upload function
   
4. Make sure to follow the hardware setup instructions provided in the documentation.

Using the Visual Studio Code extension for PlatformIO is highly recommended! It creates a tab in VSCode to make this process a one-click button.

## Contributing

This project is not open for contribution at this time. It is a senior development project. Please reach out regarding additions to the projects.

## License

This project is licensed under the MIT License
