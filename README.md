# Video Player Script

## Overview

This repository contains a Python script designed to automate the discovery and playback of supported video files based on the user's operating system. The script leverages the `moviepy` library for video file manipulation and adapts to file extensions recognized by major media players on macOS, Windows, and Linux.

## Features

- Automatically searches for video files with supported extensions.
- Plays the video using the default media player of the operating system.
- Exception handling for improved robustness.

## Supported Configurations

- **macOS:** Formats supported by QuickTime Player.
- **Windows:** Formats supported by the Film & TV app.
- **Linux:** Tested formats on Ubuntu 14.04.

## Usage

1. Run the Python script.
2. The program will automatically search for a supported video file in the same directory.
3. If a video file is found, it will be played using the default media player.

## Installation

Ensure you have the `moviepy` library installed:

```bash
pip install moviepy
