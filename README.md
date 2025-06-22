# WEBSEC - Phishing Detection Browser Extension

**WEBSEC** is a lightweight Chrome extension that allows users to manually check if a website is potentially phishing or safe. When the user clicks on the **pinned extension icon**, the popup appears and displays the detection status based on simple pattern checks.It analyzes the webpage content to identify potential phishing sites based on a predefined detection mechanism.

## 📸 Screenshots

Here’s how the WEBSEC extension works:

### 🔒 Safe Website Popup
![Safe Site](safe.png)

### ⚠️ Phishing Website Popup
![Phishing Site ](phishing.png)

## Features:
- 🔘 **Manual Detection**: User must click the pinned extension icon to run detection.
- 🕵️‍♂️ **Phishing Check Logic**: Identifies suspicious domains using basic heuristics (e.g., keyword matching, URL patterns).
- 📋 **Popup Display**: Shows a message inside the popup — either “Phishing site detected” or “This site seems safe.”

## Installation

Follow these steps to install and run the extension in your browser:

### 1. Download the Extension Files
Download or clone this repository to your local machine.
```bash
git clone https://github.com/Rushi19-04/WEBSEC.git
```
### 2. Enable Developer Mode
- Open Google Chrome or any Chromium-based browser.
- Navigate to `chrome://extensions/`.
- Enable **Developer mode** (toggle at the top-right corner).

### 3. Load the Extension
- Click on **Load unpacked**.
- Select the directory where the extension files are located.

### 4. Use the Extension
Once the extension is installed, follow these steps to use it:

1. **Click the Extension Icon:**
   - When you visit a website, click the extension icon in your browser's toolbar to trigger the phishing detection.
   
2. **Phishing Detection:**
   - The extension will analyze the webpage and, based on the detection logic, show a popup indicating whether the website is potentially phishing or safe.

## Contributing

Feel free to open an issue or submit a pull request if you have any improvements or bug fixes!

## License

This project is licensed under the MIT License - see the [LICENSE](License) file for details.
