---
layout: post
categories: article
title: 'Step 1: setting the flow'
image: /assets/article_images/2014-11-30-mediator_features/night-track.JPG
published: true
---

Training an agent using reinforcement learning pivots on being able to deliver precisely timed rewards to reinforce specific action, state pairs r(s,a). This poses some challenge in our watery environment for two reasons:

### Problem:
1. fish don't eat a lot (and delivering very small rewards in a technical challenge)
	As a result food may linger for a long time and other unrelated actions may get reinforced (or the fish might just get satiated)
	
2. rewards will dissolve and diffuse in our environement.
	This will blur any "spatial"/state contingencies making learning more difficult

### Solution:
To overcome this the tank will have circulating water which will remove any uneaten food, making the delivery of food more akin to an "impulse". The idea was inspried by this interesting [paper](https://www.sciencedirect.com/science/article/pii/S016643281730801X)






