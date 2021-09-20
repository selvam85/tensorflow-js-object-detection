# Object Detection using TensorFlow.js

This is a simple project for Object Detection using TensorFlow.js. This app uses the coco-ssd model for object detection which is part of pre-trained models in TensorFlow.js.

Learn more details about this project in this [blog post](https://github.com/tensorflow/tfjs/tree/master/tfjs-vis). 

## Project Contents

This project consists of the following three files. 

### index.html

The UI of this app. It loads the TensorFlow.js script, the coco-ssd model script and the custom JS file belonging to this app.

TensorFlow.js:
```HTML
<script src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs@2.0.0/dist/tf.min.js" type="text/javascript"></script>
```

coco-ssd model:
```HTML
<script src="https://cdn.jsdelivr.net/npm/@tensorflow-models/coco-ssd"></script>
```

This app's script file:
```HTML
<script src="script.js" defer></script>
```

This apps's stylesheet:
```HTML
<link rel="stylesheet" href="style.css">
```

### style.css

Stylesheet required for the elements on the web page.

### script.js

Javascript file that handles the returned prediction of objects identified on the image by the coco-ssd model. 
