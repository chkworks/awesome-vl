# Awesome VL
A collection of libraries, resources and examples for vvvv and VL.

## Official Channels

### vvvv Group

* [visualprogramming.net](https://visualprogramming.net) - The official website for vvvv gamma
* [vvvv.org](https://vvvv.org) - The old website for vvvv beta
* [Forum](https://discourse.vvvv.org) - The official forum
* [The Gray Book](https://thegraybook.vvvv.org) - The official documentation
* [vvvvTV](https://www.youtube.com/@vvvvTv42) - The official YouTube channel
* [VL-Language](https://github.com/vvvv/VL-Language) -  The official repo for the design of the VL programming language 

### Community

* [The NODE Institute](https://thenodeinstitute.org/) - Institute for applied creative computation, hosting user meetups, workshops, webinars and online courses for creative coding and media arts.
* [NODE Forum](https://nodeforum.org/) - A platform for sharing and investigating creative technologies, for artistic research and cultural and political media education.
* [Stride](stride3d.net/) - The official website of Stride, the open-source game enginge that provides the backend for 3D rendering in vvvv
* [thefuselab.io](https://www.thefuselab.io/) - The official website of FUSE, the open-source library for visually programming on the GPU.

### Sponsoring Pages
* [Stride on OpenCollective](https://opencollective.com/stride3d) - Sponsoring page for the Stride game engine.
* [The Fuse Lab on OpenCollective](https://opencollective.com/the-fuse-lab) - Sponsoring page for the VL.Fuse library.
* [Kairos Research Lab on OpenCollective](https://opencollective.com/the-fuse-lab) - Sponsoring page for the VL.Kairos library.

## Libraries

### General

* [VL.CoreLib](https://github.com/vvvv/VL.StandardLibs/tree/main/VL.CoreLib) - The main vvvv core library
* [VL.StandardLibs](https://github.com/vvvv/VL.StandardLibs) -  A collection of standard libraries for vvvv
* [VL.Addons](https://github.com/bj-rn/VL.Addons) - A place to gather contributions by the vvvv community, including a great amount of extended texture generators and filters

### Rendering

* [VL.Skia](https://github.com/vvvv/VL.StandardLibs/tree/main/VL.Skia) - The main 2D rendering engine
* [VL.Skia3d](https://github.com/vvvv/VL.Skia3d) - A simple 3D addon for VL.Skia
* [VL.Stride](https://github.com/vvvv/VL.StandardLibs/tree/main/VL.Stride) - The main 3D rendering and game engine
* [VL.Stride.TextureFX](https://github.com/vvvv/VL.StandardLibs/tree/main/VL.Stride.TextureFX) - Texture sources, filters and mixers
* [VL.Fuse](https://github.com/TheFuseLab/VL.Fuse) - An open-source library for visually programming on the GPU
* [VL.PolyTools](https://github.com/TobyKLight/VL.PolyTools) -  Tools for working with Polygons and Polypaths
* [VL.CEF](https://github.com/vvvv/VL.CEF) - Set of nodes to use the Chromium Embedded Framework (CEF)
* [VL.Video](https://github.com/vvvv/VL.StandardLibs/tree/main/VL.Video) - Set of nodes for video capture and playback
* [VL.Radiosity](https://github.com/michael-burk/VL.Radiosity) - 2D Radiosity Shader
* [VL.Boids-GPU](https://github.com/torinos-yt/VL.Boids-GPU) - GPU Boids Simulation implemented in VL

### Text

* [VL.Stride.Text3d](https://www.nuget.org/packages/VL.Stride.Text3d) - Set of nodes to create and render (extruded) 3D text 
* [VL.RichTextKit](https://github.com/sebllll/VL.RichTextKit) - Wrapper for rich text in VL
* [VL.BMFont](https://github.com/kopffarben/VL.BMFont)

### File Formats

* [VL.Alembic](https://github.com/torinos-yt/VL.Alembic) - A plugin to read .abc Alembic files.
* [VL.Assimp](https://github.com/texone/VL.Assimp) - An alternative 3d model loader for Stride
* [VL.IO.PLY](https://github.com/vvvv/VL.IO.PLY) - Provides support to read .ply files in VL
* [VL.Rhino.3dm](https://github.com/wolfmoritzcramer/VL.Rhino.3dm) - A plugin to simplify the process of importing Rhinoceros 3D files
* [VL.OpenEXR](https://github.com/torinos-yt/VL.OpenEXR) - A simple OpenEXR and .hdr image format loader

### Projection Mapping

* [VL.BadMapper](https://github.com/vvvv/VL.BadMapper) - Collection of tools for convenient manual blending (softedge) and warping (homography, bezier)
* [VL.Mapper](https://github.com/zekeadam/VL.Mapper) - Projection mapping tool for vvvv
* [VL.VIOSOWarpBlend](https://github.com/vvvv/VL.VIOSOWarpBlend) -  Wrapper for the VIOSO WarpBlend API
* [VL.ScalableDisplay](https://www.nuget.org/packages/VL.ScalableDisplay) - Support for the auto projector-alignment technology by Scalable Display Solutions (not open-source)
* [VL.Domemaster](https://discourse.vvvv.org/t/vl-domemaster/20660) - Example to render a scene in the Domemaster format (forum post)

### User Interfaces

* [VL.ImGui](https://github.com/vvvv/VL.StandardLibs/tree/main/VL.ImGui) - A node set around ImGui to render user interfaces in Skia and Stride
* [VL.Elementa](https://github.com/natan-sinigaglia/VL.Elementa) -  Collection of widgets for easy UI prototyping

### Control

* [VL.Kairos](https://github.com/KairosResearchLab/Kairos) - A complete framework for data control and composition
* [VL.AutomataUI](https://github.com/wirmachenbunt/AutomataUI.NET) - A finite statemachine editor for .NET
* [VL.LoopTool](https://github.com/vjgegenlicht/VL.LoopTool) -  A small toolset to create video loops and record them

### Computer Vision

* [VL.OpenCV](https://github.com/vvvv/VL.OpenCV) - A VL wrapper for OpenCVSharp
* [VL.MediaPipe](https://github.com/vvvv/VL.MediaPipe) - Camera tracking, image segmentation and object detection from a video stream
* [VL.Augmenta](https://github.com/vvvv/VL.Augmenta) - Support for Augmenta Tracking Technology in VL

### Audio

* [VL.Audio](https://github.com/vvvv/VL.Audio) - Record, play, filter, synthesize and analyse sound
* [VL.GameAudioPlayer](https://github.com/TobyKLight/VL.GameAudioPlayer) - High level command based audio player
* [VL.IO.Midi](https://github.com/vvvv/VL.IO.Midi) -  Midi nodes and tools
* [VL.MiDi.Music.Utils](https://github.com/lasalillo/VL.MiDi.Music.Utils) -  Midi utilities for VL
* [VL.IO.AbletonLink](https://github.com/SpaceMusicZH/VL.IO.AbletonLink) -  VL wrapper for Ableton Link
* [VL.SCSynth](https://github.com/cnisidis/VL.SCSynth) - SuperCollider Server Library for VL

### Networking

... Todo

### Devices

* [VL.IO.MouseKeyGlobal](https://github.com/bj-rn/VL.IO.MouseKeyGlobal) - Global mouse and keyboard hook

#### Cameras



### Other

* VL.Benchmarks
* System Info

## Learning

### Tutorial NuGets

* [VL.TheBigBang](https://github.com/chkworks/VL.TheBigBang) - A tutorial series of 42 chapters, covering all nodes and techniques to get you started.
* [VL.ExtendedTutorials](https://github.com/TobyKLight/VL.ExtendedTutorials) -  Extended tutorial help patches, covering common questions as learners move from beginner towards intermediate.
* [VL.GenerativeGestaltung](https://github.com/phlegma/VL.GenerativeGestaltung) - Sketches from the book "Generative Gestaltung" implemented in vvvv gamma.

### Tutorial Videos

* [NODE20 Workshops](https://vimeo.com/showcase/node20workshops) - 30 workshops, 90 hours of learning, recorded at NODE20 Forum for Digital Arts in October 2020.
* [Tutorial for Absolute Beginners of VL](https://youtube.com/playlist?list=PL2KeRstDQVRRVnzCHEambwAI4yWmpIF-p&si=Jn55GElh-JUdL-0A) - A tutorial series of 7 videos by chk, covering the most basic nodes and techniques.
* [Intermediate Tutorials for vvvv gamma](https://youtube.com/playlist?list=PLEncasrnvr2bkPb0QKdU1DrDs4Hd_Jr0V&si=u3s4YfLRyV1Sl_R3) - Tutorials by TobyK, focusing on advanced topics about development and architecture.
* [vvvv gamma graphics tutorials](https://youtube.com/playlist?list=PLK3HDkvkLePRQpgCIb8dL9CRSYOTmNbdI&si=lzo2KiwN2iz5HaB1) - Tutorials focusing on techniques on how to generate cool graphics by Takuma Nakata.
* [Model Runtime Editor Design Pattern](https://vvvv.org/contribution/model-runtime-editor-design-pattern) - A convenient way to structure your software and build a flexible app architecture.
* [Midweek Patch Therapy](https://www.youtube.com/@midweekpatchtherapy3983) - Highlights from the weekly Midweek Patch Therapy meetings, created and hosted by domj.

### Examples

* [Community Coding: Design Patterns](https://discourse.vvvv.org/t/community-coding-design-patterns) - A discussion about VL implementations of the book "Head First Design Patterns".
* [TextureFX+](https://discourse.vvvv.org/t/texture-fx-vl-addons/21631) - A forum thread about TextureFX+, a collection of texture generators and filters gathered by the community.
* [Nodevember 2022](https://discourse.vvvv.org/t/vl-examples-patches-playground01/21166) - Example patches by CeeYaa during Nodevember 2022.
* [Genuary 2023](https://github.com/CeeYaa/Genuary2023) - Example patches by CeeYaa during Genuary 2023.

### Online Courses

* [The Stride Bundle](https://thenodeinstitute.org/product/vvvv-intermediates-summer-2024-stride-bundle/)
* [The Fuse Bundle](https://thenodeinstitute.org/product/vvvv-intermediates-summer-2024-fuse-bundle/)
* [Game Logic](https://thenodeinstitute.org/courses/ss23-vvvv-game-logic/)

## Other Resources

### Tools

* [Stride Shader Explorer](https://github.com/tebjan/Stride.ShaderExplorer) - A tool showing the built-in shaders of the Stride game engine and their inheritance hierarchy.
* [List of Material Editors](https://discourse.vvvv.org/t/open-source-material-editor-material-creation-resource-list/19185) - Forum thread about open-source material editors.

### Software made with VL

* [GammaLauncher](https://github.com/sebescudie/GammaLauncher) - A simple launcher for vvvv gamma.
* [Remoter](https://github.com/vvvv/Remoter) -  GUI over PAExec and robocopy to remote a bunch of PCs at once.
* [Schema](https://github.com/domjancik/scnq-schema) - An intuitive visual programming interface and runtime.
* [TexconvGui](https://github.com/bj-rn/texconvgui) - A simple Gui for Microsoft's Texconv to batch convert images.

### Articles

* [About vvvv gamma](https://thenodeinstitute.org/about-vvvv-gamma/) - The NODE Institute
* [The flow of creative expression: Paving the way for vvvv](https://meso.design/en/articles/the-flow-of-creative-expression-paving-the-way-for-vvvv) - MESO
* [What is VVVV + Fuse and Why It's a Powerful Combo for New Media](https://www.dataisbeautiful.club/post/what-is-vvvv-fuse-and-why-it-s-a-powerful-combo-for-new-media) - Ameen Insan
