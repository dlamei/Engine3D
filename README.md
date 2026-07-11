# Atlas
## Engine for visualizing 3d Scenes

 <img width="2102" height="1316" alt="image" src="https://github.com/user-attachments/assets/fd7279c1-dac6-40fb-ba85-b41964c4377d" />


### Dependencies
GLFW, GLM, Glad,  ImGui,  ImGuizmo,  spdlog,  stb_image, Premake

### Build Instructions
1. Clone the repository with submodules:
   `git clone --recurse-submodules https://github.com/dlamei/Engine3D.git`
2. If you already cloned it, initialize submodules:
   `git submodule update --init --recursive`
3. Generate Visual Studio 2019 project files from the repo root:
   `GenerateProjects.bat`
4. Open the generated solution in Visual Studio 2019.
5. Set `Sandbox` as the startup project, choose `Debug|x64` (or `Release|x64`), and build/run.
