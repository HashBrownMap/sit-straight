# Pose Detection in the Browser: PoseNet Model

This package contains a standalone model called PoseNet, as well as some demos, for running real-time pose estimation in the browser using TensorFlow.js.

[Try the demo here!](http://slouchwatcher.com)

PoseNet can be used to estimate either a single pose or multiple poses, meaning there is a version of the algorithm that can detect only one person in an image/video and one version that can detect multiple persons in an image/video.

## Installation

You can use this as standalone es5 bundle like this:

```html
  <script src="https://unpkg.com/@tensorflow/tfjs"></script>
  <script src="https://unpkg.com/@tensorflow-models/posenet"></script>
```

Or you can install it via npm for use in a TypeScript / ES6 project.

```sh
npm install @tensorflow-models/posenet
```

Details for how to run the app are included in the `demos/` folder.

