# wedar-demo

<!DOCTYPE html>
<html>
    <head>
    <title>Web AR Example</title>
    <script src="https://aframe.io/releases/1.7.0/aframe.min.js"></script>
    <script src="https://afram.io/releases/1.2.0/jsdelivr.net/gh/AR-js-org/AR.js/aframe/build/aframe-ar.js"></script>
    </head>
    <body>
        <a-scene>
          <a-box position="-1 1 -3" rotation="0 45 0" color="#c3d94b"></a-box>
          <a-sphere position="0 1.25 -5" radius="1.25" color="#4bd9a8"></a-sphere>
          <a-cylinder position="1 0.75 -3" radius="1.5" height="0.5" color="#d9a84b"></a-cylinder>
          <a-plane position="0 0 -4" rotation="-90 0 0" width="4" height="4" color="#4BC3D9"></a-plane>
          <a-sky color="#d9614b"></a-sky>
        </a-scene>
      </body>
</html>
