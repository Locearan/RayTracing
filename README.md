# Vulkan Ray Tracing Renderer

A real-time ray tracing application built using **C++**, **Vulkan**, and **Dear ImGui**. This project demonstrates physically-based lighting, emissive materials, and dynamic scene composition with real-time parameter editing via ImGui.

![Screenshot 1](./images/one.png)
*Example with red emissive lighting*

![Screenshot 2](./images/two.png)
*Example with cyan emissive lighting*

## Features

- ⚡ Real-time ray tracing renderer using Vulkan compute shaders
- 🧱 Material system with Albedo, Roughness, Metallic, and Emission properties
- 🎮 Interactive scene editing with Dear ImGui
- 🌈 Color emission and light propagation
- 🔁 Frame accumulation toggle for noise reduction
- 📊 Live performance metrics and render timing

## Controls

- Use the **ImGui interface** to:
  - Add/edit spheres in the scene
  - Modify position, radius, and material index
  - Adjust material properties (color, emission, roughness, metallic)
  - Reset accumulation buffer after changes
- Toggle **accumulation** for better visual quality over time
- 
### Build Steps

Clone recursively: git clone --recursive https://github.com/Locearan/RayTracing
Run scripts/Setup.bat
Open RayTracing.sln and hit F5 (preferably change configuration to Release or Dist first, Debug is slow)

