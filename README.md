#  USB Physical Security
## Overview
USB Physical Security is a Python-based tool that allows users to control the enablement and disablement of USB ports on their system. This helps prevent unauthorized access through physical devices, enhancing the security of the system against data theft and malware infections via USB drives.

The project features a password-protected GUI that enables or disables the USB ports, ensuring only authorized personnel can access these controls.

## Features
- Password Protection: Prevent unauthorized access to the control functionality.
- Enable/Disable USB Ports: Easily block or unblock USB ports to control device connectivity.
- Intuitive GUI: User-friendly interface designed with Tkinter, featuring custom background images and hover effects for buttons.
- Project Info: A button that opens an HTML file with more details about the project.

## Installation
1. **Clone the repository:**
   ```bash
   git clone https://github.com/DilipAtchuthKumar/usb-physical-security.git
   cd usb-physical-security
   
2. **Install the required dependencies.**

3. **Ensure that you have the required .bat files for enabling/disabling USB ports:**
    - block_usb.bat: To disable USB ports.
    - unblock_usb.bat: To enable USB ports.
      
Modify the paths to these .bat files in the code as needed.

4. **Create a project info HTML file (project_info.html) with information about the project, and place it in the appropriate directory.**

## Usage
1. **Run the script:**
   ```bash
   python usb_physical_security.py

2. **The GUI will open, allowing you to:**
    - Disable USB ports (password-protected).
    - Enable USB ports (password-protected).
    - View project information in an HTML file.

3. **The password for accessing the enable/disable functionality can be set by modifying the password variable in the code.**


## Screenshots
Main Interface

![image](https://github.com/user-attachments/assets/8e85ce21-59dc-48df-9ec7-26d889ca7944)

## Project Structure
    usb-physical-security/
    │
    ├── usb_physical_security.py    # Main Python script for the GUI
    ├── block_usb.bat               # Batch file to disable USB ports
    ├── unblock_usb.bat             # Batch file to enable USB ports
    ├── project_info.html           # HTML file containing project information
    └── wallpaper.png               # Background image for the GUI

## Dependencies
- Python 3.x
- Tkinter
- Pillow (for image handling)
- Webbrowser (for opening project info)
- Subprocess (for running batch files)

Install dependencies via:

    pip install Pillow

## Contributing
If you would like to contribute to this project, feel free to fork the repository and submit a pull request. Any feedback, suggestions, or improvements are welcome!
