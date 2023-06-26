---
layout: page
title: Research
permalink: /Research/
image: research.png
---

Essentially, we are working on one topic: “structures in fire”. Separately speaking, we need to think about ‘What will structures be in future?’ and ‘How to tackle the evolving fire safety challenges’.

## What will structures be in future?
#### Elegantly Designed and Constructed Structures
![]({{site.baseurl}}/images/optimization.png)
We have a Vision of Future Structures as it should be of an optimal form and performance and should be elegantly constructed using autonomous robots. Currently we are developing new structural design methodologies for this goal. We use topology optimization to find optimal structural designs to meet the needs on aesthetics, load-resisting performance, and the construction ability towards autonomous approaches such as 3D concrete printing. We have developed the topology optimization package co-working with OpenSees, which is a long-time toolbox to us. We have developed isogeometric analysis elements in OpenSees that uses NURBS curves for geometric description and shape functions, which perfectly fit the design practice as it also uses NURBS as fundamental basis. While using topology optimization for structural designs, we have implemented the width control, stress limits, and architects concerned pattern into the package as objective functions. In future, we would like to develop OpenSees as a design tool in the era of autonomous construction, aiming for an integrated tool to bridge the architecture design, structural design, and construction. Go to [OPS-ITO](https://doi.org/10.1016/j.cad.2023.103517).

#### Using timber as fire-safet and low-carbon structural components
![]({{site.baseurl}}/images/timber.jpg)
While pursuing future structures of aesthetic appeal and construction automation, we believe the structural materials will continuously evolve. Timber is an ideal structural material ensuring low carbon emission and high structural performance, and timber is favoured by architects for its natural finish. Since the fire safety of timber structures has been a long-standing challenge as timber members can contribute fuel to a fire. Traditional design approaches for timber structures have focused on estimating the char propagation in Standard fires, and the Eurocode models for timber have been devoted to this purpose. However, when considering the impact of realistic fire, the effect of non-uniform and non-standard burning in compartments indicates the key necessity of developing a suitable engineering model to estimate the realistic thermal responses of timber sections. Go to [Timber modelling](https://doi.org/10.1002/fam.3115).

#### Using 3D concrete printing for autonomous construction
![]({{site.baseurl}}/images/3dprinting.png)
Autonomous construction is of essential need to the current building industry, and 3D concrete printing is a promising technology to achieve this vision. We have built a network of collaborators on 3D concrete printing construction, including research institutes working on concrete materials for printing and autonomous control technologies from mechanical engineering, and industry collaborators to support future real application. In particular, we want to integrate the advanced technologies of 3D concrete printing into the construction of structural systems.

***

## How to tackle the evolving fire safety challenges?
#### CFD simulation and fire testing to understand fire behaviour
![]({{site.baseurl}}/images/fire_behaviour.png)
Improving fire safety performance of modern buildings has been an ultimate goal of our research. This has been complicated by the evolution of building design and introduction of sustainable construction materials. It has been found that a travelling behaviour can sustain in a large open-plan compartment (e.g. office) but may be replaced by a post-flashover fire after the ignition of timber members. We have been working on CFD simulation of fires to understand the fire behaviour and a series of fire models have been proposed. On the experimental side, we have conducted a number of fire tests and we will keep doing so for validation of models. Moreover, the recently purchased H-Tris Radiant Panel testing system can provide fire-equivalent testing on building materials, as it offers unparalleled capability of heat flux range (0~250kW/m2) and observable responses facilitated by external heating approach.

#### A software platform: OpenSees for fire
![]({{site.baseurl}}/images/opsfire.png)
We have  been  dedicated to developing OpenSees to perform integrated simulation of structures and the fire edition was started in University of Edinburgh by Prof Asif Usmani. Modelling modern buildings responding to fires, comprises modules such as fire models, heat transfer module, thermo-mechanical codes and GUI interface. After years of development, we have enabled interface to CFD  models, integration middleware, and preprocessor and post-process tool  GiD for OpenSees. We have been published  a  number of publications  on OpenSees for  fire and this simulation platform has enabled large flexibility for realising the  latest research methodologies  for simulating modern buildings in complex fires. Go to our project website: [openseesforfire.github.io](http://openseesforfire.github.io/)

#### A testing platform: e-controlled radiant panel testing system
![]({{site.baseurl}}/images/Panel.png)
This radiant panel testing system is supported by the Large Equipment Fund(LEF2021-022). The system comprises a radiant panel complex, gas suppliers and controller items. The radiant panel covering a large range of heat flux (up to 200kw/m2 equivalent to large fires) is externally applied to the testing specimens, which enables direct observation of students on the thermal performance and fire response of building materials and devices. Particularly, each unit can be individually activated (e.g., only Unit 1, or Units 1&2, or all units) to offer high flexibility allowing various scales of testing. We have been developing a e-controlled version upon this radiant panel system. A GUI software has been developed by Mr Siyu Liang to access the control modules of the gas-air suppliers and the newly built servo-controlled trail. We have been using this system to test the fire response of construction materials, which essentially facilitated the observation and the real fire equivalent testing.
<iframe src="https://www.youtube.com/embed/TlnzLhNGrxw" frameborder ="0" allowfullscreen></iframe>

<br>
#### Hybrid simulation/testing based on OpenSees for fire platform
![]({{site.baseurl}}/images/hybrid.jpg)
The idea of hybrid testing is to analyze global behaviour using a structural system model and to capture local behaviour of structural members using laboratory tests. We know a large model using beam type elements can not describe complex local behaviour such as buckling induced by fire protection damage or localised heating, nor is possible to use full-3D detailed models for a whole building structure. Using OpenFRESCO as middleware and OpenSees for fire platform, we are hoping to use hybrid simulation/testing techniques to reshape the research methodology when evaluating modern buildings in fire. More excitingly, we can bring the AI approach into the simulation framework and relevant papers will come out soon. 


***
## Strategic collaboration on testing facilities and research
* Fire testing and hybrid testing in Tongji University, supported by MoU and an open fund project with [Prof LI Guoqiang](http://steelpro.net/Default.aspx).
* Large-scale fire testing in Wuhan University, Hubei Fire Research Center
* Large-scale fire testing in Sichuan Fire Research Institute ([SCFRI](https://www.scfri.cn/))
* Fire testing in China University of Mining and Technology (CMUT)
* Steel fire research group in Chongqing University([Prof WANG Weiyong](http://wangfire.net/))
* Fire safety engineering research with [Fire Group in University of Queendland](https://civil.uq.edu.au/research/fire-safety-engineering), Australia (UQ)
* Low carbon building with University of Sheffield, University of Nottingham, UK.
* Smart Construction collaborating with Shandong University ([Prof WANG Peijun](https://www.tjsl.sdu.edu.cn/info/1316/4573.htm)).
* Industrial collaborators: an extensive collection  of industrial collaborators built while working in Country Garden Group, e.g. China Construction Group, Shanghai Construction Group, a number of Real-estate developers.