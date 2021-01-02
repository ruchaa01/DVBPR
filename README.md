# Visually-Aware Fashion Recommendation andPersonalized Fashion Item Generation
This repo contains much of the code written by the original authors of the paper. [1]
As a record of specific changes in the DVBPR section to incorporate the lower resolution images and images containing customer reviewed photos, track history has been turned on.

[1] Wang-Cheng Kang, Chen Fang, Zhaowen Wang, Julian McAuley. *[Visually-Aware Fashion Recommendation and Design with Generative Image Models.](http://cseweb.ucsd.edu/~jmcauley/pdfs/icdm17.pdf)* In Proceedings of IEEE International Conference on Data Mining (ICDM'17)


The author provides three modules in our framework: 

- **Deep Visually-Aware Bayesian Personalized Ranking (DVBPR):** Jointly learn user latent factors and extract task-guided visual features from implicit feedback for fashion recommendation.
- **GANs:** A conditional generative adversarial network for fashion generation.
- **Preference Maximization:** Adjust generated images that match a user's personal taste better (personalized fashion design).

Requirements:

- TensorFlow 1.3
- Numpy
- PIL

As a use case of a different dataset, a report has also been uploaded to this repository that gives a detail overviw of changes that have been made from the original code in terms of hyperparameters and architecture.
