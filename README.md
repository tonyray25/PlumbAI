# Plumb AI - Contract Intelligence Platform

AI-powered contract analysis for DFW subcontractors. Built with Three.js 3D visualizations and modern web technologies.

## 🚀 Project Structure

```
PlumbAI/
├── index.html              # Main website file
├── images/                 # Image assets
│   ├── favicon.png         # Site favicon (441KB)
│   └── logo.png            # Company logo (561KB)
├── models/                 # 3D GLB models for Three.js scenes
│   ├── document_ring_binder.glb      # 22MB - Document input visualization
│   ├── quantum_knot.glb              # 4.7MB - AI processing visualization
│   └── server_racking_system.glb    # 13MB - Results/storage visualization
└── README.md               # This file
```

## 🎨 3D Visualization Features

### Workflow Scene (How It Works Section)
- **Three.js r128** with GLTFLoader for 3D model rendering
- **Animated workflow pipeline**: Document → AI Processing → Results
- **Interactive elements**:
  - Document ring binder (left) - 5x scale for readability
  - Quantum knot (center) - 6x scale with rotation + pulsing animation
  - Server rack (right) - 4.5x scale
- **Particle systems**: 80 flowing particles showing data flow
- **Professional lighting**: Strategic spotlights with industrial aesthetic
- **Full viewport display**: 100vh height, edge-to-edge layout
- **Performance optimized**: Intersection Observer, visibility API

### Model Scaling
All models dynamically scaled for optimal visibility:
- Document binder: `5.0 / maxDim` - Pages should be readable
- Quantum knot: `6.0 / maxDim` - Largest centerpiece
- Server rack: `4.5 / maxDim` - Prominent display

### Animation Features
- Continuous quantum knot rotation (multi-axis)
- Pulsing scale effect (±8% at 1.5 Hz)
- Sine-wave particle interpolation
- Fade-in/fade-out particle opacity
- Smooth 60fps animations
- Pauses when off-screen or tab inactive

## 🛠️ Technologies

- **Three.js r128**: 3D graphics rendering
- **GSAP 3.12.2**: Advanced animations
- **GLTFLoader**: 3D model loading
- **Vanilla JavaScript**: No framework dependencies
- **CSS3**: Modern styling with custom properties
- **HTML5**: Semantic structure

## 📱 Responsive Design

- Desktop: Full 100vh 3D scenes edge-to-edge
- Tablet: Optimized layouts with maintained 100vh
- Mobile: Touch-friendly with performance optimizations

## 🎯 Key Sections

1. **Hero**: Landing with construction site 3D scene
2. **Problem**: Pain points visualization
3. **Our Edge**: Technology advantages with industrial models
4. **How It Works**: Full workflow 3D pipeline (main feature)
5. **Risk Vectors**: 20+ contract term analysis
6. **2025 Updates**: Texas legislative monitoring
7. **Case Study**: Real-world savings examples
8. **Pricing**: Transparent pricing tiers
9. **Trust**: DFW specialty trades focus
10. **CTA**: Free risk scan signup

## 🔧 File Organization

### Images
- Favicon and logo stored in `images/` directory
- Referenced in HTML via `images/favicon.png` and `images/logo.png`

### 3D Models
- All GLB files stored in `models/` directory
- Large files (4MB-22MB) - consider CDN for production
- Loaded asynchronously with progress tracking

## ⚡ Performance Optimization

- **Lazy loading**: 3D scenes only render when visible
- **Intersection Observer**: Automatic pause when off-screen
- **Visibility API**: Stops rendering on tab switch
- **Optimized geometry**: 8-segment spheres for particles
- **Efficient materials**: MeshBasicMaterial for particles
- **RequestAnimationFrame**: Smooth 60fps animations

## 📄 License

Proprietary - Plumb AI

## 🤝 Contact

For questions about the contract analysis platform, visit the website or use the contact form.

---

**Built with precision for DFW subcontractors** | Three.js powered visualizations | Zero-risk contract intelligence
