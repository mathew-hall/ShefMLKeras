# Sheffield ML Keras Workshop

This workshop is designed to serve as a brief introduction to Deep Learning, using off-the shelf pre-trained convolutional neural networks for image classification.

Some caveats:

* This might not be the best way to do image classification! I've repurposed some old code from an old version of [FastAI's great course](http://course.fast.ai/), so head there after this workshop if you want to get more experience
* This isn't a rigorous introduction, but instead designed to capture a handful of neat intuitions (network topology, fine-tuning other people's networks, activations)
* This is definitely the wrong way to fine-tune networks: I've designed the workshop to run on commodity hardware, but you really need a GPU to train networks from scratch.

# Getting Started

The workshop is run out of a Jupyter notebook. You can choose to run the notebook on your own machine, or use an Azure notebook. If you're using your own machine, you'll need Python 3 at a bare minimum.

## Own Machine

The script `01-create-env.sh` will create a virtualenv and install the requisite packages. It will use pip to fetch everything, which almost definitely will result in slower builds of numpy and scipy. This takes a while, so if you can do this before you arrive at the meetup, you'll have a head start!