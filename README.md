# QA Companion Onboarding Demo

An interactive Unreal Engine demo showcasing the **QA Companion** vision bug detection software. This demo provides hands-on experience with bug recording and testing features.

## Overview

This demo is an Unreal game with two camera views:

- **Camera 1**: General explanation and instructions for using QA Companion
- **Camera 2**: A mesh with intentional missing texture—perfect for testing the vision bug detection system

## Getting Started

### Installation

1. Go to the [GitHub releases](https://github.com/razerofficial/Unreal_QACompanion_OnboardingDemo/releases) page
2. Download the latest release (ZIP file named something like QacFirstTimeDemo-xxxxxxx-shipping.zip)
3. Unzip the downloaded file
4. Run `QacFirstTimeDemo.exe`

### Prerequisites

Before using vision bug detection, you must:

1. **Install the Razer Game Data Bridge (RGDB)**:
   - Visit [qac.razer.ai](https://qac.razer.ai)
   - Download and install the Razer Game Data Bridge
   - Start the RGDB application
   - Verify the installation by checking the indicator in the top right of the demo—it should turn **green** when RGDB is running

2. **Have available user credits**:
   - Vision bug detection requires user credits to operate
   - Check your credit balance on the QA Companion website:
     - Log in to [qac.razer.ai](https://qac.razer.ai)
     - Click the **user tab** in the bottom left of the page
     - View your available credits balance

> **Note**: Vision bug detection will not work until RGDB is installed and running (green indicator), and you have remaining credits available.

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

- **Vision bug detection not working?** Check the following:
  - RGDB is installed and running (check the top right indicator—should be green)
  - You have available user credits (check on [qac.razer.ai](https://qac.razer.ai) via the user tab in the bottom left)
- **Demo won't start?** Verify you have the latest release and all files are properly extracted