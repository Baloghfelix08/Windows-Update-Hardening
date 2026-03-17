🎯 Purpose
By default, Windows 11 aggressively manages drivers and system versions, often leading to instability or unwanted changes. This script modifies the Windows Registry to enforce a professional update policy: Security first, stability always.

✨ Key Features
🚫 Block Forced Driver Updates: Prevents Windows Update from replacing your stable, manually installed hardware drivers with generic Microsoft versions.

⏳ 6-Month Feature Deferral: Delays major "Feature Updates" by 180 days, allowing Microsoft to fix initial bugs before they reach your system.

🛡️ Immediate Security Patches: Does NOT delay critical security updates. Your system remains protected against vulnerabilities without a single day of lag.

⚙️ Professional Control: Disables automatic reboots while a user is logged on, preventing unexpected work loss.

🔍 Metadata Privacy: Blocks the transmission of device metadata to Microsoft during hardware identification.

## 🚀 How to Use (Step-by-Step)

1. **Download:** Save the `Winupdate.ps1` file directly onto your **Desktop**.
2. **Open Terminal:** Right-click the **Start button** and select **Terminal (Admin)** or **PowerShell (Admin)**.
3. **Navigate to Desktop:** Copy and paste the following command to tell PowerShell where the file is, then press Enter: cd $home\Desktop
4. Authorize the Session: Run this command to allow the script to run in the current window: Set-ExecutionPolicy Bypass -Scope Process (If prompted, type Y or A and press Enter.)

Execute the Script: Run the file by typing: .\Winupdate.ps1
