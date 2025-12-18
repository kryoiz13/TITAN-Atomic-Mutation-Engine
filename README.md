# 🐉 TITAN Atomic Mutation Engine (v56)

**TITAN** is a high-performance automation suite for Bee Swarm Simulator. It is specifically engineered to bypass Roblox physics desync and UI lag using hardware-level mouse injection and advanced computer vision.

---

## 🚀 Key Features

* **Hydra-Grab Technology:** Mimics human micro-fumbles with a 6-click flurry to "weld" treats to the cursor, ensuring a 100% pickup rate regardless of server lag.
* **Contrast-Boost OCR:** Uses specialized grayscale thresholding to read white text on yellow bars (solving the "unreadable mutation" bug).
* **Floor-Value Logic ($\ge$):** Set a minimum percentage (e.g., 2%). TITAN will automatically stop if it detects that value OR anything higher (3%, 4%, etc.).
* **Persistent Memory:** Automatically saves your coordinate mapping and Scan Area to a local `config.json` file.
* **Session Statistics:** Real-time counter tracks exactly how many treats have been spent during your current run.

---

## 🛠️ Installation & Setup

1.  **Install Python:** Download [Python 3.10+](https://www.python.org/downloads/).
2.  **Install Tesseract OCR:** Download the [Windows Binaries](https://github.com/UB-Mannheim/tesseract/wiki/Install-Windows-Binaries). **Note:** Ensure the path in the script matches your installation folder.
3.  **Install Dependencies:**
    ```bash
    pip install customtkinter opencv-python numpy pytesseract pillow keyboard pynput
    ```
4.  **Run as Administrator:** Right-click your terminal or IDE and select **Run as Administrator**. This is required for the hardware-level mouse events to function inside the game window.

---

## 🎮 How to Use

1.  **Map Locations:** Click the **SET** buttons and right-click the corresponding positions in your game (Treat, Bee, and the 'Yes' confirmation button).
2.  **Scan Area:** Click **SELECT SCAN AREA** and draw a snug box around the location where the yellow mutation notification appears.
3.  **Configure:** Select your target mutation (e.g., Ability Rate) and enter your minimum floor percentage.
4.  **Engage:** * **F1:** Start/Stop the engine.
    * **F2:** Pause/Resume (useful for manual checks).
    * **F3:** Emergency Kill-switch.

---

## ⚠️ Disclaimer
This tool is for educational purposes only. Automated play can result in account moderation. Use responsibly.
