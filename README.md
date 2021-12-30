Made a small application by adapting chapter 2 of 'Deep Learning for Coders with fastai & PyTorch' to a different dataset.
The intent was to pull in the first 150 bing image search results for each of 'Magic the Gathering single card', 'YuGiOh single card', and 'Pokemon single card', to train a model based on resnet (via transfer learning). Based on the limited testing i've done with my own user supplied data (separate from the training or validation data sets), it seems to identify YuGiOh cards great. They've been relatively consistent throughout their print run as far as card layouts though, so this is not surprising. It seems to struggle a little more with MtG cards, but i'm sure this could be resolved with more careful selection of the data used in training.

As a concern in using the first 150 search results from the bing image search, I know I have some number of images that are showing boxed product and promotional images rather than the individual cards. Again, this could be resolved by using restraint when selecting data for training and validation.
                
URL:
https://mybinder.org/v2/gh/nstarr445/CardClassifierApp/main?urlpath=%2Fvoila%2Frender%2FCardClassifierApp.ipynb

binder page
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nstarr445/CardClassifierApp/main?urlpath=%2Fvoila%2Frender%2FCardClassifierApp.ipynb)
.. image:: https://mybinder.org/badge_logo.svg
 :target: https://mybinder.org/v2/gh/nstarr445/CardClassifierApp/main?urlpath=%2Fvoila%2Frender%2FCardClassifierApp.ipynb
