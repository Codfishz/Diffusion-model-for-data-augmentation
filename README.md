# Diffusion Model for Data Augmentation in Biological Research
In biological research, sample size imbalance is a common issue, often caused by the varying characteristics of biological subjects. For instance, when studying cell cycle phases, the sample size for dividing cells is often much smaller due to the relatively short duration of the mitotic phase compared to the interphase.

This repository presents an experiment using diffusion models for image data augmentation to address this imbalance. While GAN-based models have been widely used for data augmentation, diffusion models have recently shown exceptional performance in image generation tasks.

Key Features:
Diffusion Model for Data Augmentation: The model enhances underrepresented biological images, particularly those of dividing cells.
Improved Classifier Performance: With the inclusion of augmented data, the classifier's performance improved significantly, increasing the positive predictive value (PPV) from 0.7 to over 0.9.
Potential Applications: The results suggest that diffusion models are highly effective in addressing sample size imbalance and offer promising applications for data enhancement in various biological studies.
Results:
The experimental results demonstrate that data augmentation using the diffusion model leads to a more balanced dataset and improves classification accuracy. This technique shows strong potential for improving models that struggle with data scarcity or imbalanced classes.

