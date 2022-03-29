# VR-Gesture-Recognition

Documentation of Unreal Engine (UE) levels created as part of an honours project for the University of Glasgow.


### Executable Release Installation Guide -
* This project is currently only implemented for Vive controllers, could not test other VR HMDs.

1. Navigate to the release of this repository and download the archived project.
2. Unzip the project, then run the included executable once an appropriate VR setup has been set up.


### Unreal Engine Installation Guide - 
* If you have UE 4.26.2 installed, skip to step 4. If you have the Epic Games Launcher (EGL) installed skip to step 2.

1. Install the EGL from this link: https://store.epicgames.com/en-US/download
2. Open up the EGL and select Unreal Engine on the sidebar. Select Library on the navigation bar and click the + symbol beside Engine Versions.
3. Select the dropdown tab beside the version of the new UE slot, pick version 4.26.2 then install.
4. Use the following link to do a partial download of this repository for the current version: https://minhaskamal.github.io/DownGit/#/home?url=https://github.com/LeeonLau/VR-Gesture-Recognition/tree/main/GestureRecVR_V4
5. Once installed, open up Unreal Engine 4.26.2, click on More then Browse... to open your workspace. Extract the downloaded UE project from step 4 into your workspace.
6. Back on UE, select Refresh and the newly added project should be available. Double click to open the project.
7. Once opened, Play (or Alt+P) can be clicked start the level. Only Vive controllers are mapped since it is the only available controller I could validate correct mapping for. This can be configured in Edit -> Project Settings -> Engine -> Input.
8. To further explore the implemented functionality, in the content browser at the bottom of the editor, access Content -> VirtualRealityBP -> Blueprints -> BP_Motion Controller.
