# A Jittor Implementation of Conditional GAN

This is a Jittor implementation of Conditional GAN.
The main framework can be found at [gitlink](https://www.gitlink.org.cn/competitions/index/Jittor-5). 
Here I provide a fulfilled example of this framework.

## Setup
```bash
pip install -r requirements.txt
```
A detailed tutorial for Jittor installation can be found at [Jittor](https://cg.cs.tsinghua.edu.cn/jittor/download).

## Usage
```bash
cd src
python CGAN.py
```
The program will automatically load the MNIST dataset from web and start traning.

The last check point will be stored in `src/generator_last.pkl` and `src/discriminator_last.pkl`.

The pictures generated during training will be stored in `src` folder.
