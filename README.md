<h1> Variational Autoencoders </h1>
This is an implementation of Variational Autoencoders in pytorch. You can train and run it on both CPU as well as GPU :smile:

<h3> A brief introduction </h3>
VAEs are one of the many varients of a an architecture known as autoencoders. Now the basic aim of any autoencoder is to represent an input image in a lower dimensional state, and then reconstruction from that state. So rather than having any label as the output, the input image itself is the output of the network. The lower dimensional state is highly useful in the sense that we have constrained our network so that our network is basically forced so as to represent the input image in that lower dimension which leads to the persistence of information which is of importance to the basic architecture of the image. So in a sense, we have created an image compression algo as such which can easily be decompressed using our decoder network. However this compression is, of course, lossy in nature and may lead to loss certain important details and hence not used for compression, practically.

