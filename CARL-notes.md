# CARL Notes for daedalOS

## Project Overview
daedalOS is a desktop environment implemented in the browser, providing a wide range of functionality typically found in traditional operating systems. It includes features like:
- File system with drag & drop support
- Resizable and draggable windows
- Start menu with spotlight search
- Taskbar with window previews
- Various applications (Browser, Terminal, Text Editor, etc.)
- Games and multimedia support

## Technology Stack
- **Framework**: Next.js (React-based)
- **Key Libraries**:
  - React, ReactDOM
  - styled-components for styling
  - react-rnd for resizable/draggable windows
  - motion for animations
- **File System**: BrowserFS
- **Terminal**: xterm.js with various command implementations
- **Editor**: Monaco Editor

## Key Features
### System Components
- File Explorer with various views and context menus
- Resizable/draggable windows with minimize, maximize, close functionality
- Start menu with expandable sidebar and spotlight search
- Taskbar with window previews and AI chat agent

### Applications
- Browser app with CORS support, bookmark bar, and favicon support
- Terminal with file system access, command history, and various utilities
- Code editors (Monaco Editor and Vim.js)
- Media players (Webamp, Video Player)
- Emulators for various game systems
- Productivity tools like Paint, PDF viewer, etc.

### Games
- Classic games like DX-Ball and Space Cadet Pinball
- Minecraft Classic client (ClassiCube)
- Quake III Arena port

## Development and Build
- Uses Yarn as package manager
- Standard build process with prebuild scripts
- Docker support for containerized deployment

## Notes for Future Development
- Explore integration with more modern web technologies
- Improve performance and optimize resource usage
- Enhance accessibility features
- Expand application ecosystem

## References
- [README.md](README.md) for detailed feature overview
- [package.json](package.json) for dependencies and scripts

This file will be updated with additional notes as development progresses.