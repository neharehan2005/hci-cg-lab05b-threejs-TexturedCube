

# React Three.js Textured Cube

## Features

* Rotating 3D cube with six unique textures (one per face).
* Uses Three.js `TextureLoader` for dynamic texture application.
* Responsive rendering with camera and renderer setup.
* Implemented using React functional components and hooks (`useRef` and `useEffect`).
* Clean memory management with geometry and material disposal on component unmount.

## How It Works

* **Scene** – The main container for 3D objects.
* **Camera** – Perspective camera viewing the cube.
* **Renderer** – `WebGLRenderer` displays the scene.
* **Textures** – Each cube face uses a separate image via `TextureLoader`.
* **Animation** – Cube rotates continuously using `requestAnimationFrame`.
* **Cleanup** – Geometry and materials are disposed of to free memory.

## File Structure

```
│── index.html
│── App.jsx
│── TexturedCube.jsx
│── style.css
│── textures/
     │── right.jpg
     │── left.jpg
     │── top.jpg
     │── bottom.jpg
     │── front.jpg
     │── back.jpg
```

🚀 Live Demo

https://hci-cg-lab05b-threejs-textured-cube-eosin.vercel.app/
