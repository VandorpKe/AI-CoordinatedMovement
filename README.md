# AI-CoordinatedMovement

## Introduction

I am a student from Howest and am currently studying DAE with a major in Game Development and below you will find my research on AI-Coordinated Movement. 

This will be a simple implementation on how you could add coordinated movement to your game. Of course there is more than one way to implement coordinated movement, but this will just be a simple implementation as the movement will happen on a flat surface and not a complicated surface with hills, etc.

## Implementation

### Navigation

We need a form of navigation that gets us through obstacles and to our chosen destination. We will be using A* pathfinding to navigate our units around the field. It supports dynamic scenes that are constantly changing, works on moving objects, supports elevation and works in both 2D and 3D. This makes it really versatile.
