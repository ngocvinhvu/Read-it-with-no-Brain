---
layout: post
author: No Brain
title: "Learn Consistent Hashing in NoBrain way"
date: 2023-07-23
---

### What is consistent hashshing and what do this do?
Fistly, when we need to use the sharding technology when deploy our applications in order to share the data to these storages, we will use an "algorithm" in various hashing technique of "sharding technology" is called "Consistent Hashing".

Then, the consistent hashing will help the data is distributed equally for all data storage we used in our system when we write data continuously.

### How it's works?
![alt text](.images/2023-07-23-consistent-hashing/image.png)
We will place all distributed storage in a circle called "hash ring" like this picture above.