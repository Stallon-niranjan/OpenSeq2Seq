:github_url: https://github.com/NVIDIA/OpenSeq2Seq

.. toctree::
   :hidden:
   :maxdepth: 2

   Introduction <self>
   installation-instructions
   getting-started
   models-and-recipes
   distr-training
   mixed-precision
   in-depth-tutorials
   api-docs/modules


OpenSeq2Seq
===========

*This is a research project, not an official product by NVIDIA*

OpenSeq2Seq is a toolkit for efficient experimentation with various sequence-to-sequence models.


**Main features**:

* Distributed training: multi-GPU and multi-node support.

* A built-in support for efficient mixed-precision training on GPUs.

* Modular design and flexible configuration makes it easy to build new models and 
  experiment with different encoder-decoder
  combinations - you can combine CNN-based encoder with RNN-based decoder, etc.

* Supports different input-output modalities: speech-to-text, text-to-text and designed to be extended with new ones.


OpenSeq2Seq is built using TensorFlow. To start using this toolkit, look at the
:ref:`installation instructions <installation-instructions>` and then
see the :ref:`getting started <getting-started>` page. For more detailed
tutorials you can look into :ref:`in-depth tutorials <in_depth>` section.
If you are already familiar with the basics and have
everything set up, check out the list of available
:ref:`models and recipes <models_and_recipes>`. You can also find some useful
information in the :ref:`mixed precision training <mixed_precision>` and
:ref:`distributed training <distributed_training>` sections or look through our
:ref:`API documentation <api-docs>`.
