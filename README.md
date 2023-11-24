# HTCViveTemplateUE53
Project files for an HTC Vive Template for Unreal Engine 5 from the original Unreal Engine 4
HTC VIVE Template 

It seems the community is in need of a quality HTC Vive Template till Epic Games gets their official ones going.
Unreal Engine 4 version was original by [Carlos Montero GitHub user cman2k](https://github.com/cman2k/HTCViveTemplate-UE4)

This Unreal Project was upgraded to Unreal 5.3. The unique value of this project is its small size and easy starting point for those coming to VR

This is just hosted here. The users do not have any hardware. Therefore is no support

Steam support page is [here](https://help.steampowered.com/en/)

**NO WARRANTY** This learning tutorial and not for production use

GitHub Download: 
Installation Click the green "Code" button above select "Download Zip"

Right Click on zip file Propeties tick the "Unblock" the decompress into folder. 

Open Unreal Engine 5.3 and browse for the folder select the project. 

Version 1.0

Features:

-Smallest VR Project EVER: So far the total project size is about 6MB, WHAT?!
-Preset Rendering Settings: Don't have to go into 'Project Settings' and change anything.
-Trackpad Input Bindings included for non-room scale locomotion
-VR-Physics World: Go have some fun with picking up and throwing objects!


General Changes:

-Added HTC Vive motion controller static meshes for "hands"
-Target Hardware: Set to mobile w/ scalable 2D and 3D (this is how you achieve 6Mb project file size)

Render Settings Changes:

-Default Postprocessing Settings: All Disabled (enable if you really need them...)
-Optimization Changes: Early Z-pass set to 'Opaque Meshes Only,' Movables in early Z-Pass enabled, Clear Scene set to 'Do Not Clear,' with Vertex Deformation and GBuffer rendertargets disabled
-Instant Stereo Rendering: Enabled
-Framerate Settings: Smooth rate, min 90, max 120, min desired 90 (this one is debatable depending on who you talk to)

VR-PhysicsWorld:

-Postprocessing volume preset (no bloom, SSRs, etc.)
-Basic material that has been instanced
-Physics Cube Actors to interact with (pickup, throw, etc.)


See the full post on [Steam Unreal HTC VIVE Template](https://steamcommunity.com/app/358720/discussions/0/357284767248753791/)

