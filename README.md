
# CodeMate Compiler Service - Installation & Usage Guide

Welcome to **CodeMate**, This guide will walk you through the installation and usage of the CodeMate Compiler Service on **Windows**, **macOS**, and **Ubuntu** systems.

---

## Windows Installation Guide

### Step 1: Download the Installer  
Click below to download the latest CodeMate setup for Windows:  
[CodeMate Setup for Windows](https://github.com/CodeMate-AI/codemate-edu-release/releases/download/v2.1.1/CodeMate_Setup_v2.1.1.exe)

### Step 2: Install the Application  
- Double-click the downloaded `CodeMate.Setup.exe` file.  
- Follow the on-screen instructions to complete the installation.  
- A shortcut will be created on your **Desktop** and in the **Start Menu**.

### Step 3: Run the Compiler Service  
- Double-click the **CodeMate Compiler Service** shortcut.  
- The service will minimize and run in the **system tray** near the clock.

### Step 4: Stop the Compiler Service  
- Right-click the **CodeMate Compiler icon** in the system tray.  
- Click **Stop** to shut down the service.

---

## macOS Installation Guide

### Step 1: Download the Installer  
Click below to download the setup file for macOS:  
[CodeMate Setup for macOS](https://github.com/CodeMate-AI/codemate-edu-release/releases/download/v2.1.1/CodeMate_Setup_mac)

### Step 2: Install the Application  
- Double-click the downloaded setup file.  
- Follow the on-screen instructions to complete the installation.  
- A shortcut will appear in your **Applications Menu**.  
- If you see a warning that the app can't be opened because it's from an unidentified developer:  
  - Open **System Settings** > **Privacy & Security**.  
  - Scroll down to find a message saying "**CodeMate_Setup_mac was blocked from use**."  
  - Click **Open Anyway**, then confirm again in the prompt that appears.

### Step 3: Grant Execute Permission (if needed)  
If the app doesn't run properly after installation, try making the file executable:

1. Open the **Terminal**.  
2. Navigate to the folder containing the downloaded file:
   ```bash
   cd ~/Downloads 
   ```
3. Run the following command:
   ```bash
   chmod +x CodeMate_Setup_mac
   ```

### Step 4: Run the Compiler Service  
- Open the **CodeMate Compiler Service** from the Applications Menu.  
- The service will automatically start running in the background.

### Step 5: Stop the Compiler Service  
- Open the app and click **Stop** to shut down the service.

---

## Ubuntu Installation Guide

### Step 1: Download the Installer  
Click below to download the setup file for Linux:  
[CodeMate Setup for linux](https://github.com/CodeMate-AI/codemate-edu-release/releases/download/v2.1.1/CodeMate_Setup_linux)

### Step 2: Open Terminal and Navigate to Setup Folder
```bash
cd /path/to/download/folder
```

### Step 3: Grant Execute Permission
```bash
chmod +x ./CodeMate_Setup_linux
```

### Step 4: Run the Setup
```bash
./CodeMate_Setup_linux
```

### Step 5: Start the Compiler Service
```bash
~/.cache/.codemate/CodeMate\ Compiler\ Service
```

### Step 6: Uninstall CodeMate
```bash
cd ~/.cache/.codemate/
```
```bash
./CodeMate\ Uninstaller
```

---

## Need Help?

If you encounter any issues or have questions, please reach out to our support team at contact@codemateai.dev
