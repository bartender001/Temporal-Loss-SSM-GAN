# Temporal-Loss-SSM-GAN
Video Frame Interpolation (VFI) is a significant and active research challenge within the computer vision community. It involves generating intermediate frames between existing frames in a video sequence, improving motion smoothness and enhancing video quality. This is particularly useful in applications such as slow-motion video generation, video frame rate upscaling, and animation.

This work aims to address the temporal consistency problem in VFI. Traditional GAN-based VFI methods primarily focus on spatial features, often neglecting the temporal coherence across frames, leading to flickering or unnatural transitions. To mitigate this issue, this approach leverages a state-space model, specifically Mamba, to capture long-range dependencies across frames.

Mamba, a structured state-space model (SSM), offers an efficient and expressive way to model temporal dynamics while maintaining computational efficiency. The model aims to improve the generation of intermediate frames by learning smooth and temporally consistent transitions, ultimately enhancing the overall perceptual quality of interpolated videos.
