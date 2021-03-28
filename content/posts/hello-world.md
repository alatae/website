---
title: "Hello, world!"
date: 2021-03-28T22:21:24Z
draft: false
description: Introducing a interactive music/visual art project callled Ada Lovelace and the Analytical Engines
tldr: Introducing an experiment in generative art...
tags: blog
---

# Hello, world!
These two words, synonymous with the adventure of learning, are typically used as an introductory program for students of a new programming language. It's invocation brings to mind the first steps in an adventure of experimentation, exploration and collaboration. ALATAE's (Ada Lovelace and the Analytical Engines) adventure begins with this post, where the introduction of the idea, the technologies to be explored (at least to start), and the aspirations hoped to be achieved are outlined. Without further ado, **"Hello, world!"**

## The Idea
Generative art, algorithmic music, and creative uses for new technologies have existed for centuries - it almost seems like it's a natural progression that humans try to teach machines to engage in the creative endeavours, to endow them with the creativity of their human users. COVID-19 presented a new field to explore as people began to rethink the notion of space, collaboration, and interaction throughout all of the aspects of our lives. As someone who considers themselves a technologist with a healthy fascination in music and a curiousity in emerging platforms for sharing content and collaboration, the idea of ALATAE was born. Combining a modular synthesizer with ML models, unique interaction modes, and complex generative visuals all live-streamed to anyone throughout the world could create a new platform for experimentation in art, music, and technology.

It should be noted that this is new ground, and the format of each ALATAE "performance" will be one of mistake, happy accidents, and deep learning about the interaction between audience, machine, and code. As such, please forgive the learning process if it results in random beeps and boops instead of gorgeous symphonies - all of the work/changes will be hosted in open-source repos for anyone to contribute or comment on.

## The Technologies
The modular synth (aka The Guidonian Hand) is a collection of various modules, most of them in some form of DIY. Soldering is a relaxing way to spend time, and once you build enough modules, you begin to understand and appreciate the underlying engineering behind these wonderful gizmos. The heart of the interface for the synth is powered by the [bela platform](https://bela.io) using their [Pepper](https://learn.bela.io/products/modular/pepper/) Eurorack module.

The brain of the musical platform will be powered by [Magenta](https://magenta.tensorflow.org/) an open-source project developed for exploring applications of ML and AI as part of the creative process. The output from the various models for music generation will be sent to The Guidonian Hand to be played on a variety of sound and effect modules to generate (hopefully) musical sequences and phrases - maybe even songs? Some standalone and semi-modular equipment may make an appearance, and I'm really looking to creating and building intriguing ways of interacting with Magenta.

[p5.js](https://p5js.org/) will power the visualizations and parts of the interactions between the machine and the audience. Tying parameters of generative algorithms to the parameters of a model, using the output of the Magenta model to drive the parameters of a generative visual model, or some interpolation between the two is bound to create a playground of motifs, ideas, and visual cues that will be part of a new type of interactive experience.

## The Hopes
It's the hope of this project to produce aesthetically pleasing visual art and music using a combination of algorithmic methods and novel interaction techniques. As it's an experiment in code and art, it will be documented here on this site, and throughout the [GitHub Organization](https://github.com/alatae) created to host and provide source control for the content. It would be marvelous to have multiple contributors working on this project - anyone can join and help build a new way to experience music. In addition to the code being available under an open license, any output from the code repositories will be released under a suitable Creative Commons license for use by all. Several of these final features will be ironed out as we prepare for the first concert of Ada Lovelace and the Analytical Engines!