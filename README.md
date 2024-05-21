<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Telecom Tower Detection using YOLOv8</title>
    <style>
        body {
            font-size: 18px;
        }
    </style>
</head>
<body>

<h1>Telecom Tower Detection using YOLOv8</h1>

<h2>Table of Contents</h2>
<ul>
    <li><a href="#installation">Installation</a></li>
    <li><a href="#setup">Setup</a></li>
    <li><a href="#training-the-model">Training the Model</a></li>
    <li><a href="#making-predictions">Making Predictions</a></li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#license">License</a></li>
</ul>

<h2 id="installation">Installation</h2>
<ol>
    <li>Install the required libraries: ultralytics, torch, and opencv-python.</li>
    <li>Import the necessary modules and clear previous outputs.</li>
    <li>Mount your Google Drive to access the data.</li>
</ol>

<h2 id="setup">Setup</h2>
<ol>
    <li>Import the YOLO class from the ultralytics package.</li>
    <li>(Optional) Verify that YOLO is correctly installed.</li>
</ol>

<h2 id="training-the-model">Training the Model</h2>
<p>Train the YOLO model with your dataset. Specify the task as object detection, set the mode to train, define the number of epochs, provide the path to the dataset configuration file, and specify the YOLOv8 model to use.</p>

<h2 id="making-predictions">Making Predictions</h2>
<p>Predict using the trained model on a video file. Specify the task as object detection, set the mode to predict, provide the path to the trained model weights, and define the source video file. Optionally, display the prediction results and specify the name of the model.</p>

<h2 id="authors">Authors</h2>
<p>This project was created by Matangee Sparshananda. For any questions or issues, please contact matangee.ai@gmail.com.</p>

</body>
</html>
