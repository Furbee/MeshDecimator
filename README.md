# MeshDecimator
A mesh decimation library for .NET and [Unity](https://unity3d.com/). The project is written entirely in C# and released under the MIT license.

## Compatibility
This provided Unity Example project is currently compatible with Unity 2017.3

## Installation into Unity
After building the project, copy over *MeshDecimator.dll* and *MeshDecimator.xml* into your Unity project, anywhere within your Assets directory (for example *Assets/MeshDecimator*).

In the provided Unity example in this repository you can find examples of how to use the mesh decimation from Unity.

## Fast Quadric Mesh Simplification Algorithm
MeshDecimator uses an algorithm based on the [Fast Quadric Mesh Simplification](https://github.com/sp4cerat/Fast-Quadric-Mesh-Simplification) algorithm, completely rewritten in C#.
Currently it is the only mesh decimation algorithm available to use.

## Credits
The teddy bear model in the Unity example project is from the following package from Unity Asset Store: https://assetstore.unity.com/packages/essentials/tutorial-projects/mecanim-example-scenes-5328

## Other projects
If you are interested in a more simple mesh simplification in Unity you can visit my other project [UnityMeshSimplifier](https://github.com/Whinarn/UnityMeshSimplifier).
