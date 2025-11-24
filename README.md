# VR_acute_stress_demo
Project Name

ExpParadigm_PicoVR_Neo3

1. Project Overview
A VR acute stress application example targeting Pico VR (Neo3). The project contains scenes, UI, modular scripts, and support for the KAT omnidirectional treadmill and Protobuf.

2. Basic Information
- Engine & Version: Unity 2017+
- XR Plugin: PicoXR
- Target Device: Pico Neo3
- Dependencies: KAT treadmill plugin, Protobuf plugin, custom UPM packages

3. Project Structure (root)
- Assets: All project assets (source, scenes, prefabs, etc.)
- CustomPackages: Custom UPM packages
- Library: Unity local compilation cache (do not commit)
- Logs: Project logs directory (do not commit)
- obj: Project cache directory (do not commit)
- Package: UPM package configuration directory
- Proto: Protobuf tools folder
- Tools: Project tools directory
- UserSettings: Local user settings (do not commit)

4. Assets Directory (ExpParadigm_PicoVR_Neo3/Assets)
- AppFramework: Project framework, includes editor tool scripts, third-party plugins, project configuration, startup scene and framework scripts
- Plugins: KAT omnidirectional treadmill plugin code
- Resources: Runtime resources (UI prefabs, images, audio/video, scene assets, etc.)
- Scenes: Test and demo scenes (please specify the default startup scene in README)
- Scripts: Module code; main code is under the `Modules` subdirectory
- UI: Raw UI assets
- URP: URP render pipeline settings
- XR and XRI: PicoXR / XRI project settings and configuration

5. Modules (ExpParadigm_PicoVR_Neo3/Assets/Resources/AssetsFolder/App/Modules)
- LoginLauncher: Startup and login (requires username/password)
- Login: Scene after login
- Splash: Preparation stage (snow screen, plays snow video and audio)
- City: City scene
- Mountains: Mountain scene
- PASAT: Final PASAT test stage
