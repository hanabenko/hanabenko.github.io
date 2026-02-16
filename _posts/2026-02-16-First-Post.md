---
title: Birthday Special: Happy Numbers
date: 2026-02-16 10:00:00 -0500
categories: [Math, Number Theory]
tags: [happy numbers, number theory]
description: A birthday-themed look at happy and sad numbers.
---

It’s my 20th birthday today.  
To celebrate, here’s a special blog post about a fun concept in number theory: happy numbers.

> *In number theory, a **happy number** is a number which eventually reaches 1 when the number is replaced by the sum of the squares of each digit.*  
> — [Wikipedia](https://en.wikipedia.org/wiki/Happy_number)

Let’s take a look at two numbers in particular.

20 (the age I am now) is a *sad number* :(. 

### Proof

```text
20  => 2^2 + 0^2 = 4
4   => 4^2 = 16
16  => 1^2 + 6^2 = 1 + 36 = 37
37  => 3^2 + 7^2 = 9 + 49 = 58
58  => 5^2 + 8^2 = 25 + 64 = 89
89  => 8^2 + 9^2 = 64 + 81 = 145
145 => 1^2 + 4^2 + 5^2 = 1 + 16 + 25 = 42
42  => 4^2 + 2^2 = 16 + 4 = 20  <-- we have reached a loop
20  => ... and it begins again ```

Thus, the squared sum of the digits of 20 reaches an infinite loop and never terminates by reaching 1, implying that 20 is a sad number. This concludes the proof.

But there is hope for me.

2026 is a *happy number* :). 

### Proof

```text
2026 => 2^2 + 0^2 + 2^2 + 6^2 = 4 + 0 + 4 + 36 = 44
44   => 4^2 + 4^2 = 16 + 16 = 32
32   => 3^2 + 2^2 = 9 + 4 = 13
13   => 1^2 + 3^2 = 1 + 9 = 10
10   => 1^2 + 0^2 = 1  <-- we have reached 1 ```

Thus, the squared sum of the digits of 2026 eventually reaches 1, implying that 2026 is a happy number. This concludes the proof.

That’s all. Happy birthday to my February 16th twins!
