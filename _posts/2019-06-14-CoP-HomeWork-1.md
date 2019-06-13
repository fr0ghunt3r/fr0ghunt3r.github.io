## Homework 1 

My PC cannot handle Korean language in the default editor, so I cannot help writing down a whole post in English.

### 0. Preliminaries

For our convenience, we'd better program in the same environment. I prefer PyTorch and Python3 rather than other deep learning framework/language. So here is the environment setting for developing/implementing homework below and further works.


    # packages in environment at /home/choi/miniconda3/envs/torch:
    #
    # Name                    Version                   Build  Channel
    blas                      1.0                         mkl  
    ca-certificates           2019.1.23                     0  
    certifi                   2019.3.9                 py37_0  
    cffi                      1.12.2           py37h2e261b9_1  
    cudatoolkit               10.0.130                      0  
    cudnn                     7.3.1                cuda10.0_0  
    intel-openmp              2019.3                      199  
    libedit                   3.1.20181209         hc058e9b_0  
    libffi                    3.2.1                hd88cf55_4  
    libgcc-ng                 8.2.0                hdf63c60_1  
    libgfortran-ng            7.3.0                hdf63c60_0  
    libstdcxx-ng              8.2.0                hdf63c60_1  
    mkl                       2019.3                      199  
    mkl_fft                   1.0.10           py37ha843d7b_0  
    mkl_random                1.0.2            py37hd81dba3_0  
    ncurses                   6.1                  he6710b0_1  
    ninja                     1.9.0            py37hfd86e86_0  
    numpy                     1.16.2           py37h7e9f1db_0  
    numpy-base                1.16.2           py37hde5b4d6_0  
    openssl                   1.1.1b               h7b6447c_1  
    pip                       19.0.3                   py37_0  
    pycparser                 2.19                     py37_0  
    python                    3.7.3                h0371630_0  
    pytorch                   1.0.1           cuda100py37he554f03_0  
    readline                  7.0                  h7b6447c_5  
    setuptools                40.8.0                   py37_0  
    sqlite                    3.27.2               h7b6447c_0  
    tk                        8.6.8                hbc83047_0  
    wheel                     0.33.1                   py37_0  
    xz                        5.2.4                h14c3975_4  
    zlib                      1.2.11               h7b6447c_3  


The minor versions of packages can be changed to the compatibilities of your PC. Everything is okay if you use Python3 and PyTorch v1.xx.
Visit Anaconda websites for the detailed installation guide and usages.

    https://www.anaconda.com/distribution/

### 1. Introduction to MNIST


We will participate in a difficult challenge as a goal for CoP, and we should step up first with a simple problem to reach the goal.
I think MNIST is suitable for our first homework because the dataset is well-known and quite simple. The MNIST dataset contains of 70000 images of handwrited numbers with 28x28 pixel size. It also contains an annotation for each image. An image is matched with a ground truth label that is a number which corresponds to the image.

You can download the MNIST dataset here.

    http://yann.lecun.com/exdb/mnist/

### 2. Homework 1


Our goal in this homework is making an MNIST classifier based on deep learning algorithms.  
The first homework we should do is make a classifier which achieves over 90% of prediction accuracy on the MNIST dataset.
The classifier will get test images as input, and it predicts class numbers(labels) of the test images.

There are lots of tutorials about the MNIST classifier on websites. Here are the MNIST tutorials that run on PyTorch and Python3.

    https://medium.com/@inmoonlight/pytorch%EB%A1%9C-%EB%94%A5%EB%9F%AC%EB%8B%9D%ED%95%98%EA%B8%B0-cnn-62a9326111ae
    https://jaeyung1001.tistory.com/43
    https://github.com/pytorch/examples/tree/master/mnist

As a homework, I think we need to set some achievements for difficulty so that you can understand what we do and how it works.

1. Build a classifier that performs over 90% of prediction accuracy.
2. Build a classifier by both DNNs(fully connected layers) and CNNs.

Feel free to text/call me if you have any questions about the homework.

See you next Monday.
