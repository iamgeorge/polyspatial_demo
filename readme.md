# VisionOS Unity App

This project is a sample application built in Unity for **Apple Vision Pro** using **visionOS**. It was compiled into Xcode and runs in the Vision Pro Simulator.

## Requirements

- Mac with M1 or later
- Unity 2022.3 LTS with iOS Build Support
- Unity Pro/Industry/Enterprise license
- Xcode 15+
- Apple Vision Pro Simulator

## How to Build

1. Open the project in Unity.
2. Go to **File > Build Settings**.
3. Set platform to **visionOS**, target SDK to **Simulator SDK**.
4. Add scenes from `Assets/Samples/PolySpatial/Scenes`, move `Project Launcher` to the top.
5. Click **Build** and save the project.

## Run in Simulator

1. Open the generated `.xcodeproj` file in Xcode.
2. Set target to **Apple Vision Pro Simulator**.
3. Click **Run** to launch the app.

## Notes

- App Mode is set to Mixed Reality - Volume.
- Includes PolySpatial packages and visionOS plugins.
- For faster testing, use Play to Device (see PolySpatial docs).

Created by George
