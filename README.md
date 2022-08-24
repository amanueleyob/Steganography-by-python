# Steganography-by-python
Steganography is the art of hiding secret data in any file.

The secret data can be data of any format like text or even a file. In a nutshell, the main motive of steganography is to hide the intended information within any file, usually an image, audio, or video, without actually changing the external appearance of the file, i.e. it should look the same as before.

In this blog, we will be focussing on learning image-based steganography, i.e. hiding secret data in an image.

But before diving a little deeper into it, let’s look at what an image comprises of.

    Pixels are the building blocks of an image.
    Every pixel contains three values: (red, green, blue) also known as RGB values.
    Every RGB value ranges from 0 to 255.

This much information is enough to get started.

Now, let’s look at how we can encode and decode data into our image.
