<!---
Fri 01 Jul 2022 01:44:28 PM UTC
Portfolio Website - m0ham3d.com
--->
<p align="center">
<a href="https://twitter.com/m0ham3dxx" target="_blank">
<img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fm0ham3dx%2FFreeQuantumComputingResources&count_bg=%234C0027&title_bg=%23000C66&icon=youtubemusic.svg&icon_color=%23FFE103&title=Lurkers&edge_flat=false"/>
<a href="./LICENSE.MD">
<img src="https://img.shields.io/badge/license-custom-success">
</a>
</a>
</p>
<p align="center">
<a href="https://twitter.com/m0ham3dxx" target="_blank">
<img src="./img/qe.gif" alt="Quantum Entanglement">
<p align="center">
<a href="./infogfx/QEE.jpg" target="_blank">
<i> Illustration of Quantum Entanglement - also referred to as "Spooky Action at a distance". Click me for an illustrative explanation. </i> 
</a>
</p>
</a>
</p>
<p align="center">
<a href="https://twitter.com/m0ham3dxx" target="_blank">
</a>
</p>

----
# 🤌 TOC
- [🤌 TOC](#-toc)
- [ℹ️ REPO DESCRIPTION](#ℹ️-repo-description)
- [🎓LEARNING RESOURCES OF QC](#learning-resources-of-qc)
- [🎛️ FUNDAMENTAL PRINCIPLES OF QC](#️-fundamental-principles-of-qc)
  - [Definition of `Quantum`](#definition-of-quantum)
  - [Quantum Physics](#quantum-physics)
    - [**Quantum State**](#quantum-state)
  - [Atomic Structure](#atomic-structure)
  - [Quantum Particles](#quantum-particles)
  - [Quantum Mechanics](#quantum-mechanics)
    - [Wave Functions](#wave-functions)
- [🐱‍💻 Quantum Computing (Finally 🙃)](#-quantum-computing-finally-)
- [🔎 References](#-references)
- [📒 GLOSSARY](#-glossary)

----
# ℹ️ REPO DESCRIPTION
This repository has been made after my personal interest in Quantum Computing and it rapid development into an easily accessible form. This list will not be exhaustive and will perpetually be a WIP. I cannot guarantee that it will be free form errors. But the actual content will be referenced. 

The scientific concepts mentioned in this repository are an ovesimplification for fast understanding with no deep mathematical proofs, and do not cover the breath of theoretical knowledge that defines its existence. It is left to the reader to further explore these areas. I have ensured to included **hyperlinks** in such situations.

The goal of the scientfic concepts is to build a foundation in undertanding the origins or *QC*.

I have also added *🍌TLDR* block to each section, for fast understanding.

# 🎓LEARNING RESOURCES OF QC

These are going to links to resources which have a simplified explanation of QC, which are not math heavy. With a greater focus on videos rather than papers. Note all of these sources have been studied for the content in this repository.

N | Source | Url | Synopsis
|:--|:--:|:--:|:--:|
1 | ▶️Youtube | [▶️ Quantum Physics made simple - Wave-Particle Duality Animation](https://youtu.be/Xmq_FJd1oUQ) |  Animation describing the dual behavior of a particle as both a wave and a particle
2 | ▶️Youtube | [▶️ Physics - Chapt. 66 Quantum Mechanics (1 of 9) What Is Quantum Mechanics?](https://youtu.be/j-HdVUTemO0) | - Physics lecture on understanding *Quantum Mechanics*, thisi branch exists because standard laws of physics are modified at a subatomic level
3 | ▶️Youtube | [▶️ Quantum Computers, Explained With Quantum Physics](https://youtu.be/jHoEjvuPoB8) |  Understanding quantum computing in light of quantum physics concepts. *Qubits* the fundamenetal processing unit of QC
4 | 📷Slides | [📷 Quantum Physics Infographics](https://slidesgo.com/theme/quantum-physics-infographics) | Simplified understanding of QP by comparison to the macro world
5 | ▶️Youtube | [▶️ If You Don't Understand Quantum Physics, Try This!](https://youtu.be/Usu9xZfabPM) | Source video for *Fig 3: Components of QP*
6 | ▶️Youtube | [▶️ quantum superposition of states and decoherence](https://youtu.be/7B1llCxVdkE) | Animation superposition of quantum states of an electron and decoherence (time taken for the superposition to disappear)
7 | 📃Paper | [📃 Quantum States & Superposition](https://www.southampton.ac.uk/~doug/quantum_physics/superposition.pdf) | Mathematical discussion of Quantum States & Superposition
8 | ▶️Youtube | [▶️quantum tunnel effect and tunneling microscope](https://youtu.be/K64Tv2mK5h4) | Animation quanutm teunneling effect, ie., quantum particles can pass through objects
9 | ▶️Youtube | [▶️ Quantum Tunneling](https://youtu.be/RF7dDt3tVmI) | Animation style explanation of a wave functions



> 🍌 TLDR - Above media is more entertaining than reading the following text

# 🎛️ FUNDAMENTAL PRINCIPLES OF QC

To understand QC we have first to have understand important concepts of quantum physics. The *knowlege tree* looks like the following - 

```mermaid
flowchart TD
    A[Quantum\nComputing] --> B(Define\nQuantum)
    A --> C(Quantum\nPhysics)
    C --> C1(Quantum\nMechanics)
    A --> D(Atomic\nStructure)
    D --> D1(Quantum\nParticles)
    C <--> D1
```
<p align="center">
<i>Fig1: QC knowledge tree</i>
<p> 

## Definition of `Quantum`

Quantum(*Singular*) or Quanta(*Plural*) [defined](http://physicsbuzz.physicscentral.com/2018/02/just-what-is-quantum.html) as the smallest and simplest unit of something. In the case of Quantum Mechanics / Quantum Physics, it refers to a [sub atomic particle](https://www.livescience.com/mystery-of-proton-neutron-behavior-in-nucleus.html), such as [electrons (e<SUP>-</SUP>), protons (p<sup>+</sup>), neutrons (n<sup>0</sup>)](https://www.livescience.com/65427-fundamental-elementary-particles.html). 

> 🍌 TLDR - Quantum means the smallest and simplest unit of thing

## Quantum Physics 

[Quantum physics](https://scienceexchange.caltech.edu/topics/quantum-science-explained/quantum-physics) is the study of matter and energy at the most fundamental level. It aims to uncover the properties and behaviors of the very building blocks of nature.

<p align="center">
<a href="https://bigthink.com/hard-science/the-physics-of-everything-in-one-neat-map/" target="_blank">
<img src="./infogfx/phyla.png">
</a>
<i>Fig 2: Current landscape of understanding of physics</i>
</p>

Fig 2 - Illustrates the evolution of our understanding of physics. Until more recent times due to the advancement of experimental technologies, *Quantum Theories* are only now being observed & proved. Please note that their are active efforts of utilizing the Quantum Phenomenon for computing purposes, but our general understanding of it is quite poor

```mermaid
flowchart TD
    A[Quantum<br>Physics] -->|Objects<br>described as<br>|A1(Wave<br>Functions)
    
    A1 -->|Measuring|B
    subgraph B [Particles Seen]
        direction LR
        B1(Particle Wave<br>Duality) o--o B2(Measurement<br>Problem)
    end

    A1 -->|Consequence|C 
    subgraph C [Quantum Phenomenon]
        direction LR
        C1[Superposition] o--o C11[Entanglement]
        C11 o--o C2
        C2[Quantum\nTunneling] o--oC3[Heisenberg<br>Uncertainity<br>Principle]    
        C3 o--o C4[Energy<br>Quantization]
    end
```
<p align="center">
<i>Fig 3: Components of QP</i>
<p>

1. [**Particle Wave Duality**](https://physicsworld.com/a/wave-particle-duality-quantified-for-the-first-time/) 
[![](./infogfx/pawd.png)](https://www.electrical4u.com/wave-particle-duality/)
<p align="center">
<i>Fig 4: Wave Particle Duality</i>
<p>
One of the most counterintuitive concepts in physics – the idea that quantum objects are complementary, behaving like waves in some situations and like particles in others.
   
2. **Measurement Problem**  - 
[![](./infogfx/mepr.png)](http://www.quantumphysicslady.org/glossary/measurement-problem/)
<p align="center">
<i>Fig 5: QP Measurement Problem</i>
<p>

According to the [Copenhagen Interpretation](https://physicsworld.com/a/thirty-years-of-against-measurement/) (being debated), which states that [during measurement](https://plato.stanford.edu/entries/qm-copenhagen/), the observer gets a subjective perception of what is going on in the quantum space, which means that these particles exhibit the property of [*non-locality*](https://www.scientificamerican.com/article/how-einstein-revealed-the-universe-s-strange-nonlocality/). *Non-locality which basically means, no observed particles have an absolute location in space.* Sub atomic particles are expressed as [wave functions](https://www.quantumphysicslady.org/glossary/wave-function/) ($ \Psi $) ie., only an approxmation of its actual location can be done based on mathematical probabilities and the exact location of the particle is unknown.

The **Measurement Problem** states that these wave functions abruptly collapse into a particle in a point of space in time during observation, whose beahvior is unknown.

3. **Superposition**

Superposition | Decoherence 
|:--:|:--:|
[![](./infogfx/QSP1.png)](https://youtu.be/7B1llCxVdkE) | [![](./infogfx/QSP2.png)](https://youtu.be/7B1llCxVdkE)
<p align="center">
<i>Fig 6: Quantum Superposition & Decoherence</i>
<p>

*Superposition* or *Quantum Superposition* is defined as the ability of a sub atomic particle (such as an electron) to be in [multiple quantum states](https://jqi.umd.edu/glossary/quantum-superposition) all at the same time but when observed only has one state. In the case of an electron which gets excited (jumps to a higher energy state) in the presence of electro magnetic radiation (e.g Magnetic Field) exists in both a high energy state and a low energy state at the same time. This is deduced from the wave patterns during its observation. An important term to also know at this point is *decoherence* which is when superposition can no longer be measured.

### [**Quantum State**](https://www2.ph.ed.ac.uk/~ldeldebb/docs/QM/lect1.pdf) 

Fundamental law of Quantum Mechanics

$$
Quantum State\sim \Psi(x,t)
$$

Where the function $ \Psi $ is the *complex function* which describes *wave-particle duality* (Fig 4) which depends on the coordinate($x$) and time($t$). This wave function indicates that the behavior of a quantum object is [probabilistic](https://quantumatlas.umd.edu/entry/quantum-states/), this means that the wave function encodes all the probabilistic outcomes of the measurement and this *quantum state* equation captures the full range of these possible measurement outcomes.   

[![](./infogfx/wafu.gif)](https://youtu.be/RF7dDt3tVmI)
<p align="center">
<i>Fig 6.1: 3d Illustration of a wave function</i>
<p>

1. **👻Entanglement** (also referred to as Spooky Action)

[![](./infogfx/QEN.png)](https://www.nasa.gov/feature/jpl/particles-in-love-quantum-mechanics-explored-in-new-study)
<p align="center">
<i>Fig 7: Quantum Entanglement or Spooky Action</i>
<p>

In [Quantum Theory](https://blogs.scientificamerican.com/observations/what-does-quantum-theory-actually-tell-us-about-reality/),  [Quantum Entanglement is most bizzare and mysterious properties of quantum particles](https://www.livescience.com/what-is-quantum-entanglement.html), which states that two subatomic particles can be intimately linked to each other even if seperated by [billions of years light years in space](https://www.space.com/31933-quantum-entanglement-action-at-a-distance.html) ie., any change induced in one particle will affect the other. The mechanics of this behavior is unknown.

 These two particles share a common unified [quantum state](https://www2.ph.ed.ac.uk/~ldeldebb/docs/QM/lect1.pdf), such that any observation of one of these particles will provide information aboth the other entangled particles. And any action to one of these particles will invariably impact the others in the entangled system. 


5. **Quantum Tunneling**   

[![](./infogfx/QuTu.gif)](https://youtu.be/K64Tv2mK5h4)
<p align="center">
<i>Fig 8: Quantum Tunneling</i>
<p>

[Quantum Tunnelling is a phenomemnen](http://abyss.uoregon.edu/~js/glossary/quantum_tunneling.html) which has no counterpart in classical physics, it states that particles can [penetrate a potential energy barrier](https://opentextbc.ca/universityphysicsv3openstax/chapter/the-quantum-tunneling-of-particles-through-potential-barriers/) with a height greater than the total energy of particles. In simple terms quantum tunnelling is where an atom or a [subatomic particile can appear on the opposite of a barrier](https://www.livescience.com/quantum-tunneling-observed-and-measured.html) that should be impossible for the particle to penetrate. This is an important property in understanding [energy production models of the sun.](https://www.academia.edu/11446310/Quantum_tunnelling_in_the_sun) 


## Atomic Structure

The following diagram is an illustration of the [Standard Model](https://simple.wikipedia.org/wiki/Standard_Model) of elementary particles as described by the [particle theory in physics.](https://www.le.ac.uk/se/centres/sci/selfstudy/particle01.html)

[![](./infogfx/Particles.jpg)](https://www.livescience.com/60900-tetraquark-particle-exists.html)

> 🍌 Every thing can be broken own into smaller units. The most commonly known unit is the *molecule*. *molecules* in turn are made of smaller particles, and so and so forth until we reach the limits of observation.

## Quantum Particles



## [Quantum Mechanics](https://www.livescience.com/33816-quantum-mechanics-explanation.html) 

Defined as a sub field of physics that describes interaction between particles of the sub atomic realm. *Sub Atomic* referring to the particles that form the atoms, and those particles that form the atoms.

### Wave Functions


```mermaid 
flowchart TD 
    A --> B
```

# 🐱‍💻 Quantum Computing (Finally 🙃)

Now that we have a firm grasp (😁) of the important fundamental of QC, the following are a curated sources for some experimentation

# 🔎 References

Majority of the references will be 

1. [Header Quantum Entanglement Gif](https://tenor.com/view/entanglement-quantum-entanglement-science-atoms-gif-17770432) - Actual source of image is not described. The illustration is factual as described [HERE.](https://www.livescience.com/what-is-quantum-entanglement.html)

# 📒 GLOSSARY 

n | Term | Expansion
|:--|:--:|:--|
1 | QC | Quantum Computing 
2 | QP | Quantum Physics 
3 | QP | Quantum Mechanics