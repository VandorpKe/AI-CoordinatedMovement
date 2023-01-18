# AI-CoordinatedMovement

## Introduction

I am a student from Howest and am currently studying DAE with a major in Game Development and below you will find my research on AI-Coordinated Movement. 

This will be a simple implementation on how you could add coordinated movement to your game. Of course there is more than one way to implement coordinated movement, but this will just be a simple implementation as the movement will happen on a flat surface and not a complicated surface with hills, etc.

## Implementation

### Selection

To be able to move units around the field we are first gonna need the ability to select some units. This can be done by a number of ways, the mosst common ways are as followed. You will be able to select a unit with just LeftClick or by Shift-LeftClicking you can select multiple units. There's also the option to Click and Drag on the screen to select multiple units.

To not confuse the player while selecting, we have to visualize this selection rectangle. This will give a nice and clean visual feedback on which units will be selected. These will be the ones that are in this rectangle ofcourse. It's best to also visualize which units we have selected.

### Navigation

Unity has a built in navigation mesh that you can bake on you world.
