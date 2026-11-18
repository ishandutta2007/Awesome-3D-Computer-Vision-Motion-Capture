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

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global 3D motion capture and computer vision kinematics market is estimated at approximately **$318M to $486M in 2025–2026**, projected to approach nearly **$1B by 2030** at a CAGR of ~12.5%–13.6%. The sector exhibits **moderate-to-high fragmentation**, where specialized legacy hardware giants (Vicon, Qualisys) dominate clinical biomechanics and AAA studios, while high-velocity AI markerless SaaS entrants (Move.ai, Plask, DeepMotion) compete vigorously in an un-concentrated, democratized tier that has spurred active M&A by enterprise graphics stalwarts like Autodesk and Runway.

## SaaS/Hosted Platforms

| Company / Product | Size (Revenue / Valuation) | Pricing | Free Tier / Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Wonder Dynamics (Autodesk Flow Studio)](https://wonderdynamics.com)** | **$53B+ MCap** ($7.2B FY26 Rev, parent Autodesk) | **$7 to $10 / month** (Lite tier, billed annually/monthly) | **Free forever plan**: 300 credits/mo, 720p watermarked export; eligible university students get 2,100 credits/mo | Cloud AI VFX studio automatically detecting actor performance from video, tracking cameras, and replacing actors with rigged CG characters. |
| **[RADiCAL Motion](https://radicalmotion.com)** | **$53B+ MCap** ($7.2B FY26 Rev, acquired by Autodesk) | **$8 / month** ($96/year legacy commercial tier; integrated into Autodesk Flow ecosystem) | **Legacy Free tier**: 24 hours of total playtime/processing per year with metered FBX exports | Cloud-native AI computer vision platform providing real-time 3D human pose estimation and multiplayer motion capture from standard webcams. |
| **[Rokoko Studio](https://rokoko.com)** | **$80M+ Valuation** (~$15M funding, Naver Z backed) | **$12 / month** (Basic tier; $28/mo for Plus hardware tier) | **Free forever plan (Starter)**: 30s/mo Vision AI processing, unlimited recordings, FBX export, 3 actor profiles (no live stream/face capture) | All-in-one motion capture software and Rokoko Vision cloud platform supporting inertial Smartsuits, Smartgloves, and single/dual-camera video tracking. |
| **[Vicon Nexus & Shōgun](https://vicon.com)** | **£47M (~$58M) MCap** (£44.8M Rev, parent Oxford Metrics LSE:OMG) | **$12,500+ / seat** (perpetual standalone/network license via enterprise quote) | **Free evaluation**: 30-day evaluation trial license available upon institutional/lab demonstration request | Industry-standard optical motion capture hardware and software ecosystem for sub-millimeter life sciences, biomechanics, and virtual production. |
| **[Qualisys Track Manager (QTM)](https://qualisys.com)** | **390M SEK (~$38M) MCap** (~270M SEK Rev, Nasdaq Stockholm: QSYS) | **$8,000+ / lab** (departmental site license with unlimited seats via enterprise quote) | **Free evaluation**: Customized trial license and remote hardware demo available upon institutional request | Precision optical and markerless motion capture platform offering cloud analytics and real-time streaming for sports biomechanics and robotics. |
| **[Cascadeur](https://cascadeur.com)** | **~$30M–$50M Est. Valuation** (Nekki subsidiary, $1.5M budget + Epic MegaGrant) | **$13 to $19 / month** (or $72–$96/year billed annually, Indie tier for <$100k revenue) | **Free forever plan**: Full core physics toolset, limited strictly to `.casc` format (no `.fbx`/`.usd` exports, non-commercial only) | Physics-assisted 3D keyframe animation software featuring AI AutoPosing, video-to-mocap import, trajectory editing, and secondary motion tools. |
| **[Move.ai](https://move.ai)** | **$17.5M Funding** (£1.1M Rev, acquired by Oxford Metrics/Vicon) | **$18 / month** (Move One Starter tier, billed monthly) | **Free forever plan**: 30 one-time credits (~30s Gen-1 capture), up to 30-second clips, personal non-commercial use | Multi-camera and single-camera markerless AI motion capture platform extracting studio-grade 3D skeletal animations from standard video. |
| **[Kinetix](https://kinetix.tech)** | **$11.6M Funding** (~$6.9M ARR, acquired by Runway) | **$15 / month** (starter SDK license / €0.15 per additional emote; enterprise for game studios) | **Free trial**: Developer sandbox with up to 10,000 free generated emotes during onboarding/trial period | Cloud AI platform and SDK for converting videos into 3D character emotes and integrating user-generated motion into games and virtual worlds. |
| **[Plask](https://plask.ai)** | **$2.56M+ Funding** (Naver D2SF & Pre-Series A backed) | **$18 / month** (Standard tier, billed annually) | **Free forever plan**: 15 seconds daily motion capture generation limit, 1 GB cloud storage | Browser-based AI motion capture and 3D keyframe editing studio for extracting, cleaning, and retargeting video motion directly onto custom 3D rigs. |
| **[DeepMotion](https://deepmotion.com)** | **$2.8M Funding** (Samsung Ventures & Bandai Namco 021 backed) | **$9 to $15 / month** (Starter / Animate 3D tier) | **Free forever plan**: 60 seconds/month (60 animation credits, up to 10s per clip, non-commercial use) | Cloud AI markerless motion capture suite converting 2D videos into physics-simulated full-body, hand, and facial 3D animations with foot-locking. |





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
