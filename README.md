# WebXR Course Archive and Final Space

I worked through ten WebXR chapters, from drawing with WebGL to interacting with animated models in A-Frame. I brought those techniques together in my Final Space capstone.

## Chapters and demos

1. [Chapter 1 — Getting started](./chapters/01-getting-started/)
2. [Chapter 2 — WebGL foundations](./chapters/02-webgl-foundations/)
3. [Chapter 3 — WebGL third dimension](./chapters/03-webgl-third-dimension/)
4. [Chapter 4 — matrices and perspective](./chapters/04-webgl-matrices-perspective/)
5. [Chapter 5 — Three.js](./chapters/05-threejs/)
6. [Chapter 6 — WebXR VR](./chapters/06-webxr-vr/)
7. [Chapter 7 — WebXR AR and hit testing](./chapters/07-webxr-ar/)
8. [Chapter 8 — A-Frame ECS](./chapters/08-aframe/)
9. [Chapter 9 — A-Frame physics and interaction](./chapters/09-aframe-physics/)
10. [Chapter 10 — animated glTF and AR deployment](./chapters/10-aframe-gltf-ar/)

## Capstone

[WebXR Final Space](./capstone/webxr-final-space/)

The capstone combines custom GLSL, transforms, Three.js access, WebXR, A-Frame
components, physics, controller interaction, glTF, and animation.

## Research and licensing

- [APA research article](./RESEARCH_ARTICLE.md)
- [Third-party notices](./THIRD_PARTY_NOTICES.md)
- [MIT License](./LICENSE)

The MIT license applies to my original project files. External
libraries, documentation, and the demonstration model retain their own terms.

## Local preview

From the repository root I start a local server.

```bash
python3 -m http.server 8081
```

I open `http://localhost:8081/capstone/webxr-final-space/` for the capstone or follow a chapter directory for its examples.
