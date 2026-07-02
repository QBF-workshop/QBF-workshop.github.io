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

<h4>QBF Gallery</h4>
This year there will be another edition of the QBF Gallery. 
You can find more information at <a href="https://qbf.pages.sai.jku.at/gallery26/" target="_blank">https://qbf.pages.sai.jku.at/gallery26/</a>.

<h4>Invited Speakers </h4>
We are delighted to announce that there will be two invited talks at the QBF workshop.

<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Invited Speakers | QBF Workshop </title>
    <style>
        .speakers-container {
            display: grid;
            grid-template-columns: repeat(2, minmax(320px, 1fr));
            gap: 30px;
            
        }
        
        .speaker-card {
            background-color: white;
            border-radius: 12px;
            overflow: hidden;
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            cursor: pointer;
            position: relative;
        }
        
        .speaker-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.15);
        }
        
        .speaker-img {
            width: 100%;
            height: 280px;
            object-fit: cover;
            display: block;
        }
        
        .speaker-info {
            padding: 25px;
        }
        
        .speaker-name {            
            font-size: 1.5rem;
            margin-top: 0px;
        }
        
        .speaker-affiliation {
            font-size: 1rem;
            margin-bottom: 15px;
            display: flex;
            align-items: center;
        }
        
        .speaker-affiliation i {
            margin-right: 8px;
        }
        
        .speaker-talk {
            font-size: 0.95rem;
            border-top: 1px dashed #e0e0e0;
            padding-top: 15px;
            line-height: 1.5;
        }
        
        .talk-title {
            font-weight: 600;
            margin-bottom: 5px;
        }
                

        
        /* Tooltip text */
        .tooltiptext {
          visibility: hidden; /* Hidden by default */
          background-color: white;
          text-align: left;
          position: absolute;
          left: 10px;
          z-index: 1; /* Ensure tooltip is displayed above content */
        }
        
        @media (max-width: 650px) {
            .speakers-container {
                grid-template-columns: 1fr;
            }
            
        }
    </style>
</head>
<body>
    <section class="speakers-container">
        <!-- Speaker 1 -->
        <div class="speaker-card" onclick="window.open('https://www.fmi.uni-jena.de/en/18117/dr-benjamin-boehm', '_blank')">
            <!-- <img src="/assets/images/image.png" alt="Benjamin Böhm" class="speaker-img">  -->
            <div class="speaker-info">
                <h3 class="speaker-name">Benjamin Böhm</h3>
                <p class="speaker-affiliation"><i class="fas fa-university"></i>University of Jena, Germany</p>
                <div class="speaker-talk">
                    <p class="talk-title">The Complexity of Quantified CDCL</p>
                    <p>
                        Solving Quantified Boolean Formulas (QBFs) extends the well-known SAT problem by allowing quantification over variables. 
                        As the canonical PSPACE-complete problem, QBF is generally considered to be significantly harder than the NP-complete SAT problem. 
                        Despite the absence of polynomial-time algorithms for SAT, the dominant practical approach, Conflict Driven Clause Learning (CDCL), performs remarkably well on many industrial instances. 
                        For unsatisfiable formulas, CDCL generates Resolution refutations, and a result by Pipatsrisawat and Darwiche (2011) established that CDCL, viewed as a proof system, is equivalent to Resolution.
                    </p><p>
                        A common strategy in QBF solving is to lift successful SAT-solving techniques to the quantified setting. 
                        In particular, CDCL can be generalized to Quantified Conflict Driven Clause Learning (QCDCL). 
                        In this talk, we examine the similarities and differences between CDCL and QCDCL. 
                        We identify limitations of QCDCL by applying exponential lower bounds and use these results to compare and separate different QCDCL variants. 
                        A central question is whether there exists a variant of QCDCL that simulates its underlying proof system in the same way that CDCL simulates Resolution. 
                        We present several modifications of QCDCL and show how they can strengthen the framework and potentially improve its performance compared to the standard version widely used in practice.
                    </p>
                </div> 
            </div>
        </div>
        
        <!-- Speaker 2 -->
        <div class="speaker-card" onclick="window.open('https://www.ac.tuwien.ac.at/people/peitl/', '_blank')">
            <!-- <img src="/assets/images/image.png" alt="Tomáš Peitl" class="speaker-img">  -->
            <div class="speaker-info">
                <h3 class="speaker-name">Tomáš Peitl</h3>
                <p class="speaker-affiliation"><i class="fas fa-university"></i>TU Wien, Austria</p>
                <div class="speaker-talk">
                    <p class="talk-title">Dependency Schemes from Antiquity to Modernity</p>
                    <p>
                        Dependency schemes modify the quantifier structure of quantified Boolean formulas with the goal of making them easier to solve or reason about. 
                        The term dependency scheme was coined by Samer and Szeider in their SAT'07 paper (and JAR'09). 
                        Dependency schemes have since found use in both solvers and proof theory, yielding exponential separations in proof complexity and finding unexpected applications in proof systems.
                    </p><p>
                        Originally, dependency schemes were formalized as truth-preserving quantifier-shifting transformations of QBFs. 
                        This viewpoint proved cumbersome as quantifier shifting is too coarse to operate on individual variable pairs. 
                        Integration into the solver DepQBF inspired a proof-theoretic perspective, in which dependency schemes extend proof systems. 
                        This ultimately led back to a semantic view: today dependency schemes are understood once again as truth-preserving prefix transformations—this time of Dependency Quantified Boolean Formulas.
                    </p><p>
                        The schemes themselves evolved as well. 
                        Samer and Szeider proposed the standard (and also triangle) dependency scheme, based on variable connectivity. 
                        Better understanding of the underlying semantics has since led to increasingly more general notions of connectivity, and, in turn, to ever stronger dependency schemes. 
                        Dependency schemes are alive and well in 2026: two SAT papers propose new schemes, while a third resolves a long-standing open problem.
                    </p>
                </div> 
            </div>
        </div>
        
        
    </section>
</body>

<h4>About</h4>

Continued improvements in the performance of propositional satisfiability (SAT) solvers are enabling a growing number of applications in the area of electronic design automation, such as model checking, synthesis, and symbolic execution. SAT solvers are also a driving force behind recent progress in constrained sampling and counting, and competitive planning tools. In most of these cases, SAT solvers deal with problems from complexity classes beyond NP and propositional encodings that grow super-polynomially in the size of the original instances. Clever techniques such as incremental solving can partly alleviate this issue, but ultimately the underlying asymptotics lead to formulas that are too large to be solved by even the most efficient SAT solvers.

This has prompted the development of decision procedures for more succinct generalizations of propositional logic such as Quantified Boolean Formulas (QBFs), which allow for explicit quantification over truth values. The decision problem of QBF is PSPACE-complete, and thus many problems from application domains such as model checking, formal verification or synthesis—which happen to be PSPACE-complete—could be succinctly encoded in QBF.

Considerable progress has been made in QBF solving throughout the past years. However, in contrast to SAT, QBF solvers generally do not scale well enough on practically relevant problems arising in an industrial setting.

- The main aim of the workshop is to bring together researchers working on QBF theory and solver developers so as to further our theoretical understanding of this hardness and find ways of overcoming it in practice. It provides a forum in which the community can identify immediate and long-term research challenges. That includes (potential) users, which are invited to reflect on the current state-of-the-art and identify obstacles to the adoption of QBF solvers as well as specific problems (instances) for developers to target.

- Researchers in other areas of automated reasoning face similar problems in lifting techniques and algorithms for quantifier-free formulas to a quantified version. For instance, this is the case in Quantified Constrained Satisfaction Problems (QCSP), or Sat Modulo Theory (SMT) with quantifiers. This workshop also seeks to promote an exchange of ideas and collaboration between researchers working on QBF and those in other subfields of automated reasoning that deal with quantification.

- Recent years have seen research on Dependency QBF (DQBF), which further generalize QBFs by allowing non-linear quantifier prefixes. Given that DQBF evaluation is NEXP-complete, and in view of the difficulties presented by QBF solving, the development of DQBF solvers may seem futile. However, the trade-off between succinctness and complexity offered by DQBF may be favorable in practice. The workshop also aims to be a platform for research on formalisms that go beyond QBF in this way.

