# 🧘 Stretch Reminder Web App

## Overview

Stretch Reminder is a web application designed to help you maintain a healthy stretching routine throughout your day. It provides a simple, intuitive interface to schedule and randomly play stretch videos at customizable intervals.

## 🌟 Features

### Timer and Reminders
- Customizable interval timer (supports minutes and fractions)
- Color-coded timer (green → orange → red)
- Hotkey 'R' to reset timer
- Automatic stretch video selection when timer expires

### Video Management
- Add multiple YouTube stretch videos
- Store timestamps and descriptions for each stretch
- Easy import/export of video collections
- Persistent storage using localStorage

### User Experience
- Alarm sound when it's time to stretch
- Volume control for alarm
- Floating clipboard notification
- Responsive design

## 🚀 How to Use

### Adding Stretch Videos
1. Use the textarea to add videos in the format:
   ```
   YouTube URL;Timestamps;Descriptions
   ```
2. Example input:
   ```
   https://youtu.be/dQw4w9WgXcQ;1:00,2:30;First Stretch,Second Stretch
   ```
3. Click "Add Videos" to save your stretches

### Timer Controls
- Set desired interval in minutes
- Click "Start Timer" to begin
- Use 'R' key to reset timer at any time

### Additional Functions
- Export videos to clipboard
- Import videos from clipboard
- Delete individual videos
- Adjust alarm volume

## 🛠 Technical Details

- Built with HTML, CSS, and JavaScript
- Uses localStorage for data persistence
- Dynamically embeds YouTube videos
- Responsive design
- No external libraries required