# Underwater_Image_Enhancement_method

### General content of the paper
- propose an underwater image enhancement method based on **adaptive histogram equalisation** and **improved cGAN**. 

- Firstly, an adaptive histogram equalisation model is developed to enhance the brightness and contrast of the image.
- Subsequently, an image enhancement model based on improved cGAN is developed to design an encoder-decoder network as the **generator** based on the **U-Net** principle,
 and the **discriminator** uses a Markov PatchGAN structure to effectively capture the high frequency features of the image. 
- The loss function combines the conditional generative adversarial network loss function, global similarity loss and content perception loss. ([see Pytorch](/Pytorch/))

- Modules for image quality analysis based on **UIQM**, **SSIM**, and **PSNR** ([see Evaluation](/Evaluation/))

- The **UIEB dataset** is used as the training set and test set, and the result examples can be seen in the file.([see result](/result/))
