# Welcome to the pyCoAn GitHub page

CoAn stands for Correlative Analysis of electron microscopy data.  CoAn was originally designed for correlation-based docking of atomic models into lower-resolution densities generated by electron microscopy and image reconstruction.  The distinguishing factor of the underlying docking methodology is the use of correlation statistics which explicitly accounts for measurement errors through cross-validation and allows the definition of confidence intervals for the rotational and translational parameters, thus defining a solution set of docked models, all of which are compatible with the data within their margin of error.

Since its inception, CoAn has grown significantly in scope to incorporate analysis algorithms including denoising, segmentation, and pattern recognition. It has now evolved into a python-based design framework, PyCoAn, similar in concept to Matlab, but tailor-made for Computational Analysis of electron microscopy data.  pyCoAn not only incorporates much of the functionality of the original CoAn package and its extensions, it also provides seamless access to a multitude of image- and data-processing software packages with a unified interface. This allows the end-user great flexibility in data analysis and allows him or her to focus on the questions at hand, rather than spending time figuring out how to reformat data from package A into something package B can use.  The functionality of the pyCoAn base distribution can be extended with separately distributed add-ons as well as standard Python modules. 

pyCoAn is in a constant state of ongoing development, as new algorithms get incorporated and more of the original algorithms are being refactored as Python modules, along with continued work on parallelizing compute-intensive tasks. 
