
## NAFNet: Nonlinear Activation Free Network for Image Restoration

```bash
git clone https://github.com/megvii-research/NAFNet
cd NAFNet
conda create -n nafnet python=3.9.5
conda activate nafnet
conda install pytorch==1.11.0 torchvision==0.12.0 torchaudio==0.11.0 cudatoolkit=11.3 -c pytorch
pip install -r requirements.txt
python setup.py develop --no_cuda_ext
pip install gdown matplotlib imageio
```


## Denoising

```bash
python denoiser.py --dir <directory of noisy images> --im_size <size of input and output images, default= No resizing>
```
Denoised images are stored in folder `denoised_images'.


## Debluring

```bash
python deblur.py --dir <directory of noisy images> --im_size <size of input and output images, default= No resizing>
```

Deblurred images are stored in folder `deblurred_images'.





## Reference

https://github.com/megvii-research/NAFNet



