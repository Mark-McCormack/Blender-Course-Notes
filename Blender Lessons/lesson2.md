# Lesson 2: Exploring Blender (Working with Lights and Intro to Animation)

## Objective

In this lesson, students will learn how to add lights to a scene in Blender, customize their colors and settings, and animate them using simple keyframes.

## Materials Needed

- Blender Software

## Introduction

In the previous lesson, we created basic 3D objects like cubes, spheres, and cones. We also explored using materials to enhance the appearance of these objects. By the end of the class, we created scenes like a snowman using spheres, cones, and cylinders.

Today, we'll build on that by adding Christmas lights to the snowman model and animating them to move as if they are blowing in the wind.

![Snowman](https://mir-s3-cdn-cf.behance.net/project_modules/1400/f2535c73677607.5c1137c482ac1.png)

### Lighting in Blender

Blender offers several types of lights you can use in a scene:

- **Point Light**: Like a lightbulb, it emits light in all directions from a single point.
- **Sun Light**: Functions like the sun, where light spreads out in parallel rays from a distant point.
- **Area Light**: Acts like a glowing panel or floodlight, sending light out in a rectangular shape.
- **Spot Light**: Directs light in a focused cone, similar to a spotlight in a theater.

### How to Add Lights to the Scene

![Lighting](https://i.ytimg.com/vi/OFh2_Fu743E/maxresdefault.jpg)

To add a light in Blender:

1. Press <kbd>Shift</kbd> + <kbd>A</kbd>.
2. From the menu that appears, select "Light" instead of "Mesh".
3. Choose the type of light you want to add.

A small dot will appear in your scene, representing the light source. On the right side in the properties panel, you’ll see settings for the light. Feel free to experiment with the light’s color, intensity, and other settings.

### Viewing Lights in the Scene

![Viewport Settings](https://artisticrender.com/wp-content/uploads/2021/01/preview-render.png)

To see how the lights affect your scene, you need to adjust the viewport settings:

1. **Wireframe View**: Shows the skeleton (or framework) of the objects.
2. **Solid View**: Displays the full shape of each object.
3. **Material View**: Shows the colors and materials applied to the objects.
4. **Rendered View**: Displays the final look, including lighting and shadows.

**Task**: Create two area lights in your scene—one orange and one blue—and position them on either side of a cube.

### Animating the Lights

Now let's animate the lights! This involves using "keyframes," which work similarly to stop-motion animation (like in "Wallace and Gromit"). In stop-motion, the characters are moved slightly between each frame, and when the frames are played in sequence, it looks like they are moving.

In Blender, we use keyframes to record the position, rotation, or scale of an object at specific points in time. Blender then animates the object by smoothly transitioning between those keyframes.

![Tracking Keyframes](https://upload.wikimedia.org/wikipedia/commons/5/5c/Blender-keyframes.png)

#### Steps for Animating Lights:

1. **Open the Animation Window**: Drag up the timeline controls from the bottom of the screen.
2. **Select Your Object**: Click on the light you want to animate.
3. **Enable Recording**: Press the "Record" button in the animation window.
4. **Set Keyframes**: Change the light’s position, rotation, or scale. Blender will automatically create a keyframe (shown as a golden diamond).
5. **Move the Scrubber**: Drag the timeline scrubber to a new point in time and adjust the light’s position to create a new keyframe.

Blender will fill in the movement between these keyframes, creating a smooth animation.

**Task**: Animate the lights to spin around the cube in your scene.

## Homework

Use what you’ve learned to experiment further by creating a variation of the animation by adding them to float around the snowman.
