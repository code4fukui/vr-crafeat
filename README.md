# vr-crafeat

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A WebXR experience showcasing 3D scanned food models from CRAFEAT, built with A-Frame.

## Demo

**[https://code4fukui.github.io/vr-crafeat/](https://code4fukui.github.io/vr-crafeat/)**

The experience places you in front of two floating, high-fidelity 3D models: a Kani (crab) Burger and Shishiniku (wild boar meat).

## Features

- **WebXR Ready:** Built with A-Frame for immersive viewing on VR headsets and desktop browsers.
- **High-Fidelity Models:** Features two realistic 3D food models: `kani-burger` and `shishiniku`.
- **Cross-Platform Assets:** Models are provided in both `.glb` (for WebXR) and `.usdz` (for iOS AR) formats.
- **Device-Aware Scaling:** Automatically adjusts the scale and position of models for optimal viewing on both desktop and Meta Quest headsets.
- **Color Management:** The A-Frame scene is configured with color management for better visual quality.

## Usage

1.  Visit the [demo link](https://code4fukui.github.io/vr-crafeat/) in a supported web browser.
2.  On a WebXR-compatible device (e.g., Meta Quest), click the "Enter VR" button to view the scene immersively.
3.  To run locally, serve the `index.html` file from a local web server.

## 3D Models

The following 3D model assets are included in this repository:

- `kani-burger.glb` / `kani-burger.usdz`
- `shishiniku.glb` / `shishiniku.usdz`

The scene is rendered using A-Frame's `<a-scene>` and `<a-entity gltf-model="...">` components.

## Attribution

- The 3D food models are from [CRAFE