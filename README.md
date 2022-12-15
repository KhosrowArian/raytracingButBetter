# raytracingButBetter
Graphics Final project

Running Instructions:
Before running the project you must download VulkanSDK in the main directory of this repo. The folders can be found here <google docs link coming soon>.
The repository contains the already built version of the project (Note: it was built on Windows using Visual Studio 2022). To run the project, navigate to vkRayTracer/build. There, you can open the vkraytracing.sln. In the solution, right click on vk_ray_tracing__simple_KHR' and press 'Debug,' then 'Start Without Debugging.'

Changing the Scene:
In the built project solution, navigate to Sources/main.cpp. In the main function, on line 160 and 161, the obj models are being loaded. There, the .obj files can be changed to the .obj files in the ../media/scenes folder.

Libraries and SDKs:
VulkanSDK: https://vulkan.lunarg.com/sdk/home
Nvvk libraries: https://github.com/nvpro-samples/nvpro_core.git
imgui: https://github.com/ocornut/imgui
GLFW: https://github.com/glfw/glfw
