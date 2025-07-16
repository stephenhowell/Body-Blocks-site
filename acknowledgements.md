---
layout: default
title: Acknowledgements
---

## Acknowledgements

This project would not be possible without the incredible open source communities and projects that make creative computing accessible to all.

## Core Technologies

### Scratch

Body Blocks is built on [Scratch](https://scratch.mit.edu/), the visual programming language developed by the Lifelong Kindergarten Group at the MIT Media Lab.  
Scratch is a project of the Scratch Foundation, in collaboration with the Lifelong Kindergarten Group at the MIT Media Lab. It is available for free at [https://scratch.mit.edu/](https://scratch.mit.edu/).

In particular, this project contains a fork of:

- **Scratch GUI** - Copyright (c) 2016-2024 Massachusetts Institute of Technology (MIT)
  - Licensed under AGPL-3.0
  - Repository: [https://github.com/scratchfoundation/scratch-gui](https://github.com/scratchfoundation/scratch-gui)
- **Scratch VM** - Copyright (c) 2016-2024 Massachusetts Institute of Technology (MIT)  
  - Licensed under AGPL-3.0
  - Repository: [https://github.com/scratchfoundation/scratch-vm](https://github.com/scratchfoundation/scratch-vm)

We are deeply grateful to the Scratch team for creating a programming environment that prioritizes creativity, community, and accessibility.

### MediaPipe
Pose detection in Body Blocks is powered by [MediaPipe pose landmark detection](https://ai.google.dev/edge/mediapipe/solutions/vision/pose_landmarker), part of Google's open source framework for building multimodal applied ML pipelines.

- **License**: Apache License 2.0
- **Component Used**: BlazePose for real-time pose detection
- **Website**: [https://ai.google.dev/edge/mediapipe/solutions/vision/pose_landmarker](https://ai.google.dev/edge/mediapipe/solutions/vision/pose_landmarker)

MediaPipe's efficient on-device processing makes Body Blocks possible on mid-range smartphones without requiring specialized hardware.

### easy-scratch3

Body Blocks uses a feature from [easy-scratch3-extension](https://github.com/Yokobond/easy-scratch3-extension) for loading a sample project on launch.

- **License**: BSD-3-Clause license
- **Repository**: [https://github.com/open-scratch/easy-scratch3-](https://github.com/open-scratch/easy-scratch3)

### Electron

The desktop version of Body Blocks is built with [Electron](https://www.electronjs.org/), enabling cross-platform desktop applications with web technologies.

- **License**: MIT License
- **Website**: [https://www.electronjs.org/](https://www.electronjs.org/)

## Additional Libraries

Body Blocks also uses numerous other open source libraries including:

- **Node.js** and the npm ecosystem
- **WebSocket libraries** for real-time communication
- **React** (via Scratch's implementation)
- **Blockly** (via Scratch's implementation)

## Community Contributions

### Kinect2Scratch Community

Special thanks to the original Kinect2Scratch community whose feedback, workshops, and projects shaped the evolution into Body Blocks.

## Personal Thanks

- The Lifelong Kindergarten Group at MIT Media Lab for Scratch and their philosophy of creative learning
- Prof Lizbeth Goodman, SMARTlab, University College Dublin for supporting and supervising this research
- Workshop participants, teachers, and students who have shaped this tool through their creative use
- The open source community for making tools that empower learners worldwide

---

## License Information

Body Blocks itself is released under the [AGPL-3.0](https://opensource.org/licenses/AGPL-3.0), chosen to maximize compatibility with educational use and further development.

Each component maintains its original license. Users of Body Blocks should be aware of the license requirements of all included components if creating derivative works.

## Contributing

We welcome contributions! See our [Developer Guide]({{ '/developers' | relative_url }}) for information on:

- Building Body Blocks from source
- Contributing code or translations
- Reporting issues
- Joining the development community

---

<div style="text-align: center; margin-top: 3rem;">
    <p><strong>Open source software is a gift economy.</strong></p>
    <p>We gratefully receive from and contribute back to this community.</p>
</div>