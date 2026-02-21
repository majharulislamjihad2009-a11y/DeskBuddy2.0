# DeskBuddy2.0
A tiny AI-powered desk companion with emotions, weather, world time and focus tools

## Supported Versions

### ESP32-S3 Version 

- Display: SSD1306 OLED
- Wiring:
  - SDA → GPIO41
  - SCL → GPIO42
  - Touch → GPIO44
- Board: ESP32-S3

Features:
- Full DeskBuddy UI
- Weather + Forecast
- World Clock
- Pomodoro
- AI Popup
- WiFiManager Config Portal
- Triple Tap Config Mode


---

### ESP32-C3 Version (Viewer Edition)

- Display: SH1106 OLED
- Wiring:
  - SDA → GPIO8
  - SCL → GPIO9
  - Touch → GPIO3
- Board: ESP32C3 Dev Module

Same Features Included:
- Emotional Eyes
- Clock
- Weather + 3-day Forecast
- World Clock
- Pomodoro Timer
- AI Quotes (OpenRouter)
- WiFiManager Setup Portal
- Triple Tap Config Mode
- Double Tap Brightness
- Long Press Mood
- Extra Long Press AI Popup


## 🔌 Wiring

### ESP32-S3 Version

| Component     | Pin       | ESP32-S3 GPIO |
|---------------|-----------|---------------|
| OLED SDA      | SDA       | GPIO41        |
| OLED SCL      | SCL       | GPIO42        |
| OLED VCC      | VCC       | 3.3V          |
| OLED GND      | GND       | GND           |
| Touch Sensor  | OUT       | GPIO44        |
| Touch Sensor  | VCC       | 3.3V          |
| Touch Sensor  | GND       | GND           |


---

### ESP32-C3 Version

| Component     | Pin       | ESP32-C3 GPIO |
|---------------|-----------|---------------|
| OLED SDA      | SDA       | GPIO8         |
| OLED SCL      | SCL       | GPIO9         |
| OLED VCC      | VCC       | 3.3V          |
| OLED GND      | GND       | GND           |
| Touch Sensor  | OUT       | GPIO3         |
| Touch Sensor  | VCC       | 3.3V          |
| Touch Sensor  | GND       | GND           |

OLED I2C Address: `0x3C`
