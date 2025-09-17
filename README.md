![header](src/header.jpg)

# NaturalAntibody Platform

This package provides an implementation of the on-premise version of the NaturalAntibody PLatform. Use of this Software is subject to the [Standard Terms and the End User License Agreement (EULA)](https://github.com/NaturalAntibody/on-premise/blob/master/EULA.pdf). By downloading, installing, or using the Software, you acknowledge that you have read, understood, and agree to the [Standard Terms and Conditions](https://github.com/NaturalAntibody/on-premise/blob/master/STANDARD%20TERMS%20AND%20CONDITIONS.pdf) and [End-User License Agreement](https://github.com/NaturalAntibody/on-premise/blob/master/LICENCE).

NaturalAntibody Platform is available at for commercial and non-commercial use. More about Platform you can find at [naturalantibody.com](https://naturalantibody.com/).

If you have any questions, please contact the NaturalAntibody team at [contact@naturalantibody.com](mailto:contact@naturalantibody.com).


## About NaturalAntibody Platform
NaturalAntibody is an artificial intelligence-based platform that allows in silico discovery and design of antibodies. It combines the comprehensive Antibody Database with modules for predicting antibody characteristics such as immunogenicity, mutability, and developability.

Using the platform, you can quickly check if a given sequence was observed in any of the covered databases (patents, scientific literature, GenBank, and more), find a similar sequence with legal protection, or leverage antibody data for predictive tasks such as mapping the mutational diversity, immunogenicity or developability of antibodies.

The GUI platform version consists of four main modules:

*   Antibody Database - to find antibody-related information in all major external databases (e.g. patents, GenBank, therapeutics etc.).
*   Sequence Engineering - optimization of single sequences, e.g. humanization, liabilities removal.
*   Batch Sequence Annotation with Clustering - filtering and clustering of repertoire data by computationally annotated liabilities for improved candidate selection.
*   Structure Modeling - create a 3D model of your antibody structure using the latest deep learning methods
*   Antibody Docking - Given structures of an antibody (ligand) and antigen (receptor) generate a number of possible binding orientations (decoys) sorted by predicted quality metric of molecular interface.



## Installation and Running Platform

See the [Setup for NaturalAntibody On Premise](https://github.com/NaturalAntibody/on-premise/blob/master/Setup%20for%20NaturalAntibody%20On%20Premise.pdf) pdf. Document outlines how to create a setup to run dockers that are needed to run our application in your environment. All the examples are based on how we did it with our infrastructure, but it should be as much service-agnostic as possible. In your case, some resources might have to be adjusted.

We will provide you with an example of Kubernetes manifests. In this document we will sometimes reference names of those manifests when discussing applying it. We are using Fargate and EC2 for this setup.
