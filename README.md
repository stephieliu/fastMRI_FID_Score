# fastMRI_FID_Score [IN PROGRESS]

FID Score implementation for the fastMRI Latent Diffusion Model project.

The official PyTorch implementation must be slightly modified such that the raw image feature vectors are dependent on k-space images from the original fastMRI dataset. The generated samples from the fastMRI LDM will be compared against these customised feature vectors rather than the default vectors to test for validity. Currently, there have been no major modifications made to the code.

## References
The official PyTorch FID implementation can be found here: https://github.com/mseitzer/pytorch-fid
