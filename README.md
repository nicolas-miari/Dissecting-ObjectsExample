# Dissecting Apple's "ObjectsExample"

This repository serves as a playground to make version-controllable modifications and experimentation on Apple's sample project: "Adopting Metal II - Designing and Implementing a Real-World Metal Renderer" (_ObjectsExample.xcodeproj_, original sample code [here](https://developer.apple.com/library/content/samplecode/AdoptingMetalII/Introduction/Intro.html)).

In particular, the original project has many user-configurable switches that determine which of the mutliple possible render paths are used (e.g., multithreaded render vs. single threaded; render shadows or not) and is therefore quite difficult to follow.

This repository will host several "feature" branches in which the rendering paths have been simplified (e.g., `if` statements removed altogether) for clarity. 
