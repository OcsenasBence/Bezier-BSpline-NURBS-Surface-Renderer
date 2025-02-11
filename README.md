---

# Bezier-BSpline-NURBS-Surface-Renderer

This project was developed during my university studies in the "Computer Graphics" course. It provides an implementation of surface rendering techniques using Bézier, B-Spline, and NURBS (Non-Uniform Rational B-Splines) surfaces.

## Project Overview

The project focuses on rendering complex surfaces by utilizing Bézier, B-Spline, and NURBS representations. These mathematical models are fundamental in computer graphics for creating smooth and flexible curves and surfaces.

## Repository Contents

- `main.py`: The main script that initializes the rendering process and handles user interactions.
- `bezier.py`: Contains functions and classes related to Bézier surface calculations and rendering.
- `bspline.py`: Includes implementations for B-Spline surface computations.
- `nurbs.py`: Provides functionalities for NURBS surface rendering.
- `utils.py`: Utility functions supporting the main rendering processes.
- `README.md`: Project description and overview.

## Getting Started

To run the project, ensure you have Python installed along with the necessary libraries. Follow these steps:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/OcsenasBence/Bezier-BSpline-NURBS-Surface-Renderer.git
   cd Bezier-BSpline-NURBS-Surface-Renderer
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Application**:
   ```bash
   python main.py
   ```
   This will launch the rendering application, allowing you to interact with and visualize the surfaces.

## Understanding Bézier, B-Spline, and NURBS Surfaces

- **Bézier Surfaces**: Defined by a set of control points, Bézier surfaces are widely used in computer graphics for modeling smooth curves and surfaces.

- **B-Spline Surfaces**: An extension of Bézier surfaces, B-Splines offer greater flexibility and control, allowing for complex surface modeling.

- **NURBS Surfaces**: Generalizing both Bézier and B-Spline surfaces, NURBS introduce weights to control points, enabling the representation of both standard geometric shapes and free-form surfaces.

For a comprehensive understanding of these concepts, you can refer to the Wikipedia article on [Non-uniform rational B-spline](https://en.wikipedia.org/wiki/Non-uniform_rational_B-spline).

## Acknowledgments

This project was inspired by the "Computer Graphics" course and aims to provide practical experience in rendering complex surfaces using advanced mathematical models.

---
