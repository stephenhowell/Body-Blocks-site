---
layout: default
title: Developers
---

# Developer Guide

Welcome to the Body Blocks developer documentation. Whether you want to contribute code, report issues, or build your own version, you'll find the information you need here.

<div class="info">
<strong>🚧 Note:</strong> Body Blocks is in active development. APIs and build processes may change. This page will be updated as the project stabilizes.
</div>

<!-- 

## Source Code

Body Blocks consists of several repositories:

### Main Application
- **Repository**: [github.com/stephenhowell/bodyblocks](https://github.com/stephenhowell/bodyblocks)
- **Language**: JavaScript/TypeScript
- **Framework**: Electron + Scratch 3.0 fork

### Mobile Apps
- **Android**: Java/Kotlin with MediaPipe
- **iOS**: *Coming soon*

## Building from Source

### Prerequisites
- Node.js 16+ and npm
- Git
- Platform-specific tools:
  - **Windows**: Visual Studio Build Tools
  - **macOS**: Xcode Command Line Tools
  - **Linux**: build-essential

### Build Instructions

```bash
# Clone the repository
git clone https://github.com/stephenhowell/bodyblocks.git
cd bodyblocks

# Install dependencies
npm install

# Run in development mode
npm run dev

# Build for production
npm run build

# Package for distribution
npm run dist
```

<div class="warning">
<strong>Note:</strong> Full build instructions for each platform coming soon. For now, refer to the README in each repository.
</div>

## Architecture Overview

Body Blocks uses a client-server architecture:

1. **Desktop Application** (Electron)
   - Hosts modified Scratch 3.0 environment
   - Runs WebSocket server on port 8183
   - Manages Body Blocks extension

2. **Mobile Application**
   - Captures camera feed
   - Runs MediaPipe pose detection
   - Sends pose data via WebSocket

3. **Communication Protocol**
   - JSON messages over WebSocket
   - 30 FPS pose updates
   - Automatic reconnection

## Contributing

### Current Status
<div class="warning">
<strong>⚠️ Limited Contributions:</strong> While we appreciate interest in contributing, Body Blocks is currently part of active PhD research. Pull requests are reviewed on a case-by-case basis to maintain research integrity.
</div>

### How to Contribute

1. **Report Issues**
   - Use GitHub Issues for bug reports
   - Include OS, version, and steps to reproduce
   - Check existing issues first

2. **Suggest Features**
   - Open a discussion in GitHub Discussions
   - Explain the educational use case
   - Consider accessibility implications

3. **Code Contributions**
   - Small bug fixes are welcome
   - Major features should be discussed first
   - Follow existing code style
   - Include tests where applicable

### Code Style
- JavaScript: StandardJS
- 2 spaces for indentation
- Meaningful variable names
- Comments for complex logic

## Localization

Body Blocks supports multiple languages through Scratch's localization system.

### Adding a New Language
1. Copy `en.json` language file
2. Translate all strings
3. Submit as a pull request
4. Test with native speakers

### Current Languages
- English (en)
- *More coming soon*

## API Documentation

### WebSocket Messages

#### Pose Update
```json
{
  "type": "pose",
  "timestamp": 1234567890,
  "landmarks": [
    {"x": 0.5, "y": 0.5, "z": 0.0, "visibility": 0.99},
    // ... 33 landmarks total
  ]
}
```

#### Connection Status
```json
{
  "type": "status",
  "connected": true,
  "version": "1.0.0"
}
```

<div class="info">
<strong>Note:</strong> Full API documentation coming soon.
</div>

## Testing

### Running Tests
```bash
npm test           # Run all tests
npm run test:unit  # Unit tests only
npm run test:e2e   # End-to-end tests
```

### Testing Guidelines
- Test on multiple devices
- Include accessibility testing
- Verify offline functionality
- Check performance on low-end devices

## Release Process

Releases are managed through GitHub Releases:

1. Version bump in package.json
2. Update CHANGELOG.md
3. Create git tag
4. Build all platforms
5. Create GitHub Release
6. Upload built artifacts 

-->

## Support

### Developer Support
- Email: [stephenhowell@outlook.ie](mailto:stephenhowell@outlook.ie) for research collaborations

<!-- 
### Known Issues
- See GitHub Issues for current bugs
- Check wiki for workarounds -->

---

<div style="text-align: center; margin-top: 3rem;">
    <p><strong>Building tools that empower learners to move and create.</strong></p>
</div>