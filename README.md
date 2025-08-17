# Portfolio

## Education
- B.E., Computer Science: Birla Institute of Technology and Science, Pilani
- Relevant Coursework: Generative AI, Introduction to LLMs, Natural Language Processing, Deep Learning, Linear Algebra, Probability & Statistics

---

## Experience
- ### Research on Computational Photography using Federated Learning (Aug. 2024 – May 2025)
Research under [Prof. Pratik Narang](https://www.bits-pilani.ac.in/pilani/pratik-narang/) related to augmenting computational photography tasks, specifically denoising, with federated learning techniques to solve the problem of limited noisy-clean image pair data. During this project, I worked on training and evaluating established approaches like DnCNN, DBSN, and Blind2Unblind on custom noise models in federated setups. 
<img width="500" height="167" alt="denoising_result" src="https://github.com/user-attachments/assets/c254e7a2-bb27-49ad-a514-7afb48932fc5" />



- ### [Research on Crime Detection in Surveillance Videos](https://github.com/droy824/anomaly_detection/) (Nov. 2023 – May 2024)
Worked on the task of detecting and classifying 10 crime types in the UCF-Crime dataset using YOLOv3 and DeepSORT. We preprocessed 1000+ videos, then designed, trained, and tuned an LSTM model, achieving an AUC score of 62.5%, approaching state-of-the-art performance. 
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/305f85c1-54b6-4be6-995f-be58355cbc75" />



- ### Software Engineering Intern @ Stripe (May 2025 - Jul. 2025)
Saved $200K per annum by reducing 700K manual verifications for merchant addresses using LLMs. Conducted prompt engineering experiments with 1,000 user addresses to reduce the LLM’s false rejection rate to <2%. Also created an abstract framework to reduce time to create new LLM verification systems from ∼2 weeks to ∼1 day.

---

## Projects
- ### 3D Semantic Segmentation of EPFL Electron Microscopy Dataset
Solved 3D segmentation task on the [EPFL Electron Microscopy Dataset](https://www.epfl.ch/labs/cvlab/data/data-em/) using [Morphological Post-Processing](https://ieeexplore.ieee.org/document/9761519), [nnU-Net](https://arxiv.org/abs/1809.10486), and [Foundation Models](https://arxiv.org/abs/2306.16925). After producing a strong baseline Dice score of 94.05% with nnU-Net, I experimented with MIS-FM. Here, I pre-trained PCT-Net using Volume Fusion on the unannotated volume, achieving Dice of 99.93% on the pretext task. To tune downstream training, I analysed and experimented with preprocessing, Focal Dice, schedulers, postprocessing, increasing the Dice score from 42% to 93%.
<img width="448" height="121" alt="Screenshot 2025-08-17 at 1 44 32 AM" src="https://github.com/user-attachments/assets/5fee0a27-cef8-4eb6-91cd-27c209c494fd" />



- ### [Implementation of Conditional PixelVAE, PixelCNN for Handwritten Digit Generation](https://github.com/droy824/pixelcnn-in-pytorch)
Implemented the [PixelCNN](https://arxiv.org/abs/1601.06759), [conditional PixelCNN](https://arxiv.org/abs/1606.05328), and [PixelVAE](https://arxiv.org/abs/1611.05013) architectures. I also extended the PixelVAE architecture by creating a conditional PixelVAE. This network achieved strong quantitative performance on binarised MNIST dataset with an average NLL of 0.169 nats per pixel.
<img width="395" height="395" alt="image" src="https://github.com/user-attachments/assets/827aee43-19bf-4d1e-a481-2087a175c094" />



- ### [From-Scratch Neural Learning in NumPy via Adam Optimisation](https://github.com/droy824/neural-networks-with-numpy)
Built forward/backward passes with analytical gradients and gradient descent to study neural learning without frameworks. During this study, I also re-constructed the Adam optimiser from scratch, yielding 100% test accuracy. Finally, I visualised the model's predictions via decision boundaries.
<img width="495" height="225" alt="image" src="https://github.com/user-attachments/assets/e3ee10d9-b7c1-46df-a4b2-920abba78a42" />
