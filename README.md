# Expo DocumentPicker Android: Unexpected Null URI

This repository demonstrates a bug in Expo's DocumentPicker API on Android where the selected file's URI can unexpectedly resolve to null, even after a successful file selection. This inconsistent behavior can cause issues in applications that rely on accessing selected files.

## Bug Reproduction

1. Run the `bug.js` file on an Android device or emulator.
2. Select a file using the DocumentPicker.
3. Observe that sometimes the `uri` property in the returned result is null despite the picker showing a successful file selection.