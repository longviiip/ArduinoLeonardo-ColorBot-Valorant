<h1 align="center">Colorant 🍇</h1>
### About
install `pip install pyserial`
`pip install pyautogui`
`pip install termcolor`
`pip install colorant`
`pip install opencv-python`
`pip install mss`
`
Colorant is a highly efficient color aimbot designed to rapidly scan for a range of purple color of the valorant enemy player outlines on your screen and precisely aim/shoot at it, without any interference with the game memory or files of Valorant.

Unlike conventional video game cheats that rely on the process memory to function, Colorant adopt a unique approach by avoiding any memory reading altogether. This innovative approach has the potential to remain undetectable by anti-cheat mechanisms that typically attempt to block memory reads. Additionally, sending input to the video game without triggering any flags can be a challenging aspect to consider.

The primary objective of this project is to showcase a proof of concept, demonstrating the potential of Colorant's novel approach to aimbot technology.

---

![image](https://user-images.githubusercontent.com/82477000/225608740-5f690006-9cc8-4d88-8a60-cda89d0f936f.png)

[![Downloads][downloads-shield]][downloads-link]
[![Discord][discord-shield]][discord-link]
[![Language][language-shield]][language-link]
[![License][license-shield]][license-link]

## Getting started

#### You will need the following prerequisites:
- [ARDUINO LEONARDO](https://www.amazon.com/Arduino-org-A000057-Arduino-Leonardo-Headers/dp/B008A36R2Y)
- [USB HOST SHIELD](https://www.amazon.com/Compatible-Arduino-Support-Android-Function/dp/B0B3TH6H6N)
- [Python](https://www.python.org/)

The initial setup can be a bit challenging, as you will need to set up your Arduino and USB host shield. It is important to note that some USB shields may come unsoldered, so you may need to solder both 5V ports and the bottom 3.3V port to ensure that it works correctly. For further clarification, you can refer to [THIS](https://www.youtube.com/watch?v=nBttwvgNOr8) video.

Next, you will need to download and install Python, with [Version 3.8](https://www.python.org/ftp/python/3.8.0/python-3.8.0-amd64.exe) being recommended as it was the version used to develop this project. Once Python is installed, you can download Colorant and install the necessary dependencies by using the command `pip install -r the-requirements.txt`.

To utilize the Arduino board as a computer mouse, you can choose from five different sketches that are located within the [ArduinoSketches](https://github.com/hafyzwithawhy/Colorant/tree/main/ArduinoSketches) folder. Connect the Arduino board to your computer and open the Arduino IDE software. Then, select the appropriate board and port, and upload the desired sketch. By following these steps, you can turn your Arduino board into a functional computer mouse, enabling you to control the cursor and perform clicking functions using the board's hardware. I suggest trying out each of the five sketches to determine which one works best for your mouse.

With the prerequisites and dependencies installed, you can now run the `main.py` file, which is the main entry point of the program. You do not need to make any changes to the code, as it is ready to use.

By following these steps, you can enjoy using Colorant to quickly and accurately aim and shoot within your favorite valorant gamemode.
