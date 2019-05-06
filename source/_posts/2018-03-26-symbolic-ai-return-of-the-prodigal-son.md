---
title: Symbolic AI, return of the prodigal son
author: Imam
use: [posts]
tags:
    - symbolic-ai
    - ml
overview: A very elementary overview of Symbolic AI
---

![Robot looking at a dog in the snow. It can't decide whether he sees a wolf or a dog.](/blog/images/Symbolic-AI.png)

**What is Symbolic AI ?** 

As humans, we represent the world around us through high level concepts. For example,  words like 'Trees', 'Flowers', 'Skyscrapers' are symbols that stand for something or someone.  The essence of symbolic AI is reasoning through relationships among high level concepts, such as “All men are mortal; Caius is a man; therefore Caius is mortal – associating mortality with all men. However, it is quite labour  intensive, as a human has to encode these high level concepts and their relationship into rules. These rules are encoded as if then statements.

**A bit about its history** 

Symbolic AI was the dominant form of AI until the 1980s when statistical methods took over. The term artificial intelligence was coined at the seminal conference in 1956 at Dartmouth, organized by John McCarthy. The pioneers of the field John McCarthy and Marvin Minsky believed a rule-based system will ultimately lead to human level intelligence (Artificial General Intelligence) and beyond. Symbolic AI is also often referred as 'Good Old Fashioned AI' because of this historical context. There is an ongoing project called 'Cyc' is-, one of the longest running. It aims to codify all of the 'common sense knowledge' a human possesses. The hypothesis is that an artificial system should eventually be able to reason like a human once this system has access to all common sense knowledge.

**Why it failed to deliver on its promise ?**

The approach was overtaken by statistical methods for basically two reasons.

1.	Hard coding a chain of rules for sufficiently complex tasks can be overwhelming and requires domain expertise. Imagine defining a set of rules to recognize dogs in images-  they are furry (but not always), have got two eyes and four legs, and have different shapes, sizes and colours. Defining rules to identify every possible species of dogs can soon become overwhelmingly complex and impractical.
2.	Rule based reasoning systems are not robust against noisy data. The real world is noisy, peppered with counter examples. Going back to earlier examples of defining rules for identifying dogs. Dogs are four legged animals, but some might be born with three due to a genetic defect or might lose one due to an accident. A system based on rigid set or chain of rules is very difficult to modify and accommodate for all the variations found in nature.

**Finally, its resurgence or why do we need it again ?**

Statistical machine learning and its modern avatar deep learning (including deep reinforcement learning) has had a profound impact on our society. Autonomous cars, super human performance in the game of GO and near perfect speech recognition is the result of deep learning and specialized hardware. However, these systems are notorious for being data intensive. 

When DeepMind achieved super human results in the Atari game of  Pong and Breakout using deep reinforcement learning it had to play millions of games with itself, while humans can understand the game mechanics and become decent players with just few examples. The deep network has no concept of a ball, pedal or that the ball needs to be struck with the pedal. The system learns everything from scratch (just pixels).

This is where a hybrid system (Symbolic AI + Deep learning) could potentially be revolutionary as they complement each other quite well. If the system can learn to represent high level concepts like ball, pedal and their relationships as step 1 that would speed up learning to play the game quite significantly. Higher level concepts and relationships also makes it re-usable and easy to transfer knowledge.

**Summary**

Symbolic AI is set of powerful tools to build intelligent systems that humans can understand and reason about. The tedious nature of building these systems eventually resulted in statistical methods becoming dominant for AI, however it issreturningmaking a comeback . Shortcomings of deep learning align well with strengths of Symbolic systems, hence its poised to take the field of AI to the next level.

**To learn more**

[Symbolic reasoning](https://skymind.ai/wiki/symbolic-reasoning)

[A nice video introduction](https://www.youtube.com/watch?v=iiMCOIGWcok)

[What was Good Old Fashioned AI and why did it fail](https://www.reddit.com/r/artificial/comments/ziw60/what_was_gofai_and_why_did_it_fail/c6531lf/)

[Towards Deep Symbolic Reinforcement Learning](https://arxiv.org/pdf/1609.05518.pdf)

[Artwork by offoff.studio](https://offoff.studio/)




