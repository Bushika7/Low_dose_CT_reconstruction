# Low dose CT reconstruction

The goal of this project is to build a deep learning model which is able to recostruct clean, high-dose & high quality images from low-dose (noisy) CT sinograms.

Why is this beneficial?

A full body CT scan with the traditional dose and traditional reconstruction method ( https://www.youtube.com/watch?v=pZ7JlXagT0w ) is equivalent to around 100-300 chest X-rays in terms of radiation dose absorbed by the body. Lowering the dose of each scan can result in significantly less absorbed radiation which reduces the chance of potential adverse effects of CT. Lowering the dose on the other hand results in highly noisy, decreased quality images which have significantly less diagnostic value if reconstructed with the traditional reconstruction methods.

Modern deep learning networks however have the capacity to restore high quality images from low-dose CT scans, resulting in equivalent diagnostic quality images as high-dose CT scans,effectively reducing the harmul potential of the technology.

For this, you need to train the network on low-dose noisy sinogram / high quality high dose image pairs.

I'm using the following dataset: https://zenodo.org/records/3384092 and I'm trying to implement a reconstruction method with the help of tensorflow
