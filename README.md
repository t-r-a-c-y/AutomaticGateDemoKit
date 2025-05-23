🚪 Automatic Gate Demo Kit
This project demonstrates an automatic gate control system using an Arduino Uno and an ultrasonic distance sensor. It simulates how automated gates can operate in real-world scenarios like parking lots or secure facilities.

🔧 Features
Object Detection: Uses an HC-SR04 ultrasonic sensor to detect objects within a 50 cm range.

Automatic Gate Control:

Gate opens automatically when an object is detected.

Gate remains open as long as the object is present.

Gate closes after 5 seconds once the object is no longer detected.

LED Indicators:

🔴 Red LED: Gate is closed.

🔵 Blue LED: Gate is open.

Buzzer Feedback:

Emits a continuous beep while the gate is open for audio feedback.

🧰 Components Used
🧠 Arduino Uno

📏 Ultrasonic Sensor (HC-SR04)

⚙️ Servo Motor

🔴 Red LED (cathode setup)

🔵 Blue LED (cathode setup)

🔊 Buzzer

⚡ Resistors and jumper wires

🔌 Breadboard and Power Supply

📝 How It Works
The ultrasonic sensor measures the distance in front of the gate.

If an object is within 50 cm, the servo motor rotates to open the gate.

While the object is still detected, the gate stays open.

Once the object is gone, a 5-second timer starts.

If no object is detected after 5 seconds, the servo rotates back, closing the gate.

LEDs and buzzer give visual and audio status feedback.

⚙️ Future Improvements (Optional)
Add an LCD screen to display distance and status.

Integrate RFID or keypad for authorized entry.

Use a relay and motor for a full-scale gate.