# Bootcamp (Roland Copy)
If you are new to coding, this will guide you through setup of a modern development environment on your computer.
Beware there are dozens of languages and frameworks to choose from. We are suggesting *nuxt* for your first hackathon, because it is particularly easy to set up and get started. 

---

## Prerequisites

* Git (version control system)
* Node.js (platform) and npm (package manager)
* Visual Studio Code (Code Editor)

### Windows (11 and newer 10):
```winget install -e --id Microsoft.VisualStudioCode```

```winget install -e --id OpenJS.NodeJS```

```winget install -e --id Git.Git```

Older Windows: Install chocolatey and `choco install vscode git nodejs`

### Mac
1. Install brew (https://brew.sh/)
2. `brew install git node`
3. Install vs code from website (https://code.visualstudio.com/)

### Check prerequisites
(in terminal, command line / terminal->new terminal in vscode)

```node --version```

```npm --version```

```git --version```

All these 3 commands should return a version number.

---

## Getting Started
1. Log in to github (create an account if necessary)
2. fork this repository.

### Make sure to install the dependencies:

```bash
# npm
npm install
```

### Development Server

Start the development server on http://localhost:3000

```bash
npm run dev
```

Checkout the [deployment documentation](https://v3.nuxtjs.org/guide/deploy/presets) for more information.

---

