# Awesome-3D-Computer-Vision-Motion-Capture
# Awesome-3D-Computer-Vision-Motion-Capture

## Top 3D Computer Vision & Motion Capture Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Markerless AI Motion Capture, Multi-View 3D Pose Estimation, Optical Mocap & Video Character Replacement*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **3D Computer Vision & Motion Capture**. These tools extract 3D human and object kinematics from single or multi-camera RGB videos, optical infrared arrays, and inertial sensors—converting raw visual feeds into clean SMPL/SMPL-X meshes, BVH/FBX skeletal animations, and VFX character replacements.



**Examples** include Move.ai, DeepMotion, Plask, Rokoko Studio, Kinetix, Radical Motion, Wonder Dynamics (Autodesk Flow Studio), Cascadeur, Vicon Nexus, Qualisys QTM, and Orange-3DV-Team/MoCha (the category leaders). 



**Open-source emphasis**: This section is heavily expanded with every major active project for local markerless multi-camera triangulation, monocular 3D human mesh recovery (HMR), biomechanical kinematics, and open-source character replacement — ideal for computer vision researchers, indie game studios, biomechanists, and VFX artists building transparent mocap pipelines.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Move.ai](https://move.ai)**  

  Multi-camera and single-camera markerless AI motion capture platform extracting studio-grade 3D skeletal animations from standard video without suits or markers.



- **[DeepMotion](https://deepmotion.com)**  

  Cloud AI markerless motion capture suite converting 2D videos into physics-simulated full-body, hand, and facial 3D animations with automatic foot-locking.



- **[Plask](https://plask.ai)**  

  Browser-based AI motion capture and 3D keyframe editing studio for extracting, cleaning, and retargeting video motion directly onto custom 3D rigs.



- **[Rokoko Studio](https://rokoko.com)**  

  All-in-one motion capture software and Rokoko Vision cloud platform supporting inertial Smartsuits, Smartgloves, and single/dual-camera AI video tracking.



- **[Kinetix](https://kinetix.tech)**  

  No-code cloud AI platform and SDK for converting videos into 3D character emotes and integrating user-generated motion into games and virtual worlds.



- **[RADiCAL Motion](https://radicalmotion.com)**  

  Cloud-native AI computer vision platform providing real-time, browser-based 3D human pose estimation and multiplayer motion capture from standard webcams.



- **[Wonder Dynamics (Autodesk Flow Studio)](https://wonderdynamics.com)**  

  Cloud AI VFX studio that automatically detects actor performance from live-action footage, tracks cameras, and replaces actors with rigged CG characters.



- **[Cascadeur](https://cascadeur.com)**  

  Physics-assisted 3D keyframe animation software featuring cloud/AI-powered AutoPosing, video-to-mocap import, trajectory editing, and secondary motion tools.



- **[Vicon Nexus & Shōgun](https://vicon.com)**  

  Industry-standard optical motion capture hardware and cloud-connected software ecosystem for sub-millimeter life sciences, biomechanics, and virtual production tracking.



- **[Qualisys Track Manager (QTM)](https://qualisys.com)**  

  Precision optical and markerless motion capture platform offering cloud analytics and real-time streaming for sports biomechanics, robotics, and animation.





## Open-Source GitHub Projects



- **[Orange-3DV-Team/MoCha](https://github.com)**  

  Open-source end-to-end video character replacement model built on Wan2.1 that swaps characters from a single first-frame mask without structural skeleton guidance while preserving lighting and shadows.



- **[FreeMoCap](https://github.com)**  

  Free, hardware-agnostic open-source (`AGPL-3.0`) multi-camera markerless motion capture system designed to deliver research-grade 3D full-body and object tracking locally.



- **[EasyMocap (zju3dv)](https://github.com)**  

  Comprehensive open-source 3D computer vision toolbox for single/multi-person markerless motion capture and SMPL/SMPL-X/MANO parametric body recovery from RGB videos.



- **[MAMMA (cuevhv)](https://github.com)**  

  CVPR 2026 open-source framework for Markerless Accurate Multi-person Motion Acquisition using deep learning and multi-view SMPL-X 3D human reconstruction.



- **[Pose2Sim](https://github.com)**  

  Open-source markerless kinematics pipeline that triangulates 2D computer vision pose estimates from arbitrary cameras into 3D OpenSim biomechanical models and Blender rigs.



- **[OpenCap Monocular](https://github.com)**  

  Open-source computer vision and musculoskeletal dynamics pipeline estimating validated 3D human movement kinematics (`*.trc`, `*.mot`, `*.osim`) from a single smartphone video.



- **[Mo=Cat Studio](https://github.com)**  

  AI-powered open-source Linux motion capture studio utilizing Meta's SAM 3D Body model, InsightFace re-identification, and ORB camera compensation to export `.glb` mocap files.



- **[WHAM (World-Grounded Humans with Accurate Motion)](https://github.com)**  

  Open-source monocular video-to-3D human motion recovery method reconstructing globally accurate 3D trajectories and SMPL meshes in world coordinates rather than camera space.



- **[4D-Humans / HMR 2.0](https://github.com)**  

  Open-source Transformer-based 3D human mesh recovery and tracking framework capable of reconstructing 3D human pose and shape across video sequences.



- **[GVHMR (Gravity-View Human Motion Recovery)](https://github.com)**  

  Open-source monocular 3D human motion estimation model operating in a gravity-view coordinate system for stable, drift-free world-space skeletal animations.



- **[MediaPipe Pose Landmarker (Google)](https://github.com)**  

  Open-source (`Apache-2.0`) cross-platform computer vision pipeline providing real-time 33-keypoint 3D world-space body, hand, and face landmark tracking on CPU/GPU/WebAssembly.



- **[MMPose (OpenMMLab)](https://github.com)**  

  Modular open-source (`Apache-2.0`) PyTorch toolbox supporting 2D/3D human pose estimation, whole-body keypoint detection, and multi-view 3D triangulation models.



- **[Anipose](https://github.com)**  

  Open-source Python toolkit for markerless multi-camera calibration, 3D keypoint triangulation, and spatiotemporal filtering across humans, animals, and robotics.



- **[BlendCap](https://github.com)**  

  Offline open-source (`GPL-3.0`) single-video computer vision performance capture add-on for Blender 4.2+ with body, hand, and face tracking plus foot-grounding cleanup.



- **[3d-pose-estimation-mocap-align](https://github.com)**  

  Open-source computer vision pipeline implementing multi-view 2D detection, 3D triangulation, and temporal/spatial alignment against ground-truth optical MoCap datasets.



### Additional Strong Open-Source Options



- **[MoCap Anything](https://github.com)** and **[vid2anim](https://github.com)** for single-video 3D motion extraction and universal retargeting onto Mixamo, Rigify, and UE5 rigs.

- **[AlphaPose](https://github.com)** and **[RTMPose](https://github.com)** for high-accuracy multi-person 2D/3D whole-body pose estimation backends.

- **[COLMAP](https://github.com)** and **[Nerfstudio](https://github.com)** for camera pose estimation and 3D scene reconstruction paired with human mocap ([3D-scene-and-human-capture](https://github.com)).

- **[AMASS Loader](https://github.com)** and **[SMPL-X](https://github.com)** for unified large-scale 3D human motion datasets and expressive body-hand-face parametric models.

- **[gesture-3d-studio](https://github.com)** and **[3D-MOTION-TRACKING](https://github.com)** for real-time browser WebGL and WebSocket MediaPipe 3D motion visualization.



**Frameworks for building custom systems**: Combine **FreeMoCap** or **EasyMocap** with **WHAM / GVHMR**, **Pose2Sim**, and **Blender** (or **Orange-3DV-Team/MoCha** for direct video character replacement) for end-to-end local 3D computer vision motion capture pipelines.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Many academic 3D human mesh recovery repositories rely on **SMPL / SMPL-X** body models, which carry separate non-commercial research licenses — verify license terms before commercial deployment.

- Multi-camera markerless mocap setups require synchronized frame timestamps and intrinsic/extrinsic camera calibration (e.g., ChArUco boards) for accurate 3D triangulation.



---



**Made for computer vision engineers, biomechanists, technical artists, and indie game developers.**  

Let's make 3D computer vision and motion capture more open, accurate, and accessible.
