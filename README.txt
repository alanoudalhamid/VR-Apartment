# Build an Apartment
Starter project for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Course: VR Scenes & Objects
- Project: Build an Apartment


### Versions Used
- [Unity LTS Release 2017.4.4](https://unity3d.com/unity/qa/lts-releases?version=2017.4)
- [GVR SDK for Unity v1.100.1](https://github.com/googlevr/gvr-unity-sdk/releases/tag/v1.100.1)


### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated lesson.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.


### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is included.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.100.1, make sure you accept any API update pop-up prompts triggered by Unity. Alternatively, you can manually run the API updater (Unity menu `Assets` > `Run API Updater...`) after the import has completed.


### Related Repositories
- [VR Scenes and Objects - Game Objects](https://github.com/udacity/VR-Scenes-and-Objects_Game-Objects/releases)
- [VR Scenes and Objects - Animations](https://github.com/udacity/VR-Scenes-and-Objects_Animations/releases)
- [VR Scenes and Objects - Cameras](https://github.com/udacity/VR-Scenes-and-Objects_Cameras/releases)
- [VR Scenes and Objects - Lights](https://github.com/udacity/VR-Scenes-and-Objects_Lights/releases)
- VR Scenes and Objects - Build an Apartment


Project Submitted By: Alanoud Alhamid (alanoudalhamid@gmail.com)
Submitted Build Platform: Android
GVR Version: v1.100.1
Unity Version: 2017.4.4f1
Credits: Some 3D models found in the 'Build an apartment' scene were downloaded from 3D Warehouse and is arranged and exported using SketchUp Pro. This project is purely for educational purposes and there is no possibility of any personal or organizational profiting out of its use.

Personal Reflection:
This project took a total of a week to complete. A week of intensive yet mostly delightful learning. I Particularly enjoyed placing the 3D models and experimenting with SketchUp, a tool that I wasn't familiar with before, to do so.
The trickiest part was choosing the right lightmap resolution. I noticed that the larger the value is, the blotchier the 3D models' materials looked, whether they were compressed or uncompressed. So I thought the resolution of 2 looked the most pleasing in this situation. And therefore, the idea of shadows was 'out the window' (get it?)  since it would be wasted computational cost for something that wouldn't even be visible.