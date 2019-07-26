* This jupyter notebook lives in https://github.com/tomsercu/gan-tutorial-pytorch
* [Launch on Google Colab!](https://colab.research.google.com/github/tomsercu/gan-tutorial-pytorch/blob/master/2019-04-23%20GAN%20Tutorial.ipynb)
* This tutorial was first presented at the [NYC AI & ML meetup](https://www.meetup.com/NYC-Artificial-Intelligence-Machine-Learning/events/260064765/) on April 23d 2019.

## Short abstract

This talk is a hands-on live coding tutorial. We will implement a Generative Adversarial Network (GAN) to learn to generate small images.
We will assume only a superficial familiarity with deep learning and a notion of PyTorch. This tutorial is as self-contained as possible. The goal is that this talk/tutorial can serve as an introduction to PyTorch at the same time as being an introduction to GANs.
GANs are a relatively recent development in unsupervised learning and generative modeling, where we want to learn the distribution of our data. Instead of fitting an explicit density model (with strong assumptions on the data distribution), GANs generate samples, defining an implicit density model. They are able to generate sharp samples from a (meaningful) continuous latent space.

The tutorial will be given in Jupyter notebook, fill-in the blank style. Participants are expected to bring laptops, with Jupyter + PyTorch 1.1.0 already installed (an alternative is to use google Colab).

Tutorial notebook in repository: https://github.com/tomsercu/gan-tutorial-pytorch
