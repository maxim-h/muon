Release notes
=============

.. contents:: :local:
    :depth: 3

.. toctree::
   :maxdepth: 10

   *


v0.1.1
------

* Fixes:

  * Fix reading ``.h5mu`` files in backed mode when modalities have ``.raw`` attributes.

* New features:
  
  * ATAC module
    
    * Handle fragments files with barcodes different than ``obs_names``.

v0.1.0
------

Initial ``muon`` release with ``MuData`` (:class:`muon.MuData`), ``atac`` and ``prot`` submodules (:mod:`muon.atac` and :mod:`muon.prot`), and multi-omics integration with ``MOFA`` (:func:`muon.tl.mofa`) and ``WNN`` (:func:`muon.pp.neighbors`).
