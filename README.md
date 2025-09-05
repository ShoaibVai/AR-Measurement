# AR-Measurement

An Augmented Reality concept project for measuring real-world distances and objects using a mobile device camera. This repo currently hosts licensing and documentation; the Unity source is not included in this folder.

## Overview
- Goal: place anchors on detected surfaces, measure linear distances, and compute simple areas.
- Platform: Mobile (Android/iOS) using AR Foundation and ARCore/ARKit in a typical setup.

## Features (intended)
- Place start/end points on planes.
- Show live distance in meters/feet.
- Toggle unit systems.
- Save a snapshot with overlaid measurements.

## Getting started
Because the Unity project files aren’t present here, import the features into your own Unity 2022 LTS project:
1) Create a new Unity 2022.3 LTS project (3D URP or 3D).
2) Install AR Foundation, ARCore XR Plugin, and/or ARKit XR Plugin.
3) Add plane detection and a tap-to-place interaction.
4) Compute world-space distances between placed anchors and display them with TextMeshPro.

## Build targets
- Android: Minimum ARCore-capable device.
- iOS: ARKit-capable device.

## License
See LICENSE.

