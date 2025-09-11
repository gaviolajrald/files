<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Hello World</title>
  <style>
    body {
      background-color: gold;
      margin: 20px; /* Adds margin around the body */
      padding: 20px; /* Adds padding inside the body */
      font-family: Arial, sans-serif;
      perspective: 1000px; /* Creates a 3D perspective for child elements */
    }

    h1 {
      text-align: center;
      margin-bottom: 30px;
      padding: 10px;
      font-size: 2em;
      transform: rotate(-5deg); /* 2D transformation: rotating the heading */
    }

    p {
      text-align: center;
      font-size: 1.2em;
      margin-bottom: 30px;
      padding: 10px;
    }

    a {
      display: block;
      text-align: center;
      font-size: 1.5em;
      margin-bottom: 20px;
      text-decoration: none;
      color: blue;
      padding: 10px;
      transition: color 0.3s ease;
    }

    a:hover {
      color: darkblue; /* Change link color on hover */
    }

    img {
      display: block;
      margin: 0 auto 30px; /* Center the image and add bottom margin */
      padding: 10px;
      max-width: 20%;
      height: auto;
      transform: scale(1.1); /* 2D transformation: scale image */
    }

    /* 3D effect on video */
    video {
      display: block;
      margin: 0 auto 30px; /* Center the video and add bottom margin */
      padding: 10px;
      transform: rotateY(10deg) rotateX(5deg) scale(1.05); /* 3D transformations */
      transition: transform 1s; /* Smooth transition */
    }

    /* Hover effect for video */
    video:hover {
      transform: rotateY(15deg) rotateX(10deg) scale(1.1); /* Increased 3D effect on hover */
    }
  </style>
</head>
<body>
  <h1>Hello</h1>
  <p>Welcome to my Page.</p>

  <a href="https://www.google.com" target="_blank">Visit Chrome!</a>

  <img src="C:\Users\jerald.gaviola\Downloads\Gaviola1\Mountain.jpg" height="500" alt="Mountain Image"/>

  <video width="640" height="360" controls>
    <source src="C:\Users\jerald.gaviola\Downloads\Gaviola1\FLOWERVID.mp4" type="video/mp4">
    <source src="C:\Users\jerald.gaviola\Downloads\Gaviola1\FLOWERVID.mp4" type="video/webm">
    Your browser does not support the video tag.
  </video>
</body>
</html>
