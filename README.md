 # Bentoit - Swift Student Challenge Submission
 ![output](https://github.com/user-attachments/assets/0ff32c3f-31ff-4218-a39a-b9fa90e03c8d)
## Overview
**Bentoit** is a tool designed to simplify the creation of professional marketing assets, specificly static and animated bento grids. It enables indie developers and creators to craft visually appealing promotional materials effortlessly in minutes - no graphic design skills.

## Features
  - **Dynamic Bento Layouts**: Drag, resize, add, or ditch elements with ease.
  - **Auto Generate Layouts**: Tap once, get a flawless layout.
  - **Rich Content Integration**: Drop in text, symbols, and images.
  - **Animations**: Make your grids pop with Metal and SwiftUI effects.
  - **Photo & Video Export**: Share your Bento grids anywhere.

## Technologies Used
  - Swift
  - SwiftUI
  - PhotoUI
  - Metal (for custom shaders)
  - AVFoundation (for video generation)
  - TipKit
  - iOS 18 Container APIs (e.g., Group(subviews:))

## Showcase
https://github.com/user-attachments/assets/df339f68-029a-4e9e-b76d-20e738fe81d6

## Development Challenges
  - Building the Dynamic Layout:
    - Implemented a bin-packing algorithm for efficient element placement.
    - Developed comprehensive collision resolution logic for dealing with dragging and resizing.
  - Exporting SwiftUI animations to video:
    - Engineered a frame-by-frame snapshot system with AVFoundation for video rendering.
