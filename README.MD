# Nudge App Maestro Tests

This repository contains automated tests for the Nudge app using Maestro.

## Setup

1. Install Maestro: `curl -Ls "https://get.maestro.mobile.dev" | bash`
2. Download the Nudge test APK from: [Google Drive Link](https://drive.google.com/file/d/14DArV3YKWQFAk5w-H-4BlNCNOJNW4HEj/view?usp=sharing)
3. Install the APK on your Android device or emulator

## Running Tests

To run all tests:
-maestro test nudge_app_tests.yaml
-To run individual test flows:
  -maestro test new_user_flow.yaml
  -maestro test existing_user_flow.yaml
  -maestro test story_flow.yaml
  -maestro test quiz_flow.yaml
  -maestro test user_deletion_flow.yaml

## Test Scenarios

- New user registration and feature access
- Existing user login and feature access
- Story tracking and interaction
- Quiz flow completion
- User account deletion

Note: These tests assume certain UI elements and flows. You may need to adjust the scripts based on the actual app implementation.
