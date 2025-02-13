---
title: Home
layout: home
nav_order: 1
tags: [Computer Science Dept., Ferdowsi University of Mashhad, علوم کامپیوتر دانشگاه فردوسی مشهد]
---


Ferdowsi University of Mashhad, Fall 2024 (1403 SH)
{: .mb-2}

Deep Learning Course
{: .mb-0 .fs-6 .text-grey-dk-000 }


<div>
{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
  <div class="role">
    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>
</div>

# About
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Course policies and information


Welcome to our website dedicated to Deep Learning Course! 
Deep learning is a subfield of machine learning that uses algorithms inspired by the structure and function of the human brain, called artificial neural networks. In this course, you will learn the basics of deep learning, and build your own deep neural networks using **PyTorch**.  You’ll gain hands-on experience with PyTorch through coding exercises and projects that involve classification and regression tasks. PyTorch is a widely used deep learning framework in academia, enabling you to leverage the power of GPUs and other accelerators. Additionally, it offers an automatic differentiation library, which is invaluable for implementing neural networks.

Here, Learning is done by Doing :)


## Class time and Location

Saturday 10:00-11:30 and Monday 8:00-9:30* (Fall 2024), Room XX.


## References

This course uses various resources to teach the concepts and applications of deep learning. Some of these resources are:

- [**Learn PyTorch for Deep Learning: Zero to Mastery book**](https://www.learnpytorch.io/)
- [Neural Networks, FUM](https://fum-cs.github.io/neural-networks)
- [Deep Learning Course, FUM, Fall 2023](https://fum-cs.github.io/dl-fall-2023)
  * [Convolution Slides](https://mamintoosi-cs.github.io/slides/topics/DL-TF/Chapter8-Introductio-to-Deep-learning-for-Computer-Vision.html)
- [Polo Club of Data Science](https://poloclub.github.io/)
- [Deep Learning with Python](https://www.manning.com/books/deep-learning-with-python-second-edition)
   by François Chollet, Second Edition, 2021
   * [Jupyter notebooks for the code samples of the book "Deep Learning with Python"](https://github.com/fchollet/deep-learning-with-python-notebooks)
- [Hands On Machine Learning with Scikit-Learn, Keras, and TensorFlow Concepts, Tools, and Techniques to Build Intelligent Systems-O'Reilly Media](https://www.oreilly.com/library/view/hands-on-machine-learning/9781492032632/), [Book](https://cloudflare-ipfs.com/ipfs/bafykbzaceae4tae6nlan27vd2g2df7mtkp7ikzs4bhywu4c7awmy6fhj2fk4w?filename=Aur%C3%A9lien%20G%C3%A9ron%20-%20Hands-On%20Machine%20Learning%20with%20Scikit-Learn%2C%20Keras%2C%20and%20TensorFlow_%20Concepts%2C%20Tools%2C%20and%20Techniques%20to%20Build%20Intelligent%20Systems-O%27Reilly%20Media%20%282022%29.pdf) by Aurélien Géron, 2022, Part II.
- [Dive into Deep Learning](https://d2l.ai/): A free online book that teaches deep neural networks using PyTorch and TensorFlow. [Discuss](https://discuss.d2l.ai/)
- [Introduction to Deep Learning](http://introtodeeplearning.com/): A course from MIT that covers the foundations of deep learning and its applications to computer vision, natural language processing, generative models, and reinforcement learning.
- [CS230 Deep Learning](https://cs230.stanford.edu/): A course from Stanford that focuses on the practical aspects of deep learning, such as how to design, train, debug, and deploy neural networks.
- [CS231n Convolutional Neural Networks for Visual Recognition](http://cs231n.stanford.edu/): A course from Stanford that covers the theory and practice of convolutional neural networks for image classification, object detection, segmentation, and generative models.
- [CS182 Deep Reinforcement Learning](https://inst.eecs.berkeley.edu/~cs182/sp23/): A course from UC Berkeley that introduces the basic concepts and algorithms of reinforcement learning and how to apply them to problems such as robotics, games, and natural language processing.
- [Learn PyTorch](https://www.learnpytorch.io/): A website that provides tutorials and examples on how to use PyTorch for various deep learning tasks.

## Grading:
* Homework – 20% <br>
* Midterm – 30% <br>
— Will consist of mathematical problems and/or programming assignments.
* Seminars - 10%
* Final – 40%

## Academic Honor Code
Honesty and integrity are vital elements of the academic works. All your submitted assignments must be entirely your own (or your own group's).

We will follow the standard of Faculty of Mathematical Sciences approach: 
* You should not use code of others or be looking at code of others when you write your own: You can talk to people but have to write your own solution/code
*  You can talk to others about the algorithm(s) to be used to solve a homework problem; as long as you then mention their name(s) on the work you submit

## Questions?
I will be having office hours for this course on Monday (10:00 AM--11:30 AM). If this is not convenient, email me at m.amintoosi@um.ac.ir, talk to me after class or [schedule an appointment via Calendly](https://calendly.com/m-amintoosi/30min).

## Our Slack workspace
Come and [join our Slack](https://join.slack.com/t/fum-cs/shared_invite/zt-1zntzuw2t-JOWbsyQdGASNz~40AhWy_Q) group to engage in course discussions.
