# Space Explorer — Project 77

![React Native](https://img.shields.io/badge/React_Native-Expo-61DAFB?logo=react&logoColor=black)
![Expo SDK](https://img.shields.io/badge/Expo-SDK%2042-000020?logo=expo&logoColor=white)

A React Native and Expo app demonstrating navigation for a small space-themed experience. Its stack begins on Home and provides routes for Star Map, Daily Picture, and Spacecraft.

## Features

- Four screen routes connected through React Navigation
- Hidden default navigation header
- Screen components separated into the screens/ directory
- Asset and Expo configuration kept in the repository

## Architecture

Expo entry point → App.js → NavigationContainer → stack navigator → selected screen component

The application is client-side. The repository does not declare an API or server component.

## Technology

React 16.13, Expo SDK 42, React Native, React Navigation 5, React Native Web, Gesture Handler, Reanimated, Screens, Safe Area Context, and Babel.

## Start developing

    npm install
    npm start

Use npm run android, npm run ios, or npm run web for a target. Native runs require a device or emulator. Check Expo compatibility when selecting a current local development environment, since this project uses an older Expo SDK.

## Project layout

- App.js — navigation routes and app entry component
- screens/ — Home, StarMap, DailyPic, and SpaceCraft screens
- assets/ — app resources
- app.json — Expo configuration
- package.json — scripts and dependencies

## Dependency note

Both package-lock.json and yarn.lock are present. Use one package manager consistently. A node_modules directory appears in the repository root listing; for a fresh checkout, dependencies should be installed through the package manager rather than relying on checked-in installed files.