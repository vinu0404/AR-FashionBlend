# FashionBlend: AR Virtual Try-On

FashionBlend is an augmented reality (AR) mobile app that lets users virtually try on clothes in real-time using a smartphone camera. Built with Unity, ARCore, and TensorFlow, it offers a seamless e-commerce experience by addressing sizing issues and reducing returns.

## Features

- Real-time AR garment visualization
- 2D/3D pose estimation for accurate mapping
- 3D garment models with dynamic scaling
- User-friendly Android interface
- Asynchronous server-side processing

## Tech Stack

- **Frontend**: Android, Unity, ARCore
- **Backend**: Python, Flask
- **ML**: TensorFlow (OpenPose-inspired)
- **3D Modeling**: Blender
- **Database**: SQLite

## Requirements

- Android device (API 24+, ARCore support)
- ARMv7 CPU, 2GB+ RAM

## Installation

1. Clone the repo: `git clone https://github.com/vinu0404/FashionBlend.git`
2. Set up the server: `pip install -r requirements.txt`
3. Build the Android app in Unity.
4. Run the server: `python server.py`
5. Launch the app and follow the UI to try on garments.

## Usage

1. Record a video in the app.
2. Select a garment from the library.
3. View the AR try-on results after server processing.