# Bezier and Catmull Spline Curve Interpolation App

This Python application provides a graphical user interface (GUI) to draw points and visualize the interpolated curves between them using Bezier and Catmull spline curve interpolation algorithms.

## Features

- **Point Drawing:** Users can draw points on the canvas by clicking on it.
- **Curve Interpolation:** Choose between Bezier or Catmull spline algorithms to generate curves connecting the drawn points. (Choosing the algorithm is hard coded now, but will be implemented in the UI in the future.)
- **Visualization:** Display the interpolated curves in real-time as the points are modified.
- **Clear Functionality:** Clear the canvas to start fresh with new points by right-clicking.
- **Screenshot:** Save a screenshot of the canvas to the project directory by pressing the `P` key.

## Requirements

- Python 3.x
- PyOpenGL
- glfw

## Installation

1. Clone the repository: `git clone https://github.com/amireskandariii/curveinterpolation.git`
2. Navigate to the project directory.
3. Install requirements with `pip install -r requirements.txt` or `pip3 install -r requirements.txt`.

## Usage
0. Choose one of the algorithms by uncommenting the corresponding line. (line 304 or 305)
1. Run the application using Python: `python3 bezier_catmull.py`.
2. Use the UI to draw points on the canvas.
3. Clear the canvas if needed to start over.

## Examples

Screenshots of some drawing done with the application is included.

- Bezier Curve Interpolation Algorithm:

![411da878-2ae0-4a1b-bef3-65db2c74d5b8](https://github.com/amireskandariii/curveinterpolation/assets/129678832/df73f328-7ef3-4c9e-8b07-953783cb3892)

- Catmull-Rom Curve Interpolation Algorithm:

![7beddbdb-0ab1-4229-abb1-82171c12eb7a](https://github.com/amireskandariii/curveinterpolation/assets/129678832/153515ae-9646-4b98-8c2d-f1e28706c48e)


