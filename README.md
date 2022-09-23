# Nordic44
## Introduction
This is the repository for the Nordic44 that is a synthetic power system model of the Nordic high voltage transmission system described in [IEC](https://www.iec.ch/homepage) Common Information Model [(CIM)](https://en.wikipedia.org/wiki/Common_Information_Model_(electricity)) .

## Purpose
The main objective of Nordic44 is to provide the necessary information to do market based simulation of the nordic electrical power grid. This include the support for:
- Static Power flow 
- is to develop a grid model "translator" capable of transforming the information (parameters & structure) and the physical behavior of the simulation models. This entails to transform each of a grid model’s sub-systems (e.g. generator, turbine, controller, etc.) from one endogenous representation, to many exogenous representations. This is achieved by using a “model transformation” (MT) tool developed in the project. The aim of using an MT solution is to save effort and to reduce errors by automating the building and modification of models where possible. An MT can be seen as a computer program that takes models as an input (source), and produces models as an output (target), by specifying the metamodel (model of a model) to which target or source models conform.




## Content

## Related work
### DIGIN10
The Nordic44 is intendent to be created so that it can be merged with the [DIGN10](https://github.com/digin-energi/Grunnprofil) project so that is possible to do analysis accross High Voltage (HV), Medium Voltage (MV) and Low Voltage (LV).

### NYPA Model Transformation
A version of Nordic44 has been used in the [NYPA Model Transformation](https://github.com/ALSETLab/NYPAModelTransformation).
In the repository there are multiple version of [Nordic44](https://github.com/ALSETLab/NYPAModelTransformation/tree/master/ModelTransf-Tool/Prototype/examples/nordic-44) and relevant PSSE.  

## Accreditation
The first released version of the Nordic44 model was published in the following paper, with the following authors:
L. Vanfretti, S.H. Olsen, V.S. Narasimham Arava, G. Laera, A. Bidadfar, T. Rabuzin, S. H. Jakobsen, J. Lavenius, M. Baudette and F.J. Gómez-López, “An Open Data Repository and a Data Processing Software Toolset of an Equivalent Nordic Grid Model Matched to Historical Electricity Market Data,” Data in Brief (Elsevier), February 17th 2017. http://dx.doi.org/10.1016/j.dib.2017.02.021
The original PSSE based model was provided by Emil Hillberg at STRI (https://www.stri.se/).

The original Nordic44 model was created to support static power flow and dynamic stability analysis under relevant marked condition for the nordic power system based on the market data published by Nord Pool (https://www.nordpoolgroup.com/en/). It was trained and validated for all electricity market's operation hours during 2015 with power flow and dynamic response. The result was used to train and test Machine Learning techniques (e.g. Decision Trees) and other computational techniques that
are essential in the work flows used for dynamic security assessment of electrical power systems.

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg
