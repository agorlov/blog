---
layout: post
title: "Employee Turnover Is Good for the Maintainability of Your Code Base"
date: 2015-12-29
place: Kiev, Ukraine
tags: management
description: |
  Low turnover is a symptom of trouble, while a reasonable
  amount of it will lead to higher maintainability
  and greater robustness of your software.
keywords:
  - employee turnover
  - hero driven development
  - fire fighting
  - high turnover
  - low turnover
image: /images/2015/12/commando.jpg
jb_picture:
  caption: Commando (1985) by Mark L. Lester
---

This is what Wikipedia [says](https://en.wikipedia.org/wiki/Turnover_%28employment%29) about this:
"High turnover may be harmful to a company's
productivity if skilled workers are often leaving,
and the worker population contains a high percentage of novices."
I agree. However, I believe that low turnover may also
be very harmful.

<!--more-->

{% jb_picture_body %}

I've found this
[good article](http://www.eremedia.com/ere/a-low-turnover-rate-could-mean-that-you-have-ugly-employees/)
where John Sullivan explains why low turnover could be a troubling
symptom. It's a really good read, but rather generic. It is not specifically about software
teams. My experience is mostly focused on programmers and their
turnover. I've learned that low turnover negatively affects code maintainability
and encourages **hero-driven development** and **strong code ownership**
(both of which are bad practices).

{% quote If you consider programmers to be a valuable long-term asset, you're wrong %}

"Turnover" is basically the act of replacing an employee
with a new employee for any reason, including termination,
retirement, resignation, or any other. Simply put, the more
people your team loses every year, the higher your turnover.
If there are 20 programmers on your team, and five of them
walk away every year, your turnover is 25 percent.

{% youtube xbovkm0tTn0 %}

I can't pinpoint what number you should aim for, but I strongly believe
that if you consider **programmers** to be a **valuable long-term asset**,
and try to retain them at all cost, you're doing it wrong.

My point is that a healthy software team must
**replace** programmers **regularly**. I would say having one
person on board for longer than a year is asking for trouble.

By replacing, I don't necessarily mean
[firing]({% pst 2015/sep/2015-09-16-how-to-fire-someone-right %}).
Not at all. I mean moving them
**away** from the code base. Obviously, if you have a single code
base, replacing will mean firing.

When programmers stay together for a long time, working on the
same code base, they inevitably become subject matter **experts**. First of
all, this leads to strong code ownership. Naturally, each of them
becomes a specialist in his or her own part of the code, mostly because
it's easier to work with something you're familiar with instead of jumping
from module to module. Needless to say, strong code ownership is
a bad practice. Collective code ownership is a much better alternative,
as [explained](http://martinfowler.com/bliki/CodeOwnership.html) by Martin Fowler.

{% quote Having strong experts on the team inevitably leads to hero-driven development %}

Then, having strong experts on the team inevitably leads to
hero-driven development, where firefighting is very much appreciated.
An expert doesn't want to lose his or her position, and always tries to demonstrate
how valuable he or she is for the team. The best way to do this is to
solve a problem that nobody else can solve. That's how one gets "job security."
And that's how the team starts to degrade.
This [blog post](http://highlevelbits.com/2014/08/hero-driven-development.html)
by Fredrik Rubensson is right about this problem.

{% youtube pt9uHp35fwM %}

Thus, to achieve higher maintainability of the source code and
robustness of the product, we must **rotate** programmers, preventing
them from becoming subject matter experts.

I realize this idea sounds counter-intuitive, but think about it.
By keeping people together, working on the same problem for a long time,
we put a lot of knowledge into their heads, not our source code.
These people become the **asset**. They become smarter, they know the
solution very well, and they solve all issues rather quickly.
But the code base degrades.

When the time comes to change someone (for any reason), the loss will be
damaging. We may lose significant knowledge, and the code base left
behind will be unmaintainable. In most cases, we will have to re-write it.
That's why in most software teams, management is **afraid** of programmers.
They are scared to lose key software developers, because the
consequences may be fatal.

{% youtube b6r2W3P9vgY %}

In the end, programmers control management, not the other way around.

[It's Not a School!]({% pst 2015/feb/2015-02-16-it-is-not-a-school %})&mdash;This earlier post explains how this problem can be solved without
[firing]({% pst 2015/sep/2015-09-16-how-to-fire-someone-right %})
or rotating programmers, but few teams, especially co-located ones,
can afford it. If your team can't, just try to keep your turnover high
enough to prevent the appearance of **heroes** (a.k.a. subject matter experts).

