---
title: Symbolic AI, return of the prodigal son
author: Imam
use: [posts]
tags:
    - symbolic-ai
    - ml
overview: A very elementary overview of Symbolic AI
---

**What is Symbolic AI ?** 

We humans, represent the world around us through high level concepts. For example, the word 'Man', it stands for something, in this case a biological entity that has certain properties.  Similarly words like 'Trees' , 'Flowers', 'Skyscrapers' are symbols that stand for something or someone. It might sound like I am explaining the trivial, however, it is important to grok this idea to understand the essence of Symbolic AI. Now, lets analyse this statement that dates back to ancient Rome, "All men are mortal;  Caius is a man; therefore Caius is mortal. " Here we associated mortality with all men, thus deducing Caius is also mortal,since he is a man. This is the essence of symbolic AI, reasoning through relationships among high level concepts. But its quite labour intensive, a human has to encode these high level concepts and their relationship into rules. These rules are encoded as if then statements.

**A bit about its history** 

Symbolic AI was the dominant form of AI until 1980s when statistical methods took over. The term artificial intelligence was coined at the seminal conference in 1956 at Dartmouth, organized by John McCarthy. The pioneers of the field John McCarthy and Marvin Minsky believed rule based system will ultimately lead to human level intelligence (Artificial General Intelligence) and beyond.  Symbolic AI is also often referred as ' 'Good Old Fashioned AI ' because of this historical context. There is an ongoing project called 'Cyc', one of the longest running that aims to codify all of the 'common sense knowledge' a human possesses, the hypothesis is that an articial system should eventually be able to reason like a human once this system has access to all common sense knowledge. 


**Why it failed to deliver on its promise ?**

The approach was overtaken by statistical methods for basically two reasons.

1. Hard coding a chain of rules for sufficiently complex tasks can be overwhelming and requires domain expertise.  Imagine defining set of rules to recognise dogs in images, well they are furry (but not always), have got two eyes and four legs, and have different shapes, sizes and colours. Defining rules to identify every possible specicies of dogs can soon become overwhelmingly complex and impractical.
2. Rule based reasoning systems are not robust against noisy data. Real world is noisy, peppered with counter examples. Going back to earlier examples of defining rules for identifying dogs. Dogs are four legged animals but some might be born with three due to a genetic defect or might loose one due to an accident. A system based on rigid set or chain of rules is very difficult to modify and accomodate for all the variations found in nature. 


**Finally, its resurgence or why do we need it again ?**

Statistical machine learning and its modern avatar deep learning (including deep reinforcement learning) has had a profound impact on our society. Autonomous cars, super human performance in the game of GO and near perfect speech recognition is the result of deep learning and specialised hardware. However, these systems are also notoriously difficult to interpret. Imagine applying for a loan, the deep neural network that the bank might be using to assess your credit worthiness would probably take in dozens if not hundreds of data points about your employment, marital status, education and many more. In case your loan application is rejected you may want to know 
the reason. With deep nets its very difficult to pin down the exact reason because the learned model is basically a high dimensional matrix of weights that transforms input variables into a Yes or a No decision. 


**To learn more** 
