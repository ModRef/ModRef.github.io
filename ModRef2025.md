---
layout: Layout2025
title: ModRef 2025
redirect_from: "/"
---

ModRef 2025 is the 24th in a [series of workshops on Constraint Modelling and Reformulation](https://www-users.york.ac.uk/~af9/ModRef/) organized as part of CP 2025, the [31st International Conference on Principles and Practice of Constraint Programming](https://cp2025.a4cp.org/).
It will be held on September 2nd, directly preceding the CP conference. 

The importance of modelling and model reformulation is widely recognised, particularly for CP but also for MIP, SAT, SMT and other kinds of general-purpose solvers. There has been significant research effort in recent years into modelling and model reformulation, such as automating techniques used by expert modellers, and developing tools and techniques to target multiple types of solvers from one model. 

The purpose of ModRef is to be a forum for all kinds of work in constraint modelling, including new models or new modelling ideas for any amenable problem (whether a new application or a classic benchmark), constraint reformulation techniques to improve the performance of models when solved by general-purpose solvers, and automated modelling techniques, tools, and languages. We solicit original papers that contribute to the understanding of constraint modelling or model reformulation.  

Workshop topics include:

- Application papers describing interesting problems and interesting ways to model them;
- Contributions to understanding modelling that could guide the manual or automatic formulation of models;
- Identification of the criteria that should be used in evaluating models and the design of pragmatic techniques that facilitate the choice and possible combination among alternative models;
- Design of higher-level modelling languages;
- Automatic reformulation techniques; and
- Techniques which allow automatically targeting multiple kinds of solvers from a single declarative model.

## <a name="importantDates"></a> Important Dates

|------------------------------------------|--------------------------------------------:|
| Abstract Submission                      | **July 3rd, 2024**                          |
| Paper Submission                         | **July 7th, 2024**                          |
| Notification of acceptance/rejection     | **July 13th, 2024**                         |
| Camera ready version                     | **August 23rd, 2024**                       |
| Workshop day                             | **September 2nd, 2024**                     |

## <a name="callForPapers"></a> Call for Papers 

This year ModRef will again accept paper submissions. In addition to the presentation of research results, we especially welcome submissions of novel (ongoing) work, recent breakthroughs, future directions, and descriptions of interesting aspects of existing systems.

There are three types of paper submissions: extended abstracts (at most two pages), short papers (at most eight pages) and long papers (at most fifteen pages). References are not part of the page limit. Papers are submitted through [EasyChair](https://easychair.org/conferences/?conf=modref2024), as a PDF file following [LIPIcs guidelines](https://submission.dagstuhl.de/series/details/5#author). There is no requirement for papers to be anonymised before submission. 

We also accept (and encourage) non-traditional electronic submissions, such as interactive works/tool demonstrations. In this case, please contact the chairs to discuss the suitability of your submission for ModRef. 
<!--[chairs](mailto://helene.verhaeghe@kuleuven.be)--> 


All submissions will be reviewed and those that are well-written and make a worthwhile contribution to the topic of the workshop will be accepted for publication in the workshop proceedings. The proceedings will be available electronically at CP 2024. Accepted contributions will be allowed a time slot for a presentation at the workshop. In-person presentation is preferable, but we will allow remote presentation of papers when necessary. 

## <a name="invitedTalk"></a> Invited Talk

### **From ModRef 2014 to ModRef 2024: Ten years of CP models for solving differential cryptanalysis problems** by Christine Solnon

[(slides)](slides/ModRef2024_FromModRef2014toModRef2024.pdf)

Abstract: This talk will tell the 10-year story of using CP for differential cryptanalysis. The story starts at ModRef 2014, where a first CP model is introduced for computing differential characteristics for AES, the most famous symmetric cipher [1]. This first model is straightforward and it does not scale well enough to solve all instances. Improvements introduced in [2] and [3] allow CP solvers to outperform dedicated approaches and solve all instances in a few hours. Since then, similar CP models have been proposed for other symmetric ciphers (e.g., Midori [4], Skinny [5], and Rijndael [6]), and other differential cryptanalysis problems (e.g., boomerang [7,8] and rectangle attacks [9]). Finally, in [10] and [11], we introduce a generic tool for automatically generating these CP models for all word-oriented ciphers.

[1] M. Minier, C. Solnon, J. Reboul: Solving a Symmetric Key Cryptographic Problem with Constraint Programming, in ModRef 2014

[2] D. Gérault, M. Minier, C. Solnon: Constraint Programming Models for Chosen Key Differential Cryptanalysis, in CP 2016

[3] D. Gérault, P. Lafourcade, M. Minier, C. Solnon: Computing AES related-key differential characteristics with constraint programming, in AIJ 2020

[4] D Gérault, P Lafourcade: Related-key cryptanalysis of midori, in IndoCrypt 2016

[5] S. Sun, D. Gerault, P. Lafourcade, Q. Yang, Y. Todo, K. Qiao, L. Hu: Analysis of AES, SKINNY, and others with constraint programming, in IACR transactions on symmetric cryptology 2017

[6] L. Rouquette, D. Gerault, M. Minier, C Solnon: And rijndael? Automatic related-key differential analysis of rijndael, in AfricaCrypt 2022

[7] S. Delaune, P. Derbez, M. Vavrille: Catching the Fastest Boomerangs: Application to SKINNY, in IACR Transactions on Symmetric Cryptology 2020

[8] L. Rouquette, M. Minier, C. Solnon: Automatic boomerang attacks search on Rijndael, in Mathematical Cryptology 2024

[9] V. Lallemand, M. Minier, L. Rouquette: Automatic search of rectangle attacks on feistel ciphers: application to WARP, in IACR Transactions on Symmetric Cryptology 2022

[10] L. Libralesso, F. Delobel, P. Lafourcade, C. Solnon: Automatic Generation of Declarative Models for Differential Cryptanalysis, in CP 2021

[11] F. Delobel, P. Derbez, A. Gontier, L. Rouquette, C. Solnon: A CP-based Automatic Tool for Instantiating Truncated Differential Characteristics, in INDOCRYPT 2023

## <a name="acceptedPapers"></a> Accepted Papers

- Csobán Balogh, Ruth Hoffmann and Joan Espasa, **Towards Understanding Differences Between Modelling Pipelines: a Modelers Perspective** 
[(paper)](papers/ModRef2024_TowardsUnderstandingDifferencesBetweenModellingPipelines.pdf) [(slides)](slides/ModRef2024_TowardsUnderstandingDifferencesBetweenModellingPipelines.pdf)
- Stephan Frühwirt, Roxane Koitz-Hristov and Franz Wotawa, **MIN2SMT - A MINION to SMT-LIB2 Compiler**
[(paper)](papers/ModRef2024_MIN2SMT.pdf)
- Joan Espasa Arxer, Ian Gent, Ian Miguel, Peter Nightingale, András Z. Salamon and Mateu Villaret, **Cross-Paradigm Modelling: A Case Study of Puzznic**
[(paper)](papers/ModRef2024_CrossParadigmModelling.pdf)
- David Saikali and Gilles Pesant, **Constrained Molecule Generation Modelled using the Grammar Constraint**
[(paper)](papers/ModRef2024_ConstrainedMoleculeGenerationModelledusingtheGrammarConstraint.pdf) [(slides)](slides/ModRef2024_ConstrainedMoleculeGenerationModelledusingtheGrammarConstraint.pdf)
- Helmut Simonis, **Approximating a Global Objective by Solving Repeated Sub-problems for an Oven Scheduling Problem**
[(paper)](papers/ModRef2024_ApproximatingaGlobalObjectivebySolvingRepeatedSubproblems.pdf)
- Andrea Balogh, Sharmi Dev Gupta, Jheisson Argiro López Restrepo, Barry O'Sullivan, Helmut Simonis and Filipe Souza, **Modelling Choices for the Roadef 2022 Challenge**
[(paper)](papers/ModRef2024_ModellingChoicesfortheRoadef2022Challenge.pdf)
- Deepak Ajwani, Peter Nightingale and Felix Ulrich-Oltean, **Generalizing Learning-to-Prune for Constraint Programming**
[(paper)](papers/ModRef2024_GeneralizingLearningtoPruneforConstraintProgramming.pdf)
- Carla Davesa Sureda, Joan Espasa Arxer, Ian Miguel and Mateu Villaret Auselle, **Towards High-Level Modelling in Automated Planning**
[(paper)](papers/ModRef2024_TowardsHighLevelModellinginAutomatedPlanning.pdf)
- Felix Ulrich-Oltean, Peter Nightingale and James Alfred Walker, **IndiCon: Selecting SAT Encodings for Individual Pseudo-Boolean and Linear Integer Constraints**
[(paper)](papers/ModRef2024_IndiCon.pdf)
- Nguyen Dang, Ian Gent, Peter Nightingale, Felix Ulrich-Oltean and Jack Waller, **Constraint Models for Relaxed Klondike Variants**
[(paper)](papers/ModRef2024_ConstraintModelsforRelaxedKlondikeVariants.pdf) [(slides)](slides/ModRef2024_ConstraintModelsforRelaxedKlondikeVariants.pdf)
- Alessio Pellegrino, Özgür Akgün, Nguyen Dang, Zeynep Kiziltan and Ian Miguel, **Automatic Feature Learning for Essence: a Case Study on Car Sequencing**
[(paper)](papers/ModRef2024_AutomaticFeatureLearningforEssence.pdf) [(slides)](slides/ModRef2024_AutomaticFeatureLearningforEssence.pdf)
- Ignace Bleukx, Hélène Verhaeghe, Dimosthenis C. Tsouros and Tias Guns, **Efficient Modeling of Half-reified Global Constraints**
[(paper)](papers/ModRef2024_EfficientModelingofHalfreifiedGlobalConstraints.pdf) [(slides)](slides/ModRef2024_EfficientModelingofHalfreifiedGlobalConstraints.pdf)
- Pierre Schaus, Roger Kameugne and Charles Thomas, **Implementing Cumulative Functions for Conditional Task Intervals using a Generalized Cumulative Constraint** (Extended Abstract)
[(paper)](papers/ModRef2024_ImplementingCumulativeFunctionsforConditionalTaskIntervals.pdf) [(slides)](slides/ModRef2024_ImplementingCumulativeFunctionsforConditionalTaskIntervals.pdf)
- Davide Di Pierro, Stephan Mennicke and Stefano Ferilli, **A Schema-aware Logic Reformulation for Graph Reachability**
[(paper)](papers/ModRef2024_ASchemaawareLogicReformulationforGraphReachability.pdf)
- Orhan Yigit Yazicilar, Ozgur Akgun and Ian Miguel, **Automated Nogood-Filtered Fine-Grained Streamlining: A Case Study on Covering Arrays**
[(paper)](papers/ModRef2024_AutomatedNogoodFilteredFineGrainedStreamlining.pdf)
- Jo Devriendt, **ManyWorlds: Combinatorial Programming with Functions**
[(paper)](papers/ModRef2024_ManyWorlds.pdf) [(slides)](slides/ModRef2024_ManyWorlds.pdf)


## <a name="schedule"></a> Schedule

TBA

## <a name="programCommittee"></a> Program Committee

|-----------------------------------------|-------------------------------------| 
| Nysret Musliu (Chair)                   | TU Wien                             |
| Hélène Verhaeghe (Chair)                | KU Leuven/UCLouvain                 |
| Özgür Akgün                             | University of St Andrews            |
| Ignace Bleukx                           | KU Leuven                           |
| Jip Dekker                              | Monash University                   |
| Emir Demirović                          | TU Delft                            |
| Andreina Francisco Rodriguez            | Uppsala University                  |
| Zeynep Kiziltan                         | University of Bologna               |
| Lucas Kletzander                        | TU Wien                             |
| Jimmy Lee                               | The Chinese University of Hong Kong |
| Kevin Leo                               | Monash University                   |
| Ciaran McCreesh                         | University of Glasgow               |
| Peter Nightingale                       | University of York                  |
| Helmut Simonis                          | University College Cork             |
| Charles Thomas                          | UCLouvain                           |
| Dimosthenis Tsouros                     | KU Leuven                           |
| Mateu Villaret                          | Universitat de Girona               |
| Felix Winter                            | TU Wien                             |



