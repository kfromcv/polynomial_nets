=======================================
Π-nets: Deep Polynomial Neural Networks
=======================================

.. image:: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
	:target: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg
	:alt: License

Official implementation of several experiments in the paper `"**Π-nets: Deep Polynomial Neural Networks**" <https://openaccess.thecvf.com/content_CVPR_2020/papers/Chrysos_P-nets_Deep_Polynomial_Neural_Networks_CVPR_2020_paper.pdf>`_ and its `extension <https://arxiv.org/abs/2006.13026>`_.

Each folder contains a different experiment. Please follow the instructions 
in the respective folder on how to run the experiments and reproduce the results. 
`This repository <https://github.com/grigorisg9gr/polynomial_nets>`_ contains implementations in `MXNet <https://mxnet.apache.org/>`_, `PyTorch <https://pytorch.org/>`_ and `Chainer <https://chainer.org/>`_.



Browsing the experiments
========================
The folder structure is the following:

*    ``face_recognition``: The folder contains the code for the `face verification and identification experiments <https://github.com/grigorisg9gr/polynomial_nets/tree/master/face_recognition>`_.

*    ``image_generation_chainer``: The folder  contains the `image generation experiment on Chainer <https://github.com/grigorisg9gr/polynomial_nets/tree/master/image_generation_chainer>`_; specifically the experiment without activation functions between the layers.

*    ``image_generation_pytorch``: The folder contains the `image generation experiment on PyTorch <https://github.com/grigorisg9gr/polynomial_nets/tree/master/image_generation_pytorch>`_; specifically the conversion of a DCGAN-like generator into a polynomial generator.

*    ``mesh_pi_nets``: The folder contains the code for `mesh representation learning <https://github.com/grigorisg9gr/polynomial_nets/tree/master/mesh_pi_nets>`_ with polynomial networks.




Citing
======
If you use this code, please cite [1]_:

*BibTeX*:: 

  @inproceedings{
  poly2020,
  title={$\Pi-$nets: Deep Polynomial Neural Networks},
  author={Chrysos, Grigorios and Moschoglou, Stylianos and Bouritsas, Giorgos and Panagakis, Yannis and Deng, Jiankang and Zafeiriou, Stefanos},
  booktitle={Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2020}
  }
  
References
==========

.. [1] Grigorios G. Chrysos, Stylianos Moschoglou, Giorgos Bouritsas, Yannis Panagakis, Jiankang Deng and Stefanos Zafeiriou, **Π-nets: Deep Polynomial Neural Networks**, *Conference on Computer Vision and Pattern Recognition (CVPR)*, 2020.


