# Lab 2: Deep learning (DL)

This lab is part of our journey through the concepts and applications of deep learning in medicine and biomedical research.<br>
Some of the material has inspiration from and links to the work of great educators and researchers in the field, e.g. [Grant Sanderson](https://www.3blue1brown.com/about), [Daniel Bourke](https://www.mrdbourke.com/about), and [Andrej Karpathy](https://karpathy.ai)<br>
_update: 2025-01-18_

<!-- ![img](../assets/GPT-MedAI.png)<br> -->
<img src="../assets/GPT-MedAI.png" width="600"><br>
If you have a subscription to [ChatGPT Plus](https://openai.com/blog/chatgpt-plus), you can also try out the the [**Medical AI Assistant (UiBmed - ELMED219 & BMED365)**](https://chat.openai.com/g/g-d90dfN17H-medical-ai-assistant-uibmed-elmed219-bmed365) <br> [GPT](https://openai.com/blog/introducing-gpts) and see if you can get it to answer some of your questions. See also [_Q&A-in-the-wild_](./Q&A-in-the-wild.md)

## Slides 
<in progress ...>

<a href="https://docs.google.com/presentation/d/e/2PACX-1vRUu4XSPSOL6nHyeIpbJATMKvu4lWcjosw5sWUG3iDlNWbHTK-6MRj3VfxepE9Vw2CDM25dikA8XFuU/pub?start=false&loop=false&delayms=3000"><img src="./assets/Lab2_slide0_2025.png"></a>

-----

### Notebooks

| Notebook    |      1-Click Notebook     
|:----------|------|
|  [00a-CNN-basics.ipynb](https://nbviewer.org/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/00a-CNN-basics.ipynb)  <br>A short introduction to **CNNs** for medical students - an AI-assisted notebook prompted and created in "25 minutes" <br>with [cursor](https://www.cursor.com) and [claude-3.5-sonnet](https://www.anthropic.com/news/claude-3-5-sonnet)| [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/00a-CNN-basics.ipynb)<br>
|  [00b-Pytorch-Lightning-basics.ipynb](https://nbviewer.org/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/00b-Pytorch-Lightning-basics.ipynb)  <br>A short introduction to **Pytorch** and **Lightning** for medical students - an AI-assisted notebook prompted and created in "25 minutes" <br>with [cursor](https://www.cursor.com) and [claude-3.5-sonnet](https://www.anthropic.com/news/claude-3-5-sonnet)| [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/00b-Pytorch-Lightning-basics.ipynb)<br>
|  [01-MNIST-collect-organize.ipynb](https://nbviewer.org/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/01-MNIST-collect-organize.ipynb)  <br>MNIST data collection, inspection and organization. | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/01-MNIST-collect-organize.ipynb)<br>
|  [02-MNIST-Classification-with-Random-Forest.ipynb](https://nbviewer.org/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/02-MNIST-Classification-with-Random-Forest.ipynb)  <br>MNIST classification using Random Forest (flattening the 28x28 images to 1X784 pixel value vectors). | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/02-MNIST-Classification-with-Random-Forest.ipynb)<br>
|  [03-MNIST-Classification-with-MLP.ipynb](https://nbviewer.org/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/03-MNIST-Classification-with-MLP.ipynb)  <br>MNIST classification using a multilayer perceptron, MLP with 784 neurons in the input layer (flattening the 28x28 images to 1X784 pixel arrays), 2 hidden layers, and 10 neurons (one for each digit 0,...,9) in the output layer.  | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/03-MNIST-Classification-with-MLP.ipynb)<br>
|  [04-MNIST-Classifcation-with-CNN.ipynb]()  <br>MNIST classification using a convolutional neural network, CNN. Check the repo: [PyTorch-Lightning-MNIST-Classifier](https://github.com/sxg/PyTorch-Lightning-MNIST-Classifier)| [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)]()<br>
|  [05-BrainTumor-Segmentation.ipynb](https://nbviewer.org/github/MMIV-ML/fastMONAI/blob/master/nbs/10d_tutorial_multiclass_segmentation.ipynb)  <br>Brain tumor segmentation from multiparametric MRI data. Check the repo: [fastMONAI](https://fastmonai.no) | [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/fastMONAI/blob/master/nbs/10d_tutorial_multiclass_segmentation.ipynb)<br>
|  [06-TabPFN-explore.ipynb](https://nbviewer.org/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/06-TabPFN-explore.ipynb)  <br>Exploring deep learning analysis of tabular data with TabPFN.| [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/06-TabPFN-explore.ipynb)<br>
|  [07-TabPFN-neuro.ipynb](https://nbviewer.org/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/07-TabPFN-neuro.ipynb)  <br>Deep learning analysis of tabular data with TabPFN applied to neuroscience.| [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MMIV-ML/BMED365-2025/blob/main/Lab2-DL/notebooks/07-TabPFN-neuro.ipynb)<br>




</p>

## Learning motivations - watch these
(in the order of duration ...)

- _What is Deep Learning?_ (Deep Learning Tutorial For Beginners, 2023) by [Simplilearn](https://www.simplilearn.com)   -  [[link](https://youtu.be/6M5VXKLf4D4?si=L87yONRHjlTJMo0F)] (5:51 min)

- _But what is a neural network?_ by  [Grant Sanderson](https://www.3blue1brown.com/about) - [[link](https://youtu.be/aircAruvnKk?si=t_bPXdX1Zh0Z2VoC)] (18:39 min)
  - See also his 3Blue1Brown: _The basics of neural networks, and the math behind how they learn_ - https://www.3blue1brown.com/lessons/neural-networks - [code](https://github.com/3b1b/videos/blob/master/_2017/nn/part1.py)
  - and: _Gradient descent, how neural networks learn_ - [[link](https://youtu.be/IHZwWFHWa-w?si=uIrC21467xXQ2Tuw)] (20:33 min)
  - and: _Analyzing our neural network_ - [[link](https://www.3blue1brown.com/lessons/neural-network-analysis)]
  - and: _But what is a convolution?_ [[link](https://youtu.be/KuXjwB4LzSA?si=g1s-zIR-s2twmef1)]  (23:00 min)
  - and: _What is backpropagation really doing?_ [[link](https://youtu.be/Ilg3gGewQ5U?si=Tyl_x1oiq5PHtxel)] (12:46 min)
  - and: _Backpropagation calculus_ [[link](https://youtu.be/tIeHLnjs5U8?si=2TLpjbvcW9RgoejJ)] (10:17 min)
  - all made with his [Manim](https://github.com/3b1b/manim) engine - see his [TEDxBerkeley](https://youtu.be/s_L-fp8gDzY?si=udAe8y7Tbpln4U8b) talk ... (and also the ManimCE Example [Gallery](https://docs.manim.community/en/stable/examples.html))

- _Building a neural network FROM SCRATCH (no Tensorflow/Pytorch, just numpy & math)_ by Samson Zhang - [[link](https://youtu.be/w8yWXqWQYmU)]  (31:27 min)
  - [code](https://www.kaggle.com/code/wwsalmon/simple-mnist-nn-from-scratch-numpy-no-tf-keras/notebook)

- _Deep Learning State of the Art (anno 2019) - MIT_ by [Lex Fridman](https://en.wikipedia.org/wiki/Lex_Fridman) -  [[link](https://youtu.be/53YvP6gdD7U?si=xZegsW0rVFKz6lG7)] (46:24 min)

- _MIT Introduction to Deep Learning 6.S191: Lecture 1_ in Foundations of Deep Learning by [Alexander Amini](https://www.mit.edu/~amini)  - [[link](https://youtu.be/QDX-1M5Nj7s?si=3W467sl_b08ad-YR)] (58:11 min)
    - For all lectures, slides, and lab materials in [MIT 6.S191](https://twitter.com/MITDeepLearning) see http://introtodeeplearning.com and https://github.com/aamini/introtodeeplearning

- _The spelled-out intro to neural networks and backpropagation: building micrograd_ by [Andrej Karpathy](https://karpathy.ai) - [[link](https://youtu.be/VMj-3S1tku0?si=TRX02JJLExYoYObA)]   (2:21:51 hr)
    - "It only assumes basic knowledge of Python and a vague recollection of calculus from high school ..."
    -  micrograd on github: https://github.com/karpathy/micrograd
    -  Jupyter notebooks built in the video: https://github.com/karpathy/nn-zero-to-hero/tree/master/lectures/micrograd

- _Deep Learning Crash Course 2023_ | Learn Deep Learning Fundamentals In 5 Hours | [Simplilearn](https://www.simplilearn.com) -   [[link](https://youtu.be/CzBLfz89_60?si=M779kWYSnmQVgMwm)] (5:23:36 hr)

- _Learn PyTorch for deep learning in a day. Literally._ by [Daniel Bourke](https://www.mrdbourke.com/about) - [[link](https://youtu.be/Z_ikDlimN6A?si=TD1dob4O3dp0XjLE)] [5 Chapters](https://www.mrdbourke.com/pytorch-in-a-day) (25 hrs, 36 min and 57 sec long) 
    - For data, code, exercises, and slides  - https://github.com/mrdbourke/pytorch-deep-learning
    -  Read the course materials online - https://learnpytorch.io
 
- _Convolutional Neural Networks for Visual Recognition_ the CS231n course @ Stanford University by [Fei-Fei Li](https://en.wikipedia.org/wiki/Fei-Fei_Li) et al. [[link](http://vision.stanford.edu/teaching/cs231n)] (10-week course)
    - GitHub repo: https://github.com/cs231n/cs231n.github.io
    - Python Numpy Tutorial (with Jupyter and Colab): https://cs231n.github.io/python-numpy-tutorial
      


### How to get started?

You can read the Lab2-DL materials on any device but this course is best viewed and coded along within a desktop browser.

For the hands-on Lab, Google Colab can be used. If you have no experience with it, go through the free Introduction to [Google Colab tutorial](https://colab.research.google.com/notebooks/basic_features_overview.ipynb).

To dig into **Pytorch** and **tensors**:

- Click on link ["00. PyTorch Fundamentals"](https://www.learnpytorch.io/00_pytorch_fundamentals)
- Click the "Open in Colab" button up the top
- Press SHIFT+Enter a few times and see what happens

