# Sudarshana

Sudarshana is a women's safety app built as a student project. It is designed to help a user react quickly in an emergency by sending SOS alerts, sharing live location, saving emergency contacts, and giving fast access to helpline numbers and useful support websites.

## Main Features

- One-tap SOS button
- Save up to 4 emergency contacts
- Share current location through SMS
- Helpline numbers in one place
- Useful reporting and support websites
- Android APK version available
- Local backend for storing contacts, location, and SOS activity

## Tech Stack

- HTML
- CSS
- JavaScript
- PowerShell
- Kotlin
- Gradle

## Project Structure

- `public/` - frontend pages, styles, scripts, manifest, and LinkedIn project page
- `data/` - saved app data such as contacts, location, and SOS history
- `server.ps1` - local backend server
- `start.bat` - easy launcher for the local app
- `android/` - Android app wrapper project and APK build files

## Run the Web App

1. Open PowerShell in this folder
2. Run:

```powershell
.\start.bat
```

3. Open the app in the browser if it does not open automatically:

```text
http://127.0.0.1:8080
```

## Android APK

The latest built debug APK is available here:

- `android/app/build/outputs/apk/debug/app-debug.apk`

Install steps:

1. Copy `app-debug.apk` to your Android phone
2. Open it on your phone
3. Allow `Install unknown apps` if Android asks
4. Install and open the app
5. Allow Location and SMS permissions

## How It Works

- The user saves emergency contacts in the app
- The app can capture live location
- When the SOS button is pressed, the app saves the SOS event
- On Android, the app can send SMS alerts to saved contacts
- The web version also provides local backend support for contact and alert storage

## Backend API

- `GET /api/config`
- `PUT /api/contact`
- `DELETE /api/contact`
- `POST /api/location`
- `POST /api/sos`
- `GET /api/health`

## LinkedIn / Project Page

A project page for sharing is included here:

- `public/linkedin.html`

When the local server is running, you can open it at:

- `http://127.0.0.1:8080/linkedin.html`

To share this publicly on LinkedIn, the project should be hosted on GitHub Pages, Netlify, or another public hosting service.

## Team

Team Gen Next

- Amit Mistry - Team Leader
- Soumyadipta Dey - Back-end Developer
- Arpan Das - Front-end Developer
- Sohini Mukherjee - Poster Designer

## Purpose

This project was created to address a real problem using technology. The aim of Sudarshana is to make it easier and faster to reach help during unsafe situations.
