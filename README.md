# Computer Graphics Course

Course material for an undergraduate level course in [computer
graphics](https://en.wikipedia.org/wiki/Computer_graphics)

Course designed by [Prof. Alec Jacobson](http://www.cs.toronto.edu/~jacobson/),
David I.W. Levin and Karan Singh from University of Toronto, with assistance
from Yotam Gingold at GMU.

## Prerequisites and dependencies

In general, the materials in this course assume that students should have
already taken **Linear Algebra** and **Calculus**.

Students should have already taken **Introduction to Computer Science** and should
be proficient in computer programming (in any language) and should feel
comfortable programming in **C++**. 

Some coding assignments make use of
[Eigen](https://en.wikipedia.org/wiki/Eigen_(C%2B%2B_library)), an open-source
linear algebra library; and [libigl](http://libigl.github.io/libigl/), an
open-source geometry processing library.  Each assigment is built using
[CMake](https://en.wikipedia.org/wiki/CMake).

## Organization

The course is structured to run with fast paced _weekly_ assignments in the
following order:

  1. [Introduction & Raster Images](https://github.com/alecjacobson/computer-graphics-raster-images)
  2. [Ray Casting](https://github.com/alecjacobson/computer-graphics-ray-casting)
  3. [Ray Tracing](https://github.com/alecjacobson/computer-graphics-ray-tracing)
  4. [Meshes](https://github.com/alecjacobson/computer-graphics-meshes)
  5. [Boundary Volume Hierarchy](https://github.com/alecjacobson/computer-graphics-boundary-volume-hierarchy)
  6. [Shader Pipeline](https://github.com/alecjacobson/computer-graphics-shader-pipeline)
  7. [Kinematics](https://github.com/alecjacobson/computer-graphics-kinematics)
  8. [Mass-Spring Systems](https://github.com/alecjacobson/computer-graphics-mass-spring-systems)

There is a slight dependence to these assignments:

  - [Ray Casting](https://github.com/alecjacobson/computer-graphics-ray-casting)
    before [Ray
    Tracing](https://github.com/alecjacobson/computer-graphics-ray-tracing)

Each topic has its own git repository. Inside each, there is a `README.md` file
contains background information necessary for understanding the topic's coding
assignment. 

The
[Introduction](https://github.com/alecjacobson/computer-graphics-raster-images)
`README.md` contains detailed information about compilation, file layout and
assignment protocols. 

## Textbook

![The Book.](https://www.cs.cornell.edu/~srm/fcg4/K22616_cover-300.jpg)

These assignments were prepared to closely follow:

[_Fundamentals of Computer Graphics, Fourth
Edition_](https://www.cs.cornell.edu/~srm/fcg4/), Steve Marschner, Pete Shirley,
et al. 2015.

## Wikipedia

The background materials link heavily to Wikipedia articles. Sometimes the
wikipedia articles relating to computer graphics are less informative than they
could be. Edit them!

## Are you an instructor?

There are instructor repositories for all of the assignments above. If you're an
instructor for a geometry processing course, send an email to
jacobson@cs.toronto.edu for an invitation.

> For my reference, I can add a new instructor with github id `[githubid]` to all solution repos using:
>
> ```
> github-add-user -u alecjacobson -r $(echo alecjacobson/computer-graphics-{raster-images,ray-casting,ray-tracing,bounding-volume-hierarchy,meshes,shader-pipeline,kinematics,mass-spring-systems}-solution | tr ' ' ',') [githubid]
> ```

### Corresponding solution/instructor (private) repos are located at:

  0. [Pre test](https://github.com/alecjacobson/computer-graphics-pre-test)
  1. [Introduction & Raster Images](https://github.com/alecjacobson/computer-graphics-raster-images-solution)
  2. [Ray Casting](https://github.com/alecjacobson/computer-graphics-ray-casting-solution)
  3. [Ray Tracing](https://github.com/alecjacobson/computer-graphics-ray-tracing-solution)
  4. [Bounding Volume Hierarchy](https://github.com/alecjacobson/computer-graphics-bounding-volume-hierarchy-solution)
  5. [Meshes](https://github.com/alecjacobson/computer-graphics-meshes-solution)
  6. [Shader Pipeline](https://github.com/alecjacobson/computer-graphics-shader-pipeline-solution)
  7. [Kinematics](https://github.com/alecjacobson/computer-graphics-kinematics-solution)
  8. [Mass-Spring Systems](https://github.com/alecjacobson/computer-graphics-mass-spring-systems-solution)

## Future Assignments

 - Ambient Occlusion + Occluding Contours (Multipass rendering)
 - Boids
 - Rigid Body with contacts
 - Cloth Simulation
 - Physically Based Real-Time Rendering
 - Half-Edge Data-structre 
 - 1D plotting (vector graphics line rasterization)
 - Path Tracing, BRDFs
 - Mesh Laplacians 
