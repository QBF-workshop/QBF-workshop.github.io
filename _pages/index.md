---
permalink: /
title: "Welcome to QBF 2026"
layout: splash
header:
  overlay_image: /assets/images/lisbon.jpg
  overlay_filter: "0.5" # darkens image for better text readability
  overlay_color: "#000" # black overlay (optional)
excerpt: "19 July 2026 · Lisbon, Portugal"
---

<h4>Overview</h4>
Quantified Boolean formulas (QBF) are an extension of propositional logic which allows for explicit quantification over propositional variables. The decision problem of QBF is PSPACE-complete, compared to the NP-completeness of the decision problem of propositional logic (SAT). Many problems from application domains such as model checking, formal verification or synthesis are PSPACE-complete, and hence could be encoded in QBF in a natural way. Considerable progress has been made in QBF solving throughout the past years. However, in contrast to SAT, QBF is not yet widely applied to practical problems in academic or industrial settings. For example, the extraction and validation of models of (un)satisfiability of QBFs has turned out to be challenging, given that state-of-the-art solvers implement different solving paradigms. The goal of the International Workshop on Quantified Boolean Formulas (QBF Workshop) is to bring together researchers working on theoretical and practical aspects of QBF solving and extensions like DQBF. In addition to that, it addresses (potential) users of QBF in order to reflect on the state-of-the-art and to consolidate on immediate and long-term research challenges.

The workshop also welcomes work on reasoning with quantifiers in related problems, such as dependency QBF (DQBF), quantified constraint satisfaction problems (QCSP), and satisfiability modulo theories (SMT) with quantifiers.


<h4>About</h4>

Continued improvements in the performance of propositional satisfiability (SAT) solvers are enabling a growing number of applications in the area of electronic design automation, such as model checking, synthesis, and symbolic execution. SAT solvers are also a driving force behind recent progress in constrained sampling and counting, and competitive planning tools. In most of these cases, SAT solvers deal with problems from complexity classes beyond NP and propositional encodings that grow super-polynomially in the size of the original instances. Clever techniques such as incremental solving can partly alleviate this issue, but ultimately the underlying asymptotics lead to formulas that are too large to be solved by even the most efficient SAT solvers.

This has prompted the development of decision procedures for more succinct generalizations of propositional logic such as Quantified Boolean Formulas (QBFs), which allow for explicit quantification over truth values. The decision problem of QBF is PSPACE-complete, and thus many problems from application domains such as model checking, formal verification or synthesis—which happen to be PSPACE-complete— could be succinctly encoded in QBF.

Considerable progress has been made in QBF solving throughout the past years. However, in contrast to SAT, QBF solvers generally do not scale well enough on practically relevant problems arising in an industrial setting.

- The main aim of the workshop is to bring together researchers working on QBF theory and solver developers so as to further our theoretical understanding of this hardness and find ways of overcoming it in practice. It provides a forum in which the community can identify immediate and long-term research challenges. That includes (potential) users, which are invited to reflect on the current state-of-the-art and identify obstacles to the adoption of QBF solvers as well as specific problems (instances) for developers to target.

- Researchers in other areas of automated reasoning face similar problems in lifting techniques and algorithms for quantifier-free formulas to a quantified version. For instance, this is the case in Quantified Constrained Satisfaction Problems (QCSP), or Sat Modulo Theory (SMT) with quantifiers. This workshop also seeks to promote an exchange of ideas and collaboration between researchers working on QBF and those in other subfields of automated reasoning that deal with quantification.

- Recent years have seen research on Dependency QBF (DQBF), which further generalize QBFs by allowing non-linear quantifier prefixes. Given that DQBF evaluation is NEXP-complete, and in view of the difficulties presented by QBF solving, the development of DQBF solvers may seem futile. However, the trade-off between succinctness and complexity offered by DQBF may be favorable in practice. The workshop also aims to be a platform for research on formalisms that go beyond QBF in this way.

