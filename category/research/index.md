---
layout: category
title: Research
category: research
sidebar_sort_order: 1
---

{% include imgcard.html imgpath="/assets/img/ariana_woodblock_blackhole.jpg" title="Traditional Wood Block Printmaking" imgtext="Traditional Wood Block Printmaking" credit="&copy; Ariana Coveney." %}

My research focuses on developing mathematical models
for strongly interacting, complex systems that cannot be
analyzed with traditional reductionist techniques.
In other words, systems where the whole is greater than
the sum of its parts. I particularly focus on the "brain"
of the small nematode *C. elegans*.

### Data-driven modeling of biological systems

A key component of my PhD has focused on analysis of
calcium imaging data of neurons acting in real time.
This network of neurons can be treated as a controlled system
using the Dynamic Mode Decomposition with Control (DMDc)
framework. [publication coming soon]


### Modeling control systems

Dynamic Mode Decomposition with Control (DMDc) is a popular
technique for modeling the dynamics of a system with external
inputs, aka control signals. I have developed an algorithm with
increased accuracy and decreased sensitivity to user-defined
parameters: [publication coming soon]


### Interpreting models

#### "All models are wrong...

Interestingly, the way in which they are wrong can be incredibly
informative. In particular, most modeling finds a
best-fit to data as defined in an L2 sense; this is
analogous to positing that the model captures all of
the data except for Gaussian random noise.
Mathematically, we can search for places in which
our models are wrong in a non-Gaussian way, and, using the control signal
framework of DMDc, make our models much better.

I am working on developing the theory and some applications
of this unsupervised problem, [publication coming soon].

#### "... but some are useful."

Machine learning methods are extremely popular at the moment
and are increasingly being used with ambiguous datasets
for which no "ground truth" is known. Fortunately, they
seem to perform very well! Unfortunately, this does not mean
that such models have actually captured something about
the system that will generalize beyond the specific training
data. This issue extends to mathematical modeling more
broadly, and another area of my work focuses on which
portions of mathematical models, in particular DMDc,
are interpretable and how confident we can be.
[publication coming soon]
