This folder contains the codes and report for the second project. 

The private dataset contains a total of 5000 high-quality (HQ) training images and 400 low-quality-high-quality (LQ-HQ) validation image pairs. We are required to perform a series of degradation to the training images to obtain
the corresponding LQ images from the HQ images. After training our network, we evaluate on 400 test images using peak signal-to-noise ratio (PSNR).

Here, we used a standard SRResNet for the super-resolution task. We also included two degree of degradation to the training images. In our experiments, we also devised a custom loss function that seems to provide a better training landscape. 
