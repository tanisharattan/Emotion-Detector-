Facial Emotion Detector
Web app that detects your face emotions using AI and matches them with emojis.
Built using ReactJS and face-API.js
Face-API.js is a JavaScript API for face detection and face recognition in the browser implemented on top of the tensorflow.js core API.
Version 2.0
URL / Live demo
louiejancevski.github.io/FacialEmotionDetector
About this project
The main objective was very simple, to display emojis based on the facial expressions that we make in front of our camera.

Once the app detects your face, it will do two things:

Change the background color.
Replace the default emoji with the one that it thinks is the best match to your expression.
Face-API.js was used to faciliate this process. You can read more about it here.

Note: You are not being recorded at any point, it all happens in your own browser!

Taking a look inside
I'm going to take Dwayne Johnson, The Rock, as an example to showcase the site.

Very straightforward.

Whenever he smiles, the emoji turns into a lauging emoji, and the background color changes to green.
