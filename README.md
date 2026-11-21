# Chord AI

**Chord detection, playback, and music practice for Android.**

Chord AI is a native Android application developed by **BRYGAR**. It brings audio analysis, chord visualization, recording, and practice tools into one Material 3 interface.

> **Development status:** v1.19.2 is the first GitHub pre-release. Features and behavior may change, and testing builds may contain bugs.

## Features

- Analyze supported local audio files and imported audio sources.
- Display detected chords alongside playback and a navigable waveform.
- Choose between **Basic** and **Precise** chord presentations.
- View chord diagrams and explore supported instrument voicings.
- Adjust playback pitch and speed, including linked adjustments, and practice with A–B loops.
- Record audio with a separate live chord card, then analyze the completed recording.
- Browse saved analyses in the Library, with search and favorites.
- Use built-in tuner and metronome tools.
- Choose light, dark, or system appearance.

Some features depend on device permissions, Android version, and source compatibility.

## Download and install

Open [GitHub Releases](https://github.com/ZeBry09/Chord-AI/releases), select **v1.19.2**, and download the **testing APK** attached to the pre-release. Open the APK on an Android device and follow Android's installation prompts.

Only install APKs from a source you trust. Android may ask you to allow installation from the app used to open the file.

**The APK is for installation.** The Android App Bundle (AAB) is not distributed in this GitHub release.

## What's new in v1.19.2

Recording waveforms no longer display live chord overlays. The **separate live chord card remains active**, and final chord analysis after stopping a recording is preserved.

This is Chord AI's **first GitHub pre-release**.

See [CHANGELOG.md](CHANGELOG.md) for release notes.

## Building from source

The Android project is written in Kotlin and Jetpack Compose and uses Gradle. When the full source is published:

1. Clone this repository.
2. Open the project in Android Studio.
3. Let Gradle sync and install the required Android SDK components.
4. Build and run the app on an Android device or emulator.

**Important:** The full application source is not yet committed to this repository. The current repository documentation does not guarantee that a source checkout can build the app. The original project also references model assets whose redistribution rights have not been established. Do not publish those extracted weights without appropriate permission.

## Privacy and permissions

The app uses local storage for saved app data and requests device permissions for features such as microphone recording and importing audio. Online imports, including YouTube-related functionality, may contact external services. Consult the app's privacy policy and Android permission prompts for details.

## Licensing and third-party assets

**No repository-wide open-source license is granted at this time.** Third-party libraries, fonts, icons, and other components retain their own licenses.

The extracted chord-detection model weights documented in the supplied project are **not original to this project**. Their redistribution rights have not been established. This repository is not affiliated with or endorsed by the original model/app developer.

See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for further details.

## Feedback

Found a bug or have a feature request? Open an [issue](https://github.com/ZeBry09/Chord-AI/issues) with the app version, device, Android version, steps to reproduce, and relevant screenshots or logs (without personal information).

**Developer:** BRYGAR  
**Contact:** brygar.official@gmail.com
