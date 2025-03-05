# DCS - Affine Transformations Playground

An interactive web application demonstrating 2D affine transformations and projections in computer graphics, developed for the Data and Computer Science (DCS) course.

## Features

### Problem 1: Basic Affine Transformations
- **Translation**: Move shapes along X and Y axes
- **Rotation**: Rotate shapes around the origin
- **Scaling**: Scale shapes independently on X and Y axes
- **Reflection**: Reflect shapes across the X-axis

### Problem 2: Composite Transformations
- **Translation + Rotation**: Apply translation followed by rotation
- **Rotation + Translation**: Apply rotation followed by translation
- **Custom Line Reflection**: Reflect shapes across any line defined by y = mx + b

### Problem 3: Projections
- **Parallel Projection**: Project points along a specified direction vector
- **Central Projection**: Apply perspective projection with adjustable focal length

### Problem 4: Affine Properties Analysis
- Test whether transformations preserve affine combinations
- Numerical verification of midpoint preservation
- Analysis of which projection types maintain affine relationships

## Usage
1. Use the left canvas to manipulate the original shape (drag points to modify)
2. Select a transformation from the collapsible sections
3. Enter parameters for the chosen transformation
4. Click the corresponding button to apply the transformation
5. View the transformed shape in the right canvas

## Mathematical Foundations
The application implements the following mathematical concepts:
- Affine transformation matrices
- Homogeneous coordinates
- Linear algebra operations
- Projection mathematics
- Preservation of geometric properties