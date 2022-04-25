Lots of papers have been trying to address the problem of posterior collapse with VAEs. Due to huge number of publications, I thought it is intersting to have a list of related papers. 

| Paper                                              | Implementation | Publication Year | Citation | Link |
| ---------------------------------------------------| -------------- | ---------------- | -------- | ---- |
| Ladder variational autoencoders                    | Yes            |  2016            | 200+     | [Link](https://arxiv.org/abs/1602.02282) |
| Fixing a broken ELBO                               | No             |  2017            | 70+      | [Link](https://arxiv.org/abs/1711.00464) |
| Neural discrete representation learning            | Third Party    |  2017            | 128+     | [Link](https://arxiv.org/abs/1711.00937) |
| Tackling Over-pruning in Variational Autoencoders  | No             |  2017            | 20+      | [Link](https://arxiv.org/abs/1706.03643) |
| Filtering Variational Objectives                   | Yes             |  2017            | 60+      | [Link](https://arxiv.org/abs/1705.09279) |
| Auxiliary Guided Autoregressive Variational Autoencoders | Third Party  |  2017            | 10-      | [Link](https://arxiv.org/abs/1711.11479) |
| VAE with a VampPrior                               | Yes            |  2017            | 70+      | [Link](https://arxiv.org/abs/1705.07120) |
| Z-Forcing: Training Stochastic Recurrent Networks  | Third Party    |  2017            | 40+      | [Link](https://arxiv.org/abs/1711.05411) |
| Latent Space Optimal Transport for Generative Models                |  No             |  2018     | 10- | [Link](https://arxiv.org/abs/1809.05964) |
| Improving explorability in variational inference with annealed variational objectives | No | 2018 | 10- | [Link](https://arxiv.org/abs/1809.01818) |
| Taming VAEs                                        | No             |  2018            | 10+      | [Link](https://arxiv.org/abs/1810.00597) |
| Semi-Amortized Variational Autoencoders            | No             |  2018            | 40+      | [Link](https://arxiv.org/abs/1802.02550) |
| Avoiding Latent Variable Collapse with Generative Skip Models | No            |  2018            | 15+      | [Link](https://arxiv.org/abs/1807.04863) |
| Spherical Latent Spaces for Stable Variational Autoencoders   |  Yes          |  2018     | 10+      | [Link](https://arxiv.org/abs/1808.10805) |
| Unsupervised Discrete Sentence Representation Learning for Interpretable Neural Dialog Generation      | No             |  2018            | 10+      | [Link](https://arxiv.org/abs/1804.08069) |
| Learning Latent Representations For Style Control And Transfer in End-To-End Speech Synthesis    | Third Party | 2018 | 10-| [Link](https://arxiv.org/abs/1812.04342) |
| The Mutual Autoencoder: Controlling Information in Latent Code Representations  | No             |  2018            | 10-      | [Link](https://openreview.net/forum?id=HkbmWqxCZ) |
| Hierarchicaly-Structured Variational Autoencoder For Long Text Generation     | No             |  2018            | 10-      | [Link](https://openreview.net/forum?id=Hk41X2AqtQ) |
| Iterative Amortized Inference                                                   | No             |2018              |20+ | [Link](https://arxiv.org/abs/1807.09356) |
| BIVA: A very deep hierarchy of latent variables for generative modeling         | No             |  2019            | 10-    | [Link](https://arxiv.org/abs/1902.02102) |
| Preventing posterior collapse with delta-VAEs                                   | No             |  2019            | 10-      | [Link](https://arxiv.org/abs/1901.03416) |
| Diagnosing and enhancing VAE model                                              | No             |  2019            | 10-      | [Link](https://arxiv.org/abs/1903.05789) |
| MAE: Mutual Posterior-Divergence Regularization For Variational Auto Encoder   | No             |  2019            | 10-      | [Link](https://arxiv.org/abs/1901.01498) |
| Topic-Guided Variational Autoencoders for Text Generation                       | No             |  2019            | 10-      | [Link](https://arxiv.org/abs/1903.07137) |
| Importance Weighted Hierarchical Variational Inference                          | No             |  2019            | 10-      | [Link](https://arxiv.org/abs/1905.03290) |
| Generated Loss, Augmented Training, And Multiscale VAE                          | No             |  2019            | 40+      | [Link](https://arxiv.org/abs/1904.10446) |
| mμ-Forcing: Training Variational Recurrent Autoencoders for Text Generation     | No             |  2019            | 10-      | [Link](https://arxiv.org/abs/1905.10072) |
| Dueling Decoders: Regularizing Variational Autoencoder Latent Spaces            | No             |  2019            | 10-      | [Link](https://arxiv.org/abs/1905.07478) |
| Riemannian Normalizing Flow on Variational Wasserstein Autoencoder for Text Modeling    | No             |  2019    | 10-   | [Link](https://arxiv.org/abs/1904.02399) |
| LIA: Latently Invertible Autoencoder with Adversarial Learning                  | Yes             |  2019            | 10-      | [Link](https://openreview.net/forum?id=ryefE1SYDr) |
| Compound Variational Auto-Encoder                                               | No             |  2019            | 10-      | [Link](https://ieeexplore.ieee.org/document/8683633) |
| Quantization-Based Regularization for Autoencoders                              | No             |  2019            |  10-     | [Link](https://arxiv.org/abs/1905.11062) |
| Lagging Ingerence Network And Posterior Collapse In Variational Autoencoders    | Yes             |  2019            | 10+       | [Link](https://arxiv.org/abs/1901.05534) |
| Cyclical Annealing Schedule: A Simple Approach to Mitigating KL Vanishing       | No             | 2019             | 10-       | [Link](https://arxiv.org/abs/1903.10145) |
| Understanding Posterior Collapse in Generative Latent Variable Models           | No             | 2019             | 10-  | [Link](https://openreview.net/forum?id=r1xaVLUYuE) |


Some papers observed posterior collapse for a particular task and tried to alleviate it mostly by KL-annealing: 

| Paper                                              | Implementation | Publication Year | Citation | Link |
| ---------------------------------------------------| -------------- | ---------------- | -------- | ---- |
| Generating Sentences from a Continuous Space       | Third Party            |  2015            | 600+     | [Link](https://arxiv.org/abs/1511.06349) |
| A Neural Representation of Sketch Drawings         | No             |  2017            | 150+      | [Link](https://arxiv.org/abs/1704.03477) |
| Improved Variational Autoencoders for Text Modeling using Dilated Convolutions | Third Party |  2017   | 80+     | [Link](https://arxiv.org/abs/1702.08139) |
| Diverse and Accurate Image Description Using a Variational Auto-Encoder with an Additive Gaussian Encoding Space                               | Thrid Party        |  2017            | 40+      | [Link](https://arxiv.org/abs/1711.07068) |
| A Hierarchical Latent Vector Model for Learning Long-Term Structure in Music | Yes             |  2018            | 50+     | [Link](https://arxiv.org/abs/1803.05428) |
| Improving Variational Encoder-Decoders in Dialogue Generation | Third Party  | 2018           | 50      | [Link](https://arxiv.org/abs/1802.02032) |
| The challenge of realistic music generation: modelling raw audio at scale      | No             |  2018           | 20+      | [Link](https://arxiv.org/abs/1806.10474) |
| Learning Product Codebooks Using Vector-Quantized Autoencoder For Image Retrieval | Yes           |  2018           | 20+      | [Link](https://arxiv.org/abs/1807.04629) |
| Auto-Encoding Variational Neural Machine Translation             | No             |  2018           | 20+      | [Link](https://arxiv.org/abs/1807.10564) |
| Trajectory-User Linking via Variational AutoEncoder              | No             |  2018           | 20+      | [Link](https://www.ijcai.org/proceedings/2018/446) |
| SAGNet: Structure-aware Generative Network for 3D-Shape Modeling         | No             |  2018           | 20+      | [Link](https://arxiv.org/abs/1808.03981) |
| Unsupervised speech representation learning using WaveNet autoencoders    | No             |  2019           | 10-   | [Link](https://arxiv.org/abs/1901.08810) |
| Syntax-Infused Variational Autoencoder for Text Generation                | No             |  2019          | 10-   | [Link](https://arxiv.org/abs/1906.02181) |
| Unsupervised Recurrent Neural Network Grammars                            | No             |  2019          | 10-   | [Link](https://arxiv.org/abs/1904.03746) |
| Learning Latent Plans from Play                                           | No             | 2019             | 10-      | [Link](https://arxiv.org/abs/1903.01973) |
| DialogWAE: Multimodal Response Generation With Conditional Wasserstein Auto-Encoder | No             | 2019             | 10-  | [Link](https://arxiv.org/abs/1805.12352) |

Highly related papers but not exactly on Posterior Collapse:

| Paper                                              | Implementation | Publication Year | Citation | Link |
| ---------------------------------------------------| -------------- | ---------------- | -------- | ---- |
| Adversarial Autoencoders                                            |  Third Party     | 2015     | 750+ | [Link](https://arxiv.org/abs/1511.05644) |
| Improved variational inference with inverse autoregressive flow     | Yes              |  2016            | 400+     | [Link](https://arxiv.org/abs/1606.04934) |
| Stick-Breaking Variational Autoencoders                                 | No             |  2016            | 40+      | [Link](https://arxiv.org/abs/1605.06197) |
| Variational lossy autoencoder                     | No             |  2016            | 190+      | [Link](https://arxiv.org/abs/1611.02731) |
| Symmetrized Variational Inference    |  No        |  2016   | 10-     | [Link](http://approximateinference.org/2016/accepted/Moore2016.pdf) |
| ELBO surgery: yet another way to carve up the variational evidence lower bound  |  No          | 2017            | 70+      | [Link](http://approximateinference.org/accepted/HoffmanJohnson2016.pdf) |
| Adversarially Regularized Autoencoders                                          | Yes             |  2018            | 60+      | [Link](https://arxiv.org/abs/1706.04223) |
| Adversarial Symmetric Variational Autoencoder | No             |  2017            | 25+     | [Link](https://arxiv.org/abs/1711.04915) |
| beta-VAE: Learning basic visual concepts with a constrained variational framework| Third Party |  2017   | 350+     | [Link](https://openreview.net/forum?id=Sy2fzU9gl) |
| Distribution matching in variational inference     | Third Party    |  2017            | 15+      | [Link](https://arxiv.org/abs/1802.06847) |
| Learning Latent Representations for Style Control And Transfer In end-to-end Speech Synthesis | Third Party  | 2018     |50+   | [Link](https://arxiv.org/abs/1812.04342) |
| Wassertain Auto-Encoder: Latent Dimentionality And Random Encoders        | No             |  2018           | 10-      | [Link](https://openreview.net/forum?id=r157GIJvz) |
| Learning Deep Representation by Mutual Information Estimation And  Maximization  | No           |  2018           | 20+      | [Link](https://arxiv.org/abs/1808.06670) |
| Sinkhorn AutoEncoders              | No             |  2018           | 10-      | [Link](https://arxiv.org/abs/1810.01118) |
| Learning Priors for Adversarial Autoencoders       | No             |  2018           | 10-      | [Link](https://arxiv.org/abs/1909.04443) |
| Hyperspherical Variational Auto-Encoders           | Yes | 2018 | 30+ | [Link](https://arxiv.org/abs/1804.00891) |
| Universal Audio Synthesizer Control With Normalizing Flows       | Yes             |  2018           | 10-      | [Link](https://arxiv.org/abs/1907.00971) |
| Representation Learning with Contrastive Predictive Coding       | Third Party     | 2018            | 50+      | [Link](https://arxiv.org/abs/1807.03748) |
