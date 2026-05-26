# StudioBP Network - iOS App Wrapper

This repository contains the native iOS wrapper app shell for **StudioBP Network Immobiliare**, generated and configured to work seamlessly with PWABuilder and Codemagic CI/CD.

## App Configurations

- **Target URL:** `https://ais-pre-ikru6x2p2pe3myocx5zpi3-387847488873.europe-west2.run.app`
- **Application Name:** `StudioBP Network`
- **Build System:** Codemagic CI/CD (using the integrated `codemagic.yaml` workflow)

## How to Build the App on Codemagic

1. Go to your **Codemagic Dashboard** and connect this repository: `dopelleg1/StudioBP-Network`.
2. Select the **Build iOS PWA** workflow defined in the `codemagic.yaml`.
3. Set your iOS credentials (certificates & profiles) under Environment Variables if you want to sign the production app, or run an unsigned build for instant simulator testing!
4. Click **Start Build**!