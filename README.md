# G. L. Narasimha Reddy — Immersive 3D Developer Portfolio

> **Obsidian Terminal Design System** · Interactive Three.js Cyber-Physical Sculpture · In-Page & Pull-Up POSIX Terminal · 3D Parallax Tilt

A cutting-edge, high-contrast, aerospace & HUD-inspired developer portfolio designed for **G. L. Narasimha Reddy** (Systems Architect & ML Engineer). Built from the Google Stitch design specification, adhering strictly to the **Obsidian Terminal** design token hierarchy.

---

## ⚡ Live Highlights & Features

- **3D Cyber-Physical Centerpiece (Three.js WebGL):**
  - Truncated dark octahedron core with wireframe opacity layering.
  - Outer golden/amber wireframe icosahedron shell (`#f59e0b`).
  - Luminous high-specularity dodecahedron crystal core.
  - 3 Multi-axis orbital gyro rings (`#94de2d`, `#f59e0b`, `#38bdf8`) with counter-rotating angular momentum.
  - 380-node spherical particle constellation reacting in real time to cursor parallax.
- **Dual Interactive Linux Terminals (CachyOS-Zen Emulation):**
  - **In-Page Workstation Terminal:** Run commands directly on the page with real-time feedback, terminal output stream, and command history (`↑` / `↓` arrow keys).
  - **Pull-Up Drawer Console:** Toggleable anywhere using the global hotkey **`~`** or **`` ` ``** or the **`⚡ Terminal ~`** button in the header bar.
  - **Available Commands:** `help`, `fastfetch`, `projects`, `sentinel-x`, `chaotic`, `myshell`, `library`, `skills`, `chess`, `about`, `contact`, `whoami`, `uname`, `ls`, `matrix`, `clear`.
- **Tactile 3D Tilt Dynamics (`card-3d-interactive`):**
  - Real-time perspective rotation on mouse hover across all cards, skills, and milestones.
- **Production Showcase:**
  1. **Sentinel-X:** Winner of the **Yukthi National Hackathon** — raw socket AF_PACKET packet sniffer and real-time ARP spoofing / MITM defense engine.
  2. **PROJECT-CHAOTIC:** AI workflow priority tree orchestrator with OpenAI completions and Vim-inspired modal interaction.
  3. **Library Management System:** Modern C++ OOP inventory system with atomic binary fstream disk persistence.
  4. **myshell.cpp:** UNIX POSIX shell written from scratch implementing `fork()`, `execvp()`, multi-stage pipes (`cmd1 | cmd2 | cmd3`), and background zombie process reaping.
- **Live System Telemetry HUD:**
  - Pinned bottom-right HUD displaying live simulated network ping jitter (14ms–19ms), active Linux kernel, Hyprland Wayland compositor, and real-time IST clock.
- **Responsive Architecture & ScrollSpy:**
  - Asymmetric 12-column modular grid with mobile navigation drawer, fluid typography, and active section tracking.

---

## 🛠️ Tech Stack & Typography

- **Framework:** Vanilla HTML5 / ESNext JavaScript (zero runtime bloat)
- **3D Rendering:** Three.js WebGL
- **Styling:** Tailwind CSS with custom Obsidian Terminal color tokens
- **Typography:**
  - **Display & Headlines:** `Syne` (700, 600)
  - **Editorial Body:** `Plus Jakarta Sans` (400, 500, 600)
  - **Telemetry, HUD & Code:** `JetBrains Mono` (400, 500, 600)
- **Icons:** Google Material Symbols Outlined

---

## 🚀 Getting Started

### Option 1: Using Vite Dev Server (Recommended)

```bash
# Install dependencies
npm install

# Start development server
npm run dev
```
Open [http://localhost:3000](http://localhost:3000) in your browser.

### Option 2: Production Build & Preview

```bash
# Build production bundle into dist/
npm run build

# Preview production build locally
npm run preview
```

### Option 3: Direct Browser Viewing

You can open `index.html` directly in any web browser without needing any build tools or web servers:

```bash
chromium index.html
# or
firefox index.html
```

---

## 📁 Directory Structure

```text
stitch-immersive-3d-developer-portfolio/
├── assets/
│   ├── logo.svg              # Geometric hexagonal NR Monogram logo
│   ├── portrait.jpg          # Studio portrait cutout asset
│   └── three.min.js          # Standalone Three.js library
├── public/
│   ├── assets/               # Public assets bundled by Vite
│   ├── logo.svg
│   └── portrait.jpg
├── dist/                     # Optimized production build
├── DESIGN.md                 # Obsidian Terminal design system tokens
├── index.html                # Main application entry point
├── package.json              # Project scripts & devDependencies
├── vite.config.js            # Vite configuration
└── README.md                 # Documentation
```

---

## 👤 Author

**Ganapam Lakshmi Narasimha Reddy (G. L. Narasimha Reddy)**
- **Role:** Systems Architect & ML Engineer
- **Institution:** Mohan Babu University · Class of 2029
- **GitHub:** [@0xnarasimha](https://github.com/0xnarasimha)
- **Email:** [simhareddy20071206@gmail.com](mailto:simhareddy20071206@gmail.com)
- **Location:** Tirupati, India
