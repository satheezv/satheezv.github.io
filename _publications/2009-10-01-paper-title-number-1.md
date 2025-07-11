---
title: "Multi-Head Path Planning of SwarmItFIX Agents: A Markov Decision Process Approach"
collection: publications
category: Conference
permalink: "https://doi.org/10.1007/978-3-030-20131-9_221"
excerpt: 'In this work, an artificial intelligence technique developed based on Markov Decision Process (MDP) is implemented for the task of multi-head based fixturing suitable for operations such as drilling, milling etc.'
date: 2019-06-14
venue: 'IFToMM WC 2019. Mechanisms and Machine Science'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://link.springer.com/chapter/10.1007/978-3-030-20131-9_221'
# bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Veeramani, Satheeshkumar, et al. "Multi-head path planning of SwarmItFIX agents: A Markov decision process approach." IFToMM World Congress on Mechanism and Machine Science. Cham: Springer International Publishing, 2019.'
---
SwarmItFIX is a flexible fixturing system designed and developed for sheet metal manufacturing applications. In this work, an artificial intelligence technique developed based on Markov Decision Process (MDP) is implemented for the task of multi-head based fixturing suitable for operations such as drilling, milling etc. The trajectory of the machining tool is split into various line segments for the ease of applying the MDP. The MDP is applied for obtaining the state parameters such as position coordinates and orientation of the intermediate heads of all the segments individually. The state parameters of the corner heads are calculated directly by finding the intersection angles of consecutive segments. In MDP, the evolution of utility values of all states are obtained using value iteration algorithm. For the convergence of the optimal policy of all segments in the contour, the policy iteration algorithm is employed. The execution time of both the algorithms were observed. Finally, the multi-head path planning model has been developed based on the algorithm having least execution time. The model returns the optimal policies for all the segments. Computer simulations are performed, and the results show that the multi-robot heads could be positioned in an effective manner in the given trajectory. Therefore, in near future the developed multi-head path planning model will be tested and implemented into the SwarmItFIX setup at the PMAR laboratory, University of Genoa.