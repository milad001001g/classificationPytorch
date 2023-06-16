{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# PyTorch Tutorial by Modar\n",
    "\n",
    "Basic PyTorch classification tutorial with links and references to useful materials to get started.\n",
    "This tutorial was presented on the 6th of August 2018 as part of the [weekly meetings](https://github.com/IVUL-KAUST/GroupReading) of [IVUL-KAUST](http://ivul.kaust.edu.sa) research group.\n",
    "\n",
    "## Resources\n",
    " - [PyTorch Tutorials Page](https://pytorch.org/tutorials/)\n",
    " - [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)\n",
    " - [PyTorch Examples](https://github.com/pytorch/examples)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## PyTorch as GPU accelerated Numpy\n",
    "\n",
    " - [Most useful functions](https://pytorch.org/docs/stable/torch.html)\n",
    " - [torch.tensor == np.ndarray](https://pytorch.org/docs/stable/tensors.html)\n",
    "     - default types and auto-casting\n",
    "     - shapes and dimensions\n",
    "     - in-place vs output operations\n",
    " - [Moving into any GPU](https://pytorch.org/tutorials/beginner/blitz/data_parallel_tutorial.html#sphx-glr-beginner-blitz-data-parallel-tutorial-py)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    " ## PyTorch for Deep Learning\n",
    " \n",
    " - [Autograd](https://pytorch.org/tutorials/beginner/blitz/autograd_tutorial.html#)\n",
    " - [Modules](https://pytorch.org/tutorials/beginner/blitz/neural_networks_tutorial.html) (Neural Networks)\n",
    " - [Dealing with Data](https://pytorch.org/tutorials/beginner/data_loading_tutorial.html)\n",
    "   - [Dataset](https://pytorch.org/docs/stable/data.html#torch.utils.data.Dataset) and [ImageFolder](https://pytorch.org/docs/stable/torchvision/datasets.html#imagefolder)\n",
    "   - [Transforms](https://pytorch.org/docs/stable/torchvision/transforms.html)\n",
    "   - [DataLoader](https://pytorch.org/docs/stable/data.html#torch.utils.data.DataLoader)\n",
    "   - [Pinned vs. Pageable Memory](https://pytorch.org/docs/stable/data.html#torch.utils.data.DataLoader) (for CPU-GPU data transfer)\n",
    " - [Optimizers](https://pytorch.org/docs/stable/optim.html)"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## High-Level PyTorch Wrappers\n",
    "\n",
    "There exists high-level APIs for PyTorch analogous to Keras for Tensorflow such as:\n",
    "\n",
    " - [torchsample](https://github.com/ncullen93/torchsample)\n",
    " - [ignite](https://github.com/pytorch/ignite) (the official one)\n",
    " - [torchtools](https://github.com/Time1ess/torchtools)\n",
    " - [beauty-net](https://github.com/cms-flash/beauty-net)\n",
    " \n",
    "Also, it is not that hard to use tensorboard with PyTorch:\n",
    "\n",
    " - [simple example](https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/04-utils/tensorboard)\n",
    " - [tensorbaordX](https://github.com/lanpa/tensorboardX)"
   ]
  }
