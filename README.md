

A high-performance, professional-grade memory dumper for Counter-Strike 1.6 (GoldSrc). This tool is designed to find offsets and signatures for external cheat development with maximum accuracy and minimum effort.

## 🚀 Features

- **Brute Force Memory Scanning:** Scans the entire process memory map, not just specific modules.
- **CE Mod (Automatic Scanning):** Integrated "Changed/Unchanged" logic similar to Cheat Engine for complex offsets like PunchAngle, Velocity, and ViewAngles.
- **29+ Critical Offsets:** Supports dumping of Health, Armor, Team, Weapon ID, Ammo, Bone Matrix, Ground Flags, and more.
- **Pattern Generation & Verification:** Automatically creates unique AOB signatures for your offsets to survive game updates.
- **Premium CLI Interface:** Sleek, colorized dashboard with real-time feedback and calibration steps.
- **UAC Admin Support:** Automatically requests administrator privileges for deep memory access.

## 🛠️ Requirements

- Python 3.10+
- Windows OS (x86/x64)
- Administrator Privileges

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ECLIPSE-CS16-Dumper.git
   cd ECLIPSE-CS16-Dumper
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## 🎮 Usage

1. Launch Counter-Strike 1.6 (`hl.exe`).
2. Run the dumper:
   ```bash
   python cs16_external.py
   ```
3. Follow the interactive calibration steps to find your offsets.
4. Use **Option [7]** to generate signatures and **Option [8]** to verify them.

## 📂 Project Structure

- `cs16_external.py`: The main dumper logic and UI.
- `eclipse_auth.py`: Authentication and configuration handler.
- `cs16_offsets.json`: (Generated) Storage for found offsets.
- `cs16_signatures.json`: (Generated) Storage for AOB patterns.

## ⚠️ Disclaimer

This tool is for educational and research purposes only. Use it at your own risk. The developers are not responsible for any bans or legal issues resulting from the use of this software.

---
