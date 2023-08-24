# CONCORNET2023 (Corrosion Damage on Concrete Structures Image Dataset) 🧑‍🏫

![](Corrosion_detection_.png)
 
## Description: 📝
This repository stores an image dataset about corrosion damage on concrete structures.

## Dataset Title: 👌
CONCORNET2023: Corroded concrete Image dataset for machine learning and deep learning applications.

## Researchers 🧑‍🔬
- *Dr. José A. Guzmán-Torres* <br />
jose.alberto.guzman@umich.mx <br />
https://orcid.org/0000-0002-9309-9390

- *Dr. Francisco J. Domínguez-Mota* <br />
francisco.mota@umich.mx <br />
https://orcid.org/0000-0001-6837-172X
- *Dr. Gerardo Tinoco-Guerrero* <br />
gerardo.tinoco@umich.mx <br />
https://orcid.org/0000-0003-3119-770X

Universidad Michoacana de San Nicolás de Hidalgo, Faculty of Civil Engineering <br />
AULA-CIMNE, Morelia

## Project summary, description or abstract: 📚
<p align="justify"> CONCORNET2023 is a labeled image dataset for training, testing, validating, and benchmarking artificial intelligence-based corrosion detection algorithms for concrete structures. </p>

<p align="justify"> CONCORNET2023 contains 790 photographs of concrete structures with signs of corrosion problems. The photos relate to various concrete structures such as columns, beams, slabs, etc. </p>

<p align="justify"> The dataset includes different corrosion damage levels and photographs with various perturbations, including channel shift, horizontal flip, horizontal shift, random rotation, and random zoom.</p>

<p align="justify"> CONCORNET2023 will come in handy for the continued development of concrete corrosion detection tasks on algorithms based on deep learning, a field gaining momentum in Civil Engineering applications. </p>

## Files description: ✍️
<p align="justify"> The repository contains a directory named Images, which contains the corrosion images on concrete structures in three sub-directories, train (632), test(79), and val (79). All the images are two-dimensional color images with .jpg extension. </p>

 <p align="justify"> Also, this repository stores a file named best.pt, which contains the computed weights using the YOLOv3 framework (ultralytics/yolov3) by the authors. The retrieved weights are parameters related to the employment of CONCORNET2023. </p>

## Definition of acronyms: ✨
CONCORNET2023: Concrete Corrosion Network 2023.

## Please cite the following paper if you use this dataset in your research:

@article{guzman2023damage, <br />
author = {Guzmán-Torres, José A and Domínguez-Mota, Francisco J and Martínez-Molina, Wilfrido and Naser, MZ and Tinoco-Guerrero, Gerardo and Tinoco-Ruíz, José G}, <br />
title = {Damage Detection on Steel-Reinforced Concrete Produced by Corrosion via YOLOv3; A detailed guide}, <br />
journal = {Frontiers in Built Environment}, <br />
volume = {9}, <br />
pages = {41}, <br />
year = {2023}, <br />
publisher={Frontiers} <br />
doi = {http://dx.doi.org/10.3389/fbuil.2023.1144606 }, <br />
URL = {https://www.frontiersin.org/articles/10.3389/fbuil.2023.1144606/full }, <br />
}
