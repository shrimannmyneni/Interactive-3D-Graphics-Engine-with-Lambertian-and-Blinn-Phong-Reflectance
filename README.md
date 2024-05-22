# Interactive-3D-Graphics-Engine-with-Lambertian-and-Blinn-Phong-Reflectance
Developed for MATH 214 at UofMichigan; project demonstrates computer graphics concepts using Lambertian and Blinn-Phong reflectance models. The 3D engine uses OpenGL, GLFW, and PyOpenGL for realistic rendering. Key concepts include shading algorithms, matrix transformations, and vector math, with support for flat, Gouraud, and Phong shading.
### Project Title: Interactive 3D Graphics Engine with Lambertian and Blinn-Phong Reflectance

#### Description:
This project, developed for MATH 214 at the University of Michigan, aims to demonstrate fundamental concepts in computer graphics by implementing Lambertian and Blinn-Phong reflectance models. The interactive 3D graphics engine showcases realistic rendering techniques using OpenGL, GLFW, and PyOpenGL. Key computer science concepts covered include shading algorithms, matrix transformations, and vector mathematics. Users can explore flat, Gouraud, and Phong shading models within a simulated 3D environment.

---

## README

### Project Title: Interactive 3D Graphics Engine with Lambertian and Blinn-Phong Reflectance

#### Overview
This project, developed for MATH 214 at the University of Michigan, demonstrates fundamental concepts in computer graphics through the implementation of Lambertian and Blinn-Phong reflectance models. The interactive 3D graphics engine allows users to explore realistic rendering techniques, employing OpenGL, GLFW, and PyOpenGL libraries.

#### Features
- **Realistic Shading Models**: Implements Lambertian reflectance for diffuse shading and Blinn-Phong reflectance for specular highlights.
- **Interactive Environment**: Users can interact with a 3D environment, navigating and observing the effects of different lighting models.
- **Multiple Shading Techniques**: Supports flat shading, Gouraud shading, and Phong shading, showcasing the evolution of shading algorithms.

#### Key Concepts
- **Shading Algorithms**: Demonstrates the use of Lambertian and Blinn-Phong models for light reflection.
- **Matrix Transformations**: Utilizes matrix operations for 3D transformations and perspective projections.
- **Vector Mathematics**: Applies vector math for calculating lighting, normals, and reflections.

#### Getting Started

##### Prerequisites
- Python 3.x
- OpenGL
- GLFW
- PyOpenGL
- NumPy
- PIL

##### Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/3d-graphics-engine.git
    ```
2. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

##### Running the Application
1. Navigate to the project directory.
2. Run the main application script:
    ```bash
    python main.py
    ```

#### Usage
- Use `W`, `A`, `S`, `D` keys to move the camera.
- Use the mouse to look around the environment.
- Observe the effects of different shading models on the rendered objects.

#### Project Structure
- `main.py`: Entry point of the application.
- `shaders/`: Contains GLSL shader programs for vertex and fragment processing.
- `models/`: Includes 3D model files used in the scene.
- `gfx/`: Contains texture images for materials.
- `src/`: Source code implementing the graphics engine, entities, and scene management.

#### Contributors
- [Your Name](https://github.com/yourusername)

#### License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

#### References
- Lambertian Reflectance
- Blinn-Phong Shading Model
- OpenGL Documentation
