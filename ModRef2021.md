---
layout: Layout2021
title: ModRef 2021
---

ModRef 2021 is the 20th in a [series of workshops on Constraint Modelling and Reformulation](https://www-users.cs.york.ac.uk/~frisch/ModRef/).
It takes place virtually on October 25, preceding CP 2021, the [The 27th International Conference on Principles and Practice of Constraint Programming, CP2021](http://cp2021.a4cp.org/).

The main aim of the workshop is to identify recent trends in constraint modelling, including (but not limited to) innovative modelling techniques, reformulation and preprocessing techniques, and understanding search. This year we have two important components:

1. (half a day) Short presentations and talks about recent developments by the participants.

    Topics of interest include:
    - Application papers describing interesting problems and interesting ways to model them;
    Contributions to understanding modelling that could guide the manual or automatic
    formulation of models;
    - Identification of the criteria that should be used in evaluating models and the design of
    pragmatic techniques that facilitate the choice and possible combination among
    alternative models;
    - Design of higher-level modelling languages;
    - Automatic reformulation techniques;
    - Techniques which allow automatically targeting multiple kinds of solvers from a single declarative model.

2.  (half a day) The second half will be a collaborative exercise to identify challenges for the next five years of modelling, with the goal of producing a jointly-written white/research paper to guide future research. This component will consist of a series of lightning talks (from both users and developers of modelling tools) pointing out pain-points or desired features for modelling, then a series of focussed discussions to identify common features, possible solutions and research directions.

## <a name="invtalks"></a> Invited Talks

### **Prof. Torsten Schaub** (Universität Potsdam, Germany) - Answer Set Programming in a Nutshell

Answer Set Programming (ASP) has become a popular approach to declarative problem solving.
More precisely, ASP is a rule-based formalism for modeling and solving knowledge-intense combinatorial (optimization) problems.
What makes ASP attractive is its combination of a declarative modeling language with highly effective solving engines.
This allows us to concentrate on specifying - rather than programming the algorithm for solving - a problem at hand.
Historically, ASP has its roots in deductive databases, logic programming, and non-monotonic reasoning;
its solving engines draw on the same technology as solvers for satisfiability testing.
Given this origin, ASP is tailored to support closed as well as open world reasoning,
which makes it predestined for knowledge representation and reasoning tasks.
Interesting applications of ASP can be found in decision support systems, industrial team-building, music composition,
train scheduling, product and software configuration, phylogeneticics, robotics, systems biology, timetabling,
and many more.

The talk will give a gentle introduction to ASP, its logical foundations, modeling capabilities, and solving engines,
and conclude with an outlook on the ASP's potential impact as a knowledge-driven AI tool.

### **Dr. Bart Bogaerts** (Vrije Universiteit Brussel, Belgium) - Predicate Logic as a Modelling Language: The IDP system

I introduce the IDP system: syntax, formal and informal semantics, and inference methods. Special attention will be devoted to
 1. the knowledge base system paradigm: the idea that a single knowledge base can be used for multiple inferences
 2. informal semantics: the idea that formal statements should correspond to their informal (natural language) reading. 
 3. inductive definitions, and 
 4. the rationale behind some design decisions in IDP. 

## <a name="callForPapers"></a> Call for Papers 
We invite submissions of novel (ongoing) work, recent breakthroughs, future directions, and descriptions of interesting aspects of existing systems related (but not limited) to the following topics:

Application papers describing interesting problems and innovative ways to model them;
Contributions to understanding modelling that could guide the manual or automatic formulation of models;
Identification of the criteria that should be used in evaluating models and the design of pragmatic techniques that facilitate the choice and possible combination among alternative models;
Design of higher-level modelling languages;
Automatic reformulation techniques;
Techniques which allow automatically targeting multiple kinds of solvers from a single declarative model.

There are two types of submissions: extended abstracts (at most two pages) and full papers (at most fifteen pages). References are not part of the page limit. Papers are submitted through [EasyChair](https://easychair.org/conferences/?conf=modref2021) in the [Lecture Notes in Computer Science (LNCS) style](https://resource-cms.springernature.com/springer-cms/rest/v1/content/19238648/data/v1).

We also accept (and encourage) non-traditional electronic submissions, such as interactive works/tool demonstrations. In this case, please contact the [chairs](mailto://modref2021@tudelft.nl) to discuss the suitability of your submission for ModRef.

All submissions will be reviewed and those that are well-written and make a worthwhile contribution to the topic of the workshop will be accepted for publication in the workshop proceedings. The proceedings will be available electronically at CP 2021. Accepted contributions will be allowed a time slot for a presentation at the workshop. At least one author of each accepted paper must attend and present at the workshop. Please note that every workshop participant needs to be registered for the workshop.


## <a name="callForLightning"></a> Call for Lightning Talks
This year, ModRef will host a round-table discussion to identify exciting directions for future
improvements in modelling, and model transformation. As a lead-in to this, we will be holding
a series of 2-3 minute lightning talks, with the theme `What really bugs me about modelling is...`.

Do you have some favourite problem, that is just really awkward to model? Or a really nice formulation,
that somehow becomes garbage by the time it reaches a solver? Some way you really want to use
solvers, and they just won't let you? Come along, and vent your spleen! And together, maybe we'll come
up with some neat ideas.

Please submit your lightning talk ideas through [EasyChair](https://easychair.org/conferences/?conf=modref2021) by submitting a PDF with a few sentences
describing the main idea of your talk.

## <a name="importantDates"></a> Important Dates

|------------------------------------------|---------------------:|
| Abstract submission                      | ~~August 23rd, 2021~~  |
| Lightning talk proposals                  | ~~September 2nd, 2021~~  |
| Final submission (extended abstract/full paper)                     | ~~September 2nd, 2021~~  |
| Notification of acceptance/rejection | ~~September 13th, 2021~~ |
| Camera ready version                 | ~~September 30th, 2021~~ |
| Workshop day                             | **October 25th, 2021**  |

For questions about the workshop, please contact the chairs Dr. Emir Demirović and Dr. Graeme Gange: <modref2021@tudelft.nl>

## <a name="programCommittee"></a> Program Committee

|-------------------------------|------------------|
| Emir Demirović (Chair)        | TU Delft         | 
| Graeme Gange (Chair)          | Monash University |
| Joan Espasa Arxer | University of St. Andrews |
| Nguyen Dang | University of St. Andrews |
| Kevin Leo | Monash University |
| Alan Frisch | University of York |
| Mateu Villaret | Universitat de Girona |
| Peter Nightingale | University of York |
| Michael Morin | Université Laval |
| Zeynep Kiziltan | University of Bologna |
| María Andreína Francisco Rodríguez | Uppsala University |
| Ciaran McCreesh | University of Glasgow |
| Özgür Akgün | University of St. Andrews |
| Ken Brown | University College Cork |
| Jimmy H.M. Lee | Chinese University of Hong Kong |


## <a name="timetable"></a> Program (October 25th, 2021)

| Time (CEST) | Authors | Title |
|------| ------- | ----- |
| 08:45 |  | Welcome |
| 09:00 | *Invited talk:* Torsten Schaub | Answer-set Programming in a Nutshell |
| 10:00 | Felix Ulrich-Oltean, Peter Nightingale and James Alfred Walker | Selecting SAT Encodings for Pseudo-Boolean and Linear Constraints: Preliminary Results  [(paper)](papers/ModRef2021_SAT-PBLinear.pdf) |
| 10:20 | Peter J. Stuckey and Guido Tack | Enumerated Types, Type Extensions and Defaults for MiniZinc [(paper)](papers/ModRef2021_MiniZincEnumeratedTypes.pdf) |
| 10:40 | Sophia Saller and Jana Koehler | Easy, adaptable and high-quality Modelling with Domain-Specific Constraint Patterns [(paper)](papers/ModRef2021_ModellingConstraintPatterns.pdf) |
| 11:00 | *Break* | |
| 11:15 | *Invited talk:* Bart Bogaerts | Predicate Logic as a Modelling Language: The IDP System |
| 12:15 | Jordi Coll, Joan Espasa Arxer, Ian Miguel and Mateu Villaret | A preliminary Case Study of Planning With Complex Transitions: Plotting [(paper)](papers/ModRef2021_PlanningPlotting.pdf) |
| 12:35 | Hélène Verhaeghe, Roger Kameugne, Christophe Lecoutre and Pierre Schaus | Improved Filtering of Scheduling Problems using Redundant Table Constraints [(paper)](papers/ModRef2021_SchedulingRedundantTable.pdf) |
| 12:55 | Özgür Akgün, Alan M. Frisch, Ian P. Gent, Christopher Jefferson, Ian Miguel, Peter Nightingale and András Z. Salamon | Towards Reformulating Essence Specifications for Robustness [(paper)](papers/ModRef2021_ReformulatingEssenceRobustness.pdf) |
| 13:15 | *Lunch Break * | |
| 13:45 | Lightning Talks | |
| 14:00 | Community Discussion | Integrating modelling as a component |

### Session 3: Lightning Talks & Community Discussion

The last session will be a collaborative exercise to identify challenges for the next five years of modelling, with the goal of producing a
jointly-written white/research paper to guide future research. The main topic is on *the integration of modelling as a component in larger systems*.
This session will consist of a series of lightning talks pointing out pain-points or desired features for modelling, then a series of focussed
discussions to identify common features, possible solutions and research directions.

## <a name="pmodrefs"></a> Previous ModRef Workshops
The ModRef workshop has been running for 20 years and has hosted many interesting presentations.

 - In 2020 the workshop page moved to its current home [here](ModRef2020).
 - The 2019 workshop page was hosted at ModRef2019.github.io, and is duplicated [here](ModRef2019).
 - Past events in this workshop series can be found [here](https://www-users.cs.york.ac.uk/~frisch/ModRef/).
 - A searchable list of previous presentations can be found [here](ModRefHistory) (Note: links to slides, papers and posters are not working).
