# sparse-categorical-crossentropy

Access this notebook via Google colab: https://colab.research.google.com/github/rajdeep-biswas/sparse-categorical-crossentropy/blob/master/sparcat.ipynb.  
The last (training) step produces an error if connected to a CPU runtime but it trains (albeit with nan loss and 0 accuracy) if connected to a GPU runtime.

Probably has something to do with eager execution being disabled on GPU, but not entirely.
Source 1: https://github.com/googlecolab/colabtools/issues/262.
