# webgl-3d-scene
A basic WebGL illustration of a 3d scene providing users camera control capabilities.

# Requirements to run
- Browsers by default do not allow retrieval of images from the local system, resulting in the scene not loading properly.
  One solution is to place the images on a secure web-server, by modifying their URLs in the code appropriately.
  **Alternatively**, one can disable the relevant check for secure locations in the preferences of the browser,
  **with all due caution** for any potential problems that may arise from doing so.
- The source code needs to be in the same path location as the asset and library files.
  Open the .html file with your browser to gain access to the 3d scene.

# Features
- Start the animation to rotate around the main objects of the scene, which is a table and a chair
- Stop the animation
- Alter the angle of the perspective view
- Alter the distance of the camera from the center of the scene
- Alter the step of the camera rotation, the speed it rotates
- Alter the step of the camera height, the speed it elevates
