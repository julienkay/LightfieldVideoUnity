A Unity implementation of the rendering part of Google's [Immersive Light Field Video With A Layered Mesh Representation](https://mobile-nerf.github.io/)[^1]

This repository's sole purpose right now is to provide access to the compiled viewer applications for mobile & desktop VR (Oculus Quest & Rift) in the [release section.](https://github.com/julienkay/LightfieldVideoUnity/releases/tag/v0.0.1)

Code might be released someday, but Unity's own video player technology is too inefficient for stutter-free playback of these high-resolution videos, and other video players for Unity used in the viewer applications are proprietary.

Also, sadly Google never released the training code for this research project. Looking at how quickly people picked up NeRF and Gaussian Splatting techniques to create products around them makes me think about where this could have gone. Because I feel like their layered mesh representation hits a sweet spot between quality & realtime rendering performance that I feel is missing in a lot of the other "learned-through-gradient-descent" 3D volume representation approaches.

[^1]: [Michael Broxton and John Flynn and Ryan Overbeck and Daniel Erickson and Peter Hedman and Matthew DuVall and Jason Dourgarian and Jay Busch and Matt Whalen and Paul Debevec. Immersive Light Field Video with a Layered Mesh Representation. ACM Transactions on Graphics (Proc. SIGGRAPH), 2020](https://augmentedperception.github.io/deepviewvideo/)
