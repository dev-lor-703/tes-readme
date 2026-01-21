<p align="center">
  <img src="https://electronjs.org/images/electron-logo.svg" width="110" alt="Electron Logo" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" width="120" alt="React Logo" />
  &nbsp;&nbsp;&nbsp;
  <img src="https://vitejs.dev/logo.svg" width="110" alt="Vite Logo" />
</p>

<p align="center">
  Frontend application for <b>Rookwork</b>, built with 
  <b>React + Vite + Tailwind CSS</b> for Web
  and <b>Electron</b> for Desktop.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-19-blue.svg" alt="React" />
  <img src="https://img.shields.io/badge/Vite-7-purple.svg" alt="Vite" />
  <img src="https://img.shields.io/badge/TailwindCSS-v4-38bdf8.svg" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Electron-28-47848F.svg" alt="Electron" />
  <img src="https://img.shields.io/badge/License-ISC-green.svg" alt="License" />
</p>

## Decription

Supported Operating Systems: [Windown 10+](https://learn.microsoft.com/windows), [MacOS](https://www.apple.com/macos/), [Linux (Ubuntu / Debian / Arch / …)](https://www.kernel.org/)
Electron will automatically build binaries suitable for each operating system.

<b>Prerequisites</b>
- [Node.js (LTS ≥ 18)](https://nodejs.org/en/download/)
- [Yarn (Classic v1](https://classic.yarnpkg.com/en/docs/install))
- [Git](https://git-scm.com/downloads)

## Getting Started

Clone repository
```bash
git clone https://github.com/warmdrobe/rookwork-frontend.git
cd rookwork-frontend
```

The project uses Yarn Workspaces; dependencies only need to be installed once at the root directory.
```bash
yarn install
```

## Usage

Running Browser (Web) and Electron (Desktop) concurrently - <b>recommended<b/>
```bash
yarn dev
```
- Web: http://localhost:5173
- Electron: opens the desktop app window automatically

only Browser (Web) or Electron (Desktop) only
```bash
#start browser
yarn start:browser

#start electron
yarn start:electron
```

## Build 

<b>Build browser (Web)<b/>
```bash
yarn build:browser
```
Output:
```bash
browser-app/dist
```

<b>Build electron (Desktop)<b/>
```bash
yarn build:electron
```

<b>Build all<b/>
```bash
yarn build
```

## Note

- Electron (dev mode) loads from http://localhost:5173
- Electron (production mode) loads from `browser-app/dist/index.html`
- Tailwind CSS is preconfigured
