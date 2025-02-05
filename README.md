# Expo CLI Android Build Error: AGP Version Conflict

This repository demonstrates a common issue encountered when building Android apps using Expo CLI: a conflict or incompatibility with the Android Gradle Plugin (AGP) version.

The `AGPVersionConflict.gradle` file showcases a scenario where the AGP version is mismatched, leading to a build failure. The solution provided in `AGPVersionSolution.gradle` addresses the conflict and ensures a successful build.

## Steps to Reproduce

1. Clone this repository.
2. Navigate to the `android` directory.
3. Try to build the project using the original `build.gradle` (AGPVersionConflict.gradle). You will likely encounter an error related to AGP version incompatibility. 
4. Replace the `build.gradle` file with `AGPVersionSolution.gradle` and build again. The build should succeed.

## Solution

The solution involves carefully reviewing and adjusting the AGP version defined in the project's `build.gradle` file, ensuring compatibility with the Expo CLI and other dependencies.