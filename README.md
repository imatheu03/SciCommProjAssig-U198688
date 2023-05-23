# SciCommProjAssig-U198688

My name is Inés Matheu (u198688) and I am a Biomedical Engineering student at Universitat Pompeu Fabra. This repository contains sample code and the materials associated with the paper "In vitro neuronal cultures and network analysis to build a proof-of-concept biological computing AI device", written by Auba Fuster Palà. The aim of this repository is to bring some light to what the project was about and to briefly summarize the methods that were employed. 



## In vitro neuronal cultures and network analysis to build a proof-of-concept biological computing AI device ##

_By Auba Fuster Palà_



**Table of Contents**

- [Abstract](#abstract)
- [State of the art](#state-of-the-art)
- [Hypothesis and Objectives of the paper](#hypothesis-and-objectives-of-the-paper)
- [Methodology](#methodology)
- [Results and Conclusions](#results-and-conclusions)

 
 
## Abstract

The limitations of current computation and artificial intelligence approaches have led to the emergence of biological computation, which has been studied in recent years as an alternative to traditional computation methods. The NeuChiP European project (funded in the European Union's Horizon 2020) aims to develop a proof-of-concept for a biological computing AI device. This thesis investigated different culture setups using both primary cultures and human induced pluripotent stem cell (iPSC)-derived cortical neurons as a first step towards biological computation. The cultures were recorded using calcium imaging, and the results were analyzed from a network perspective to study activity and connectivity. 
The findings indicated that culture functional connectivity could be configured through physical constraints, chemical agents affecting synaptic transmission, and mechanical agents like random cuts, which had a direct effect on network activity and connectivity. However, the cultures eventually adapted to external changes due to the inherent plasticity of biological neuronal networks, highlighting the need for effective and durable stimulation methods. Finally, it was stated that reproducing results with primary cultures using iPSC-derived cortical neurons was challenging but essential for future studies in the biological computing research field.


## State of the Art

Artificial intelligence (AI) and machine learning have become integral to various fields, with significant global impact. Neural networks, a key AI technology, have played a crucial role in the AI revolution. Initially, AI research explored both symbolism and connectionism, but connectionism prevailed due to its efficiency and effectiveness. However, current AI systems have limitations such as unsustainable energy consumption and the need for extensive computing power. To overcome these constraints, the NeuChip project aims to develop a biological computation alternative inspired by the human brain. It seeks to use human neural networks as low-power computing components, surpassing conventional artificial neural networks in adaptability and performance. The University of Barcelona is involved in shaping network self-organization and training as part of the project. In vitro neuronal cultures are being studied to build high-capacity AI systems with modest energy consumption and self-organization. Challenges include recreating the rich spatiotemporal activity patterns of native tissue and inducing patterning in the connectivity of neuronal cultures. Such biological computation has vast potential, including applications in medical therapies and studying neurodegenerative diseases. Neuroengineering with in vitro neuronal cultures enables the exploration of network architecture and dynamics in disease research and transplant therapies.


## Hypothesis and Objectives of the paper

The hypothesis of this paper suggests that neuronal cultures and network analysis techniques can be used to shape in vitro network dynamics and control spatiotemporal activity patterns, mimicking the complexity of the brain. The stated objectives include: 
- Designing PDMS molds for shaping neuronal connectivity
- Generating cortical neurons from human iPSC
- Preparing neuronal cultures on PDMS molds
- Measuring neuronal activity using calcium imaging recordings
- Analyzing the data using MATLAB extensions
- Defining experimental setups to observe the behavior of the cultures under different conditions.

## Methodology

Here we have a general pipeline for the methodology employed for this project! For a more detailed explanation of some of the methods, you can check the Wiki page!


## Results and Conclusions

The discussed text presents the findings and implications of a research project involving in vitro neuronal cultures. The study aimed to explore experimental setups and methodologies for shaping and controlling spatiotemporal activity patterns in these cultures, as well as investigating their potential for mimicking brain richness and complex computations. The research successfully demonstrated the viability of various experimental setups using a single methodology and protocol. The text discusses the temporal evolution of patterned cultures and the effects of physical constraints on network connectivity. It suggests the need for more precise and durable physical constraint methods to maintain network connectivity in mature cultures. The text also discusses the use of chemical agents, such as bicuculline and CNQX, to modulate neuronal activity. It explains the expected effects of these agents based on previous studies and compares them to the obtained results. In the case of bicuculline, there is a contradiction between the expected decrease in inter-burst interval (IBI) and the observed increase, which has been reported in previous studies as well. The text proposes potential reasons for this inconsistency, including the influence of refractory periods and the specific topographical PDMS pattern used in the experiments. Regarding CNQX, the text confirms its inhibitory effects on excitatory synapses and demonstrates the culture's ability to recover partially from the perturbation by increasing synaptic weights. However, this recovery is accompanied by a loss of variability in spatiotemporal activity patterns. The text also discusses the effects of an external perturbation in the form of a controlled incision on the neuronal cultures. It describes the changes in network fraction, variability, and richness of activity following the perturbation, as well as the alterations in connectivity parameters and organization. The study suggests that the cultures are capable of fighting against perturbations and adapting their activity. Overall, the research provides insights into the dynamics and plasticity of in vitro neuronal cultures, highlighting their potential for studying network activity and investigating synaptic plasticity phenomena.

## Preface or Prologue

One of the most fascinating aspects of my Biomedical Engineering Degree is the multidisciplinary nature of the subjects, teachers, and knowledge we acquire. Therefore, I eagerly sought a final bachelor's project that embraced this multidisciplinary approach, and the NeuChip European project provided the perfect opportunity. The project's central theme, biological computation, captivated my interest, as attempting to mimic brain functions with real biological neurons in the lab represented a complex and ambitious objective for my thesis.

The NeuChip project is a collaborative effort among entities from various European institutions, including Aston University, University of Barcelona, Loughborough University, French National Centre for Scientific Research, Technion – Israel Institute of Technology, and 3Brain AG company from Switzerland. Each entity has distinct roles and defined objectives within the project, ranging from in silico work in modeling biological neural networks to cellular differentiation and chemical work in building microscale plastic patterns. Despite our diverse academic backgrounds and specific objectives, we collaborate and work together on discussions and major decisions. In fact, just weeks before submitting this thesis, I had the honor of actively participating in the project's first annual face-to-face meeting in Barcelona.

As a biomedical engineer, I was able to provide a broad perspective on the project's feasibility and the interconnection of different components, bridging the computational and biological realms. This is also why I had two supervisors, as I aimed to incorporate both computational and experimental work into this thesis to make it as comprehensive as possible, reflecting the role of a biomedical engineer.

Furthermore, I would like to emphasize the significance of biological computation. Alongside the examples presented in this thesis, it is important to note that the NeuChip project received funding from the European Union's Horizon 2020 program, underscoring the academic research interest in biological computation. Industry stakeholders are also invested in this field, exemplified by the inclusion of 3Brain, a company involved in the NeuChip project, and the European Union's mid-term objective of creating a spin-off company.
