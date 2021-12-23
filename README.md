# CycleGAN with Simpsons stylization
This project was based upon the official PyTorch implementation of CycleGAN. Total Variation loss and Edge Promoting loss were implemented in respectively the generator and discriminator networks. Other than that, data augmentation and Gaussian Blur was used to experiment with getting better results. The current results are however likely due to poor quality data sets. 

### Run with Gaussian Blur only 
![GaussianBlurOnly](https://user-images.githubusercontent.com/15377936/147256160-f417ef5f-af04-4795-bba3-d3c22addc73d.png)

### Run with Gaussian Blur and Data Augmentation
![GaussianBlurPlusDataAug](https://user-images.githubusercontent.com/15377936/147256174-7b1e5ebf-1c17-4782-afe9-ca7039353ea2.png)

### Run with TV loss, Guassian Blur and Data Augmentation
![TVlossPlusGaussianBlur](https://user-images.githubusercontent.com/15377936/147256118-018759be-68b1-4d77-bea3-12d425dbbf9a.png)

### Run with Edge Promoting loss, Guassian Blur and Data Augmentation
![EdgePromotingLoss](https://user-images.githubusercontent.com/15377936/147256145-b1621804-b03c-4cdd-b4dc-1c4d424f7f20.png)

### Run with TV Loss, Edge Promoting loss, Gaussian Blur and Data Augmentation 
![cartoonGAN](https://user-images.githubusercontent.com/15377936/147256136-abe29940-84c4-4064-bfc9-759eee8c680e.png)
