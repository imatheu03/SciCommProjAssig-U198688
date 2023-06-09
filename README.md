# SciCommProjAssig-U198688

Hi, my name is Inés Matheu (u198688) and I am a Biomedical Engineering student at Universitat Pompeu Fabra! This repository contains sample code and the materials associated with the paper "In vitro neuronal cultures and network analysis to build a proof-of-concept biological computing AI device", written by Auba Fuster Palà. The aim of this is to bring some light to what the project was about and to briefly summarize the methods that were employed. I hope you find it useful!


## In vitro neuronal cultures and network analysis to build a proof-of-concept biological computing AI device ##

_By Auba Fuster Palà_



**Table of Contents**

- [Abstract](#abstract)
- [State of the art](#state-of-the-art)
- [Hypothesis and Objectives of the paper](#hypothesis-and-objectives-of-the-paper)
- [Methodology](#methodology)
- [Results and Conclusions](#results-and-conclusions)
- [Bibliography](#bibliography)
- [Citation](#citation)
- [License](#license)

 
 
## Abstract

The limitations of current computation and artificial intelligence approaches have led to the emergence of biological computation, which has been studied in recent years as an alternative to traditional computation methods. The NeuChiP European project (in which this study partakes) aims to develop a proof-of-concept for a biological computing AI device. This thesis investigated different culture setups using both primary cultures and human induced pluripotent stem cell (iPSC)-derived cortical neurons as a first step towards biological computation. The cultures were recorded using calcium imaging, and the results were analyzed from a network perspective to study activity and connectivity. 
The findings indicated that culture functional connectivity could be configured through physical constraints, chemical agents affecting synaptic transmission, and mechanical agents like random cuts, which had a direct effect on network activity and connectivity. However, the cultures eventually adapted to external changes due to the inherent plasticity of biological neuronal networks, highlighting the need for effective and durable stimulation methods. Finally, it was stated that reproducing results with primary cultures using iPSC-derived cortical neurons was challenging but essential for future studies in the biological computing research field.



## State of the Art

Artificial intelligence (AI) and machine learning have become integral to various fields, with significant global impact [1]. Neural networks, a key AI technology, have played a crucial role in the AI revolution [2]. Initially, AI research explored both symbolism and connectionism, but connectionism prevailed due to its efficiency and effectiveness [3]. However, current AI systems have limitations such as unsustainable energy consumption and the need for extensive computing power. To overcome these constraints, the NeuChip project aims to develop a biological computation alternative inspired by the human brain. It seeks to use human neural networks as low-power computing components, surpassing conventional artificial neural networks in adaptability and performance [4]. In vitro neuronal cultures are being studied to build high-capacity AI systems with modest energy consumption and self-organization. Challenges include recreating the rich spatiotemporal activity patterns of native tissue and inducing patterning in the connectivity of neuronal cultures. Such biological computation has a lot of potential, including applications in medical therapies and studying neurodegenerative diseases. Neuroengineering with in vitro neuronal cultures makes possible the exploration of network architecture and dynamics in disease research and transplant therapies.


## Hypothesis and Objectives of the paper

The hypothesis of this paper suggests that neuronal cultures and network analysis techniques can be used to shape in vitro network dynamics and control spatiotemporal activity patterns, mimicking the complexity of the brain. The stated objectives include: 
- Designing PDMS molds for shaping neuronal connectivity
- Generating cortical neurons from human iPSC
- Preparing neuronal cultures on PDMS molds
- Measuring neuronal activity using calcium imaging recordings
- Analyzing the data using MATLAB extensions
- Defining experimental setups to observe the behavior of the cultures under different conditions.

## Methodology

Here we have a general pipeline for the methodology employed for this project! For a more detailed explanation of some of the methods, you can check the Wiki Page!

![image](https://github.com/imatheu03/SciCommProjAssig-U198688/assets/132487259/94784b59-df24-4667-a27c-3b91dc92c0e6)

## Results and Conclusions

This research successfully demonstrated the viability of various experimental setups using a single methodology and protocol. When it comes to temporal evolution of patterned cultures and the effects of physical constraints on network connectivity, it is suggested the need for more precise and durable physical constraint methods to maintain network connectivity in mature cultures,as the plasticity of the networks lead to adapting to the test actions. 

![image](https://github.com/imatheu03/SciCommProjAssig-U198688/assets/132487259/f61edd23-c522-42e5-8158-1146045f11ff)
_Figure 10 in: Fuster Palà, Auba. “In vitro neuronal cultures and network analysis to build a proof-of-concept biological computing AI device.” (2022)_

In the case of bicuculline, there is a contradiction between the expected decrease in inter-burst interval (IBI) and the observed increase, which has been reported in previous studies as well. They propose potential reasons for this inconsistency, including the influence of refractory periods and the specific topographical PDMS pattern used in the experiments. Regarding CNQX, it was confirmed its inhibitory effects on excitatory synapses and demonstrates the culture's ability to recover partially from the perturbation by increasing synaptic weights. However, this recovery is accompanied by a loss of variability in spatiotemporal activity patterns. It is also discussed the effects of an external perturbation in the form of a controlled incision on the neuronal cultures. It describes the changes in network fraction, variability, and richness of activity following the perturbation, as well as the alterations in connectivity parameters and organization.
The study suggests that the cultures are capable of fighting against perturbations and adapting their activity as to mantain the network. Overall, the research provides insights into the dynamics and plasticity of in vitro neuronal cultures, highlighting their potential for studying network activity and investigating synaptic plasticity phenomena.


## Bibliography

[1] Dwivedi, Y. K., et al. (2021). Artificial Intelligence (AI): Multidisciplinary perspectives on emerging challenges, opportunities, and agenda for research, practice and policy. International Journal of Information Management, 57, 101994. https://doi.org/10.1016/j.ijinfomgt.2019.08.002

[2] Gallant, S., I. (1993). Neural Network Learning and Expert Systems; Mit Press. Bradford Book. ISBN 978-0262527897

[3] Minsky, M and Papert, S. (1972). Perceptrons: An Introduction to Computational Geometry. The MIT Press. ISBN 0-262-63022-2

[4] Chelly Dagdia, Z., Avdeyev, P., & Bayzid, M. S. (2021). Biological computation and computational biology: survey, challenges, and discussion. Artificial Intelligence Review, 54(6), 4169–4235. https://doi.org/10.1007/s10462-020-09951-1 


## Citation
If you want to use the ideas presented in the paper for your own research, please consider citing the original paper:
Fuster Palá, Auba. In vitro neuronal cultures and network analysis to build a proof-of-concept biological computing AI device. 2022
http://hdl.handle.net/10230/54577

## License
Creative-Common License (CC 4.0)
