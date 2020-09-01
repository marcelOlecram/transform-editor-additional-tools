# Unity custom tools

Tools for unity editor, to expand functionality.
----
## About
The custom transfor inspector idea came from this [tutorial](http://naplandgames.com/blog/2016/08/27/unity-3d-tutorial-custom-transform-inspector/).

The purpose of this repository is to expand functionality to the default transform inspector component.

Developed under _Unity 2019.4.8f1_

The project uses a MIT License. Use it as you want it

The basic Transform inspector in Unity only provides Position, Rotation and Scale information. This custom transform inspector, expand from this, adding:

###  Custom Transform Inspector

- Real world position of the GameObject (instead of the relative position to theri parent)
- A quaternion foldout (which is main idea from the tutorial linked above).
- A set of tools to place a gameobject such as: 
    - Reset buttons to set Position to zero, Rotation to zero, and Scale to one, and one in all button
    - Random position (between a range designated from two Vector3), with an Axis constraint
    - Random rotation (calculated in EulerAngles from 0 to 360 degress), with Axis contraint
    - Random scale (calculated between two floats, this random scale is applied to all xis). Keeping uniformity

## Installation

On your Unity Project > Window > Package Manager > Plus sign > Add Package from git URL > _paste this repo URL_

## Ideas / TODOs in a future
- make repo more presentable
- subdivide in more tools
