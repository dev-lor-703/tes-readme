<p align="center">
  <img src="https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=white" />
  <img src="https://img.shields.io/badge/Vite-7-646CFF?logo=vite&logoColor=white" />
  <img src="https://img.shields.io/badge/TailwindCSS-v4-38BDF8?logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Electron-28-47848F?logo=electron&logoColor=white" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-%E2%89%A518-339933?logo=node.js&logoColor=white" />
  <img src="https://img.shields.io/badge/Yarn-Classic-2C8EBB?logo=yarn&logoColor=white" />
  <img src="https://img.shields.io/badge/Monorepo-Yarn%20Workspaces-6DA544" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Desktop-black" />
  <img src="https://img.shields.io/badge/OS-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey" />
  <img src="https://img.shields.io/badge/License-ISC-green" />
</p>

<p align="center">
  <a href="https://github.com/warmdrobe/rookwork-frontend">
    <img src="https://img.shields.io/badge/GitHub-rookwork--frontend-181717?logo=github" />
  </a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg" width="36" alt="Node.js" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" width="36" alt="TypeScript" />
  &nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/yarn/yarn-original.svg" width="36" alt="Yarn" />
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

Running Browser (Web) and Electron (Desktop) concurrently - **recommended**
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

**Build browser (Web)**
```bash
yarn build:browser
```
Output:
```bash
browser-app/dist
```

**Build electron (Desktop)**
```bash
yarn build:electron
```

**Build all**
```bash
yarn build
```

## Note

- Electron (dev mode) loads from http://localhost:5173
- Electron (production mode) loads from `browser-app/dist/index.html`
- Tailwind CSS is preconfigured
