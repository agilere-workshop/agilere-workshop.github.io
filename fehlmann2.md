---
layout: page
title: Contribution by Thomas Fehlmann and Eberhard Kranich
---

Mini-Tutorial<br/>
*Applying a Grey Multi–Criteria Decision Making Method to Agile Requirements*<br/>
Thomas Fehlmann and Eberhard Kranich<br/>
Abstract:
Multi–Criteria Decision Making (MCDM) is a process of selecting the best solution on the basis of a set of given alternatives by taking appropriate criteria into account. The more complex the decision is, the more criteria have to be fulfilled. Popular MCDM techniques for establishing the best solution or for prioritizing the alternatives are the Analytic Hierarchy Process (AHP) and the Net Promoter Score (NPS), respectively. Furthermore, applying MCDM techniques in an agile environment is beneficial, since making more or less complex decisions in this context is a common task.

The usage of an arbitrary MCDM technique is initialized by generating the so–called decision matrix, where the entries of this matrix reflect the rated relationships between the stated alternatives and corresponding criteria. It is evident that a lack of information concerning any decision matrix entry may result in a wrong decision with potentially serious consequences. For instance, lack of information may be caused when a considered matrix entry cannot be set to a fixed value,
but the value of the entry is known to lie in a finite interval. Entries with this property provide only partial information and are therefore called a grey entry, in contrast to a black entry which does not yield any information and a white entry which comprises complete information.

Nonetheless making decisions in this grey context is still possible. MCDM techniques based on Grey Systems Theory have the advantage that only a relatively small amount of data and only partial information enables to assess the quantitative and qualitative relationships between the alternatives and corresponding criteria. Such an MCDM grey technique is the possibility degree procedure, actually applied in an agile requirements engineering setting.

For the sake of simplicity, assume that a set of requirements and associated criteria are available and that the requirements have been prioritized by some method resulting in a vector, the so–called goal profile. In addition, suppose that the possibility degree procedure has been executed so that the Euclidean distance between the resulting solution profile and the goal profile can be determined. If the Euclidean distance is strictly lower than a predefined threshold, then the best
solution with respect to the decision matrix is detected. Otherwise, perform a sensitivity analysis on the basis of the current decision matrix, with the aim to improve the solution profile and thus the Euclidean distance. Note that the greyness of each decision matrix entry plays a prominent role in the course of the sensitivity analysis.