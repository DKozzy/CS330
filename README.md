# CS330
Welcome to the CS-330 organization. This repository contains projects I developed as part of the CS-330 Computational Graphics and Visualization course at Southern New Hampshire University. This class focused on building interactive 3D scenes using OpenGL and C++, developing an understanding of lighting, shading, texturing, and real-time rendering.

## About the Course
CS-330 emphasizes the fundamentals of 3D graphics programming, including transformations, camera systems, and shader development. The projects here demonstrate my ability to design, code, and render low-polygon 3D environments while applying reusable and efficient software design practices.

## What You'll Find Here

- Final Project: 3D Scene and Design Decisions Document
A complete OpenGL project featuring a realistic tabletop environment with multiple textured and lit objects.
- Source Code: Modularized across SceneManager, ViewManager, and ShaderManager classes
- Shader Programs: Vertex and fragment shaders supporting Phong lighting and layered textures
- Textures Folder: Includes custom 1024x1024 textures for realistic materials

## Why This Project Matters
This project shows my ability to combine both technical and creative skills to produce a fully realized 3D world. It highlights knowledge of lighting models, texture mapping, and alpha transparency while using a clean, modular C++ architecture. It also demonstrates an understanding of how rendering pipelines work at the shader level, something that directly applies to professional tools like Blender and Unity.

## Reflection
**How do I approach designing software?**

I approach design by breaking problems into smaller systems that can be built, tested, and reused independently. For this project, I used a modular structure with classes like SceneManager for scene setup and ViewManager for camera control. I focused on maintainability and clarity so that each part of the codebase could be updated without affecting others.

**What new design skills has your work on the project helped you to craft?**

This project helped me develop stronger visual design and shader programming skills. I learned how to manage materials and lighting together in code and how to apply layered textures using alpha blending. These skills taught me to think about both the look and structure of a program at the same time.

**What design process did you follow for your project work?**

I followed an iterative process: build simple shapes, arrange them, then refine with materials and lighting. I started with basic geometry, then tested camera movement and shading before applying textures. Each pass made the scene more realistic and helped me balance performance with presentation.

**How could tactics from your design approach be applied in future work?**

This same modular, iterative approach fits well in future projects like simulations, visual tools, or games. Planning around reusable systems makes it easier to adapt code for new environments or scale it up for larger projects.

**How do I approach developing programs?**

I develop by starting with a functional foundation, then layering in visual and interactive features. I focus on writing organized, reusable code that clearly separates logic, visuals, and data. Each major feature of this project—camera movement, materials, and lighting—was developed and tested independently before being integrated.

**What new development strategies did you use while working on your 3D scene?**

I built a reusable materials list that stores ambient, diffuse, and specular values, along with shininess and transparency. I also added custom shader logic that allows layered texturing and blending. These systems make it easy to apply different surface looks to multiple objects and can be reused in other OpenGL projects.

**How did iteration factor into your development?**

Iteration played a huge role. I constantly refined object positioning, lighting balance, and shader settings until everything worked together naturally. Testing each stage visually helped me catch issues early and make steady improvements without breaking previous work.

**How has your approach to developing code evolved throughout the milestones, which led you to the project’s completion?**

At the beginning of the course, I wasn’t completely sure which parts of the code controlled what. The first few milestones were mostly trial and error, testing different settings and seeing what each change actually did in the scene. It took a bit of time to get comfortable with how everything worked together, especially between the camera, shaders, and object transformations. Once I started to recognize how each system connected, I began to make more intentional adjustments and improvements instead of just experimenting. By the time I reached the final project, I understood how to expand the program in a structured way. I could confidently tweak materials, lighting, and shaders to create the results I wanted instead of just hoping something worked.

**How can computer science help me in reaching my goals?**

Computer science gives me the technical foundation to bring creative ideas to life. Whether through rendering, simulation, or game development, understanding how systems work at a low level lets me design solutions that are both efficient and intentional.

**How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future educational pathway?**

This project deepened my understanding of how math, logic, and art work together in 3D rendering. Knowing how to write shaders, handle lighting, and build camera systems will be useful in any advanced coursework involving interactive systems or graphics programming.

**How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future professional pathway?**

These skills directly apply to indie game development and 3D visualization. Understanding OpenGL gives me insight into how engines like Blender or Unity work under the hood. I can now approach visual design with both creativity and technical control, bridging the gap between programming and art.

## Future Applications
In the future, I plan to use these techniques to continue building interactive 3D scenes and small game prototypes. The experience of writing shaders, defining materials, and managing lighting from scratch gives me a strong foundation for any graphics-focused project, whether in school or independent development.
