DSIM PROJECT 2026: AUDIO SOURCE SEPARATION & DRUM ANALYSIS
======================================================================

Group Members: Chiara Pelizza 880217, Enrico Moriggi 880354
University of Milano-Bicocca 


PROJECT OVERVIEW:
This project explores advanced audio signal processing and deep learning 
techniques for music source separation, focusing specifically on isolating 
drum tracks from professional mixtures. Using the MUSDB18 dataset, we 
implemented a progression of methods: from 1D feature extraction and 
kick-detection to 2D spectral analysis (SSM, HPS), concluding with 
state-of-the-art architectures such as U-Nets (with SpecAugment) 
and Conditional GANs.

LINK TO GOOGLE DRIVE FOLDER:
[https://drive.google.com/drive/folders/1TpbILLbjqHRVeYU49Ap5ojFjrAUUSg8w?usp=drive_link]

----------------------------------------------------------------------
SUBMISSION STRUCTURE
----------------------------------------------------------------------

1. E-LEARNING SUBMISSION:
   - Audio_Source_separation.pdf: Final project presentation covering methodology, evaluation, and results.
   - README.txt: This file.

2. GOOGLE DRIVE CONTENTS:
   - Mono_dimensional_signal_processing_final.ipynb: 1D Time/Frequency analysis & Kick detection.
   - BiDimensional Processing.ipynb: 2D representations, SSM analysis, HPS, and CNN classification.
   - Task3.ipynb: Training pipeline for Source Separation models.
   - Tas3-Evaluation.ipynb: Comprehensive statistical evaluation using MAE, SSIM, and Binary Detection metrics (Precision, Recall, F1).
   - Music_AI_Project: folder containing the following models: 
      * model_base.keras (U-Net Baseline)
      * unet_pro_aug_final.keras (U-Net with SpecAugment)
      * music_gan_generator.keras (GAN Generator)
   - musdb18.zip: zipped version of the musdb18 dataset
   - demo.ipynb: script for our web-application.
   - demo_record.mp4: Video demonstration of the developed source separation webapp.
----------------------------------------------------------------------
EXECUTION INSTRUCTIONS
----------------------------------------------------------------------

The notebooks are designed to run in a Google Colab environment.
To ensure correct execution:
1. Install dependencies listed at the beginning of each notebook (musdb, stempeg, museval).
2. Mount your Google Drive to access the MUSDB18 dataset (zip format).
3. To test pre-trained models, load the .keras files from the provided Drive link.

