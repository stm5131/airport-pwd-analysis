# Comment Classifier for Airport review comments

This repository contains a jupyter notebook as well as some data to get started for comment downloading and analysis using an LLM. By default the python notebook uses BS4 and urllib for requrests but other methods can be used as well. It also defaults to using the MNLI trained BART model by Lewis et. al. as it performs well across chaotic data sets like the ones downloaded in this notebook. The overall code structure involves data download, data pre-processing, data anlysis for various sets of provided labels and then finally visualization and filtering.

Tested on Python 3.12.7
