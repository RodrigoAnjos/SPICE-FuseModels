# Introduction
Although fuses are relatively simple devices from a constructive pesrpective, modelling such devices is not so straightforward. Being inherently non-linear and thermally coupled devices, precise models are very hard to come by. Although in most scenarios fuse models can be ignored, in some specific applications precise models can dictace if the electronic project is a success or not.


$$[Figure 1]$$


# Objectives

Given such considerations, our objectives in this repository are few:
1. Review the physical aspects of fuses and understand their principle of operations, with special care to their non-linear properties and coupling properties.
2. Build increasingly precise models, with special care to clearly delimitate the **mathematics** governing each model; the **application scenarios** in which such models are valid; and which **parameters** are required for such model operations.

At the end of this document, we should have a comprehensive view of all of the models that could be applied and how could one build them. Additionally, some though will be given in how could a technician extract such models.

A necessary disclaimer that should be taken into considerations is that the models provided here are purely a academic interpretation of a well known and used electrical device. Thus, such models provided here are not extensively validated and should be used with care. 

# Methodology

## First Steps
As almost anyone that has interest in this topic should already know by now, fuses are devices that essentially protect our circuits from excessive current. This device should be designed into a electronic project as one of the **weak-links** that predictably fail before any other component (specially the critical ones) do so.

Before any physical equation is layed-out, let's start our journey by taking a birds eye view of how fuses can be cathegorized, which will give us some perspetive of what are the key design parameters.

$$[What are the fuse types]$$

$$[key parameters from mouser.com]$$

## Physical Modelling
Although not all fuses are of the typical glass catridge type, we will use this version of the device as a simple physical basis for our models.

$$[figure of glass cartridge fuse]$$

Generically speaking, all fuses work by breaking the circuit's continuity by melting a thin conductive wire (W). As our main goal is to melt the wire, and not create a fire hazard, our thin conductive wire should be resistant to oxidation, and thus are made of silver alloys or coated with silver. In order to create a fuse with predictable behavior, typical glass cartridge fuses encapsulate this thin strip of wire inside a glass barrel (G) with metalic end-caps (M), avoiding the penetration of any foreign elements that could affect the fuse's characteristics and allowing for current to flow from one side to the other. 

Although the description above is rather obvious, it will guide our though process through the physical modelling of the fuse. As the most important aspect of a fuse is that it melts a thin strip of wire to break contact, our first modeled aspect will be Thermal. To do so, we will make usage of the Thermal Equivalent Circuit technique, which heat transfer is modelled through thermal resistances, capacitances, heat sources and temperature potentials. To aid in our though process, we will also make use of the FEMM 4.2 software, which is not only free, but also solves 2D Transient Heat-Conduction problems.

Our problem can be well defined by the following hypothesis and boundary problems:
1. [H1]: All physical elements of the problem have no internal temperature differential (homogeneus internal temperature)
2. [H2]: Both convection and radiation phenomena are ignored


$$[figure of glass cartridge thermal properties]$$

As can be seen in the figure above, 



## [Model 1] - The Naive apporach

## [Model 2] - Adding Energy

## [Model 3] - Considering Time Constants 

## [Model 4] - 

# Results


# Discussion


# References
https://electrical-engineering-portal.com/fuses-principles-of-design-and-operation
https://grlcn.com/cartridge-fuse/
https://www.kempstoncontrols.com/knowledge-base/guide-to-fuses