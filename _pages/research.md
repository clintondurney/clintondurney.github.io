---
layout: page
title: research 
permalink: /research/
description:  
---
I use mathematical modelling and computation to understand and to provide quantitative descriptions to the natural world.  This has ranged from purely theoretical models of populations to highly descriptive models of cell-scale biological systems.  I loosely fall into the fields of Mathematical Biology and Biophysics.  Details of **current** research projects are below. 


### Epithelial Morphogenesis

How cells organize themselves into tissues and undergo coordinated movement to form life is one of the fundamental mysterys of developmental biology. Individual cells must control their size, movement, division and shape changes through chemical and mechanical factors. Spatial organization of individual cells is necessary to form tissues and organs which are required to sustain life. Through combining experimental observations with mathematical descriptions, I build mechano-chemical mathematical models of epithelial morphogenesis of the *Drosophila* embryo.  

***Drosophila* Dorsal Closure**

I developed a vertex-based model for *Drosophila* dorsal closure that predicts the mechanics of cell oscillation and contraction from the dynamics of the PAR proteins. Based on experimental observations of how aPKC, Par-6, and Bazooka translocate from the circumference of the apical surface to the medial domain, and how they interact with each other and ultimately regulate the apicomedial actomyosin, I formulated a system of differential equations that captures the key features of dorsal closure, including distinctive behaviors in its early, slow, and fast phases. The oscillation in cell area in the early phase of dorsal closure results from an intracellular negative feedback loop that involves myosin, an actomyosin regulator, aPKC, and Bazooka. In the slow phase, gradual sequestration of apicomedial aPKC by Bazooka clusters causes incomplete disassembly of the actomyosin network over each cycle of oscillation, thus producing a so-called ratchet. The fast phase of rapid cell and tissue contraction arises when medial myosin, no longer antagonized by aPKC, builds up in time and produces sustained contraction. Thus, a minimal set of rules governing the dynamics of the PAR proteins, extracted from experimental observations, can account for all major mechanical outcomes of dorsal closure, including the transitions between its three distinct phases. 

The following figures are schematics of the mechanical model and the intracellular signaling network of the PAR-proteins.

<img src="/assets/img/dc_fig1.png" alt="drawing" width="500"/>

**Salivary Gland Tubologenesis**

My second project aims to develop a comprehensive 3D vertex framework for Drosophila salivary gland formation. Most tissue morphogenetic problems involve 3D structures with out-of-plane dynamics that cannot be simplified into planar problems. Due to the complex cellular geometries within tissues and the computational complexity that lies therein, very few 3D models exist in practice. During salivary gland formation, a tubular structure is formed from a simple planar epithelial tissue. The goal of this work is to provide a mechanistic explanation for how anisotropic apical constriction of the flat epithelial sheet causes buckling into an invaginated tubular structure. To answer this, I developed a novel 3D vertex model in which cells are generalized to polyhedrons which is able to account for descriptions of cellular morphologies in 3D and physical forces such as pressure due to the cytosol.

The following figure shows how cells are modelled in a 3D vertex based model. 

<img src="/assets/img/3D.png" alt="drawing" width="300"/>


