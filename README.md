# 🌈 WS2812B NeoPixel LED Effects — Arduino Uno

A collection of amazing LED effects for WS2812B NeoPixel strip using Arduino Uno and FastLED library.

---

## 📸 Hardware Used

| Component | Details |
|-----------|---------|
| Microcontroller | Arduino Uno |
| LED Strip | WS2812B NeoPixel (4 LEDs) |
| Library | FastLED |

---

## 🔌 Wiring

```
Arduino Uno        WS2812B Strip
-----------        -------------
5V         →       +5V
GND        →       GND
Pin 6      →       DI (Data In)
```

> ⚠️ Make sure to connect to **DI** (Data In) not **DO** (Data Out)!

---

## ✨ Effects

| Effect | Description |
|--------|-------------|
| 🌠 Meteor Rain | Comet with fading tail |
| 🔥 Fire | Flickering flame simulation |
| 🌊 Color Wave | Smooth rainbow scroll |
| ✨ Twinkle | Random sparkles |
| 🏀 Bouncing Ball | Ball bounces back and forth |
| ⚡ Strobe | Camera flash effect |
| 💜 Breathing | Smooth fade in and out |
| 🚔 Police | Red blue emergency flash |
| 🎨 Color Fill | Fills strip color by color |
| 🌈 Rainbow Chaser | Rainbow dot chase |

---

## 🚀 Getting Started

### 1. Install Library
- Open Arduino IDE or ArduinoDroid
- Install **FastLED** library

### 2. Upload Code
- Open `main.ino`
- Select board → **Arduino Uno**
- Select correct COM port
- Click Upload

### 3. Customize
Change these values at the top of the code:
```cpp
#define PIN      6    // Change to your data pin
#define NUM_LEDS 4    // Change to your LED count
#define BRIGHTNESS 255 // 0-255
```

---

## 📁 Project Structure

```
ws2812b-led-effects/
├── main/
│   └── main.ino       # Main Arduino sketch
└── README.md          # This file
```

---

## 🛠️ Tested With

- Arduino Uno
- ArduinoDroid (Android)
- FastLED v3.x

---

## 📜 License

MIT License — free to use and modify!

---

## 🙌 Credits

Built with ❤️ using [FastLED](https://github.com/FastLED/FastLED)
