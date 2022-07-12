---
layout: default
title: ModRef 2022
redirect_from: "/"
---

ModRef 2022 is the 21st in a [series of workshops on Constraint Modelling and Reformulation](https://www-users.cs.york.ac.uk/~frisch/ModRef/) organized as part of FLoC 2022, the [Federated Logic Conference](https://www.floc2022.org/).
It will be held on July 31st, preceding CP 2022, the [28th International Conference on Principles and Practice of Constraint Programming](http://cp2022.a4cp.org/).

Recent years have witnessed significant research devoted to modelling and solving problems with constraints. The importance of modelling and model reformulation is widely recognized. There have been developments in systematic and automated ways of improving aspects of modelling and model reformulation. Tools and techniques which provide the ability to target multiple kinds of solvers were also developed.

The key goals of this workshop are to extend the understanding of constraint modelling and to automate aspects of modelling or model reformulation to extend the reach of constraint solvers on difficult problems and ease the task of modelling. We solicit original papers that contribute to either or both of these goals. Workshop topics include:

- Application papers describing interesting problems and interesting ways to model them;
- Contributions to understanding modelling that could guide the manual or automatic formulation of models;
- Identification of the criteria that should be used in evaluating models and the design of pragmatic techniques that facilitate the choice and possible combination among alternative models;
- Design of higher-level modelling languages;
- Automatic reformulation techniques; and
- Techniques which allow automatically targeting multiple kinds of solvers from a single declarative model.

## <a name="timetable"></a> Program

The detailed program can also be found on [EasyChair](https://easychair.org/smart-program/FLoC2022/ModRef-index.html)


| Time                         | Event                                                                                                |
|------------------------------|------------------------------------------------------------------------------------------------------|
| **Session 1**: 9:00 - 10:30  | *Invited Talk*: Constraint modelling and solving: Learning from observing people -- Ruth Hoffman |
|                              | *Paper*: Solving XCSP3 constraint problems using tools from software verification -- Martin Mariusz Lester [(paper)](papers/ModRef2022_SolvingXCSP3ConstraintProblemsUsingToolsFromSoftwareVerification.pdf) |
|                              | *Paper*: Constraint-based Part-of-Speech Tagging -- Neng-Fa Zhou [(paper)](papers/ModRef2022_ConstraintBasedPartOfSpeechTagging.pdf) |
| **Break**: 10:30 - 11:00     |                                                                                                      |
| **Session 2**: 11:00 - 12:30 | *Paper*: A portfolio-based analysis method for competition results -- Nguyen Dang [(paper)](papers/ModRef2022_PortfolioBasedAnalysisMethodForCompetitionResults.pdf) |
|                              | *Paper*: Efficiently Explaining CSPs with Unsatisfiable Subset Optimization -- Emilio Gamba, Bart Bogaerts and Tias Guns [(paper)](papers/ModRef2022_EfficientExplainingCSPsWithUnsatisfiableSubsetOptimization.pdf) |
|                              | *Paper*: Automatic Generation of Dominance Breaking Nogoods for Constraint Optimization -- Jimmy H. M. Lee and Allen Z. Zhong [(paper)](papers/ModRef2022_AutomaticGenerationOfDominanceBreakNogoodsForConstraintOptimization.pdf) |
| **Lunch**: 12:30 - 14:00     |                                                                                                      |
| **Session 3**: 14:00 - 15:30 | *Invited Talk*: A Constraint-Based Tool for Generating Benchmark Instances -- Nguyen Dang        |
|                              | **Modelling competition**                                                                            |
| **Break**: 15:30 - 16:00     |                                                                                                      |
| **Session 4**: 16:00 - 17:15 | **Modelling competition**                                                                            |
|                              | *17:00*: Competition results                                                                         |


## <a name="invtalks"></a> Invited Talks

### **dr. Ruth Hoffman** (University of St Andrews, Scotland) - Constraint modelling and solving: Learning from observing people

*Coming soon...*

### **dr. Nguyen Dang** (University of St Andrews, Scotland) - A Constraint-Based Tool for Generating Benchmark Instances

Benchmarking is fundamental for assessing the relative performance of
alternative solving approaches. For an informative benchmark we often need a
sufficient quantity of instances with different levels of difficulty and the
ability to explore subsets of the instance space to detect performance
discrimination among solvers. In this talk, I will present AutoIG, an
automated tool for generating benchmark instances for constraint solvers.
AutoIG supports generating two types of instances: graded instances
(i.e., solvable at a certain difficult level by a solver), and discriminating
instances (i.e., favouring a solver over another). The usefulness of the tool
in benchmarking is demonstrated via an application on five problems taken
from the MiniZinc Challenges. Our experiments show that the large number of
instances found by AutoIG can provide more detailed insights into the
performance of the solvers rather than just a ranking. Cases where a solver
is weak or even faulty can be detected, providing valuable information to
solver developers. Moreover, discriminating instances can reveal parts of the
instance space where a generally weak solver actually performs well relative
to others, and therefore could be useful as part of an algorithm portfolio.

## <a name="modcomp"></a> Modelling Competition

This year ModRef will host a modelling competition. Teams of up to five
members will compete to be the quickest to find the best solutions for
different instances of described problems. Teams can compete either on
location at FLoC 2022 or remotely. We will organize a chat server to
communicate with the teams competing remotely. The problem descriptions will
be available from circa 14:45 (UTC+3) and solutions can be submitted until
17:00 (UTC+3), after which the winners will be directly announced.

*Additional information, including the scoring method, will be announced soon.*

**Registration**: [Google Form](https://docs.google.com/forms/d/e/1FAIpQLSfGWdx7IVUGYFIm5wUD1au08i1ssuoCl6i5PFsgqXKBgZ94dw/viewform?usp=sf_link), or in-person at FLoC 2022


## <a name="importantDates"></a> Important Dates

|------------------------------------------|-----------------------------------------:|
| Paper Abstract Submission                | ~~May 3rd, 2022~~                        |
| Paper Full Submission                    | ~~May 10th, 2022~~                       |
| Notification of acceptance/rejection     | ~~June 15th, 2022~~                      |
| Camera ready version                     | July 1st, 2022                           |
| Workshop day                             | **July 31st, 2022**                      |

For questions about the workshop, please contact the chairs dr. Jip J. Dekker and dr. Guido Tack: <modref@a4cp.org>

## <a name="callForPapers"></a> Call for Papers 

This year ModRef will again paper submissions. In addition to the presentation of research results, we especially welcome submissions of novel (ongoing) work, recent breakthroughs, future directions, and descriptions of interesting aspects of existing systems.

There are two types of paper submissions: extended abstracts (at most two pages) and full papers (at most fifteen pages). References are not part of the page limit. Papers are submitted through [EasyChair](https://easychair.org/conferences/?conf=modref2022), as a PDF file following [LIPIcs guidelines](https://submission.dagstuhl.de/series/details/5#author).

We also accept (and encourage) non-traditional electronic submissions, such as interactive works/tool demonstrations. In this case, please contact the [chairs](mailto://modref@a4cp.org) to discuss the suitability of your submission for ModRef.

All submissions will be reviewed and those that are well-written and make a worthwhile contribution to the topic of the workshop will be accepted for publication in the workshop proceedings. The proceedings will be available electronically at CP 2022. Accepted contributions will be allowed a time slot for a presentation at the workshop. At least one author of each accepted paper must attend and present at the workshop. Please note that every workshop participant needs to be registered for the workshop.

## <a name="programCommittee"></a> Program Committee

|------------------------------------|--------------------|
| Jip J. Dekker (Chair)              | Monash University  | 
| Guido Tack (Chair)                 | Monash University  |
| Emir Demirović                     | TU Delft           | 
| María Andreína Francisco Rodríguez | Uppsala University |
| Jimmy H.M. Lee        | Chinese University of Hong Kong |
| Kevin Leo                          | Monash University  |


## <a name="pmodrefs"></a> Previous ModRef Workshops
The ModRef workshop has been running for 21 years and has hosted many interesting presentations.

 - In 2021 the workshop page moved to its current home [here](ModRef2021).
 - Past events in this workshop series can be found [here](https://www-users.cs.york.ac.uk/~frisch/ModRef/).
 - A searchable list of previous presentations can be found [here](ModRefHistory) (Note: links to slides, papers and posters are not working).
