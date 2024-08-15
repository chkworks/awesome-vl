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
* [Stride](stride3d.net/) - The official website of Stride, the open-source game enginge that provides the backend for 3D rendering in vvvv.
* [thefuselab.io](https://www.thefuselab.io/) - The official website of FUSE, the open-source library for visually programming on the GPU.

### Sponsoring Pages
* [Stride on OpenCollective](https://opencollective.com/stride3d) - Sponsoring page for the Stride game engine.
* [The Fuse Lab on OpenCollective](https://opencollective.com/the-fuse-lab) - Sponsoring page for the VL.Fuse library.
* [Kairos Research Lab on OpenCollective](https://opencollective.com/the-fuse-lab) - Sponsoring page for the VL.Kairos library.
* [chk on Ko-Fi](https://ko-fi.com/chk) - Sponsoring page for chk and VL.TheBigBang.

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
 
#### Shaders
* [VL.Fuse](https://github.com/TheFuseLab/VL.Fuse) - An open-source library for visually programming on the GPU
* [VL.Radiosity](https://github.com/michael-burk/VL.Radiosity) - 2D Radiosity Shader
* [VL.Boids-GPU](https://github.com/torinos-yt/VL.Boids-GPU) - GPU Boids Simulation implemented in VL

#### Video
* [VL.Video](https://github.com/vvvv/VL.StandardLibs/tree/main/VL.Video) - Set of nodes for video capture and playback
* [VL.HapPlayer](https://www.nuget.org/packages/VL.HapPlayer) - HAP GPU Video Playback Plugin (*requires a license*)

#### Text
* [VL.Stride.Text3d](https://www.nuget.org/packages/VL.Stride.Text3d) - Set of nodes to create and render (extruded) 3D text 
* [VL.RichTextKit](https://github.com/sebllll/VL.RichTextKit) - Wrapper for rich text in VL
* [VL.BMFont](https://github.com/kopffarben/VL.BMFont)

#### Other
* [VL.PolyTools](https://github.com/TobyKLight/VL.PolyTools) -  Tools for working with Polygons and Polypaths
* [VL.CEF](https://github.com/vvvv/VL.CEF) - Set of nodes to use the Chromium Embedded Framework (CEF)

### Control
* [VL.Kairos](https://github.com/KairosResearchLab/Kairos) - A complete framework for data control and composition
* [VL.AutomataUI](https://github.com/wirmachenbunt/AutomataUI.NET) - A finite statemachine editor for .NET
* [VL.LoopTool](https://github.com/vjgegenlicht/VL.LoopTool) -  A small toolset to create video loops and record them

### Computer Vision
* [VL.OpenCV](https://github.com/vvvv/VL.OpenCV) - A VL wrapper for OpenCVSharp
* [VL.MediaPipe](https://github.com/vvvv/VL.MediaPipe) - Camera tracking, image segmentation and object detection from a video stream
* [VL.Augmenta](https://github.com/vvvv/VL.Augmenta) - Support for Augmenta Tracking Technology in VL

### User Interfaces
* [VL.ImGui](https://github.com/vvvv/VL.StandardLibs/tree/main/VL.ImGui) - A node set around ImGui to render user interfaces in Skia and Stride
* [VL.Elementa](https://github.com/natan-sinigaglia/VL.Elementa) -  Collection of widgets for easy UI prototyping

### Audio
* [VL.Audio](https://github.com/vvvv/VL.Audio) - Record, play, filter, synthesize and analyse sound
* [VL.GameAudioPlayer](https://github.com/TobyKLight/VL.GameAudioPlayer) - High level command based audio player
* [VL.MiDi.Music.Utils](https://github.com/lasalillo/VL.MiDi.Music.Utils) -  Midi utilities for VL
* [VL.SCSynth](https://github.com/cnisidis/VL.SCSynth) - SuperCollider Server Library for VL

### Projection Mapping
* [VL.BadMapper](https://github.com/vvvv/VL.BadMapper) - Collection of tools for convenient manual blending (softedge) and warping (homography, bezier)
* [VL.Mapper](https://github.com/zekeadam/VL.Mapper) - Projection mapping tool for vvvv
* [VL.VIOSOWarpBlend](https://github.com/vvvv/VL.VIOSOWarpBlend) -  Wrapper for the VIOSO WarpBlend API
* [VL.ScalableDisplay](https://www.nuget.org/packages/VL.ScalableDisplay) - Support for the auto projector-alignment technology by Scalable Display Solutions (not open-source)
* [VL.Domemaster](https://discourse.vvvv.org/t/vl-domemaster/20660) - Example to render a scene in the Domemaster format (forum post)

### File Formats
* [VL.Alembic](https://github.com/torinos-yt/VL.Alembic) - A plugin to read .abc Alembic files.
* [VL.Assimp](https://github.com/texone/VL.Assimp) - An alternative 3d model loader for Stride
* [VL.IO.PLY](https://github.com/vvvv/VL.IO.PLY) - Provides support to read .ply files in VL
* [VL.Rhino.3dm](https://github.com/wolfmoritzcramer/VL.Rhino.3dm) - A plugin to simplify the process of importing Rhinoceros 3D files
* [VL.OpenEXR](https://github.com/torinos-yt/VL.OpenEXR) - A simple OpenEXR and .hdr image format loader
  
### Protocols
* [VL.IO.AbletonLink](https://github.com/SpaceMusicZH/VL.IO.AbletonLink) -  Wrapper for Ableton Link
* [VL.IO.ArtNet](https://github.com/vvvv/VL.IO.ArtNet) - Support for sending and receiving Art-Net
* [VL.IO.HTTP.WebServer](https://github.com/vvvv/VL.IO.HTTP.WebServer) - Set of nodes to use run a webserver
* [VL.IO.M2MQTT](https://github.com/vvvv/VL.IO.M2MQTT) - An MQTT client for accessing an MQTT broker
* [VL.IO.Midi](https://github.com/vvvv/VL.IO.Midi) -  Midi nodes and tools
* [VL.IO.MQTTnet](https://github.com/mhusinsky/VL.IO.MQTTnet) - MQTT nodes, based on MQTTnet
* [VL.IO.NDI](https://github.com/vvvv/VL.IO.NDI) - Provides support for NDI®
* [VL.IO.NetMQ](https://github.com/vvvv/VL.IO.NetMQ) - Set of nodes to work with NetMQ aka ZeroMQ
* [VL.IO.OSC](https://github.com/vvvv/VL.IO.OSC) - Provides support for the OSC protocol
* [VL.IO.OSCQuery](https://github.com/vvvv/VL.StandardLibs/tree/main/VL.IO.OSCQuery) - Allows to expose parameters via the OSCQuery protocol
* [VL.IO.RCP](https://github.com/rabbitControl/VL.IO.RCP) - Set of nodes to use RCP
* [VL.IO.SPNet](https://github.com/vvvv/VL.IO.SPNet) - Receive data via the SPNet protocol
* [VL.IO.TCP](https://github.com/vvvv/VL.IO.TCP) - Set of nodes to use TCP
* [VL.IO.TUIO](https://github.com/vvvv/VL.IO.TUIO) - Provides support for the TUIO protocol
* [VL.IO.WebSocket](https://github.com/vvvv/VL.IO.WebSocket) - Set of nodes to use websocket client and server
* [VL.BlueIOT](https://github.com/vvvv/VL.BlueIOT) - Support for the BlueIOT open API
* [VL.PJLink](https://github.com/sebllll/VL.PJLink) - Nodes to connect and control projectors via the PJLink protocol
* [VL.SimpleHTTP](https://github.com/sebescudie/VL.SimpleHTTP) - A super-simple set of nodes to perform basic HTTP queries

### Devices

#### Input
* [VL.Devices.SpaceMouse](https://github.com/vvvv/VL.Devices.SpaceMouse) - A package for using the SpaceMouse by 3dconnexion
* [VL.Devices.StreamDeck](https://github.com/mhusinsky/VL.Devices.StreamDeck) - A package for using Elgato StreamDeck button displays
* [VL.Devices.TheEyeTribe](https://github.com/vvvv/VL.Devices.TheEyeTribe) - Set of nodes to use the eye tracker by TheEyeTribe
* [VL.Devices.WinTab](https://github.com/vvvv/VL.Devices.WinTab) - A set of VL nodes for using WinTab devices
* [VL.Devices.SICK](https://github.com/sebescudie/VL.Devices.SICK) - A plugin to interact with SICK lidar scanners
* [VL.GameController](https://github.com/heavy-d/VL.GameController/) - A library to support SDL GameControllers
* [VL.IO.MouseKeyGlobal](https://github.com/bj-rn/VL.IO.MouseKeyGlobal) - Global mouse and keyboard hook
* [VL.IO.Xbox360Controller](https://github.com/domjancik/VL.IO.Xbox360Controller) - Nodes for the Xbox 360 Controller

#### Output
* [VL.Devices.ENTTEC](https://github.com/vvvv/VL.Devices.ENTTEC) - Support for ENTTEC DMX devices
* [VL.ILDA](https://github.com/lasalillo/VL.ILDA) - ILDA laser control
* [VL.M8Display](https://github.com/gamingrobot/VL.M8Display) - A library for Dirtywave M8 Remote Displays
  
#### Cameras & Video Capture
* [VL.Devices.Astra](https://github.com/vvvv/VL.Devices.Astra) - A package for using Astra depth cameras by Orbbec
* [VL.Devices.AzureKinect](https://github.com/vvvv/VL.Devices.AzureKinect) - A package for using Azure Kinect depth cameras by Microsoft
* [VL.Devices.AzureKinect.Body](https://github.com/vvvv/VL.Devices.AzureKinect.Body) - A package for using Azure Kinect body tracking
* [VL.Devices.DeckLink](https://github.com/vvvv/VL.Devices.DeckLink) - A package for using DeckLink capture cards by Blackmagic Design
* [VL.Devices.DigiCamControl](https://github.com/vvvv/VL.Devices.DigiCamControl) - A package for remote controlling DSLR cameras
* [VL.Devices.IDS](https://github.com/vvvv/VL.Devices.IDS) - Support for uEye and uEye+ industrial cameras
* [VL.Devices.Kinect](https://github.com/vvvv/VL.Devices.Kinect) - A package for using Kinect and Kinect XBOX 360 by Microsoft
* [VL.Devices.Kinect2](https://github.com/vvvv/VL.Devices.Kinect2) - A package for using Kinect2 depth cameras by Microsoft
* [VL.Devices.LeapOrion](https://github.com/vvvv/VL.Devices.LeapOrion) - A package for using the Motion Controller by Ultraleap, using the Orion SDK
* [VL.Devices.NuiTrack](https://github.com/vvvv/VL.Devices.NuiTrack) - A package for using the Nuitrack depth camera API
* [VL.Devices.RealSense](https://github.com/vvvv/VL.Devices.RealSense) - A package for using RealSense depth cameras by Intel
* [VL.Devices.TheImagingSource](https://github.com/vvvv/VL.Devices.TheImagingSource) - Support for using industrial cameras by The Imaging Source
* [VL.Devices.uEye](https://github.com/schnellebuntebilder/VL.Devices.uEye) - VL nodes for using uEye cameras by IDS-Imaging
* [VL.Devices.ZED](https://github.com/vvvv/VL.Devices.ZED) - A package for using ZED depth cameras by Stereolabs
* [VL.PTZ](https://github.com/lasalillo/VL.PTZ) - Set of nodes to work with PTZ cameras

#### Physical Computing
* Todo: https://thegraybook.vvvv.org/reference/libraries/physicalcomputing.html

### Machine Learning
* Todo: https://thegraybook.vvvv.org/reference/libraries/machinelearning.html

### Tools & Extensions
* [VL.Benchmarks](https://github.com/tebjan/VL.Benchmarks) - A performance testing suite for VL
* [VL.DebugInfo.HDE](https://github.com/sebescudie/VL.DebugInfo.HDE) - An editor extension that displays relevant debug information

### Other / Todo
* Todo: https://thegraybook.vvvv.org/reference/libraries/misc.html
* [VL.3D.Curve](https://github.com/torinos-yt/VL.3D.Curve) - 
* [VL.GlassWindow](https://github.com/torinos-yt/VL.GlassWindow) - 
* [VL.RogueSharp](https://github.com/TobyKLight/VL.RogueSharp) - 
* [VL.Postman](https://github.com/sebescudie/VL.Postman) - 
* [VL.Fuse.DomainExtensions](https://github.com/torinos-yt/VL.Fuse.DomainExtensions) - 
* [VL.Fresnel](https://github.com/artrevinho/VL.Fresnel) - 
* [VL.OpenWeather](https://github.com/sebescudie/VL.OpenWeather) - 
* [VL.TUIO.HDE](https://github.com/vvvv/VL.TUIO.HDE) - 
* [VL.2D.CurveFitting](https://github.com/mhusinsky/VL.2D.CurveFitting) - 
* [VL.Wekinator](https://github.com/sebescudie/VL.Wekinator) - 
* [VL.QRCode](https://github.com/vvvv/VL.QRCode) - 
* [VL.IO.Firmata](https://github.com/vvvv/VL.IO.Firmata) - 
* [VL.ScreenRecorder](https://github.com/vvvv/VL.ScreenRecorder) - 
* [VL.DemoLib](https://github.com/vvvv/VL.DemoLib) - 
* [VL.Telegram](https://github.com/sebescudie/VL.Telegram) - 
* [VL.2D.DollarQ](https://github.com/vvvv/VL.2D.DollarQ) - 
* [VL.2D.Voronoi](https://github.com/vvvv/VL.2D.Voronoi) - 
* [VL.StringExtensions](https://github.com/sebescudie/VL.StringExtensions) - 
* [VL.ShadowCatcher](https://github.com/torinos-yt/VL.ShadowCatcher) - 
* [VL.Attractors](https://github.com/juanhurle/VL.Attractors) - 
* [VL.Music](https://github.com/natan-sinigaglia/VL.Music) - 
* [VL.Snake](https://github.com/ravazquez/VL.Snake) - 
* [VL.Breakout](https://github.com/ravazquez/VL.Breakout) - 
* [VL.Dope](https://github.com/digitalwannabe/VL.Dope) - 
* [VL.AetherPhysics](https://github.com/elektromeier/VL.AetherPhysics) - 
* [VL.Interpolator](https://github.com/lasalillo/VL.Interpolator) - 
* [VL.Harmony](https://github.com/lasalillo/VL.Harmony) - 
* [VL.NewLibrary.Template](https://github.com/vvvv/VL.NewLibrary.Template) - 
* [VL.Accord](https://github.com/cnisidis/VL.Accord) - 
* [VL.TUIO](https://github.com/InteractiveScapeGmbH/VL.TUIO) - 
* [VL.PDF](https://github.com/eqbic/VL.PDF) - 
* [VL.Devices.Robotiq](https://github.com/phlegma/VL.Devices.Robotiq) -
* 
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

* [Community Coding: Design Patterns](https://discourse.vvvv.org/t/community-coding-design-patterns) - A discussion about implementing various design patterns taken from the book "Head First Design Patterns".
* [VL.HeadFirstDesignPatterns](https://github.com/sebescudie/VL.HeadFirstDesignPatterns) - Repository containing examples of design patterns taken from the book "Head First Design Patterns". 
* [TextureFX+](https://discourse.vvvv.org/t/texture-fx-vl-addons/21631) - A forum thread about TextureFX+, a collection of texture generators and filters gathered by the community.
* [Nodevember 2022](https://discourse.vvvv.org/t/vl-examples-patches-playground01/21166) - Example patches by CeeYaa during Nodevember 2022.
* [Genuary 2023](https://github.com/CeeYaa/Genuary2023) - Example patches by CeeYaa during Genuary 2023.

### Online Courses

* [The Stride Bundle](https://thenodeinstitute.org/product/vvvv-intermediates-summer-2024-stride-bundle/)
* [The Fuse Bundle](https://thenodeinstitute.org/product/vvvv-intermediates-summer-2024-fuse-bundle/)
* [Game Logic](https://thenodeinstitute.org/courses/ss23-vvvv-game-logic/)

## Other Resources

### Tools

* [MergeVLDocs](https://github.com/vvvv/MergeVLDocs) - A first step towards an easy-to-use visual merge tool
* [Stride Shader Explorer](https://github.com/tebjan/Stride.ShaderExplorer) - A tool showing the built-in shaders of the Stride game engine and their inheritance hierarchy.
* [List of Material Editors](https://discourse.vvvv.org/t/open-source-material-editor-material-creation-resource-list/19185) - Forum thread about open-source material editors.

### Software made with VL

* [GammaLauncher](https://github.com/sebescudie/GammaLauncher) - A simple launcher for vvvv gamma.
* [Remoter](https://github.com/vvvv/Remoter) -  GUI over PAExec and robocopy to remote a bunch of PCs at once.
* [Schema](https://github.com/domjancik/scnq-schema) - An intuitive visual programming interface and runtime.
* [TexconvGui](https://github.com/bj-rn/texconvgui) - A simple Gui for Microsoft's Texconv to batch convert images.

### Articles

* [About vvvv gamma](https://thenodeinstitute.org/about-vvvv-gamma/) - The NODE Institute
* [Resolume vs. TouchDesigner vs. vvvv](https://interactiveimmersive.io/blog/technology/resolume-vs-touchdesigner/) - The Interactive & Immersive HQ
* [The flow of creative expression: Paving the way for vvvv](https://meso.design/en/articles/the-flow-of-creative-expression-paving-the-way-for-vvvv) - MESO
* [What is VVVV + Fuse and Why It's a Powerful Combo for New Media](https://www.dataisbeautiful.club/post/what-is-vvvv-fuse-and-why-it-s-a-powerful-combo-for-new-media) - Ameen Insan
