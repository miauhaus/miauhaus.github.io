wip
---
layout: research
title: MFP-SEI
description: Research on an Interdimensional Evolutive emergent System based on topological behaviour
thumbnail: https://i.postimg.cc/GpRCtvcJ/Screen-Shot-2018-10-21-at-16-15-34.png
author: Francesc Sòria Castellet
language: en
date: 2019-10-06 00:00
---
{::comment}
https://live.staticflickr.com/65535/48846425098_b1f4b0e945_b.jpg
{:/comment}
# An Interdimensional Evolutive System

## P0.00 Definition
Interdimensional evolutive systems. Evolutive methodology exploration exercise. 
Based on the panarchical scheme, a set of algorithms that represent behaviours, mechanisms and metabolisms are here presented and intertwined. From more basic to more complex entities and their concatenation in an evolutive system, a whole is created where each one depends on the other.

## P0.01 Introduction
This investigation is born from a far-fetched intention, and is has been thought to be a small part in the intension towards it. The aim to understand the dynamics of relation and translation is simplified to creating a recursive algorithm that grows and develops in different stages, exhibiting behaviours and needs specific to each.

### P1.00 Context
Being it that human fields of knowledge and their consequences in “day to day experience”are increasingly intra-related, the need for tools that can help study the dynamics of relation and the dynamics and consequences of scope are increasingly pressing. The use of process metaphorization and detail distillation allows translation and joining between any set of systems. Making this information movements understandable asks for multi-dimensional and empatic interfaces. For this to be achieved, procedural systems that work with the most basic items of information and from them construct complex infromation sequences are needed.
In this specific effort, wishing to explore a free form surface modeler based on NURBS as Rhino and it’s parametrization plug-in Grasshopper are, it has been decided for the systems at play and their resulting relations to stem from the “layers” of geometrical complexity and the possible projective dimensions with which the software works.

### P2.00 Objectives
P2.01 Investigate simple algorithms that represent biological processes that can enact sensible interfaces from and to the relations that form them. Assess the possibilities of data translation, use and reuse to generate intra-related evolving growth.
P2.02 Generate relations between algorithms to generate different possibilities of stable concatenation. Explore the idea of stability and recursiveness in systems based on stochastic dynamics, as biology does, rather than deterministic ones.

### P3.00 Methodology
Wanting to create a growth scheme, the order in which to design is a path from the simplest to the most complex geometries at play. Each upstream step depends on the previous and its possibilities, amounts and behaviours.
It starts with the 2D confined point as the most simple geometry. By multiplying the point, the project works its way up to straight lines. Connecting the lines, creating polylines, two possible paths appear; one is to create 2D polygons, the other one is to create 2D NURBS curves. This two possibilities are then set to create two different growth processes: from the polygons, a grouping intention is programmed that creaes 2D polygonal meshes, in turn, when these comply with a series of conditions, can develop 3D polygonal meshes that will seek other 2D meshes in order to grow. From the NURBS and their splittings a self reproducing algorythm is set, when these comply with another sereis of conditions, they start projecting in the third dimension and create 3D NURBS that develop into a surface.
Other than the basic offer of possibilities that comes with Grasshopper, two main plug-in methods have been used to generate the processes.
Anemone works with loop iterations of a certain behaviour to generate a cumulative result, Kangaroo works with geometries, forces and constraints to create a single result from a certain input. By combining the two, and adding randomness into amounts at play, the results and characteristics of the kinds of entities vary and bring to light information about the needed characteristics for their growth and survival.

### P4.00 Production 
Programmed Dynamic Prototype based on Visual Programming Platform (Grasshopper3D node-based software, McneelTM)

### P5.00 Results, Conclusions and Future Research 
Daniel Davies talks about direct process of design, non mediated by stochastic processes, bout deterministic models, and about the fail rate of the stochastic processes. To do that he talks about the following concepts: Latency and Correctness.
Latency measures the delay in seeing the geometry change after changing a model’s parameters. With the dataflow model, modifications to the Excel values would propagate out into the geometry produced by Digital Project within a few seconds, which was not quite real-time but near enough for this project. Conversely, the logic programming model had a pronounced latency between editing the axioms and seeing the resulting geometry. Minutes would elapse while the interpreter worked to derive the parametric model after axiom changes.10 Since the derived parametric model did not always have parameters in intuitive places, often the only way to change numerical values (like the angle of the minor fronton) was to change the axioms and then wait as the interpreter derived a new parametric model. This latency made changing the logic programming model a more involved and less intuitive process than with the dataflow model.
Correctness describes whether a program does what is expected (Meyer 1997, 4-5). For both programming paradigms it was difficult to verify the models were doing what was expected. In the dataflow language the quantity of relationships obfuscated the flow of data, which made it hard to work out what the model should have been doing. On three occasions this led to the wrong geometric operation being applied. These errors were not apparent by looking at the dataflow model or by visually inspecting the geometry, and they were only caught by the project architects manually measuring the model. Logic programming was equally difficult to verify because it was not always apparent how the geometry derived from the axioms. Often I would end up adding axioms one-by-one to understand their impact on the final geometry. In the end, both programming paradigms produced parametric models that did what was expected but, in a project where the geometric changes were subtle and the relationships numerous, often the only way to verify correctness was to examine what the model did rather than understand how the model did it.
Daniel Davies. Modelled on Software Engineering: Flexible Parametric Models in the Practice of Architecture, chapter 5.
One of the main problems encountered in the project is in this concept of latency. When dealing with stochastic processes, the delay on the generation of structures based on the previous existence and behaviour of others, creates situations that are both hard to develop computationally and control manually, even if they are algorithmically accounted for. What this errors mean for the project is that certain structures only work while the algorythm is working as a standalone, but either fails to adequate its resulting geometry to the needs of the following stage, or if it does adequate them properly, the amount of computation power needed to progress in the scheme in a time that is properly informative for the viewer is much too much. However, this range of errors is also considered as a metaphor, a proto-synthesis, towards the simulation of processes of abiogenesis. It has been observed that in some algorithms, the error range answers to the complexity of the previous information, this would translate, in genesis of life kind of situations, to a non-viable option, finding the possible way to generate a metaphor for life from geometrical conditions seems like a very interesting project indeed. This has added to an interest and a concern that arises when thinking about the algorithms complexity and it’s relation to latency; if problems have been met when scaling up in size and hierarchy during a one way growth process, when the project continues and establishes the recursive relations that will interlink all stages and strata of the project to one another, every bit of complexity from the different entities will be present in every other one. What this calls for is further investigation on several things: more work dedicated to latency reduction and correctness increase, both inside algorithms and in their connections, by better understanding and treating the generative topology of geometrical structures, to better be able to assess how much it costs for a sub-element to become or create another. i.e.: the generation of surfaces from points takes longer to compute than mesh generation.
Lastly, a possible path of further study that would help the development of the two other conclusive processes. The analysis of the computation times that each phase of the design needs. There are situations in which the computer might be able to reduce the times between two phases to what perceptually might be immediate, artificial latency processes might have to be designed and added to the code for this immediacies to be elongated and thus communicated properly. Comparing the times in which phase transitions of the phanarchical and natural processes are computationally and cognitively processed might bring light into how to design and metaphorize the discourse that wants to be communicated. Dealing with organically and empathetically communicating processes that are faster for human cognition than for computers to compute, is a harder task that will have to be looked onto.

![](https://live.staticflickr.com/65535/48847514862_a6df04aa56_b.jpg)

![](https://live.staticflickr.com/65535/48847320656_2364d23bff_b.jpg)

![](https://live.staticflickr.com/65535/48847518317_4cd28fcb61_b.jpg)

### R2.00 Bibliography 
[1] Brand, F. S., and K. Jax. 2007. Focusing the meaning(s) of resilience: resilience as a descriptive concept and a boundary object. Ecology and Society 12(1): 23
[2] Diego L. Rapoport 2011 Möbius strip and Klein Bottle Genomic Topologies, Self-reference, Harmonics and Evolution
[3] Patricia G. Gensel, Daniele Edwards. 2001. Plants invade the land. Evolutionary and Environmental Perspectives
[4] Daniel Davies 2013. Modelled on Software Engineering: Flexible Parametric Models in the Practice of Architecture
[5] Alejandro Groppo, 2011. Tres versiones contemporáneas de la comunidad: Hacia una teoría política post-fundacionalista. Página 53: Jean-Luc Nancy: comunidad y ontología
[6] Karen Barad, 2003. Posthumanist performativity
[7] Anita Nuopponen, 1994. On causal concept relationships and causal concept systems.
[8] Nicholas M. Gotts, 2007. Resilience, Panarchy, and World-Systems Analysis
[9] Alberto T. Estévez, 2015. Bio digital architecture & etics
