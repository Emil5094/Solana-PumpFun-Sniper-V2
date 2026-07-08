# 🚀 Solana-PumpFun-Sniper-V2 (Jito MEV Bypass)
The most advanced, blazing-fast automated sniper bot for Solana's Pump.fun and Raydium pools. Developed for private use, now open-sourced for the community.
## 🔥 Features
- **0ms Latency:** Direct RPC node connection logic.
- **Jito MEV Bypass:** Prevents sandwich attacks on your buys.
- **Auto-Sell:** Configurable take-profit and stop-loss directly in code.
- **Rug-Pull Protection:** Simulates dev wallet movements before buying.
## 🛠️ Installation & Setup
1. Make sure you have Python 3.10+ installed.
2. Download or clone this repository.
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
Edit the config file (or input details on first launch).
Run the bot:
python main.py
[!WARNING] Important Note on Windows Defender / Antivirus: The bot utilizes low-level socket connections and aggressively multi-threads network requests to bypass Jito MEV protection. Many standard antiviruses (like Windows Defender) falsely flag these aggressive network packets as suspicious and will terminate the script, causing you to lose your entry position. It is highly recommended to add the bot's folder to your Antivirus exclusions or temporarily disable real-time protection before running main.py for optimal performance.

💡 Usage
Once started, the bot will ask for the contract address you want to snipe. Input the CA and let the algorithm do the rest. Good luck, anon! 📈
