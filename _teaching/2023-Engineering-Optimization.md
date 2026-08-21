---
title: "Engineering Optimization (工程优化)"
collection: teaching
layout: archive
type: "Undergraduate course"
permalink: /teaching/2023-Engineering-Optimization
venue: "Zhengzhou University, School of Management"
date: 2023-02-02
location: "Zhengzhou, China"
---

## Course information
- Course name: Engineering Optimization
- Course ID: 074090.01
- Lectures/Location:
    - 周三上午 1‑4 节（1‑4、6‑9 周），上课地点：**主校区 北 1_206**
    - 周五下午 5‑8 节（1‑2、5‑6 周），上课地点：**主校区 北 1_103**
    - 3、4、7、8、9周无周五课程
- Instructor: [Yanjie Zhou](https://ieyjzhou.github.io/) 
- Email: [ieyjzhou@zzu.edu.cn](ieyjzhou@zzu.edu.cn)

## Prerequisites
- Calculus I and II
- Linear algebra
- Operation research
- Data structure
- Programming language (familiar with one programming language): C/C++; Python; Java; Matlab; Julia

## Coursework
- Homework (100%)


## Course Description

 This course, based on the textbook *Engineering Optimization: Problems, Methods, and Applications* by Yanjie Zhou, delivers a top‑down perspective of engineering optimization. Instead of merely teaching isolated optimization algorithms, it focuses on **identifying practical engineering optimization problems first, then selecting and adapting appropriate solving methods**.

This subject builds a complete knowledge system covering five major parts: foundations, core engineering optimization concepts, typical engineering optimization problem categories, optimization solution methodologies, and real‑world application cases. Students will distinguish decision problems, optimization problems and practical engineering problems, master problem decomposition techniques, and understand the essential gap between theoretical optimal solutions and practically deployable best solutions. Core thinking modes including coarse‑to‑fine modelling, multiple and near‑optimal solution analysis, and three‑dimensional engineering trade‑offs (model fidelity versus tractability, method power versus computational cost, solution optimality versus practical acceptability) are emphasized throughout the lectures.

The course systematically introduces mainstream problem classes: combinatorial deterministic optimization, robust optimization, bilevel programming, multi‑objective optimization, goal programming, multi‑stage stochastic optimization, and competitive game‑theoretic optimization. It further surveys classical exact algorithms, meta‑heuristics, matheuristics, simulation‑driven optimization and learning‑based optimization approaches. The whole textbook adopts **container terminal operation management as a running case study**, using Yangshan automated container terminal to illustrate how diverse optimization problem classes are coupled within one complex real‑life engineering system.

Prerequisites include calculus, linear algebra, and basic programming skills. No closed‑book written examinations are arranged. Assessment is entirely based on group projects. Students are required to complete full‑cycle engineering optimization practice: problem identification, mathematical modelling, method selection, implementation, and result interpretation, taking container‑terminal‑related sub‑problems as the research object. Upon completing this course, learners are capable of analyzing complex industrial systems, decomposing practical challenges into formal optimization formulations, and producing implementable engineering decisions rather than pursuing purely theoretical optima.

    
## Schedule (tentative)

<table border="1">
<thead>
<tr>
<th>周次</th>
<th>星期&amp;节次</th>
<th>上课地点</th>
<th>本次学时</th>
<th>教材章节</th>
<th>授课主题</th>
<th>课堂任务</th>
</tr>
</thead>
<tbody>
<tr>
<td rowspan="2">1</td>
<td>周三（上午1‑4节）</td>
<td>主校区 北1_206</td>
<td>4</td>
<td>Part‑I Ch1</td>
<td>【Part‑I 基础】课程导论；Ch1 决策问题、优化问题、工程问题，三类问题嵌套关系、多项式等价；可/不可数学建模的工程问题</td>
<td>理论讲授，介绍课程考核项目要求</td>
</tr>
<tr>
<td>周五（下午5‑8节）</td>
<td>主校区 北1_103</td>
<td>4</td>
<td>Part‑I Ch2‑Ch3</td>
<td>【Part‑I 基础】Ch2 问题分解：分解维度、分解‑协调机制、集装箱码头分解案例；Ch3 解的概念：理论最优解与工程最佳解，精确解、ε‑近优解，多重最优解，工程意义“足够好”判定</td>
<td>理论讲授，建立基础概念框架</td>
</tr>
<tr>
<td rowspan="2">2</td>
<td>周三（上午1‑4节）</td>
<td>主校区 北1_206</td>
<td>4</td>
<td>Part‑I Ch4‑Ch5</td>
<td>【Part‑I 基础完结】Ch4 优化理论方法与工程实践方法对比；Ch5工程优化三重权衡：模型保真度‑可求解性、方法能力‑计算代价、解质量最优‑可接受；NP‑hard工程困境</td>
<td>理论讲授，理解工程优化权衡思想</td>
</tr>
<tr>
<td>周五（下午5‑8节）</td>
<td>主校区 北1_103</td>
<td>4</td>
<td>Part‑II Ch6‑Ch7</td>
<td>【Part‑II 工程优化】Ch6工程优化定义、问题多维度分类，自上而下求解工作流，洋山四期码头案例；Ch7工程优化迭代求解流程，从现象到核心模型，模型拓展与反馈闭环，工程引擎概念</td>
<td>理论讲授，掌握迭代求解完整流程</td>
</tr>
<tr>
<td>3</td>
<td>周三（上午1‑4节）</td>
<td>主校区 北1_206</td>
<td>4</td>
<td>Part‑II Ch8‑Ch9</td>
<td>【Part‑II 工程优化完结】Ch8由粗到细建模方法，粗阶段‑精细阶段，集装箱重定位CRP案例；Ch9多重最优解、最优集合，ε‑近优集合，多样化近优解集生成，利用解集支撑工程决策</td>
<td>理论讲授，掌握粗‑细建模与近优解集理论</td>
</tr>
<tr>
<td>4</td>
<td>周三（上午1‑4节）</td>
<td>主校区 北1_206</td>
<td>4</td>
<td>Part‑III Ch10‑Ch11</td>
<td>【Part‑III 工程优化问题】Ch10确定性与组合优化，原型问题，整数间隙，NP‑hard，集装箱码头组合子问题；Ch11鲁棒优化，不确定性集合，鲁棒对等模型，可调鲁棒优化与工程应用</td>
<td>理论讲授，学习组合优化、鲁棒优化</td>
</tr>
<tr>
<td>5</td>
<td>周五（下午5‑8节）</td>
<td>主校区 北1_103</td>
<td>4</td>
<td>Part‑III Ch12‑Ch13</td>
<td>【Part‑III 工程优化问题】Ch12双层规划，领导者‑跟随者结构，问题难点，KKT转化、罚函数、元启发求解思路；Ch13多目标优化，帕累托占优、帕累托前沿，标量化、进化多目标算法</td>
<td>理论讲授，掌握双层、多目标优化理论</td>
</tr>
<tr>
<td rowspan="2">6</td>
<td>周三（上午1‑4节）</td>
<td>主校区 北1_206</td>
<td>4</td>
<td>Part‑III Ch14‑Ch15</td>
<td>【Part‑III 工程优化问题】Ch14目标规划，加权、词典序、切比雪夫GP，目标规划与多目标优化对比；Ch15多阶段随机优化，情景树，两阶段/多阶段模型</td>
<td>理论讲授，辨析目标规划，学习多阶段随机优化</td>
</tr>
<tr>
<td>周五（下午5‑8节）</td>
<td>主校区 北1_103</td>
<td>4</td>
<td>Part‑III Ch16；Part‑IV Ch17‑Ch18</td>
<td>【Part‑III完结 + Part‑IV工程优化方法】Ch16竞争博弈问题，纳什均衡，古诺、伯特兰模型，网络拥塞博弈；Ch17‑18方法总览，精确、元启发式、matheuristics数学启发方法，各类方法适用边界</td>
<td>理论讲授，建立“问题匹配求解方法”思维</td>
</tr>
<tr>
<td>7</td>
<td>周三（上午1‑4节）</td>
<td>主校区 北1_206</td>
<td>4</td>
<td>Part‑IV Ch19‑Ch20</td>
<td>【Part‑IV 工程优化方法完结】Ch19基于仿真的优化，蒙特卡洛、离散事件仿真，仿真优化范式；Ch20基于学习的优化，端到端学习优化，强化学习在优化中的应用与局限</td>
<td>理论讲授，掌握仿真、学习驱动优化方法</td>
</tr>
<tr>
<td>8</td>
<td>周三（上午1‑4节）</td>
<td>主校区 北1_206</td>
<td>4</td>
<td>Part‑V Ch21‑Ch22</td>
<td>【Part‑V 应用】Ch21集装箱码头运营管理，海侧‑堆场‑陆侧各环节对应的优化子问题；Ch22集装箱码头自动化演进，辨析自动化不是越高级越好，需求、能力、制度现实约束</td>
<td>理论讲授，熟悉集装箱码头工程背景</td>
</tr>
<tr>
<td>9</td>
<td>周三（上午1‑4节）</td>
<td>主校区 北1_206</td>
<td>4</td>
<td>Part‑V Ch23；全书复盘</td>
<td>【Part‑V完结】Ch23集装箱码头系统综合集成案例；岸桥调度实例；组合/鲁棒/多目标/双层/多阶段/博弈各类问题在码头系统耦合；全书Part‑I~Part‑V完整知识复盘梳理</td>
<td>理论讲授，打通全书知识体系，课程内容全部完成</td>
</tr>
</tbody>
</table>
 
## Book Content (Tentative)

- **Part I Foundations**

    - 1 Problems

        - 1\.1 Decision problems

        - 1\.2 Optimization problems

        - 1\.3 Engineering problems

        - 1\.4 Relationships among the three

            - 1\.4\.1 Decision and optimization are polynomially equivalent

            - 1\.4\.2 From engineering problem to optimization to decision

        - 1\.5 Problem formulation

            - 1\.5\.1 Problems that can be formulated as mathematical models

            - 1\.5\.2 Problems that cannot be formulated as mathematical models

    - 2 Problem Decomposition

        - 2\.1 Why decompose?

        - 2\.2 Dimensions of decomposition

            - 2\.2\.1 By decision agent \(distributed / bilevel\)

            - 2\.2\.2 By time horizon \(planning / scheduling / control\)

            - 2\.2\.3 By spatial region or subsystem

            - 2\.2\.4 By objective \(scalarise, then reconcile\)

            - 2\.2\.5 Hierarchical / recursive decomposition

        - 2\.3 An example: a container terminal

        - 2\.4 Decomposition and coordination

        - 2\.5 Relationship to the rest of the book

    - 3 Solution

        - 3\.1 Solution of decision problem

        - 3\.2 Solution of optimization problem

        - 3\.3 Solution of engineering problem

        - 3\.4 Best solution VS optimal solution in engineering optimization

        - 3\.5 Exact, approximate, and near‑optimal solutions

        - 3\.6 How do we know a solution is optimal?

        - 3\.7 Multiple and non‑unique solutions

        - 3\.8 How good is good enough?

        - 3\.9 How to obtain the best solution in practice

    - 4 Methods

        - 4\.1 Methods for Optimization Theory

        - 4\.2 Methods for Real Engineering Problems

        - 4\.3 Theory vs\. Engineering: a comparison

        - 4\.4 Roadmap

    - 5 Trade‑offs among Problems, Solutions, and Methods

        - 5\.1 Why engineering is not just applied theory

        - 5\.2 The three trade‑off dimensions

            - 5\.2\.1 Problem approximation \(fidelity vs\. tractability\)

            - 5\.2\.2 Method selection \(power vs\. cost\)

            - 5\.2\.3 Solution quality \(optimal vs\. acceptable\)

        - 5\.3 Synthesis: managing the trade‑off

- **Part II Engineering Optimization**

    - 6 Introduction

        - 6\.1 Engineering Optimization

            - 6\.1\.1 What is Engineering Optimization?

            - 6\.1\.2 Examples of engineering optimization

        - 6\.2 Engineering Optimization Problems

            - 6\.2\.1 By uncertainty in the data: deterministic vs\. stochastic

            - 6\.2\.2 By number of objectives: single‑objective vs\. multi‑objective

            - 6\.2\.3 By variable type: continuous vs\. discrete

            - 6\.2\.4 By model shape: linear vs\. nonlinear

            - 6\.2\.5 In practice: optimization across engineering domains

        - 6\.3 Engineering Optimization Methods

            - 6\.3\.1 Deterministic methods

            - 6\.3\.2 Stochastic methods

            - 6\.3\.3 Hybrid methods

            - 6\.3\.4 Choosing a method: a decision framework

        - 6\.4 Challenges in Engineering Optimization

        - 6\.5 The Landscape of Engineering Optimization Problems

            - 6\.5\.1 Why the combinatorial class was the gap

            - 6\.5\.2 How the classes co‑occur

        - 6\.6 A Top‑Down Problem‑Solving Workflow

            - 6\.6\.1 Preview of Part V: the container terminal

    - 7 Solving Process

        - 7\.1 Background: engineering is built stage by stage

        - 7\.2 The process at a glance

        - 7\.3 Phase I: from phenomenon to core problem

            - 7\.3\.1 Recognizing the phenomenon

            - 7\.3\.2 The core phase

        - 7\.4 From method to solution

            - 7\.4\.1 Choosing the first method

            - 7\.4\.2 Improved methods

            - 7\.4\.3 When is a solution good enough?

        - 7\.5 Extending the problem: phases II to n\+1

            - 7\.5\.1 Why models grow

            - 7\.5\.2 Extended optimization problems

        - 7\.6 The feedback loop

            - 7\.6\.1 Solutions inform the next problem

            - 7\.6\.2 A practical iteration template

            - 7\.6\.3 Connection to coarse‑to‑fine methods

            - 7\.6\.4 An engineering engine that makes the loop cheap

        - 7\.7 Chapter summary

    - 8 Coarse‑to‑fine methods

        - 8\.1 Introduction

        - 8\.2 Approximation of goals

        - 8\.3 Coarse‑to‑fine methods

            - 8\.3\.1 Coarse phase

            - 8\.3\.2 Fine phase

            - 8\.3\.3 Framework

        - 8\.4 A case study

            - 8\.4\.1 Approximation of goals

            - 8\.4\.2 Coarse to fine

    - 9 Multiple solutions make better decision

        - 9\.1 Why a single optimum is not the end of the story

        - 9\.2 Multiple optimal solutions

            - 9\.2\.1 Definition and the optimal set

            - 9\.2\.2 Where alternative optima arise

            - 9\.2\.3 The geometry of the optimal set

            - 9\.2\.4 Exploiting alternative optima: secondary optimization

            - 9\.2\.5 Illustration: an edge of optima

        - 9\.3 Multiple near‑optimal solutions

            - 9\.3\.1 Definition of ε‑optimality

            - 9\.3\.2 Why near‑optimal solutions carry the real value

            - 9\.3\.3 Generating a diverse solution pool

            - 9\.3\.4 From a pool to a decision

            - 9\.3\.5 Connection to other chapters

        - 9\.4 Summary

- **Part III Engineering Optimization Problems**

    - 10 Deterministic Optimization Problems

        - 10\.1 Classification of deterministic optimization problems

        - 10\.2 What makes a problem combinatorial

        - 10\.3 Archetypal problems

        - 10\.4 Why combinatorial problems are hard: the integrality gap

        - 10\.5 Solution approaches

        - 10\.6 Engineering features: what makes these engineering problems

        - 10\.7 Motivation: the container terminal as a combinatorial system

        - 10\.8 Summary and forward links

    - 11 Robust Optimization Problem

        - 11\.1 Motivation: data are never exact

        - 11\.2 The robust optimization framework

        - 11\.3 Uncertainty sets

            - 11\.3\.1 Box \(interval\) uncertainty

            - 11\.3\.2 Ellipsoidal uncertainty

            - 11\.3\.3 Budget of uncertainty \(Bertsimas‑Sim\)

        - 11\.4 Robust counterpart of a linear program

        - 11\.5 Adjustable robust optimization

        - 11\.6 Engineering applications

        - 11\.7 Engineering features: what makes this an engineering problem

        - 11\.8 Summary

    - 12 Bilevel Programming Problem

        - 12\.1 What is bilevel programming?

        - 12\.2 Mathematical formulation

        - 12\.3 Why bilevel problems are hard

        - 12\.4 Solution approaches

            - 12\.4\.1 KKT‑based reformulation

            - 12\.4\.2 Penalty / regularization methods

            - 12\.4\.3 Evolutionary / metaheuristic methods

        - 12\.5 Engineering applications

        - 12\.6 Engineering features: what makes this an engineering problem

        - 12\.7 Summary

    - 13 Multiple Objective Optimization Problem

        - 13\.1 From one objective to many

        - 13\.2 Domination and Pareto optimality

        - 13\.3 Classical scalarization methods

            - 13\.3\.1 Weighted sum

            - 13\.3\.2 ε‑constraint method

        - 13\.4 Evolutionary multi‑objective optimization

            - 13\.4\.1 NSGA‑II

            - 13\.4\.2 MOEA/D

        - 13\.5 Engineering example: facility location

        - 13\.6 Engineering features: what makes this an engineering problem

        - 13\.7 Summary

    - 14 Goal Programming Problem

        - 14\.1 From optimizing to satisfying

        - 14\.2 The goal‑programming model

        - 14\.3 Three ways to aggregate the deviations

            - 14\.3\.1 Weighted goal programming

            - 14\.3\.2 Lexicographic \(preemptive\) goal programming

            - 14\.3\.3 Chebyshev \(min‑max\) goal programming

        - 14\.4 How goal programming differs from multi‑objective optimization

        - 14\.5 Mapping goal programming to engineering problems

        - 14\.6 Engineering features: what makes this an engineering problem

        - 14\.7 Chapter summary

    - 15 Multiple Stage Optimization Problem

        - 15\.1 Uncertainty revealed over time

        - 15\.2 Two‑stage stochastic programming

        - 15\.3 Multi‑stage and scenario trees

        - 15\.4 Connection to dynamic programming

        - 15\.5 Engineering applications

        - 15\.6 Engineering features: what makes this an engineering problem

        - 15\.7 Summary

    - 16 Competitive Game Problem

        - 16\.1 Elements of a game

        - 16\.2 Nash equilibrium

        - 16\.3 Illustrations: Cournot and Bertrand

            - 16\.3\.1 Cournot quantity competition

            - 16\.3\.2 Bertrand price competition

        - 16\.4 Congestion and network games in engineering

        - 16\.5 Games as variational inequalities: the link to optimization

        - 16\.6 Engineering features: what makes this an engineering problem

        - 16\.7 Summary

- **Part IV Engineering Optimization Methods**

    - 17 Overview of Engineering Optimization Methods

        - 17\.1 Roadmap: matching problem types to methods

        - 17\.2 From traditional to modern: a method spectrum

        - 17\.3 Choosing a method: matching tools to problems

        - 17\.4 Summary

    - 18 Classical Optimization Methods

        - 18\.1 Traditional baselines: exact and simple heuristics

            - 18\.1\.1 Exact methods as the foundation

            - 18\.1\.2 Constructive and greedy heuristics

            - 18\.1\.3 Local search

        - 18\.2 Matheuristics: exact power meets heuristic search

            - 18\.2\.1 Mathematical formulation first, metaheuristics second

            - 18\.2\.2 Metaheuristics first, mathematical formulation second

            - 18\.2\.3 Mapping matheuristics to problem classes

        - 18\.3 Meta‑Heuristic methods

            - 18\.3\.1 Trajectory methods

            - 18\.3\.2 Population methods

            - 18\.3\.3 Multi‑objective metaheuristics

        - 18\.4 Engineering adaptation: choosing and shaping the method

        - 18\.5 Summary

    - 19 Simulation‑Based Methods

        - 19\.1 Simulation‑based methods

            - 19\.1\.1 Why simulation

            - 19\.1\.2 Monte Carlo and scenario evaluation

            - 19\.1\.3 Discrete‑event simulation

            - 19\.1\.4 Simulation optimization

            - 19\.1\.5 Mapping simulation to problem classes

        - 19\.2 Engineering adaptation: choosing simulation, and how to use it

        - 19\.3 Summary

    - 20 Learning‑Based Optimization Methods

        - 20\.1 End‑to‑end learning \(learning to optimize\)

            - 20\.1\.1 Instance‑to‑solution mapping

            - 20\.1\.2 Imitation and learning to optimize

            - 20\.1\.3 Mapping end‑to‑end learning to problem classes

        - 20\.2 Reinforcement learning

            - 20\.2\.1 The RL formalism

            - 20\.2\.2 Mapping RL to problem classes

        - 20\.3 Engineering adaptation: when to learn, and how to keep it safe

        - 20\.4 Summary

- **Part V Applications**

    - 21 Container Terminal Operation and Management

        - 21\.1 The terminal as an operations system

        - 21\.2 Seaside operations: berthing and quay cranes

        - 21\.3 Yard and horizontal transport

        - 21\.4 Land‑side operations and integration

        - 21\.5 Engineering optimization problems at the port level

        - 21\.6 Mapping the terminal onto this book’s problem classes

        - 21\.7 Chapter summary

    - 22 From Conventional to Fully Automated: The Evolution of Container Terminal Automation

        - 22\.1 Introduction

        - 22\.2 The evolution as a solving process

            - 22\.2\.1 Phase I: the conventional terminal as the core model

            - 22\.2\.2 Phase II: mechanization adds structure

            - 22\.2\.3 Phase n: computerization and semi‑automation add information and uncertainty

            - 22\.2\.4 Phase n\+1: full automation as an interacting‑agent system

        - 22\.3 Why “the more automated the better” is wrong

            - 22\.3\.1 Demand: is there enough work? \(Economy\)

            - 22\.3\.2 Capability: are the resources there? \(Labor, materials, finance\)

            - 22\.3\.3 Institution: what is permitted and directed? \(Politics and policy\)

        - 22\.4 A context‑aware, staged path

        - 22\.5 Chapter summary

    - 23 Container Terminal Systems: An Integrated Application of Engineering Optimization

        - 23\.1 The terminal as a system

        - 23\.2 The combinatorial core

        - 23\.3 Robustness and uncertainty

        - 23\.4 Multi‑objective trade‑offs

        - 23\.5 Multi‑stage rescheduling

        - 23\.6 Bilevel and competitive structure

        - 23\.7 A worked example: quay‑crane scheduling

        - 23\.8 Synthesis: the terminal as the whole book

        - 23\.9 Closing remark

## Teamwork

TBD

<a href="https://info.flagcounter.com/AZQ9"><img src="https://s11.flagcounter.com/countxl/AZQ9/bg_FFFFFF/txt_000000/border_CCCCCC/columns_8/maxflags_12/viewers_0/labels_1/pageviews_1/flags_0/percent_0/" alt="Flag Counter" border="0"></a>

