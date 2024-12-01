---
permalink: /research/
title: "Research Experience"
author_profile: true
---
<h2>{{"TruSt Implementation in Lincheck"}}</h2>
<div style="text-align: right; font-family: Arial, sans-serif; font-size: 14px;">
  Jul 2023 - Sep 2023
</div>
<br>
<div style="text-align: justify;">
I worked as an intern at Max Planck Institute for Software Systems during the summer 2023 under the supervision of <a href="https://people.mpi-sws.org/~rupak/">Prof. Rupak Majumdar</a>. I collaborated with <a href="https://github.com/PashaBarahimi">Pasha Barahimi</a> in implementing the TruSt algorithm in Lincheck, a tool for testing concurrent algorithms on the JVM. The implementation was based on the paper <a href="https://plv.mpi-sws.org/genmc/popl2022-trust.pdf">"Truly Stateless, Optimal Dynamic Partial Order Reduction"</a>. The TruSt algorithm is a stateless dynamic partial order reduction (DPOR) technique aimed at reducing the number of interleavings explored in concurrent programs in order to decrease memory usage and execution time. The repository for the implementation can be found <a href="https://github.com/rupakm/lincheck">here</a>.
</div>     
<br>
<div style="text-align: justify;">
During the implementation, we encountered many challenges related to distinguishing between the different shared variables as the default strategy in Lincheck was check all possible interleavings on the shared variables. The challenges were mainly due to some high-level features of java such as garbage-collector. We listed some of the possible solutions and their issues <a href="https://github.com/rupakm/lincheck/blob/master/src/jvm/main/org/jetbrains/kotlinx/lincheck/strategy/managed/trust/README.md">here</a>.
</div>
<!-- ---------------------------------------------------- -->
<h2>{{"TruSt Implementation in Lincheck"}}</h2>
<div style="text-align: right; font-family: Arial, sans-serif; font-size: 14px;">
  October 2024 - Current
</div>
<br>
<div style="text-align: justify;">
Currently, I am working on my bachelor’s thesis under the supervision of Prof. <a href="https://www.fatemehghassemi.ir/">Prof. Fatemeh Ghassemi</a> focusing on modeling and verifying various scheduling algorithms using networks of timed automata. In this project, I consider a finite number of tasks, with the ultimate goal of determining whether the tasks are unschedulable and measuring the time required for each task to be executed. I am using UPPAAL, an integrated tool environment for modeling, validation, and verification of real-time systems, to explore the drawbacks and advantages of different existing strategies for modeling scheduling algorithms. Additionally, my goal is to develop a modeling strategy that is applicable to a wide range of scheduling algorithms, enabling more efficient analysis and verification across various system designs.
</div>  