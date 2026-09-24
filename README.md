# Age Cal

> A modern, offline-friendly Android age calculator for precise age tracking and birthday countdowns.

Age Cal is an Android application designed to calculate a person's age in multiple time units and provide useful lifetime and birthday insights. It is intended for users who want a fast, simple, and easy-to-use age calculator that works without an internet connection.

## Highlights

- Calculate age in:
  - Years
  - Months
  - Days
  - Hours
  - Minutes
  - Seconds
- Show a live age display that updates over time
- Calculate the time remaining until the next birthday
- Display total lifetime statistics
- Provide a clean, fast, mobile-friendly interface
- Work offline after installation

## Download and Installation

The current repository distribution is a prebuilt Android APK.

1. Open the repository's **Releases** or file list on GitHub.
2. Download `Age cal.apk`.
3. On your Android device, allow installation from the source used to download the APK if Android requests permission.
4. Open the APK and follow the installation prompts.
5. Launch **Age Cal** from your app drawer.

> **Security note:** Only install APK files from a source you trust. Android may display a warning when installing an APK outside Google Play.

## How to Use

1. Open Age Cal.
2. Enter or select your date of birth.
3. Confirm the date.
4. Review your current age and the additional statistics shown by the app.
5. Use the birthday countdown to see how long remains until your next birthday.

For the most accurate results, make sure the date of birth is entered correctly. If the app asks for a time of birth, use the correct local time and timezone where applicable.

## Repository Contents

```text
.
└── Age cal.apk    Prebuilt Android application package
```

This repository currently distributes the compiled APK rather than the application source code. The source implementation, dependency manifests, build scripts, automated tests, and native Android project files are not currently included.

## Technology

The project description identifies the application as being built with:

- React
- TypeScript
- Vite
- Tailwind CSS
- Capacitor

The repository currently contains only the compiled APK, so the exact source versions and dependency configuration cannot be verified from this repository.

## Privacy and Offline Use

Age Cal is described as an offline-friendly application. Its primary calculations can be performed locally on the device, which is useful when traveling or when an internet connection is unavailable.

The APK in this repository does not include a separate privacy policy or detailed documentation of data collection behavior. Review the app's Android permissions and any in-app privacy information before use.

## Accuracy Notes

Age calculations can depend on:

- The selected date of birth
- The current date and time
- Leap years
- The device timezone and clock
- Whether a birthday has already occurred in the current year

For important legal, medical, financial, or identity-related purposes, verify results with an appropriate authoritative source.

## Development Status

The repository is currently focused on distributing the Android APK. A source-based development workflow is not available in the repository at this time.

### Suggested future improvements

- Add the React, TypeScript, Vite, Tailwind CSS, and Capacitor source code
- Add a `package.json` with reproducible dependency versions
- Add Android build and signing documentation
- Add screenshots or a product demo
- Add automated tests for date, leap-year, and birthday calculations
- Publish versioned releases with release notes and checksums
- Add a formal privacy policy
- Provide an open-source license

## Contributing

Contributions are not currently defined because the application source code is not included. If the source project is added later, contribution guidelines should document:

- Local development setup
- Required Node.js and Android tooling versions
- Formatting and linting commands
- Test commands
- APK build and signing steps
- Pull request expectations

## License

No license file is currently included. Unless a license is added, the repository contents should be treated as **all rights reserved** and may not be redistributed, modified, or reused beyond what is permitted by applicable law.

## Project Information

- **Repository:** `kumar-ayansh/Calculator-`
- **Application:** Age Cal
- **Platform:** Android
- **Distribution:** Prebuilt APK
