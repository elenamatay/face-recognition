# Face Recognition


**Purpose:** Build a face recognition system. This is a programming assignment that is part of the Convolutional Neural Networks course within the [Deep Learning Specialization by deeplearning.ai](https://www.deeplearning.ai/courses/deep-learning-specialization/#syllabus).

**Date:** 29 Dec 2024

**By:** Elena (authoring exercises solution code only).

## Overview
In this notebook, I built a face recognition system. Many of the ideas presented here are from [FaceNet](https://arxiv.org/pdf/1503.03832.pdf). Steps performed:

* Differentiate between face recognition and face verification
* Implement one-shot learning to solve a face recognition problem
* Apply the triplet loss function to learn a network's parameters in the context of face recognition
* Explain how to pose face recognition as a binary classification problem
* Map face images into 128-dimensional encodings using a pretrained model
* Perform face verification and face recognition with these encodings

## Key File
Notebook titled `Face_Recognition.ipynb`


## How to Use
1. Clone the repository:
```
git clone https://github.com/elenamatay/face-recognition.git
```

2. Set up the environment by installing the required dependencies:
```
pip install -r requirements.txt
```

3. Run the Jupyter notebook