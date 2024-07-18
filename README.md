Jet Engine AR Simulation
Experience the intricate workings of a jet engine through this Augmented Reality (AR) application developed with Unity. This project offers an immersive educational tool to visualize and understand the components and operations of a jet engine in a 3D AR environment.

Table of Contents
Features
Installation
Usage
AR Setup
Development
Contributing
License
Acknowledgements
Features
Realistic Jet Engine Simulation: View and interact with a detailed 3D model of a jet engine.
Component Breakdown: Explore individual components and understand their functions.
Interactive AR Environment: Use your mobile device to place the jet engine model in the real world and interact with it.
Educational Content: Learn about jet engine mechanics through informative overlays and animations.
Installation
Prerequisites
Unity Hub and Unity 2021.3 or later
AR Foundation, ARCore XR Plugin, and ARKit XR Plugin
Android or iOS device compatible with ARCore or ARKit
Steps
Clone the repository:

git clone https://github.com/your-username/JetEngineARSimulation.git


Open the project in Unity Hub.
Install the required packages via Unity Package Manager:
AR Foundation
ARCore XR Plugin (for Android)
ARKit XR Plugin (for iOS)
Usage
Connect your AR-compatible device to your development machine.
Open the project in Unity and load the ARScene.
Build and run the project on your device:
For Android: File -> Build Settings -> Android -> Build and Run
For iOS: File -> Build Settings -> iOS -> Build and Run
Point your device to a flat surface to place and interact with the jet engine model.
AR Setup
Android (ARCore)
Ensure your Android device supports ARCore.
Configure the project for Android build:
File -> Build Settings -> Android
Switch Platform and set Player Settings accordingly.
Enable ARCore support in Project Settings -> XR Plug-in Management.
iOS (ARKit)
Ensure your iOS device supports ARKit.
Configure the project for iOS build:
File -> Build Settings -> iOS
Switch Platform and set Player Settings accordingly.
Enable ARKit support in Project Settings -> XR Plug-in Management.
Development
Folder Structure
Assets/: Main directory containing all project assets.
Assets/Scripts: Directory for C# scripts.
Assets/Models: Directory for 3D models and textures.
Assets/Scenes: Directory for Unity scenes.
Key Scripts
JetEngineController.cs: Handles the simulation and interaction logic for the jet engine.
ARPlacementController.cs: Manages the placement and scaling of the jet engine in the AR environment.
UIManager.cs: Controls the educational overlays and user interface elements
