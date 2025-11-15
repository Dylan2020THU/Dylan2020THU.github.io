---
title: "Math in Reinforcement learning"
collection: teaching
type: "Theoretical Course"
permalink: /teaching/math_in_rl
venue: "Bilibili"
date: 2025-11-15
location: "Online"
---


Unbiased and Biased Estimation
====

In reinforcement learning, the concept of "unbiased estimation" is ubiquitous. One of the core tasks of RL is to estimate various "expected values" through the samples generated from interactions with the environment. In this class, we will first understand the basic concept of unbiased estimation, and then further compare it through two common methods in RL: the Monte Carlo method (unbiased) and the temporal difference method (biased).

Click the web link and start learning this lecture: [Bilibili - 无偏估计vs有偏估计](bilibili.com/video/BV1cQpdzvEUA/?spm_id_from=333.1387.collection.video_card.click)



Markov Decision Process
====
All reinforcement learning problems can be modeled as Markov Decision Processes (MDPs), so what exactly is an MDP? This presentation will mainly analyze it step by step from four aspects:
1. Markov property
2. Markov process/Markov chain
3. Markov reward process
4. Markov decision process

Click the web link and start learning this lecture: [Bilibili - 马尔可夫决策过程](https://www.bilibili.com/video/BV1rQ4qz4EUX/?spm_id_from=333.1387.collection.video_card.click)


What is exactly the Policy π?
====
π shows up everywhere in reinforcement learnin, but what exactly is it in math? Let's dive into this lecture and find out.

Click the web link and start learning this lecture: [Bilibili - 策略π到底是什么东西](https://www.bilibili.com/video/BV13BWnzHETG/?spm_id_from=333.1387.collection.video_card.click&vd_source=003b28715bfde4b6771fa39e28ab9f9a)


Value Function
====
Value function includes state value function and action value function. Let's invistigate their basic definitons and see how to build them in RL. This presentation mainly covers:
1. State value function V(s)
2. Action value function Q(s,a)
3. The mathematical relationship between V(s) and Q(s,a)
4. Why Q(s,a) is more commonly used in reinforcement learning?

Click the web link and start learning this lecture: [Bilibili - 价值函数](https://www.bilibili.com/video/BV1YN1gBfEgk/?spm_id_from=333.1387.collection.video_card.click&vd_source=003b28715bfde4b6771fa39e28ab9f9a)


Monte-Carlo Methods
====
The main idea of the Monte-Carlo method is as follows: When the problem to be solved is the expected value of a certain random event, through a large number of repeated random samplings, the statistical mean of the samples is used to approximate the expected value. Its mathematical essence is to use the law of large numbers in probability theory to approximate the calculation of an integral or expected value that is difficult to directly solve. This sharing includes:
1. What is the Monte Carlo method
2. The Monte Carlo method in reinforcement learning

Click the web link and start learning this lecture: [Bilibili - 蒙特卡洛方法](https://www.bilibili.com/video/BV1FYkZBNEbj/?spm_id_from=333.1387.collection.video_card.click&vd_source=003b28715bfde4b6771fa39e28ab9f9a)




