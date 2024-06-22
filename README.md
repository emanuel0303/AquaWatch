# AquaWatch 🌊

AquaWatch is an advanced water quality monitoring system designed to measure and display turbidity levels in real-time. This project uses a LiquidCrystal I2C display and a turbidity sensor to provide visual feedback on the clarity of water.

## Features ✨

- **Real-time Monitoring:** Continuously reads turbidity levels from the sensor.
- **Visual Feedback:** Displays turbidity levels on an LCD screen and indicates water quality using LEDs.
- **Simple Setup:** Easy to configure and deploy with minimal components.

## Components 🛠️

- Arduino board
- LiquidCrystal I2C display (16x2)
- Turbidity sensor
- 3 LEDs (for clear, cloudy, and dirty water indication)
- Jumper wires
- Breadboard

## Circuit Diagram 🌐

![Circuit Diagram](link_to_circuit_diagram_image)

## Installation 🛠️

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/AquaMonitor.git
    cd AquaMonitor
    ```

2. **Install the LiquidCrystal_I2C library:**
   - Open Arduino IDE.
   - Go to **Sketch** > **Include Library** > **Manage Libraries**.
   - Search for `LiquidCrystal_I2C` and install it.

3. **Upload the Code:**
   - Open the `AquaMonitor.ino` file in the Arduino IDE.
   - Connect your Arduino board to your computer.
   - Select the correct board and port under **Tools**.
   - Click on the **Upload** button.

## Wiring Instructions 🔌

1. **LiquidCrystal I2C Display:**
   - VCC to 5V
   - GND to GND
   - SDA to A4 (on most Arduino boards)
   - SCL to A5 (on most Arduino boards)

2. **Turbidity Sensor:**
   - VCC to 5V
   - GND to GND
   - Signal to A0

3. **LEDs:**
   - Connect the anodes of the LEDs to digital pins 3, 4, and 5 respectively.
   - Connect the cathodes to GND through a 220-ohm resistor.

## Usage 🚀

1. **Power the Arduino:** Connect the Arduino to a power source.
2. **Deploy the Sensor:** Place the turbidity sensor in the water body you want to monitor.
3. **View Results:**
   - The LCD will display the turbidity level.
   - The LEDs will indicate water quality:
     - **Green LED (Pin 3):** Clear water
     - **Yellow LED (Pin 4):** Cloudy water
     - **Red LED (Pin 5):** Dirty water

 ## License 📄
This project is licensed under the GNU General Public License v3.0. See the LICENSE file for details.

## Contact 📧
For questions or support, please contact us at emanuelsoloman53@gmail.com.

Enjoy monitoring water quality with AquaWatch! 💧
