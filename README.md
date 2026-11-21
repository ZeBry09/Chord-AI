# Chord AI

**Chord detection, playback, and music practice for Android.**

Chord AI is a native Android application developed by **BRYGAR**. It combines audio analysis, chord visualization, recording, and music practice tools in a Material 3 interface.

> **Current documented version: v1.20.1.** Chord AI is under active development. Release builds may still contain bugs.

## Features

- Analyze supported local audio files and imported audio sources.
- Display detected chords alongside playback and a navigable waveform.
- Switch between **Basic** and **Precise** chord detection modes.
- Explore chord diagrams and supported instrument voicings.
- Adjust playback pitch and speed, and practice with A–B loops.
- Record audio with a separate live chord card, then analyze the completed recording.
- Browse saved analyses in the Library.
- Access tuner and metronome utilities.
- Use light, dark, or system appearance.

Availability of features may vary by build, Android version, permissions, and source compatibility.

## Download and install

Visit [GitHub Releases](https://github.com/ZeBry09/Chord-AI/releases) and choose the release you want to install. Download its attached **APK**, open it on your Android device, and follow Android's installation prompts.

Only install APKs from sources you trust. GitHub releases distribute the APK; **AAB files are not included**.

## Software updates

The **Software Update** screen checks GitHub Releases when opened. It can optionally include pre-release versions, display available release notes, and offer an APK download button for a release that includes a downloadable APK.

## Latest changes: v1.20.1

- Refined light-mode selection colors for clearer selected states.
- Renamed **More links** to **Homepage** and updated the destination to the [BRYGAR homepage](https://brygar.itsbrygar.chatgpt.site/).
- Added [BRYGAR on YouTube](https://youtube.com/@BRYGAROfficial) to the social icons row.

Previous release **v1.20.0** introduced GitHub-powered software update checks, optional pre-release discovery, release notes, and APK downloads.

See the full [changelog](CHANGELOG.md).

## Building from source

The Android project uses Kotlin, Jetpack Compose, and Gradle. Once the full project source is published, open it in Android Studio, sync Gradle, and build for an Android device or emulator.

**Source availability:** The complete buildable application source has not been committed to this repository yet. Documentation and release APKs do not constitute a complete source checkout. Some model assets have unresolved redistribution permissions and should not be uploaded without appropriate rights.

## Privacy and permissions

The app stores local application data and may request permissions for microphone recording and importing audio. Online import features may contact external services. Review Android permission prompts and the application's privacy policy for details.

## Licensing and third-party assets

**No repository-wide open-source license is currently granted.** Third-party components retain their own terms. Redistribution rights for extracted chord-detection model weights have not been established. See [third-party notices](THIRD_PARTY_NOTICES.md).

## Feedback

Use [GitHub Issues](https://github.com/ZeBry09/Chord-AI/issues) to report bugs or request improvements. Include the app version, device model, Android version, and reproduction steps where applicable. Do not post private audio, credentials, or personal data.

**Developed by [BRYGAR](https://brygar.itsbrygar.chatgpt.site/).**
