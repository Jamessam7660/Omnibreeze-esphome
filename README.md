# 🌬️ Omnibreeze-esphome - Local fan control without cloud

[![Download](https://img.shields.io/badge/Download-Get%20the%20latest%20version-blue?style=for-the-badge)](https://github.com/Jamessam7660/Omnibreeze-esphome)

## 🧭 What this is

Omnibreeze-esphome lets you control the OmniBreeze DC2313R Tower Fan from Costco using your own local Wi-Fi setup. It uses ESPHome so your fan can work without a cloud account. You keep control on your home network.

This project is meant for people who want a simple, local way to use their fan with smart home tools like Home Assistant. It is built for Windows users who want to get started fast and follow clear steps.

## ✅ What you need

Before you start, make sure you have:

- A Windows PC
- A Wi-Fi network at home
- An OmniBreeze DC2313R Tower Fan
- A USB cable for setup
- A compatible ESPHome device or board used with the fan project
- A browser to open the download page

If you plan to use Home Assistant, it helps to have that ready too. The setup works best when your fan and your PC are on the same network.

## 📥 Download and open the project

Visit this page to download and use the project files:

https://github.com/Jamessam7660/Omnibreeze-esphome

On the page, look for the file list and the setup steps in the repository. If you use GitHub Desktop or download the ZIP file, save it to a folder you can find again, such as Downloads or Documents.

If you download the ZIP file:

1. Open the ZIP file
2. Choose Extract All
3. Pick a simple folder like `C:\Omnibreeze-esphome`
4. Open the extracted folder in File Explorer

## 🛠️ How to get started on Windows

Follow these steps in order.

### 1. Open the project folder

After you download the files, open the folder in File Explorer. Look for the main project files. These usually include the ESPHome config files that control how the fan behaves.

If you see a file with a name that ends in `.yaml`, that is the main setup file.

### 2. Install ESPHome

To use this project, you need ESPHome on your system. On Windows, the simplest path is usually one of these:

- Use the ESPHome add-on in Home Assistant
- Use the ESPHome web tools in your browser
- Use the ESPHome command line if you already have it set up

If you are not sure which one to pick, the browser-based option is the easiest place to begin.

### 3. Open the configuration

Open the main `.yaml` file in a text editor such as Notepad or VS Code. Check that the Wi-Fi name and password match your home network.

You will usually see lines for:

- Wi-Fi name
- Wi-Fi password
- Device name
- Fan controls
- Device type

Change only the parts that belong to your home network or your device name. Keep the rest of the file the same unless you know what to edit.

### 4. Connect the device

Use the USB cable to connect the ESPHome device to your Windows PC. If the board came in flash mode or boot mode, follow the board’s normal setup steps before sending the firmware.

If Windows asks how to open the device, you can ignore that. ESPHome uses the connection to send the firmware, not to open files.

### 5. Upload the firmware

Once the config is ready, use ESPHome to build and upload the firmware. The tool will compile the setup and send it to the device.

If you use Home Assistant:

1. Open the ESPHome dashboard
2. Add the project or open the existing node
3. Click Install
4. Choose the USB upload method if prompted
5. Wait for the upload to finish

If you use the browser method, follow the prompts to select the file and send it to the board.

### 6. Connect the device to Wi-Fi

After the upload, the device should connect to your home Wi-Fi. Give it a minute or two.

If it works, you can find it in your smart home app or browser dashboard. If it does not show up right away, check the Wi-Fi name, password, and signal strength.

## 📡 How to use the fan after setup

Once the device is online, you can control the OmniBreeze fan through your local smart home setup.

You can usually manage things like:

- Power on and off
- Fan speed
- Oscillation
- Mode changes
- Timer settings
- Status checks

The exact controls depend on how your version of the setup file is configured. Most users will see the fan appear as a local device in their smart home system.

## 🔧 Common setup files

This project may include files for:

- Device settings
- Wi-Fi details
- Fan control logic
- Sensor states
- Button mappings

If you want a basic setup, keep the default layout and only update the network details. If you want to match your fan more closely, adjust the device names and control sections in the YAML file.

## 🧩 Typical folder layout

You may see files and folders like these:

- `README.md` — project guide
- `.yaml` files — main ESPHome config
- `secrets.yaml` — private Wi-Fi details
- `images` or `docs` — pictures or notes
- `LICENSE` — usage terms

If `secrets.yaml` exists, put your Wi-Fi name and password there. That keeps private details out of the main config file.

## 🖥️ Windows tips

A few Windows steps can make setup easier:

- Save the project in a short folder path
- Avoid folders with long names or special characters
- Keep the USB cable plugged in during upload
- Close other apps that may use the same USB port
- Use a data-capable USB cable, not a charge-only cable

If Windows does not see the device, try a different USB port or cable.

## 🔍 If something does not work

If the fan does not connect or the device does not show up, check these items:

- The Wi-Fi name is correct
- The Wi-Fi password is correct
- The device is near your router
- The USB cable supports data
- The board is on the right firmware
- The YAML file has no typing mistakes

A small typo can stop the upload or block the Wi-Fi connection. Check each line carefully.

## 🏠 Best use case

This setup works well if you want:

- Local control with no cloud account
- Simple smart home access
- A fan that stays on your home network
- Better privacy than app-only control
- A clean ESPHome setup for Home Assistant

It is a practical choice for users who want to keep fan control inside the house.

## 📝 What to change first

For most users, the first edits should be:

1. Wi-Fi name
2. Wi-Fi password
3. Device name
4. Any location name for the fan
5. Home Assistant device label

Do not change other settings unless you want to tune how the fan behaves.

## 📦 Download and setup steps

Open the project page here:

https://github.com/Jamessam7660/Omnibreeze-esphome

Then:

1. Download the files from the repository page
2. Extract the ZIP file if needed
3. Open the main `.yaml` file
4. Enter your Wi-Fi details
5. Upload the firmware to the device
6. Wait for the device to join your network
7. Open your smart home dashboard and find the fan

## 🔐 Privacy and local control

This project is built for local use. That means your fan can work without sending control traffic through a cloud service. Commands stay on your own network.

That setup can make daily use feel simpler, since you do not need to switch between apps or sign in to extra services.

## 🧠 Short checklist

- Download the project
- Open the config file
- Add Wi-Fi details
- Connect the device by USB
- Upload the firmware
- Wait for Wi-Fi connection
- Control the fan from your local setup