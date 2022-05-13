---
title: "Bicolor Tower of Hanoi"
project_id: 3
layout: posts
permalink: /proj/Tower_of_Hanoi
header:
  teaser: /assets/images/proj/Tower_of_Hanoi/Tower_teaser.png
---

A discrete space puzzle game inspired by the Tower of Hanoi.

<img width="80%" src="{{ site.url }}{{ site.baseurl }}/assets/images/proj/Tower_of_Hanoi/Tower.png">

### Description

The Bicolor Tower of Hanoi is a variation of the classic children’s puzzle game, Tower of Hanoi. 

Similar in rules to the original, disks are moved one by one between the pegs while maintaining a rule that no disk has a strictly larger disk on top of it. Which is to say, a disk can move from peg *u* to peg *v* if and only if the peg *v* is empty or the top disk of the peg is of equal or larger size. 

The puzzle game acts as a simple toy problem, to explore communication problems with social robots. This component is the game server portion of my larger PhD research project. The server models the game, and contains a solver which can be used to fetch the optimal move of the current board state. The server also receives commands from a user-interface, and can output a default ASCII representation.

The project is open-source and can be found [here<i class="fab fa-fw fa-github"></i>](https://github.com/kothiga/Tower-of-Hanoi).
