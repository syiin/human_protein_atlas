# Human Protein Atlas Challenge

Managed to finish in the Top 12%

The various iterations and notes along the way to create a convolutional neural network that to recognise proteins found on microscopy staining images. 

Used the FastAI library to get started quickly as well as the pretrained models: https://github.com/Cadene/pretrained-models.pytorch.

Things done well:
1. Pulled together the minimum needed quickly to start iterating and experimenting. 
2. Held 1st place for sometime in the earlier months 
3. Managed to try a range of fancier techniques like the 1-cycle training policy, cosine annealing...etc

Things not done so well:
1. The larger SENet-154 architecture being trained at the later notebooks did not outperform the smaller simpler networks
2. Did not use the extra leaked data - insufficient hard drive space
3. Could have experimented more with oversampling

Considered leaving the trained models out of the repo but figured perhaps someone using either ResNext50 or SENet-154 may one day find these useful. 

WARNING: this is obviously not very tidy organised Jupyter notebook but I completed this project in spare time in the evenings. While some notes are maintained here, I kept most notes on a hand written book so it may be confusing to follow the train of thought. 
