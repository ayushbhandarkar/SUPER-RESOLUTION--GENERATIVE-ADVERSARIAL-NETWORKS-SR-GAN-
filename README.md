Introduction
Image upsampling is a technique used to increase
the resolution of an image without compromising its
quality. The traditional methods of upsampling are
limited in their ability to produce high-quality
images. However, with the advent of Generative
Adversarial Networks (GANs), it has become
possible to generate realistic and high-resolution
images.
GANs are a type of deep learning algorithm that
consists of two neural networks – a generator and a
discriminator. The generator creates new images,
while the discriminator evaluates the authenticity of
the generated images. This process continues until
the generator produces images that are
indistinguishable from real images.

In the case of image upsampling using GAN, the generator network takes a low-resolution image
as input and produces a high-resolution image as output. The discriminator network then
evaluates the authenticity of the generated image by comparing it to real high-resolution
images.
The generator network is trained to improve its output based on the feedback from the
discriminator network. Over time, the generator becomes better at producing high-quality
images that are almost indistinguishable from real high-resolution images. This process is known
as adversarial training, and it is what makes GANs so powerful for image upsampling.
A Generative Adversarial Network (GAN) Super Resolution architecture is a particular variety of
GAN created to improve the resolution of low-quality photographs. A discriminator network and a
generator network make up the architecture's two primary parts. A low-resolution image is sent
into the generator network, which creates a high-resolution image. It generally consists of many
convolutional layers and up samples the picture using a method like reversed convolution or sub-
pixel convolution.
The produced high-resolution photos and the actual high-resolution images are separated using
the discriminator network. It is trained to distinguish between false and real photos, classifying the
produced images as fake.
The generator network seeks to produce realistic, high-resolution pictures that are identical to the
actual pictures during training. On the other hand, the discriminator network seeks to reliably
identify whether the produced pictures are phony or real.
Minimizing the adversarial loss among the generator and discriminator nodes is a goal of the
iterative training process. The generator loss and discriminator loss, which assess how effectively
the generator produces realistic pictures and the way the discriminator distinguishes between
actual and created images, are combined to form the adversarial loss.
The resolution of surveillance films, satellite photos, and medical imaging have all been improved
with the help of the GAN Super Resolution architecture.
