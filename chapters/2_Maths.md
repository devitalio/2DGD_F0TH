The Maths Behind Game Development
=================================

This book assumes you already have some minimal knowledge of maths, including but not limited to:

- Logarithms
- Exponentials
- Roots
- Equations
- Limits

In this chapter we'll take a quick look (or if you already know them, a refresher) on the basic maths needed to make a 2D game.

Vectors
--------

For our objective, we will simplify the complex matter that is vectors as much as possible.

In the case of 2D game development, a vector is just a pair of values `(x,y)`.

Vectors usually represent a force applied to a body, its velocity or acceleration and are graphically represented with an arrow.

![Image of a vector](./images/maths/vector.pdf){width=30%}

The pain of learning about vectors is paid off by their capacity of being added and subtracted among themselves, as well as being multiplied by a number (called a "scalar").

### Adding Vectors

### Subtracting Vectors

### Scaling Vectors

### Normalizing Vectors

Coordinate Systems on computers
---------------------------------

When it comes to 2D graphics on computers, our world gets quite literally turned upside down.

In our math courses we learned about the Coordinate Plane, with an origin and an `x` axis going from left to right and a `y` axis going from bottom to top, where said axis cross it's called the "Origin".

![Image of a coordinate plane](images/math/coord.pdf)

When it comes to 2D graphics, the coordinate plane looks like this:

![Image of a screen coordinate plane](images/math/screen_coord.pdf)

The origin is placed on the top left of the screen and the `y` axis is going from top to bottom. It's a little weird at the beginning, but it's not hard to get used to it.