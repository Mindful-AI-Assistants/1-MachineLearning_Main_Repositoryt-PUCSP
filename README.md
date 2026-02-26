
<br>

**\[[🇧🇷 Português](README.pt_BR.md)\] \[**[🇺🇸 English](README.md)**\]**

<br><br>


#  <p align="center"> 1- [Machine Learning]() / [Main Repository]()

Main repo for PUC-SP 5th semester Machine Learning course (2026): weekly classes, PyTorch/TensorFlow notebooks, CNN/RNN/GAN projects, seminars, and extensionist social initiatives by Prof. Roney Coelho.

<!-- ======================================= Start DEFAULT HEADER ===========================================  -->

<br><br>


# Machine Learning Integrated Project - PUC-SP 5th Semester (2026) 🤖🧠


This is the **MAIN ML REPO** for all weekly classes, notes, Jupyter notebooks, code examples (PyTorch & TensorFlow), projects, and seminars. Organized by the official syllabus to house **every single weekly lesson** from February to June 2026. Future sub-repos (e.g., for specific projects) will link back here.

## What is Machine Learning? (Kid-Friendly Explanation) 🌈
Imagine teaching a robot puppy to fetch a ball. You show it many examples (data), it tries, makes mistakes, and gets better each time – without you telling it every single step. That's Machine Learning (ML)! Computers learn patterns from data, like how kids learn by playing and trying.  

**Key topics here:**  
- **Neural Networks**: Like a brain made of tiny math "neurons" connected together. They guess answers and fix mistakes automatically.  
- **MLP (Multilayer Perceptron)**: A simple "brain" with layers – input (sees data), hidden (thinks), output (decides). Like stacking Lego blocks to solve puzzles.  
- **CNN (Convolutional Neural Networks)**: Super for pictures! Spots edges, shapes, then faces – like your eyes scanning a photo. Great for cat vs. dog pics.  
- **Frameworks**: PyTorch (fast on Apple M-series chips, feels like Python magic) and TensorFlow (Google's tool, runs anywhere). They build these "brains" without supercomputers. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)

No need for Excel – ML learns on its own!

## Table of Contents
- [Course Objectives](#course-objectives)
- [Weekly Classes](#weekly-classes)
- [Assessment](#assessment)
- [Bibliographic References](#bibliographic-references)
- [Sub-Repositories](#sub-repositories)
- [How to Use This Repo](#how-to-use-this-repo)
- [Professor Info](#professor-info)

## Course Objectives
Present basic and advanced concepts of artificial neural networks (ANNs), their biological inspiration, and real-world applications. Focus on building practical systems with supervised/unsupervised models like MLPs, CNNs, RNNs, GANs, and Reinforcement Learning. Includes extensionist projects for social good (open-source repos for communities). [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)

## Weekly Classes
All materials (slides, code, notebooks) go in folders like `/week-1/`, `/week-2/`, etc. Update as classes happen.

| Week | Date       | Topic Summary                                                                 | Notes/Files Placeholder                  |
|------|------------|-------------------------------------------------------------------------------|------------------------------------------|
| 1    | 19 Feb    | Introduction to Machine Learning                                              | `/week-1/intro-ml.ipynb`     |
| 2    | 26 Feb    | What are neural networks? Intro to Perceptron. Basic shallow NN model.        | `/week-2/perceptron/`          |
| 3    | 05 Mar    | Supervised training: Loss functions, hyperparameter tuning.                   | `/week-3/training/`              |
| 4    | 12 Mar    | Building shallow NNs with TensorFlow & PyTorch (dense layers).                | `/week-4/tf-pytorch/`         |
| 5    | 19 Mar    | Evaluating shallow NNs: Metrics. Loading data (CSV, HDF5, images).            | `/week-5/evaluation/`        |
| 7    | 02 Apr    | Academic recess (Easter). No class.                                           | -                                        |
| 8    | 09 Apr    | Continued: Preprocessing & advanced NNs in PyTorch/TensorFlow.                | `/week-8/advanced-nns/`      |
| 9    | 16 Apr    | **Seminar 1**                                                                 | `/seminar-1/`  |
| 10   | 23 Apr    | CNNs: Intro, convolutions, pooling, fully connected layers.                   | `/week-10/cnn-intro/`          |
| 11   | 30 Apr    | Training CNNs: Loss, optimizers, regularization (dropout, L1/L2), transfer learning. | `/week-11/cnn-training/`     |
| 12   | 07 May    | CNN apps: Image classification, detection, segmentation. Data aug, visualization. | `/week-12/cnn-apps/`     |
| 13   | 14 May    | RNNs intro: LSTM/GRU layers, info flow, training.                             | `/week-13/rnns/`                 |
| 14   | 21 May    | Encoder-Decoder: Machine translation, text generation. Training challenges.   | `/week-14/encoder-decoder/`      |
| 15   | 28 May    | GANs intro: Generator vs. Discriminator, training.                            | `/week-15/gans/`                  |
| 16   | 04 Jun    | National Holiday (Corpus Christi). No class.                                  | -                                        |
| 17   | 11 Jun    | Reinforcement Learning: Agents, Markov processes, Q-Learning, SARSA.          | `/week-17/rl/`  [               |
| 18   | 18 Jun    | **Seminar 2**                                                                 | `/seminar-2/`                   |  

## Assessment
- **Seminar 1 (16 Apr 2026)**: Individual, weight 0.5. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)
- **Seminar 2 (18 Jun 2026)**: Individual, weight 0.5. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)
Methods: Dialogued lectures, TF/PyTorch projects, active methodologies, continuous evals.


## How to Use This Repo
1. Clone: `git clone https://github.com/yourusername/PUC-SP-ML-Integrated-Project-2026.git`.  
2. Add weekly folders with `README.md`, `.ipynb`, `.py` files.  
3. For PyTorch (local/Apple M): `pip install torch`. Fast on M-chips!  
4. TensorFlow: `pip install tensorflow`.  
5. Run notebooks in Colab or Jupyter. Share publicly for extensionist credit. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)

## Professor Info
**Rooney Ribeiro Albuquerque Coelho** – Expert in neural networks, PyTorch/TensorFlow, practical ML projects. Contact via PUC-SP. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)

## Bibliographic References
### Basic
- NETTO, A.; MACIEL, F. *Python for data science and machine learning made simple*. Alta Books, 2021. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)
- SILVA, F. M. da et al. *Artificial Intelligence: Applications in various human activities*. Sagah, 2019. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)
- WITTEN, I. H. et al. *Artificial Intelligence: A machine learning approach*. LTC, 2021. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)

### Complementary
- BIFET, A. et al. *Machine learning for data streams*. MIT Press, 2018. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)
- CANO, A. *Social media and machine learning*. IntechOpen, 2020. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)
- HUTTER, F.; KOTTHOFF, L.; VANSCHOREN, J. *Automated machine learning: methods, systems, challenges*. Springer Nature, 2019. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)
- SUD, K. et al. *Introduction to data science and machine learning*. IntechOpen, 2020. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)
- THOMAS, C. *Data mining*. IntechOpen, 2018. [ppl-ai-file-upload.s3.amazonaws](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/27709701/4adbb447-9791-40cd-b7a9-7fa61628bcb5/1-PROGRAM-CONTENT.pdf)

