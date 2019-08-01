Lots of papers has been trying to address the problem of posterior collapse with VAEs. Due to huge number of publications, I thought it is intersting to have a list of related papers. 

| Paper                                              | Implementation | Publication Year | Citation |
| ---------------------------------------------------| -------------- | ---------------- | -------- |
| Ladder variational autoencoders                    | Yes            |  2016            | 200+     |
| Fixing a broken ELBO                               | No             |  2017            | 70+      |
| Neural discrete representation learning            | Third Party    |  2017            | 128+     |
| Tackling Over-pruning in Variational Autoencoders  | No             |  2017            | 20+      |
| Filtering Variational Objectives                   | Yes             |  2017            | 60+      |
| Auxiliary Guided Autoregressive Variational Autoencoders | Third Party  |  2017            | 10-      |
| VAE with a VampPrior                               | Yes            |  2017            | 70+      |
| Z-Forcing: Training Stochastic Recurrent Networks  | Third Party    |  2017            | 40+      |
| Latent Space Optimal Transport for Generative Models                |  No             |  2018     | 10- |
| Improving explorability in variational inference with annealed variational objectives | No | 2018 | 10- |
| Taming VAEs                                        | No             |  2018            | 10+      |
| Semi-Amortized Variational Autoencoders            | No             |  2018            | 40+      |
| Avoiding Latent Variable Collapse with Generative Skip Models | No            |  2018            | 15+      |
| Spherical Latent Spaces for Stable Variational Autoencoders   |  Yes          |  2018     | 10+      |
| Unsupervised Discrete Sentence Representation Learning for Interpretable Neural Dialog Generation      | No             |  2018            | 10+      |
| Learning Latent Representations For Style Control And Transfer in End-To-End Speech Synthesis    | Third Party | 2018 | 10-|
| The Mutual Autoencoder: Controlling Information in Latent Code Representations  | No             |  2018            | 10-      |
| Hierarchicaly-Structured Variational Autoencoder For Long Text Generation     | No             |  2018            | 10-      |
| BIVA: A very deep hierarchy of latent variables for generative modeling         | No             |  2019            | 10-     |
|preventing posterior collapse with delta-VAEs                                   | No             |  2019            | 10-      |
| Diagnosing and enhancing VAE model                                              | No             |  2019            | 10-      |
| MAE: Mutual Posterior-Divergence Regularization For Variational Auto Encoder   | No             |  2019            | 10-      |
| Topic-Guided Variational Autoencoders for Text Generation                       | No             |  2019            | 10-      |
| Importance Weighted Hierarchical Variational Inference                          | No             |  2019            | 10-      |  
| Generated Loss, Augmented Training, And Multiscale VAE                          | No             |  2019            | 40+      |
| mμ-Forcing: Training Variational Recurrent Autoencoders for Text Generation     | No             |  2019            | 10-      |
| Dueling Decoders: Regularizing Variational Autoencoder Latent Spaces            | No             |  2019            | 10-      |
| Riemannian Normalizing Flow on Variational Wasserstein Autoencoder for Text Modeling    | No             |  2019    | 10-   |
| LIA: Latently Invertible Autoencoder with Adversarial Learning                  | Yes             |  2019            | 10-      |  
| Compound Variational Auto-Encoder                                               | No             |  2019            | 10-      |
| Quantization-Based Regularization for Autoencoders                              | No             |  2019            |  10-     |  
| Lagging Ingerence Network And Posterior Collapse In Variational Autoencoders    | Yes             |  2019            | 10+       |
| Cyclical Annealing Schedule: A Simple Approach to Mitigating KL Vanishing       | No             | 2019             | 10-       |
| Understanding Posterior Collapse in Generative Latent Variable Models           | No             | 2019             | 10-  |


Some papers observed posterior collapse for a particular task and tried to alleviate it mostly by KL-annealing: 

| Paper                                              | Implementation | Publication Year | Citation |
| ---------------------------------------------------| -------------- | ---------------- | -------- |
| Generating Sentences from a Continuous Space       | Third Party            |  2015            | 600+     |
| A Neural Representation of Sketch Drawings         | No             |  2017            | 150+      |
| Improved Variational Autoencoders for Text Modeling using Dilated Convolutions | Third Party |  2017   | 80+     |
| Diverse and Accurate Image Description Using a Variational Auto-Encoder with an Additive Gaussian Encoding Space                               | Thrid Party        |  2017            | 40+      |
| A Hierarchical Latent Vector Model for Learning Long-Term Structure in Music | Yes             |  2018            | 50+     |
| Improving Variational Encoder-Decoders in Dialogue Generation | Third Party  | 2018           | 50      |
| The challenge of realistic music generation: modelling raw audio at scale      | No             |  2018           | 20+      |
| Learning Product Codebooks Using Vector-Quantized Autoencoder For Image Retrieval | Yes           |  2018           | 20+      |
| Auto-Encoding Variational Neural Machine Translation             | No             |  2018           | 20+      |
| Trajectory-User Linking via Variational AutoEncoder              | No             |  2018           | 20+      |
| Structure-aware Generative Network for 3D-Shape Modeling         | No             |  2018           | 20+      |
| Auto-Encoding Variational Neural Machine Translation             | No             |  2018           | 20+      |
| Unsupervised speech representation learning using WaveNet autoencoders    | No             |  2019           | 10-   |
| Syntax-Infused Variational Autoencoder for Text Generation                | No             |  2019          | 10-   |
| Unsupervised Recurrent Neural Network Grammars                            | No             |  2019          | 10-   |
| Learning Latent Plans from Play                                           | No             | 2019             | 10-      |
| DialogWAE: Multimodal Response Generation With Conditional Wasserstein Auto-Encoder | No             | 2019             | 10-  |

Highly related papers but not exactly on Posterior Collapse:

| Paper                                              | Implementation | Publication Year | Citation |
| ---------------------------------------------------| -------------- | ---------------- | -------- |
| Adversarial Autoencoders                                            |  Third Party     | 2015     | 750+ | 
| Improved variational inference with inverse autoregressive flow     | Yes              |  2016            | 400+     |
| Stick-Breaking VAE                                 | No             |  2016            | 40+      |
| Variational lossy autoencoder                     | No             |  2016            | 190+      |
| Symmetrized Variational Inference    |  No        |  2016   | 10-     |
| ELBO surgery: yet another way to carve up the variational evidence lower bound  |  No          | 2017            | 70+      |
| Adversarially Regularized Autoencoders                                          | Yes             |  2018            | 60+      |
| Adversarial Symmetric Variational Autoencoder | No             |  2017            | 25+     |
| beta-VAE: Learning basic visual concepts with a constrained variational framework| Third Party |  2017   | 350+     |
| Distribution matching in variational inference     | Third Party    |  2017            | 15+      |
| Learning Latent Representations for Style Ccontrol And Transfer In end-to-end Speech Synthesis | Third Party  | 2018     |50+   |
| Wassertain Auto-Encoder: Latent Dimentionality And Random Encoders        | No             |  2018           | 10-      |
| Learning Deep Representation by Mutual Information Estimation And  Maximization  | No           |  2018           | 20+      |
| Sinkhorn AutoEncoders              | No             |  2018           | 10-      |
| Learning Priors for Adversarial Autoencoders       | No             |  2018           | 10-      |
| Hyperspherical Variational Auto-Encoders           | Yes | 2018 | 30+ |
| Universal Audio Synthesizer Control With Normalizing Flows       | Yes             |  2018           | 10-      |
| Representation Learning with Contrastive Predictive Coding       | Third Party     | 2018            | 50+      |
