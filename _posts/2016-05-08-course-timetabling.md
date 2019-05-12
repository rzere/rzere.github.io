---
title:  Applying Graph Theory and Evolutionary Computation to a Course Scheduling System
tags:
  - Genetic  Algorithms
  - Graph Theory
  - Python
  - Course Timetabling
---

We describe the design and implementation of a course timetabling system. Our system models the timetabling problem as a vertex coloring of a weighted graph, where each edge has a two-component weight corresponding to the two objectives—minimizing conflict and creating compact schedules. Previous work by Wehrer and Yellen (Wehrer and Yellen 2014) resulted in a Java-based system that scheduled the Rollins College Science Division in 2011. (Rickman and Yellen 2014) built upon this framework to explore new scheduling algorithms. As a part of my Student-Faculty Collaborative Research program, (2016) we have reconstructed the system to be more efficient.

<!--more-->

`Course timetabling` for higher education institutions is a challenging
problem that requires balancing instructor and student preferences while avoiding conflicts. The underlying model for our system is a weighted graph model with two-component edge weights. The two edge-weights represent our two objectives: avoiding conflict and creating compact schedules.

To learn more about this project, check out my [ honors thesis](https://raw.githubusercontent.com/rzere/Course_Timetabling_Research/master/Course_Timetabling.pdf)

<div class="card mb-3">
    <img class="card-img-top" src="https://raw.githubusercontent.com/rzere/Course_Timetabling_Research/master/Slide1.png"/>
    <div class="card-body bg-light">
        <div class="card-text">
            Research Poster
        </div>
    </div>
</div>

<div class="card mb-3">
    <img class="card-img-top" src="https://raw.githubusercontent.com/rzere/rzere.github.io/master/theme/img/graph.png"/>
    <div class="card-body bg-light">
        <div class="card-text">
            Graph Coloring problem
        </div>
    </div>
</div>
