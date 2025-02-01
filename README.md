# Image Generation AI Model using NVIDIA's StyleGAN

## Key Innovations in StyleGAN

1. **Mapping Network.**

 - Transforms input noise to an intermediate latent space.
 - Non-linear transformations prevent unwanted correlations.
 - Allows for more controlled generation.

2. **Synthesis Network.**

 - Progressive growing of feature maps.
 - Simulated Adaptive Instance Normalization (AdaIN).
 - Noise injection for stochastic variation.

3. **Style Mixing**

 - Ability to control different levels of image generation.
 - Separates high-level attributes from stochastic details.

## Limitations of this Implementation

 - Simplified version of the original StyleGAN.
 - Does not include full progressive growing.
 - Approximates AdaIN concept.
 - Reduced computational complexity.
