# Entry 5
##### 4/11/25

### Content

Ever since we chose a tool to add in our freedom project, we've been spending the time learning about our tool. We put the stuff we learned or did in a [file](tool/learning-log.md). In this file I didn't just learn but I also tried doing stuff. For example, when I learned about a-frame animation using tutorials on youtube and the a-frame webpage, I made an atom and tried to get it to spin using animation. 
Here's the code to see the atom spin:
``` HTML
<html>
  <head>
    <script src="https://aframe.io/releases/1.7.0/aframe.min.js"></script>
  </head>
  <body>
    <a-scene>
      <a-sky color="black"></a-sky>
      <a-entity rotation="1 1 1" animation="property: rotation; to: 30 30 360; loop: true; dur: 3000">
        <a-torus position="0 1 -10" color="white" radius="3" width=".001" radius-tubular=".05"></a-torus>
        <a-torus position="0 1 -10" color="white" radius="3" width=".001" radius-tubular=".05" rotation="90%"></a-torus>
        <a-torus position="0 1 -10" color="white" radius="3" width=".001" radius-tubular=".05" rotation="45%"></a-torus>
        <a-torus position="0 1 -10" color="white" radius="3" width=".001" radius-tubular=".05" rotation="135%"></a-torus>
        <a-sphere color="blue" radius=".4" position="-.5 1 -10"></a-sphere>
        <a-sphere color="blue" radius=".4" position="0 1 -10"></a-sphere>
        <a-sphere color="red" radius=".4" position="-.25 1.3 -10"></a-sphere>
        <a-sphere color="blue" radius=".4" position="-.5 .7 -10.3"></a-sphere>
        <a-sphere color="blue" radius=".4" position="0 .4 -10.3"></a-sphere>
        <a-sphere color="red" radius=".4" position=".4 .7 -10"></a-sphere>
        <a-sphere color="blue" radius=".4" position=".4 1.2 -10"></a-sphere>
        <a-sphere color="red" radius=".4" position=".3 .9 -9.7"></a-sphere>
        <a-sphere color="blue" radius=".4" position=".1 1.1 -9.7" ></a-sphere>
        <a-sphere color="red" radius=".4" position=".1 1.3 -9.9"></a-sphere>
        <a-sphere color="red" radius=".4" position="0 .7 -10.3"></a-sphere>
        <a-sphere color="blue" radius=".4" position="0 1 -10.3"></a-sphere>
        <a-sphere color="red" radius=".4" position="-.3 .4 -10"></a-sphere>
        <a-sphere color="red" radius=".4" position="-.3 .7 -9.7"></a-sphere>
        <a-sphere color="red" radius=".4" position="-.25 1.3 -10"></a-sphere>
        <a-sphere color="yellow" radius=".3" position="1 1 -7.3"></a-sphere>
        <a-sphere color="yellow" radius=".3" position="0 3.1 -7.9"></a-sphere>
        <a-sphere color="yellow" radius=".3" position="-1 -1 -8.1"></a-sphere>
        <a-sphere color="yellow" radius=".3" position="0 4 -10"></a-sphere>
        <a-sphere color="yellow" radius=".3" position="-1 3 -12"></a-sphere>
        <a-sphere color="yellow" radius=".3" position="1 -1 -12"></a-sphere>
        <a-sphere color="yellow" radius=".3" position="-2.3 1 -12"></a-sphere>
        <a-sphere color="yellow" radius=".3" position="-1.55 -1.5 -10"></a-sphere>
      </a-entity>
    </a-scene>
  </body>
</html>
```


[Previous](entry04.md) | [Next](entry06.md)

[Home](../README.md)
