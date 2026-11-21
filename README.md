# BISME RADIO – Tasbeeh Counter

## Overview
BISME RADIO – Tasbeeh Counter is a responsive, interactive digital Tasbeeh application designed to make daily Dhikr counting simple and convenient.

The application provides two counting interfaces: a traditional Tasbeeh bead interface and a digital Tasbeeh counter. It supports multiple languages, customizable counting targets, sound and vibration feedback, and automatic progress saving.

## Features

- **Two Tasbeeh Modes:** Traditional String Tasbeeh and Digital Tasbeeh.
- **Multiple Languages:** English, Tamil, and Malayalam.
- **Dhikr Collection:** Includes 10 Dhikr entries with Arabic text, transliteration, and meaning.
- **Custom Counting Targets:** Preset targets of 33, 99, 100, and 1000, with support for custom targets.
- **Progress Tracking:** Displays the current count and progress towards the selected target.
- **Sound and Vibration:** Supports sound, silent, vibration-only, and sound-plus-vibration modes.
- **Automatic Dhikr Progression:** Automatically moves to the next Dhikr after completing the selected target.
- **Automatic Data Saving:** Remembers the counter state, selected Dhikr, language, counting mode, sound settings, and target using browser Local Storage.
- **Responsive Design:** Optimized for mobile phones, tablets, and desktop screens.
- **Reset Option:** Allows users to reset the current count.

## File Structure

This folder contains a single HTML file:

```text
Tasbeeh-Counter/
└── Tasbeeh counter Updated.html
```

## How to Use

1. Open `Tasbeeh counter Updated.html` in a modern web browser.
2. Select your preferred Dhikr.
3. Choose a counting target.
4. Tap the Tasbeeh beads or digital counter to start counting.
5. Change the language or sound settings whenever required.
6. Use the reset option to restart your count.

## Technical Information

- **Technology:** HTML5, CSS3, and JavaScript.
- **Application Type:** Standalone web application.
- **External Backend:** Not required.
- **Database:** Not required.
- **Data Persistence:** Browser Local Storage.
- **Internet:** An internet connection is recommended for loading Google Fonts. The application itself does not require a backend or API connection.

## Dependencies

The HTML file contains its own CSS, JavaScript, and embedded digital artwork.

An optional Arabic font file named `uthmanic-hafs.ttf` can be placed alongside the HTML file for additional Arabic typography support. Without it, the application uses available fallback Arabic fonts.

## Important Notes

- User settings and counting progress are stored in the browser's Local Storage.
- Clearing browser data may erase the saved counting progress and settings.
- Saved data is browser-specific and is not synchronized between devices.
- No separate CSS, JavaScript, image, or configuration files are required.

---

**Project:** BISME RADIO – Tasbeeh Counter  
**Category:** Islamic Tools / Digital Tasbeeh  
**Format:** Standalone HTML Application
