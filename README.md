# Wi-Fi Security Auditor & Educational Tool

An educational Android application designed to test and audit the security of your own local Wi-Fi router configurations.

## ⚠️ Disclaimer
> **FOR EDUCATIONAL USE ONLY.** Test the security of your own Wi-Fi router only. Any misuse for illegal activity is strictly prohibited.

## Features
- **Permission & Safety Gate:** Enforces location/Wi-Fi permissions and agreement modals before scanning.
- **Radar & Signal Scanner:** Detects nearby Wi-Fi networks and lists them sorted by signal strength (`-dBm`).
- **Wordlist Auditor:** Tests combinations from an uploaded custom dictionary file against authorized targets.
- **Automated APK Builds:** GitHub Actions workflow configured for automated debug APK compilation.

## Getting Started via GitHub Actions
1. Push this repository to GitHub.
2. Go to the **Actions** tab to view the automated Android build status.
3. Download the compiled `.apk` artifact from the workflow run upon completion.
