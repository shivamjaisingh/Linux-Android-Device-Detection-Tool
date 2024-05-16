# Android Device Detection Script

This bash script is designed to manage Android Debug Bridge (ADB) services on Linux systems to help detect Android devices that may not be recognized by Android Studio.

## Description

The script performs a sequence of commands to reset the ADB server, ensuring that any connected Android devices are recognized and listed in Android Studio. This can be particularly useful for developers who frequently connect multiple devices or encounter issues with device detection.

## Features

- **Kills the existing ADB server**: Ensures that there are no lingering processes that might cause conflicts.
- **Starts a new ADB server**: Initializes a clean ADB environment.
- **Lists connected devices**: Displays a list of all devices currently connected to the system via USB and recognized by ADB.

## Usage

To use the script, follow these steps:

1. **Open Terminal**: Navigate to the directory containing the script.
2. **Make the script executable** (if it's not already):

```bash
   chmod +x adb_device_detect.sh
```

## Run the script

```bash
./adb_device_detect.sh
```

## Prerequisites
ADB installed: Make sure Android Debug Bridge (ADB) is installed on your Linux system. This can typically be installed via package managers like apt for Ubuntu:

```bash
sudo apt install adb
```
