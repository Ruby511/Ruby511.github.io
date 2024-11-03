---
layout: post
title: What & why is that machine learning all the time?
date: 2024-06-05
description: A beginner-friendly introductory blog to machine learning.
tags: machine-learning
categories: journal-club
thumbnail: false
related_posts: false
related_publications: true
---

Each time some compsci student says they are developing a machine learning algorithm, I pretend to be fully aware of what they are talking about. But to be honest, I can barely imagine why a machine can complete the "learning" action. Afterall, "learning" itself is still somewhat a poorly defined word in neuroscience isn't it?

What kind of information the machine is actually abosrbing in "ML" algorithms? This question always comes to me but I never treated it seriously until this summer, because I was forced to, (actually I found this trouble myself), complete a course on designing different machine learning scripts to analysis a single cell dataset and a classification task of handwritten digits. ("DO YOU KNOW how scary it was when PCA, NMF, t-SNE, multinomial logistic regression, multiclass SVM, and CNN all come together at once saying hello to a naive biology student?") And I realized, I need to start from the basic, figuring out how the concept of machine learning is developed and all of a sudden becomes an unavoidable thing to biologists.

Conclusion first, learning for a machine generally means when an algorithm takes in a training dataset to induce a classifier function that predicts data labels. In another word, a machine learning algorithm has its input as a set of data that is labelled in some useful way, and the algorithm looply optimize parameters of the classifier function so that the number of mistakes made on predicting labels is minimized. This is the definition of "supervised learning". There is also another branch of ML named unsupervised learning, in which "learning" is defined as identifing commonalities in the data and react based on the presence or absence of such commonalities in each new piece of data. 

To me, these two branches of ML is just like the different study strategy of people: When you are to answer an assignment problem, you can have an prediction at the begining, check with the answersheet, wrong answer -- you read a couple pages of the notebook, fixed the answer and go to the next question -- This time you read a bit at the former question and have a closer guess, but it is still not right, so you review the notebook again and do it again etc. At the end you finished the assignment (your training dataset) and reviewed everthing on your notebook, go to the test and get an A+, congradulations you just create an in vivo supervised machine learning algorithm (Do be aware that D- is also a possible output if you review the biology notebook for a calculus test). On the other hand, you can choose not to take any note and simply read all the textbooks and construct a knowledge map. Then you become an unsupervied learning algorithm and is ready to get your A+ without some stupid practice assignment (This strategy works, in theory, as long as I actually read the textbook as I plan to).

<hr>

tSNE introduction:

[mastering-t-sne-t-distributed-stochastic-neighbor-embedding](https://medium.com/@sachinsoni600517/mastering-t-sne-t-distributed-stochastic-neighbor-embedding-0e365ee898ea)

[t-distributed-Stochastic-Neighbor-Embedding(t-SNE)-Dimensionality-Reduction-Techniques-(4/5)](https://www.youtube.com/watch?v=U-s8q6HshZw)

[sklearn-manifold-tsne](https://scikit-learn.org/0.16/modules/generated/sklearn.manifold.TSNE.html)
