---
layout: post
title: Machine Learning
date: 2018-03-05 07:52:00 +0000
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: machine-learning.jpg # Add image post (optional)
tags: [Machine Learning, Education]
---

## Octave Cheatsheat

### Basic Operations

| Operation | Input | Output | Explanation
| --- | --- | --- | ---
| Addition | `1+2` | `ans = 3` | what is 1 plus 2?
| Subtraction | `3-2` | `ans = 1` | what is 3 minus 2?
| Multiplication | `2*2` | `ans = 4` | what is 2 times 2?
| Division | `6/2` | `ans = 3` | what is 6 divided by 2?
| Powers | `2^6` | `ans = 64` | what is 2 to the power of 6?
| Equal to | `1 == 2` | `ans = 0` | is 1 equal to 2? Returns 0=False
| Not equal to | `1 ~= 2` | `ans = 1` | is 1 not equal to 2? Returns 1=True
| AND | `1 && 0` | `ans = 0` | represents a logical AND operation that employs short-circuiting behavior<br>expr2 is not evaluated if expr1 is logical 0 (false)<br>Each expression must evaluate to a scalar logical result<br>Returns 1=True or 0=False
| OR | `1 || 0` | `ans = 1` | represents a logical OR operation that employs short-circuiting behavior<br>expr2 is not evaluated if expr1 is logical 0 (false)<br>Each expression must evaluate to a scalar logical result<br>Returns 1=True or 0=False
| xor | `xor(1,0)` | `ans = 1` | Return the exclusive or of x and y<br>For boolean expressions x and y, xor (x, y) is true if and only if one of x or y is true<br>Otherwise, if x and y are both true or both false, xor returns false
| PS1 | `PS1('>> ');` | Changes prompt | Changes prompt to string
| Integer assignment | `a = 3` | `a = 3` | Returns input
| String assignment | `b = 'hi'` | `b = hi` | Returns input
| Semicolon | `a = 3;` | none | Semicolon suppresses output
| True/False assignment | `c = (3>=1);` | none (semicolon) | Assigns a true or false statement to a variable
| True/False Return | `c` | `c = 1` |
