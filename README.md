# Christmas Animation Project - README

## Overview
This project involves creating a holiday-themed animation in Blender. It features two humanoid characters (an alien and Santa Claus), a festive environment, and dynamic animations, all combined into a single scene. Below are the detailed steps and processes used to create this project.

---

## Creation Steps

### 1. Humanoid Character
- **Base Model**: Started by creating a humanoid character in Blender 4.2 using the tutorial: [Creating a Humanoid Character](https://youtu.be/IhIGVO4fqLg?si=zp59mVnvPdgp_Bfb).  
- **Armature and IK**: Added an armature to the character for movement control and implemented Inverse Kinematics (IK) for better control, following the tutorial: [Inverse Kinematics](https://youtu.be/mYgznqvbisM?si=m17v08NRrIk1tLYd).  
- **Variations**:  
  - **Alien**: 
    - Copied the base character to a new Blender file.  
    - Enlarged the head, made the limbs thinner, and colored the skin green.  
    - Used procedural texturing to create a skin-like appearance and mapped it into bumps (inspired by [Procedural Skin Texturing](https://youtu.be/iDXGPsrO0_M?si=5JfmDIfgM8ByPvQp)).  
    - Moved to Blender 3.6 due to crashes in shading mode on Blender 4.2.  
  - **Santa Claus**: 
    - Used the base character and colored the skin normally.  
    - Added clothes by texturing a photo using UV Editing mode with UV Image Wrapping.  
    - Downloaded the shoes and hat from an external website.

---

### 2. Environment Setup
- **Imported Models**:  
  - UCC Student Centre from the provided link.  
  - Additional objects (spaceship, snow blanket, Christmas tree, presents, clouds, green ring, and dino students) downloaded from Sketchfab.  
- **Scene Arrangement**: Positioned and scaled all objects. Defined camera positions for optimal framing.  
- **Lighting**:  
  - Added a sun as the main light source.  
  - Small yellow light placed above the star on the Christmas tree.  
  - Four lights (two red and two green) positioned in front of the spaceship for a Christmassy atmosphere.  
- **Object Adjustment**: Moved all objects below the snow blanket by -1000 units. Attempts to hide objects from camera view were unsuccessful.

---

## Animation

### 1. Timeline
- Set the animation length to **1500 frames** (6 x 250 frames for a total of 60 seconds).  

### 2. Animations
- **Clouds**: Animated clouds to simulate natural movement, inspired by [Animating Clouds in Blender](https://youtu.be/dF3JMt3uM1E?si=JzkpgWqTjCWC0liE).  
- **Flag Animation**: Created a waving flag with a "Merry Christmas" message using a transparent photo, following [Cloth Animation](https://youtu.be/pFBkikMBW0U?si=q2wFs4QKvB89UnhN).  
- **Spaceship**:  
  - Animated its arrival by defining the movement path backward from its final position to the camera's view.  
  - Duplicated the path for the spaceship's departure and rotated it by 180 degrees. Used Bezier interpolation for smooth motion.  
- **Green Ring Transitions**: Animated the appearance of the characters and the Christmas tree through the green ring using linear movements.  
- **Character Actions**:  
  - Created hand-waving animations for both characters.  
  - Added a smooth walking animation for the alien as it approached the Christmas tree.  
- **Dino Students**: Animated their sudden appearance from the snow, where they received presents with a touch of "Christmas magic."  
- **Ending Sequence**: Both characters exited through the green ring back to the spaceship, which then returned to the sky.  

---

## Final Touches
- Added a 3D text displaying the title of the animation: **"Christmas is here"**.  

---

## Notes
- Blender Versions:  
  - Initial modeling and setup were done in Blender 4.2.  
  - Switched to Blender 3.6 for shading due to compatibility issues.  
- External Resources:  
  - Objects and assets were imported from Sketchfab and other specified sources.  
  - Shoes and hat for Santa were downloaded from an external website.  

--- 

## Inspiration and Tutorials
1. [Creating a Humanoid Character](https://youtu.be/IhIGVO4fqLg?si=zp59mVnvPdgp_Bfb)  
2. [Inverse Kinematics](https://youtu.be/mYgznqvbisM?si=m17v08NRrIk1tLYd)  
3. [Procedural Skin Texturing](https://youtu.be/iDXGPsrO0_M?si=5JfmDIfgM8ByPvQp)  
4. [Animating Clouds in Blender](https://youtu.be/dF3JMt3uM1E?si=JzkpgWqTjCWC0liE)  
5. [Cloth Animation](https://youtu.be/pFBkikMBW0U?si=q2wFs4QKvB89UnhN)  

