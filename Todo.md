# 🚀 VULF R&D Master Roadmap

## 🎯 Strategic Objective

Build 3 high-fidelity, commercial-grade XR/WebGPU demo scenes to serve as the foundation for client acquisition and project execution.

---

## 📋 Project Portfolio

### 1. [ArchViz Web Configurator](app://obsidian.md/ArchViz%20Web%20Configurator)

- **Core Tech**: WebGPU / Three.js / React
- **Objective**: Browser-based interactive configurator using 360° imagery and video overlays.
- **Key Deliverables**:
    - [ ] Asset pipeline for 360° equirectangular images.
    - [ ] UI/UX for real-time material/lighting toggles.
    - [ ] Mobile-responsive deployment.

### 2. [Gaussian Splat ArchViz Viewer](app://obsidian.md/Gaussian%20Splat%20ArchViz%20Viewer)

- **Core Tech**: WebGPU / Luma.ai or similar / Hybrid 3D Engine
- **Objective**: Photorealistic architectural visualization using hybrid Gaussian Splatting and low-poly 3D geometry.
- **Key Deliverables**:
    - [ ] Splat data optimization for web performance.
    - [ ] Hybrid rendering pipeline (Splats + 3D meshes).
    - [ ] Lighting/Shadow integration.

### 3. [Quest VR ArchViz Configurator](app://obsidian.md/Quest%20VR%20ArchViz%20Configurator)

- **Core Tech**: Unity / OpenXR / Meta Quest SDK
- **Objective**: Immersive, high-fidelity VR experience for architectural walkthroughs and configuration.
- **Key Deliverables**:
    - [ ] Performance optimization for Quest 3 (Target: 72/90 FPS).
    - [ ] Interaction system (Teleportation, Object manipulation).
    - [ ] Build pipeline for standalone deployment.

---

## ⚙️ Execution Framework (The "Fast-Track" Sprint)

|Phase|Focus|Action Items|
|:--|:--|:--|
|**1. Asset Prep**|Data Collection|Gather 360s, Splat data, and 3D models.|
|**2. MVP Build**|Core Functionality|Get the "Hello World" of each demo working.|
|**3. Optimization**|Performance|WebGPU/Quest frame-rate tuning.|
|**4. Deployment**|Delivery|Host on Vercel/Netlify or package for Quest.|

---

## 📅 Weekly Sprint Tracker

|Project|Current Status|Blocker|Next Action|
|:--|:--|:--|:--|
|**Web Configurator**|Planning|None|Asset collection|
|**GSplat Viewer**|Planning|None|Hybrid integration test|
|**Quest VR**|Planning|None|Environment setup|

---

## 📝 Development Principles

1. **Performance First**: If it doesn't run at 60fps, it isn't a demo.
2. **Modular Code**: Build components that can be reused across all three projects.
3. **Document Everything**: Every technical hurdle solved becomes an SOP in the `30_Operations` folder.