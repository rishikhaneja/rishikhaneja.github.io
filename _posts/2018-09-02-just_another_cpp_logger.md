---
layout: post
title: Just another C++ logger
date: 2018-09-02
---

Here's my quick attempt at a lightweight modern c++ logger https://github.com/rishikhaneja/rlog

## Lessons learnt
* std::function does multiple copies and destruction, beware!!
* Multi-platform CI should be done right from start
* Maintaining/debugging macro-magic like optional args can get really annoying, better avoid
