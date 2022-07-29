# `fontreplace`
`fontreplace` is a collection of neural networks and scripts to recognize, remove and replace text, change font in image.

## Parts of project
### Generator
To fit NNs, the images with markup required. For this, a generator exists.

Generator produces pairs of arrays (input and output), where input array is image with text, and output array is the image without text, coordinates of text and it's font.
