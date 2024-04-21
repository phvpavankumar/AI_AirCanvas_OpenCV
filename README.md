# Air Canvas: Drawing in the Air with AI

Welcome to Air Canvas with AI, a computer vision project implemented using OpenCV with AI techniques leveraging the Mediapipe library.

Have you ever imagined drawing with just the motion of your hand in the air? In this project, we'll explore how to create an Air Canvas that allows you to draw anything by simply waving your hand and detecting landmarks on your knuckles. This project is not only a fun exploration but also a fantastic addition to any machine learning enthusiast's resume.

We'll be utilizing computer vision techniques from OpenCV to bring this project to life. While Python is our preferred language due to its extensive libraries and easy-to-use syntax, understanding the basics allows for implementation in any OpenCV-supported language.

## Project Overview

### Algorithm

1. **Frame Capture**: Start by capturing frames and converting them to the HSV color space (ideal for color detection).
2. **Canvas Setup**: Prepare the canvas frame and add the respective ink buttons for drawing.
3. **Hand Detection**: Adjust the parameters of the Mediapipe initialization to detect only one hand.
4. **Landmark Detection**: Use hand landmark detection and tracking to identify landmarks on the hand.
5. **Drawing**: Find the coordinates of the forefinger and store them in an array for successive frames (to draw points on the canvas).
6. **Drawing Process**: Draw the points stored in the array on the frames and canvas.

## YouTube Video

For a comprehensive explanation and demonstration of the project, check out our YouTube video:
[Watch on YouTube](https://youtu.be/i9Wm_PAenow)

## Requirements

Make sure you have the following dependencies installed on your system:
- Python 3
- NumPy
- OpenCV
- Mediapipe

## Results

![Air Canvas Results](https://github.com/phvpavankumar/AI_AirCanvas_OpenCV/blob/main/Results.png)

Feel free to explore the code and experiment with your own creative gestures! If you have any questions or suggestions for improvement, don't hesitate to reach out. Don't forget to subscribe and like for more updates!

Enjoy drawing in the air with AI-powered creativity!