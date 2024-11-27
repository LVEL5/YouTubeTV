
# YouTube TV Chrome App: Installation Guide

This guide explains how to install and use the **YouTube TV Apps** Chrome App or the **Enable YouTube TV** background script, allowing users to enable YouTube TV functionality with their preferred setup.

---

## Option 1: Install **YouTube TV Apps**

This option provides a Chrome App that launches YouTube TV in full-screen mode with the modified Smart TV **User-Agent**.

### Files in `YouTube TV Apps` Folder:
- `manifest.json`
- `background.js`
- `icon.png`

### Installation Steps:

1. **Download Files**: 
   - Place the `manifest.json`, `background.js`,  files into a folder named `YouTube TV Apps`.

2. **Set Up Chrome App**:
   - Open **Chrome** and go to `chrome://extensions/`.
   - Enable **Developer mode** in the upper-right corner.
   - Click **Load unpacked** and select the `YouTube TV Apps` folder.

3. **Launch the App**:
   - The app will appear in the Chrome Apps list.
   - When launched, the app will:
     - Open YouTube TV in **full-screen mode**.
     - Use a Smart TV **User-Agent** for a TV-like experience.

---

## Option 2: Use **Enable YouTube TV** Background Script

This option only modifies the **User-Agent** for YouTube TV without launching an app. It can be useful if you prefer browsing YouTube TV directly in Chrome.

### Files in `Enable YouTube TV` Folder:
- `background.js`

### Installation Steps:

1. **Download the Script**:
   - Save the `background.js` file into a folder named `Enable YouTube TV`.

2. **Set Up Script as a Chrome Extension**:
   - Open **Chrome** and go to `chrome://extensions/`.
   - Enable **Developer mode**.
   - Click **Load unpacked** and select the `Enable YouTube TV` folder containing the `background.js` file.

3. **How It Works**:
   - Once installed, this extension modifies the **User-Agent** for all YouTube TV requests to mimic a Smart TV.

---

## Key Differences Between Options

| Feature                    | YouTube TV Apps         | Enable YouTube TV       |
|----------------------------|-------------------------|-------------------------|
| **Full-Screen Mode**       | Yes                    | No                      |
| **User-Agent Modification**| Yes                    | Yes                     |
| **Standalone App**         | Yes                    | No (browser extension)  |

---

## Choose Your Preferred Option

- If you want a full-screen experience, **install "YouTube TV Apps"**.
- If you want a lightweight solution without an app, **install "Enable YouTube TV"**.

Let me know if you need help with customization or troubleshooting!
