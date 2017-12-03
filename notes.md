# Class breakdown

## Who are we?
- Alexander Radkov (https://github.com/LautrecOfCarim)
- Ryan Jones (https://github.com/Polyrhythm)
- Send us questions directly here (https://github.com/Polyrhythm/shader_school) and we will answer

## Basic concepts
- How computer programs work in general (3 minutes)
  - Enter the main() function
  - Do some work starting from the top
  - Enter function calls and do some more work
  - Finish
  - Or don't
- How shaders work
  - Draw a shape on the screen
  - Do that every frame, if your engineers are good maybe 60 times per second
  - Or 120 times per second if your engineers are **really** good
  - In our case, draw a quad on the entire screen
- Explain RGB
  - We represent colors as a combination of Red, Green and Blue
  - That's how human eyes work. If we are fish or butterflies maybe we also need ultraviolet
  - Each of those values varies from 0 to 1

- **Activity**
  - Have an uniform color on the screen (http://glslsandbox.com/e#43929.0)

- Explain fragcoord, concept that shader runs on every pixel
  - Every frame the time is different
  - For every pixel the coordinate is different
  - Maybe we can also use the mouse coordinates
  
- **Activity**
  - Display the mouse coordinates (http://glslsandbox.com/e#43966.1)
  - Separate the screen in 2 or 3 vertical and/or horizontal regions

- **Optional activity**
  - Plot functions in 2d (http://glslsandbox.com/e#43969.0)
  
## session 2 - 3d + noise
* use graph visualizer to explain how to make noise (http://tobyschachman.com/Shadershop/)
* quickly go over the basics of 3d objects
* explain how to create noise on the surface of sphere
* demonstrate how cos and sin can be used as a basis for noise
* use shader here (http://glslsandbox.com/e#43750.3)
* allow students to experiment with their own noise patterns

## reference
book of shaders (http://thebookofshaders.com/)
