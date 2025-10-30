# TEDS WORLD PROJECTS - Electronics Engineer Toolkit

A modern, responsive web application providing a suite of essential, high-quality tools for electronics engineers, students, and hobbyists. Built with a focus on a clean user interface, usability, and performance.

![TEDS WORLD PROJECTS Screenshot](https://raw.githubusercontent.com/teds-world-projects/electronics-toolkit/main/screenshot.png) 

## ✨ Core Features

This toolkit is organized into three distinct, powerful modules:

### 1. Resistor Color Code Decoder
- **4 & 5-Band Support:** Accurately decodes both 4-band and 5-band resistors.
- **Intuitive Input:** Simply enter comma-separated color names (e.g., `brown, black, orange, gold`). The input is case-insensitive and handles minor spacing issues.
- **Formatted Output:** Displays the precise resistance value with the correct SI unit (Ω, kΩ, MΩ, GΩ) and the corresponding tolerance percentage.

### 2. Ohm's Law Calculator
- **Flexible Calculation:** Calculate Voltage (V), Current (I), or Resistance (R) with ease.
- **Automatic Detection:** The tool automatically determines which value to calculate based on the two fields you fill in.
- **Clear Results:** The calculated value is displayed clearly and also populates the empty field, completing the formula.

### 3. Standard Capacitor Value Lookup
- **E12 & E24 Series:** Finds the closest standard capacitor value from both the E12 (10% tolerance) and E24 (5% tolerance) series.
- **Versatile Input Parser:** Accepts various common capacitance formats, such as `100pF`, `22nF`, `0.1uF`, and `4.7µF`.
- **Side-by-Side Comparison:** Presents the closest values for both series, allowing you to choose the best fit for your application.

---

## 🚀 Key Functionality

- **Calculation History:**
  - **Save Your Work:** Save any calculation from any tool with a single click.
  - **Local Persistence:** Your last 5 calculations are automatically saved to your browser's local storage, so they're waiting for you when you return.
  - **Easy Management:** Recall recent results or clear the entire history with one button.

- **Modern & Responsive UI/UX:**
  - **Sleek Dark Theme:** A professional, eye-friendly dark mode with vibrant cyan and blue accents.
  - **Glassmorphism Effect:** Beautiful semi-transparent cards with a blurred background give the app a modern, layered feel.
  - **Fully Responsive:** The layout is optimized for a seamless experience on desktops, tablets, and mobile devices.

- **User-Friendly Conveniences:**
  - **Copy to Clipboard:** Instantly copy any result to your clipboard with a dedicated icon.
  - **Clear & Concise:** Error messages are user-friendly, helping you correct inputs quickly.

## 🛠️ Tech Stack

- **Frontend:** [React](https://reactjs.org/) (with Hooks)
- **Language:** [TypeScript](https://www.typescriptlang.org/)
- **Styling:** [Tailwind CSS](https://tailwindcss.com/)
- **State Management:** React Hooks (`useState`, `useEffect`) and a custom hook for `localStorage`.

## ⚙️ How to Use

1.  **Resistor Decoder:**
    - Type the resistor's color bands, separated by commas, into the input field.
    - Click **"Decode"**.

2.  **Ohm's Law Calculator:**
    - Fill in any two of the three fields (Voltage, Current, Resistance).
    - Click **"Calculate"**.

3.  **Capacitor Lookup:**
    - Enter the capacitance value you're looking for (e.g., `4.7nF`).
    - Click **"Find Standard Value"**.

4.  **Saving & History:**
    - After getting a result in any tool, click the **Save** icon (floppy disk) to add it to your history.
    - View your recent calculations in the **"Recent Calculations"** card at the bottom.

---

&copy; 2025 TEDS WORLD PROJECTS
