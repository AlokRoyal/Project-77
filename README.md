# Space Explorer — Project 77

A React Native and Expo app demonstrating navigation for a small space-themed experience. Its stack navigator starts on Home and provides routes for Star Map, Daily Picture, and Spacecraft.

## App structure

App.js imports screen components from screens/, registers each route in a React Navigation stack, and hides the default navigation header. Screen content and visual assets live in screens/ and assets/; app metadata is in app.json.

## Stack

React 16.13, Expo SDK 42 and React Native, React Navigation 5, React Native Web, Gesture Handler, Reanimated, Screens, and Safe Area Context.

## Start developing

    npm install
    npm start

Then use npm run android, npm run ios, or npm run web to open a target. Native testing needs a device or emulator.

## Dependency note

Both npm and Yarn lockfiles are present. Use one package manager consistently so dependency resolution stays predictable. node_modules is also listed in the repository; it is not needed in version control for a fresh install.