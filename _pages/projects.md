---
layout: page
title: Research
permalink: /research/
description: Academic projects and industrial partnerships
nav: true
nav_order: 2
display_categories: [partnerships, academic, former partnerships]
horizontal: false
---

<!-- My goal is to make methodological contributions (theorems) that lead to practically efficient algorithms on problems that matter beyond maths, and mainly to improve decision-making for industrial processes. This lead me to pursue a research agenda at the cross-road of combinatorial optimization and machine learning. -->
<!-- I have a strong taste for industrial applications, notably in the fields of transport and supply chain, which lead me to mount and chair many industrial partnerships, among which the following two ones. -->

My objective is to develop methodological advancements, particularly theorems, that result in algorithms which are not only theoretically sound but also practically effective. These algorithms are designed to address significant issues that extend beyond the realm of mathematics, with a primary focus on **enhancing decision-making within industrial operations**. This ambition has guided me to a career in **Operations Research**, where I explore a research path that intersects **Combinatorial Optimization** with **Machine Learning**.

I possess a profound interest in applying these concepts to industry, especially within the transportation and supply chain sectors. This passion has driven me to initiate and oversee numerous industrial collaborations, including two notable partnerships.

- [Artificial Intelligence for Air Transport](../projects/1_af) chair between Air France and École des Ponts.
- [Operations Research and Machine Learning for supply chain](../projects/2_renault) with Renault Supply Chain.

## Why Operations Research

The ecological transition may be the greatest challenge of our generation.
The latest IPCC report emphasizes the need to act on two fronts simultaneously to curb global warming: adopting a more frugal lifestyle and improving our production methods. The latter is painless for the end consumer, as it involves producing the same goods and services more efficiently. As long as they are economically feasible, environmentally-focused policies based on technology are thus more widely accepted. It is important to implement them as effectively as possible.

When discussing environmental technologies, public debate often centers on renewable energy or low-carbon transportation. However, better decisions can also be made with existing technology. Take home delivery, for example. Investing in electric vehicles can reduce emissions. Better organization of delivery routes can also decrease the distance traveled to make the same deliveries, thereby reducing emissions as well. Yet, manually constructing efficient vehicle routes is challenging. Even with the best techniques, manually created solutions result in routes that are, on average, 13% longer than the optimal solution. To improve this, decision-support algorithms are needed. These algorithms can reduce emissions and costs by optimizing the use of available resources. They represent the mathematical and industrial version of waste reduction.

Operations research is the mathematical discipline that provides such decision-support tools. A typical outcome of an operations research project in industry is the ability to produce more cost-effectively and with fewer resources, without changing production means or technology. Advances in the field and greater data accessibility have increased the potential applications of operations research. These methods are currently underutilized outside of network industries and represent a significant source of economic and environmental value.

## Main drivers of performance in Operations Research

<!-- The mot important driver of performance in Operations Research is **modeling**, i.e., how you translate the optimization of an industrial process into a mathematical problem. You can do the best algorithms, if they don't solve the right problem, they are going to be useless.
But the reality is deeper than this. 
Optimizing an industrial process manually is difficult.
Firms have therefore accumulated along time numerous heuristics that enable to simplify the process, such as "each client should be visited every two days, truck routes should not serve more than 3 clients, etc."
While such rules that were introduced because they simplify the life of the truck planner and not because they are an industrial necessity tend to become unbreakable rules with time. The thing is, when we have computing power and an algorithm to optimize the industrial process, such rules become not only useless but harmful since they constrain the optimization and thus decrease performance. In other words, *one always gains more by changing the rule of the game than by playing better by the same rule*. 

Modeling for Operations Research is an art that I practice because it is key for applications, but it is more on the consulting than the academic side of Operations Research. -->

In Operations Research, the most critical factor for success is **modeling**. This involves translating the optimization of an industrial process into a mathematical problem. The most sophisticated algorithms are futile if they don’t address the correct problem. But this reality takes a particular flavor in Operations Research. Manual optimization of industrial processes is arduous. Over time, companies have developed numerous heuristics to streamline these processes, such as “visit each client every two days” or “truck routes should not serve more than three clients.” Initially, these rules were adopted to simplify the planner’s task, not out of industrial necessity, and over time they have become sacrosanct. However, with the advent of computing power and sophisticated algorithms for optimizing industrial processes, these rules can become obsolete and even detrimental. They restrict optimization, leading to reduced performance. Essentially, *altering the rules of the game often yields greater benefits than improving gameplay within the existing framework*.

<!-- After modeling, the second driver of performance is **combinatorial optimization**, and more precisely to build *combinatorial optimization algorithms that scale*.
Optimizing an industrial process naturally belongs to the field of optimization.
Optimization is the part of applied mathematics that aims at minimizing functions, i.e., finding the best solutions according to a given objective among a set of solutions that satisfy some constraints.
When we optimize an industrial process, this generally means allocating resources such as vehicles, machines, etc. Those resources are typically not splittable, which leads to binary or integer variables: A plane operates a flight or does not operate it, but we cannot have a half plane operating a flight.
Combinatorial optimization is the part of optimization that deals with integer variables. 
When optimizing an industrial process, *performance generally comes from economy scales*. Consider for instance a firm that delivers parcels to clients in a city. If there are only three clients scattered in the city, even with the best algorithms, the truck is going to crisscross the city. If on the contrary there are many clients, then the algorithm can send a truck delivering all the requests in the same neighborhood. Hence, larger processes give more flexibility to the decision maker, which enables to reduce marginal costs. In other words, once a process has been modelled, **the main source of profit is decreasing marginal costs**. But reaping these economies of scales require algorithms that can take a global perspective when optimizing the process, i.e., algorithms that scale well on large instances. 
For theoretical and practical reasons, building combinatorial algorithms that scale is extremely challenging mathematically. This is the reason why *researchers in operations research have been focused on combinatorial optimization for the last 70 years*. -->

Beyond modeling, the next pivotal element for enhancing performance is **combinatorial optimization**. Specifically, the development of combinatorial optimization algorithms that are scalable. Optimization, a branch of applied mathematics, is dedicated to minimizing functions. In essence, it seeks the optimal solutions that meet a specific goal while adhering to certain constraints. In the context of industrial processes, optimization typically involves the allocation of resources like vehicles and machinery. These resources are often non-splittable, leading to binary or integer variables. For example, a plane either operates a flight or it doesn’t; there’s no such thing as half a plane on a flight. Combinatorial optimization deals with these integer variables. When it comes to industrial processes, *performance is largely driven by economies of scale*. For instance, a company delivering parcels in a city will face inefficiencies if only a few clients are spread out. However, with a higher number of clients, particularly in the same area, the delivery process becomes more efficient, allowing for reduced marginal costs. Thus, after a process is modeled, the primary profit lever is the reduction of marginal costs. Achieving these economies of scale necessitates algorithms that can take a holistic view of the process—algorithms that perform well even as the scale of operations grows.
Creating combinatorial algorithms that can handle large-scale applications is a significant mathematical challenge, both theoretically and practically. This complexity is why *operations research scholars have concentrated on combinatorial optimization for the past seven decades*.

Finally, the last driver of performance is **data**. As the saying goes *garbage in, garbage out*.
Data on industrial processes used to be scarce. Two decades of digitalization of industrial processes have changed the game. However, if data is now abundant, it is sometimes incomplete and often inherently random, which makes **machine learning** is the suitable discipline for managing uncertainty in their analysis and processing. 

When it comes to the tangible benefits of optimizing industrial processes, the hierarchy of impact generally begins with modeling, followed by combinatorial optimization, and finally, machine learning.
Applied mathematics and computer science scholars who work on Operations Research tend to focus on the methodological aspects, which lie on the optimization and on the learning side. 
Modeling is more an art than a scientific discipline. 
While a comprehensive understanding of mathematical tools is essential, it’s not the sole requirement for proficiency. True expertise in modeling also demands an appreciation for economic significance and a well-honed ability to engage with industry professionals. This engagement is crucial for speaking their language, and being able to challenge the rules of the games to unlock value.
<!-- An in-depth knowledge of the mathematical tools available is of course needed to master this art. But it is not sufficient, as mastering modeling requires a sense of what matters economically and a seasoned practice of intertacting with industrialists to be able to speak the same language, identify which rules matters and which one should be scrapped, etc. -->
<!-- In terms of practical returns on applied industrial process optimization projects, modeling is generally the key, then followed by combinatorial optimization, and then by machine learning. -->

## Today's Top Challenges in Operations Research

Two elements have profoundly changed the operations research landscape during the last decades. 
First process digitalization have made data abundant and algorithm much easier to integrate in workflows.
Second, dramatic progress have been made on combinatorial optimization.
Indeed, given the hierarchy of benefits previously outlined, it comes as no surprise that the operations research community has focused on building algorithms that scales, even if this means simplifying the objective. And it has been widely successful in this endeavor. Consider for instance mixed integer linear programming, which could be described as the Swiss knife of combinatorial optimization. On the same computer, the 2015 version of a well-known solver is 780 thousands times faster than the 1991 version. If we factor the hardware improvements, we get a 450 billion times speed-up. Problems with millions of variables and constraints are now routinely solved in the industry.

As a result, operations research is now widely applicable in the industry, and still underused.

Modeling leans more on the applied side Operations Research, 

## Research activities




## Industrial partnerships

- [Artificial Intelligence for Air Transport](../projects/1_af) chair between Air France and École des Ponts.
- [Operations Research and Machine Learning for supply chain](../projects/2_renault) partnership between Renault Supply Chain and École des Ponts.

