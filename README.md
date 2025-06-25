
# 🎶 ComradeAnthem-USSRWave

**Arduino Buzzer Project — Soviet National Anthem**

This project plays the Soviet Union National Anthem using an Arduino and a passive buzzer. A fun, beginner-friendly microcontroller project designed for educational, nostalgic, or entertainment purposes. All note frequencies are embedded directly within the code — no extra files required.

## 🏛️ Why the Soviet Anthem?

The Soviet Anthem is globally recognized for its grand, commanding sound. This project brings that historic tune to life with minimal electronics — blending nostalgia with hands-on learning.

⚠️ Note: This is purely for educational and entertainment purposes — no political affiliations implied.

---

## 🚩 Features
- Plays the **Soviet National Anthem** on a buzzer  
- Uses only Arduino and basic components  
- Self-contained code (no external `.h` files needed)  
- Continuous loop for non-stop anthem playback  
- Easy to modify for other melodies  

---

## 🎯 Components Required
- Arduino UNO (or compatible board)  
- Passive Buzzer  
- Jumper Wires  
- Breadboard (optional)  
- USB Cable for Programming  

---

## ⚡ Wiring

| Component | Arduino Pin |
|-----------|-------------|
| Buzzer (+)| Pin 7      |
| Buzzer (-)| GND        |

You can modify the `buzzerPin` in the code for different setups.

---

## 📸 Circuit Diagram
![ComradeAnthem-USSRWave Photo](https://github.com/user-attachments/assets/488adfe4-1904-4408-83db-4f5a311129e5)

---

## 🎬 Video Demonstration

Watch the project in action! 🚩

https://github.com/user-attachments/assets/9aec8bab-2d97-41ee-9a2e-b7ceb228bd49

---

## 📂 How to Use

1. Clone the repository:

```bash
git clone https://github.com/RohanVerma1308/ComradeAnthem-USSRWave.git
```

2. Open the `.ino` file in the Arduino IDE  
3. Upload to your board  
4. Listen as your Arduino proudly plays the anthem  

---

## 🎵 Demo

Your Arduino will play the **Soviet National Anthem** continuously through the buzzer.  
You can enhance the project by adding LEDs, modifying timing, or inserting other tunes.

---

## 🛠️ Customization

You can easily:

✔ Change the melody by editing the `melody[]` and `noteDurations[]` arrays  
✔ Add LEDs or other components with `digitalWrite()` commands  
✔ Control looping behavior by adjusting code placement  

---

## 🟥 Disclaimer

This project is for **educational**, **nostalgic**, and **hobbyist** purposes only.  
It is not affiliated with or intended to promote any political ideologies.

---

## ❤️ Inspired By

- Arduino community sound projects  
- Hobbyist buzzer music examples  
- Open-source learning initiatives  

**Enjoy building, experimenting, and making your buzzer sing! 🚩**

---

## 📄 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this project with proper attribution.  

For full license details, see the [LICENSE](LICENSE) file.

---

## 🎯 Project Motivation

This project was created as a fun way to combine electronics, music, and programming using Arduino. It provides a hands-on example of how microcontrollers can be used to generate recognizable melodies through simple components like buzzers.

Whether you're a beginner learning Arduino or an enthusiast building creative sound projects, this repository serves as an entertaining and educational example.

---

## ⚙️ Technical Details

- The project uses `tone()` function to generate musical notes on a passive buzzer  
- Frequencies for all required musical notes are embedded directly in the code  
- Uses a single digital output pin (Pin 11 by default)  
- Melody playback is handled using timed delays between notes  
- You can adapt this for other melodies by changing the frequency arrays  

---

## 🤝 Contributing

Contributions are welcome! Feel free to:

- Submit pull requests with new melodies  
- Improve timing, note accuracy, or functionality  
- Share ideas for enhancing the project  

**To contribute:**

1. Fork the repository  
2. Create a new branch  
3. Make your changes  
4. Submit a pull request  

---

## 📢 Feedback & Support

For questions, suggestions, or issues, feel free to open an issue on this repository.  

**Happy Building, Comrade! 🚩**

---
