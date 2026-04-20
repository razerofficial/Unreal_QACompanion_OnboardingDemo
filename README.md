# QA Companion Onboarding Demo

An interactive Unreal Engine demo showcasing the **QA Companion** vision bug detection software. This demo provides hands-on experience with bug recording and testing features.

## Overview

This demo is an Unreal game with two camera views:

- **Camera 1**: General explanation and instructions for using QA Companion
- **Camera 2**: A mesh with intentional missing texture—perfect for testing the vision bug detection system

## Getting Started

### Installation

1. Go to the [GitHub releases](https://github.com/razerofficial/Unreal_QACompanion_OnboardingDemo/releases) page
2. Download the latest release (ZIP file)
3. Unzip the downloaded file
4. Run `QacFirstTimeDemo.exe`

### Prerequisites

Before using vision bug detection, you must install the **Razer Game Data Bridge (RGDB)**:

1. Visit [qac.razer.ai](https://qac.razer.ai)
2. Download and install the Razer Game Data Bridge
3. Start the RGDB application
4. Verify the installation by checking the indicator in the top right of the demo—it should turn **green** when RGDB is running

> **Note**: Vision bug detection will not work until RGDB is installed and the indicator shows green.

## Controls

| Key | Action |
|-----|--------|
| `1` | Switch to Camera 1 (Instructions) |
| `2` | Switch to Camera 2 (Test Scene) |
| `Ctrl + Shift + B` | Record bug (captures last 20 seconds) |
| `Alt + F4` | Exit demo |

## Testing the Vision Bug Detection

Camera 2 features a mesh with missing textures—ideal for testing QA Companion's vision bug detection:

1. Switch to Camera 2 using the `2` key
2. Observe the mesh with missing texture
3. Press `Ctrl + Shift + B` to record the issue
4. QA Companion will capture the last 20 seconds of gameplay for analysis

## Troubleshooting

- **Vision bug detection not working?** Ensure RGDB is installed and running (check the top right indicator)
- **Demo won't start?** Verify you have the latest release and all files are properly extracted