# generatefaces
Generative adversarial network for generating new human faces

# Description
This repo contains code to generate never before seen human faces. Using TensorFlow convolutional layers,
the Jupyter notebook documents the construction of a generator and discriminator network to work in tandem
in order to complete this task. The generator network is responsible for taking noise as input and converting
it into an image representing a human face. During training, the discriminator attempts to classify input it
receives as either fake or real. The discriminator starts out by classifying generator input as fake with a high
probability, but over time, the generator receives feedback from the discriminator and creates more realistic
looking images. The code for this process is found in the dlnd_face_generation Jupyter and HTML files.
