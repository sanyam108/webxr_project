# WebXR project

Running instructions:

1. Download [three.js srouce code](https://github.com/mrdoob/three.js/releases/tag/r120) and place it under `three.js` subdirectory. 
OR if you don't want to download the full source code:
    
    * Download [GLTFLoader.js](https://github.com/mrdoob/three.js/blob/r120/examples/jsm/loaders/GLTFLoader.js) and place it under `three.js/examples/jsm/loaders/`
    * Download [three.module.js](https://github.com/mrdoob/three.js/blob/r120/build/three.module.js) and place it under `three.js/build/`


2. Install `npm`

3. Initialize project `npm init -y && npm install node-static`

4. Start the server `npm start`

5. Make sure your smartphone is connected to the same network as your PC, open Chrome and navigate to [https://your_local_ip:2000/webxr-threejs.html](https://your_local_ip:2000/webxr-threejs.html)
