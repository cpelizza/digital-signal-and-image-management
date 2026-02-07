DSIM PROJECT 2026: AUDIO SOURCE SEPARATION & DRUM ANALYSIS
======================================================================

Group Members: Chiara Pelizza 880217, Enrico Moriggi 880354


PROJECT OVERVIEW:
This project explores advanced audio signal processing and deep learning 
techniques for music source separation, focusing specifically on isolating 
drum tracks from professional mixtures. Using the MUSDB18 dataset, we 
implemented a progression of methods: from 1D feature extraction and 
kick-detection to 2D spectral analysis (SSM, HPS), concluding with 
state-of-the-art architectures such as U-Nets (with SpecAugment) 
and Conditional GANs.

LINK TO GOOGLE DRIVE FOLDER:
[INSERT YOUR LINK HERE]

----------------------------------------------------------------------
SUBMISSION STRUCTURE
----------------------------------------------------------------------

1. E-LEARNING SUBMISSION (Lightweight files):
   - Presentation_Progetto.pdf: Project slides and documentation.
   - README.txt: This file.

2. GOOGLE DRIVE CONTENTS (Heavyweight files):
   - Notebook_1_Monodimensional.ipynb: Time/Frequency analysis & Kick detection.
   - Notebook_2_Bidimensional.ipynb: Spectrograms, SSM, HPS, and CNN classification.
   - Notebook_3_U-Net_GAN.ipynb: Training of Source Separation models.
   - Notebook_4_Evaluation.ipynb: Final statistical evaluation on the test set.
   - /Trained_Models/: 
      * model_base.keras (U-Net Baseline)
      * unet_pro_aug_final.keras (U-Net with SpecAugment)
      * music_gan_generator.keras (GAN Generator)

----------------------------------------------------------------------
EXECUTION INSTRUCTIONS
----------------------------------------------------------------------

The notebooks are designed to run in a Google Colab environment.
To ensure correct execution:
1. Install dependencies listed at the beginning of each notebook (musdb, stempeg, museval).
2. Mount your Google Drive to access the MUSDB18 dataset (zip format).
3. To test pre-trained models, load the .keras files from the provided Drive link.

Note: The dataset is not included in this submission as per instructions, 
but will be available for demonstration during the oral exam.
======================================================================
