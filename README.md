# eww_modern-clock

A **modern, minimal clock widget** for Linux, inspired by the **Mond Rainmeter skin**,  
recreated using **eww**.

<img width="50%" src="https://github.com/user-attachments/assets/eae2a599-24e4-4b98-ae77-9d02298abedd" />

## 🕒 What is this?
This is a **desktop clock + date widget** that aims to be:
- clean
- modern
- minimal
- and very much **not Rainmeter**

It is a Linux **eww-based recreation** of the original Mond skin.

## 🎨 Inspiration & Credits
Based on the original **Mond** Rainmeter skin:

- Mond – VisualSkins  
  https://visualskins.com/skin/mond

- Mond (GitHub)  
  https://github.com/reisir/mondtholomew

All design credits go to the original author.  
This project is simply a **Linux port / reinterpretation**.

## ⚙️ Requirements
- Linux
- [eww](https://elkowar.github.io/eww/)

## 🚀 Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/noel560/eww_modern-clock.git
2. Copy (or symlink) it into your eww config directory:
   ```bash
   cd eww_modern-clock
   cp -r eww/* ~/.config/eww/
3. Install the required fonts:
   ```bash
   sudo cp fonts/* /usr/share/fonts/
   fc-cache -fv
4. Start the widget:
   ```bash
   eww daemon
   eww open clock
(If you have more monitors, edit the eww.yuck file)
