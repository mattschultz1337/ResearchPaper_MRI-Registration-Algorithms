**MRI RegistrationAlgorithms**

Matthew Schultz

*Written during CS301 for Professor G. Weinschenk Spring 2019*

## Abstract
MRI registration algorithms are used to convert data from MRI scans into three-dimensional
segmentations of the brain. VoxelMorph is a registration method developed by researchers at
MIT and Cornell University which utilizes a convolutional neural network to treat the image
mapping function parametrically. This algorithm produces results that are consistently as
accurate, and in some cases more accurate, than conventional approaches to medical image
registration. It also does all of this significantly faster, especially when using a GPU to run it.
The impact of this quicker speed could be important, but also the application of convolutional
neural networks as a way of improving older processes is an important factor. VoxelMorph is a
much quicker and equally accurate MRI image registration method, and is pushing the medical
community forward by implementing a CNN to accomplish this task.
