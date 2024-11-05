---
layout: default
title: Program
---

# Program

<p>
<strong>Abstracts</strong> can be found here: <a href="nwpt24-extended-abstracts.pdf">nwpt24-extended-abstracts.pdf</a>
</p>

<p>
The following is a draft program outline.
</p>

## Wednesday November 6
Auditorium B

* 08:30 Registration opens (with coffee, tea, croissant, and wienerbrød)
* 09:00 Workshop opens<br>
  Jakob Grue Simonsen, Head of Department, DIKU
* 09:05 Keynote, Chair: Maja Hanne Kirkeby<br>
  <b>João Saraiva</b><br>
<span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;" >_Energy Efficiency in Programming Languages_</span>
  <span style="display: none;"><br>
    <b>Affiliation:</b> University of Minho and HASLab / INESC TEC, Portugal<br>
    <b>Abstract:</b> In this talk I will compare a large set of programming languages regarding their energy efficiency.  We have taken 19 solutions to well defined programming problems, expressed in (up to) 27 programming languages, from well know repositories such as the Computer Language Benchmark Game and Rosetta Code.<br>
  In our research, my group built a framework to automatically, and systematically, run, measure and compare the efficiency of such solutions. Ultimately, it is based on such comparison that we propose a serious of efficiency rankings, based on multiple criteria.<br>
  Our results show interesting findings, such as, slower/faster languages consuming less/more energy, and how memory usage influences energy consumption. We also show how to use our results to provide software engineers support to decide which language to use when energy efficiency is a concern.<br>
  In this talk I will also  present our most recent results on leveraging power caps to save energy consumption across programming languages.<br>
    <b>Biography:</b> João Saraiva is an Associate Professor at the Department of de Informatics, University of  Minho, Braga, Portugal, and a researcher member of HASLab/INESC TEC. He obtained a MSc degree from University do Minho in 1993 and a Ph.D. degree in Computer Science from Utrecht University in 1999. His main research contributions have been in the field of programming language design and implementation, program analysis and transformation, functional programming, and green software.  He has experience in participating and coordinating research projects in his research areas, both at national level with projects funded by FCT (projects: PURe, IVY, AMADEUS, CROSS, SSaaPP, AutoSeer, FATBIT, and GreenSwLab) and at international level with projects funded by EPSRC (UK), FLAD/NSF (USA) and by the European Union.<br>
  João Saraiva is one of the founders of the successful series of summer schools on Generative and Transformational Techniques in Software Engineering (GTTSE), which he co-organized in 2005, 2007, 2009, 2011, and 2015 (volumes 4143, 5235, 6491, 7680 and 10223 of LNCS - Tutorial by Springer-Verlag) in Braga. He was the organizing chair of ETAPS'07, The European Joint Conferences on Theory and Practice of Software, organized in Braga in 2007, and the worksho co-chair of ICSE'24 held in Lisbon.<br><br>
  </span>
* 10:00 Break (with coffee and tea)
* 10:30 Session 1
  <ul>
    <li>Duc Anh Nguyen, Philipp Rümmer and Wang Yi<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;" ><i>Verification of Data-flow Networks Using the KeY Theorem Prover</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> We present a contract-based method to verify the functional correctness of data-flow networks modeled in MIMOS, a toolchain currently developed in Uppsala. We specify the functional correctness of a network using local contracts annotated on the network components, and global contracts on the inputs and outputs of the network. By utilizing the functional determinism of the model, we can construct a sequential program that is functionally equivalent to the original network. The KeY theorem prover then takes the sequential program with the contracts and checks whether the network conforms to the provided contracts.<br><br>
      </span>
    </li>
    <li>Thomas Baar and Volker Stolz<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;" ><i>Finding Inductive Invariants Fast - A Support Technique for Deductive Software Verification</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> We consider the case of formally verifying the implementation of a function being correct with respect to an annotated contract consisting of pre-/post-condition. When using tools like KeY or Verifast, the most challenging task for the user is to provide the right code annotations allowing the verification tool to verify the correctness of the function’s implementation automatically.<br><br>
      </span>
    </li>
    <li>Florian Furbach, Alceste Scalas, Roland Kuhn, Emilio Tuosto and Hernan Melgratti<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;" ><i>Compositional Design and Verification of Swarm Protocols</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> Swarm protocols are a recently introduced formalism for specifying and verifying the intended behaviour of a distributed ensemble of agents, used e.g. for factory automation. Unfortunately, existing design and verification techniques for swarm protocols are not compositional. We explain the problem and present our ongoing work that addresses it.<br><br>
      </span>
    </li>
  </ul>
* 12:00 Lunch
* 13:30 Session 2
  <ul>
    <li>Samuel Grahn and Elli Anastasiadi<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Modeling systems via register machines for the verification of weak memory models</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> Register machines can be verified against weak memory models that might be undecidable in the general case. Here we demonstrate how to model system features via register machines so that we enable their verification.<br><br>
      </span>
    </li>
    <li>Haining Tong and Keijo Heljanko<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>GPU Consistency Analysis with Dartagnan</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> In recent years, significant efforts have been made to formalize GPU consistency models. These models specify how concurrent programs behave on GPU hardware and thus help users write programs that are free of concurrency bugs. Some of the efforts have introduced prototype tools to assist researchers and developers in analyzing the correctness of GPU programs with respect to these models. However, these tools are typically tightly coupled with a specific model, making it difficult to compare consistency features between different models. Additionally, since these tools are typically built on top of the Alloy framework, they are limited to straight-line code in pseudo-assembly without control flow instructions and struggle with scalability, particularly for programs with more than a few instructions.<br>
        In this abstract, we primarily discuss our previous work on integrating support for the Nvidia PTX and Khronos Vulkan consistency models into Dartagnan, an open-source Bounded Model Checking (BMC) tool designed to check state reachability under specific memory models. The technical details of the approach will be published in an accepted manuscript to ASPLOS2024, and here we mainly outline the overall approach taken in that paper. The process involves formalizing GPU consistency models in the domain-specific language .cat, extending it with GPU-specific features, enhancing our Dartagnan to support the GPU consistency models, and implementing new front-ends for both pseudo-assembly syntax and a subset of real Spirv assembly. Additionally, we present a bug discovered in the original Vulkan consistency model.
<br><br>
      </span>
    </li>
    <li>Behnam Khodabandeloo, Chengzi Huang, Morteza Mohaqeqi, Susanne Graf and Wang Yi<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Buffer Overflow and Deadlock Detection for Timed Kahn Process Networks</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> We show that worst-case optimal joins, also for cyclic joins, are easy to program using basic programming techniques. They only require straightforward dictionaries, iterating over the smallest set when intersecting multiple sets and nested iteration over the variables in a join query in any order. We sketch a proof of worst-case optimality by amortization, where the execution cost is allocated to the generated output, but of padded input. We point out that modern database systems (still) generate asymptotically inferior code on cyclic joins.<br><br>
      </span>
    </li>
  </ul>
* 15:00 Break (with coffee, tea, and cake)
* 15:30 Session 3
  <ul>
    <li>Chad Nester and Niels Voorneveld<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>On the Operational Semantics of the Free Cornering with Protocol Choice</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> This work concerns the dynamics (operational semantics) of the free cornering with protocol choice of a monoidal category. The free cornering construction provides a double categorical notion of program interaction, but presently exists only as a formal semantics. Our project is to work backwards from this formal semantics to obtain a simple interactive programming language. Our first step is to orient some of the equations of the free cornering with protocol choice to obtain a rewriting system, by which interactive programs may be evaluated. In this extended abstract we summarize our progress towards this goal.<br><br>
      </span>
    </li>
    <li>Andreas Brandhøj, Dat Dieu, Kasper Vesteraa, Danny Poulsen, René Hansen and Kim Larsen<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>DropShadow: Hypercontracts in Go</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> Go is widely used programming language for embedded devices, systems programming, cloud, and network services. While Go provides testing tools such as property-based testing and fuzzing, many systems require more thorough testing than what is currently supported. To bridge this gap, we introduce DropShadow, a novel tool that enables the testing of hypercontracts in Go which enables properties such as non-interference to be expressed. DropShadow automatically instruments the program under test and generates tests. Experimental results showing promising benefits, though challenges remain, such as contract complexity and performance overhead.<br><br>
      </span>
    </li>
    <li>Till Hofmann and Jens Classen<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Strategy Synthesis for First-Order Agent Programs over Finite Traces</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> In this work, we consider the task of synthesizing an execution strategy for an agent from a high-level description of the initial state of the world, the actions at the agent's disposal, a control program, and a temporal goal. In particular, we look at the more realistic (and more challenging) case of infinite-state systems with unbounded object domains, obtained from the usage of specification formalisms with first-order expressiveness, as well as exogenous events, triggered by the non-deterministic environment. More specifically, we use the agent programming language Golog, which is based on the situation calculus, a first-order logic formalism for reasoning about change. Here, a situation calculus action theory (perhaps incompletely) describes the initial state of the world, together with the preconditions and effects of primitive actions at the agent's disposal, while Golog programs then combine primitive actions into more complex behaviours using sequence, iteration, non-deterministic branching, and concurrency. Some of the non-deterministic choices in the program are under the control of the environment, which makes the program realization a synthesis problem. The synthesis task is to determine an execution strategy that executes the program successfully while satisfying the temporal goal, independent of the environment's choices.<br><br>
      </span>
    </li>
  </ul>
* 17:30 Welcome reception with activities, including tapas, drinks, etc. (<a href="venue.html#welcome-reception">details</a>)


## Thursday November 7
Auditorium B

* 08:30 Day opens (with coffee, tea, croissant, and wienerbrød)
* 09:05 Keynote, Chair: Fritz Henglein<br>
  <b>Sam Staton</b><br>
  <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;" >_Programming theory meets statistical modelling_</span>
  <span style="display: none;"><br>
    <b>Affiliation:</b> University of Oxford, UK<br>
    <b>Abstract:</b> I will discuss the idea that concepts from programming theory have a role to play in statistical modelling. Indeed they are already playing this role to some extent, but in different guises. These concepts include abstract types and lazy data structures, as well as more theoretical ideas such as effect gradings, monoidal indeterminates and sheaf categories. So I will present some opportunities for using programming theory to inform and formalize the abstract structure of statistics and probability, including some recent and ongoing results from myself and collaborators. I won't assume much familiarity.<br>
    <b>Biography:</b> Sam is a professor of Computer Science in Oxford. He has previously worked in Nijmegen, Paris and Cambridge. The talk will be based on work funded by the ERC grant "BLAST: Better Languages for Statistics" and the ARIA Project "Employing categorical probability towards safe AI".<br><br>
  </span>
* 10:00 Break (with coffee and tea)
* 10:30 Session 4
  <ul>
    <li>Philipp G. Haselwarter, Kwing Hei Li, Alejandro Aguirre, Simon Oddershede Gregersen, Joseph Tassarotti and Lars Birkedal<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Approximate Relational Reasoning for Higher-Order Probabilistic Programs</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> Properties such as provable security and correctness for randomized programs are naturally expressed relationally as approximate equivalences. As a result, a number of relational program logics have been developed to reason about such approximate equivalences of probabilistic programs. However, existing approximate relational logics are mostly restricted to first-order programs without general state.<br>
        In this paper we develop Approxis, a higher-order approximate relational separation logic for reasoning about approximate equivalence of programs written in an expressive ML-like language with discrete probabilistic sampling, higher-order functions, and higher-order state. The Approxis logic recasts the concept of error credits in the relational setting to reason about relational approximation, which allows for expressive notions of modularity and composition, a range of new approximate relational rules, and an internalization of a standard limiting argument for showing exact probabilistic equivalences by approximation. We also use Approxis to develop a logical relation model that quantifies over error credits, which can be used to prove exact contextual equivalence. We demonstrate the flexibility of our approach on a range of examples, including the PRP/PRF switching lemma, IND$-CPA security of an encryption scheme, and a collection of rejection samplers. All of the results have been mechanized in the Coq proof assistant and the Iris separation logic framework.<br><br>
      </span>
    </li>
    <li>Stian Øverby and Joachim Tilsted Kristensen<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Probably: A programming language with stochastic let-bindings</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> Probabilistic programming languages can be used for specifying experiments as computer programs. We address the problem of computing the underlying probability distribution of a small toy programming language with stochastic let bindings. Our main contribution is to equip the language with probability distribution in both terms and type system, so that we can reason about probabilistic computations.<br><br>
      </span>
    </li>
    <li>Philipp Stassen, Rasmus Ejlers Møgelberg, Maaike Zwart, Alejandro Aguirre and Lars Birkedal<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Modelling a Probabilistic Programming Language in Clocked Cubical Type Theory</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> We show how to use a metalanguage with guarded recursion to construct both denotational and operational semantics for a programming language combining recursive types and finite probabilistic choice. We construct a relation between the two and show that it is adequate for reasoning about contextual equivalence. Examples include the encoding of a fair coin from an unfair one, and the equivalence of two random walks.<br><br>
      </span>
    </li>
  </ul>
* 12:00 Lunch
* 13:30 Session 5
  <ul>
    <li>Nikolaj Kristensen, Benjamin Bennetzen, Daniel Kleist, Peter Steffensen, Emilie Steinmann and Loke Walsted<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>A Type System to Ensure Non-interference in ReScript</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> Protecting confidential data from leaking is a critical challenge in computer systems, particularly given the growing number of observers on the internet. Therefore, limiting information flow using robust security policies becomes increasingly vital. We focus on the non-interference policy, where the goal is to ensure that confidential data can not impact public data. This paper presents a type system, for a subset of the ReScript syntax, designed to enforce noninterference. We conclude with a proof of soundness for the type system, demonstrating that if an expression is type-able, it is inherently non-interferent. In addition, we provide a brief overview of a type checker that implements the previously mentioned type system.<br><br>
      </span>
    </li>
    <li>Ksenija Kivojenko, Edwin Smagin, Ian Erik Varatalu and Juhan Ernits<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Towards text extraction learning with regular expressions extended with complement, intersection and lookarounds</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> Algorithmic regular expression learning can be divided into 2 categories: 1) positive and negative examples based match existence search; 2) (context aware) substring extraction.<br>
        While the first has received most attention in the literature, the second provides very efficient algorithmic tools for text extraction. We present a heuristic search based context aware substring extraction learning tool that is based on a regular expression engine extended with intersection, complement and lookarounds, that produces results that supercede those available in the literature. The approach allows us to learn regular expressions for text extraction for performing tasks some of which are similar to those achieved by BERT deep learning models, with speeds up to 1 GB/s on a single CPU thread.<br><br>
      </span>
    </li>
    <li>Nikolaj Kristensen, Benjamin Bennetzen, Loke Walsted, Peter Steffensen, Emilie Steinmann and Daniel Kleist<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Cost Analysis for Import and Export Using an Abstract Machine</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> This paper presents the syntax and reduction rules for an abstract machine based on the JavaScript XML language. We incorporate the notion of cost into our reduction rules, and create a type system that over-approximate this cost. This over-approximation results in an equation that may contain unknowns originating from while loops. We conclude with a formal proof of soundness of the type system for our abstract machine, demonstrating that it over-approximates the cost of any terminating program. An implementation of the type system, constraint gathering, and the abstract machine is also presented.<br><br>
      </span>
    </li>
  </ul>
* 15:00 Break (with coffee, tea, and cake)
* 15:30 Session 6
  <ul>
    <li>Fritz Henglein, Changjun Li and Mikkel Kragh Mathiesen<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Simple Worst-Case Optimal Joins</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> We show that worst-case optimal joins, also for cyclic joins, are easy to program using basic programming techniques. They only require straightforward dictionaries, iterating over the smallest set when intersecting multiple sets and nested iteration over the variables in a join query in any order. We sketch a proof of worst-case optimality by amortization, where the execution cost is allocated to the generated output, but of padded input. We point out that modern database systems (still) generate asymptotically inferior code on cyclic joins.<br><br>
      </span>
    </li>
    <li>Timmie Lagermann, Kristina Carter, Su Ho and Maja Kirkeby<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>UI Test Automation Framework for Energy Analysis: Exploring Energy Compositionality of Actions</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> UI Testing Frameworks have been suggested for evaluating the energy consumption of software. Previous research has studied how automation frameworks can increase the energy consumption from the individual actions, compared to a human produced baseline. In this study, we present the first explorations on the dependence between the individual actions. We explore the Selenium Test Framework’s actions Input, i.e., inputting text into a text field, and Click, i.e., the action of clicking a button. These initial results show that the energy consumed by the individual Framework actions are dependent, and they are order-independent.<br><br>
      </span>
    </li>
    <li>Joel Nyholm, Wojciech Mostowski and Christoph Reichenbach<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Bayesian Energy Profiler for Java</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> Energy efficiency is a key concern in the design of mobile software, but no less significant for understanding the environmental impact of backend software in data centers. However, understanding and improving the energy usage of even simple software systems can be challenging, and modern language run-time systems with complex, dynamic optimizations exacerbate this challenge. Consider Java: Java stores executable code in a platform-independent intermediate representation, Java bytecode, that is executed on platform-specific Java Virtual Machines (JVMs). Energy consumption of Java code thus depends not only on the dynamic behavior of the just-in-time compiler and garbage collector, but also on peculiarities of the target hardware, operating system, and JVM implementation. To understand the energy impact of some software design decision, a software engineer today would need detailed knowledge that penetrates all these abstraction layers and accounts for the peculiarities of all intended target platforms. To aid developers, we propose to offer tools that support the Static Analysis of Energy Usage in Software, that can both infer energy usage properties through scalable and explainable analysis techniques, and verify explicit developer claims via theorem-proving based verification, extending prior work on energy usage modeling to the KeY system. We split the challenge of building such tools into modeling (1) the mapping from static program structure to dynamic traces, and (2) the energy consumption of dynamic traces.<br><br>
      </span>
    </li>
  </ul>
* 18:00 to 22:00 Workshop dinner, including 3 course dinner and drinks (<a href="venue.html#workshop-dinner">details</a>)


## Friday November 8
Auditorium A

* 10:00 Day opens (with coffee, tea, croissant, and wienerbrød)
* 10:30 Session 7, Chair: Wojciech Mostowski
  <ul>
    <li>Christian Kalhauge<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Input Reduction Revisited</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> Given an input that crashes your program, finding a minimal working example is crucial to enable easy debugging. We refer to this as the input reduction problem. Current state of the art techniques are either syntax oriented, which means they cannot do interesting transformations, or they are very painstakingly written to fit a specific input type. In this series of work we present a novel technique, we call Reduction Trees. It is a technique that allows the user to map out all possible sub-inputs of an input in an ordered binary tree. Theoretically, this technique allows for fast solutions to the input reduction problem, while being flexible enough to enable transformations. However, it has one big flaw: the trees had to be specified lazily because otherwise they were too big to fit in memory. This made them hard to encode in non-lazy languages. During last years talk on Input Reduction, many great questions were asked. The best, by far, was "Is it possible to write your reductions in a language like Python?" The answer turns out to be yes! and to great effect. Given a relatively modest implementation effort we are able to produce reduction results equivalent to the state of the art in a fraction of the time.<br><br>
      </span>
    </li>
    <li>Torben Ægidius Mogensen<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>A Simple Method for Inverting Tail-Recursive Functions</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> Program inversion and reversible programming languages have long been studied. For functional programming languages, tail-recursive functions are an issue, as they are most often not reversible on their own, but only in specific calling contexts. Several solutions to this have been proposed, but they are usually either quite complex or limited to special cases (or both). We present a simple method for inverting functions in a subset of Haskell, and show that this can not handle tail recursion. We then propose a solution to this that involves a temporary rewrite of calls to tail-recursive functions to a functional iterative form, inverting this, and then rewrite back into a tail-recursive form. The method is an extension of earlier work about semi-inversion of guarded equations, but removes the limitation that the earlier method required tail-recursive functions to have exactly one non-recursive base case. We then extend the subset of Haskell that the method can handle, though it is still nowhere near full Haskell.<br><br>
      </span>
    </li>
    <li>Joachim Kristensen and Matthias Gissurarson<br>
      <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;"><i>Saving memory by consolidating fragmented lists</i></span>
      <span style="display: none;"><br>
        <b>Résumé:</b> Classic texts on algorithms and data structures, such as CLRS,focus on the imperative programming paradigm, which favours ephemeralstructures and destructive operations.--Other programming paradigms such as the functional paradigm, does not enjoysuch a rich literature, and it remains challenging to design space efficientpersistent data structures that perform as well as their ephemeralcounterparts.<br>
        In this paper, we present a fragmented representation of lists that achievesconstant time and space complexity for append operations and linear time fortraversal in Haskell. This structure is particularly effective inapplications like sorting, where an efficient implementation of append isessential.--The technique used to develop the structure, generalises to monoidalcontexts in which the result of the computation is an appendable structure,which is only traversed once.<br><br>
      </span>
    </li>
  </ul>
* 12:00 Lunch
* 13:30 Keynote, Chair: Michael Kirkedal Thomsen<br>
  <b>Martin Berger</b><br>
  <span href="#" onmouseover="this.style.cursor='pointer';" onclick="toggleNext(this);" style="text-decoration: underline;color: blue;" >_Towards GPU-accelerated automated reasoning_</span>
  <span style="display: none;"><br>
    <b>Affiliation:</b>University of Sussex & Montanarius Ltd<br>
    <b>Abstract:</b> Graphics Processing Units (GPUs) are the work-horses of high-performance computing. The acceleration they provide to applications compatible with their programming paradigm can surpass CPU performance by several orders of magnitude, as notably evidenced by the advancements in deep learning. A significant spectrum of applications, especially within automated reasoning—like SAT/SMT solvers—has yet to reap the benefits of GPU acceleration.  In this talk we discuss recent work that successfully implemented program synthesis on GPUs and used it to accelerate learning of logical specifications from examples.  We conclude by mapping out a research programme to move more formal verification workloads to GPUs.<br>
    <b>Biography:</b> Martin Berger did his PhD in formal models for distributed systems at Imperial College. He's currently an associate professor in the Department of Informatics at the University of Sussex.  He's also working as a verification consultant for the microprocessor industry, and is one of the maintainers of the official RISC-V instruction set architecture (<a href="https://github.com/riscv/sail-riscv" target="_blank">https://github.com/riscv/sail-riscv</a>).  His research interests include: logic and verification, typing systems, process calculus, meta-programming, JIT compiler.<br><br>
  </span>
* 14:30 Closing session and "fyraftensbajer" (end of work beer)

