---
title: "SkillWrapper: Generative Predicate Invention for Skill Abstraction"
collection: publications
category: workshops
permalink: /publication/2025-11-22-generative-predicate-invention
date: 2025-11-22
excerpt: 'Active, automatic, embodiment-agnostic skill predicate learning using generative models.'
venue: 'CoRL Learning Effective Abstractions for Planning workshop'
paperurl: 'https://arxiv.org/abs/2511.18203'
bibtexurl: 'https://arxiv.org/abs/2511.18203'
citation: 'Ziyi Yang, Benned Hedegaard, Ahmed Jaafar, Yichen Wei, Skye Thompson, Shreyas S. Raman, Haotian Fu, Stefanie Tellex, George Konidaris, David Paulius, Naman Shah- CoRL LEAP workshop, 2024'
---

Generalizing from individual skill executions to solving long-horizon tasks remains a core challenge in building autonomous agents. A promising direction is learning high-level, symbolic abstractions of the low-level skills of the agents, enabling reasoning and planning independent of the low-level state space. Among possible high-level representations, object-centric skill abstraction with symbolic predicates has been proven to be efficient because of its compatibility with domain-independent planners. Recent advances in foundation models have made it possible to generate symbolic predicates that operate on raw sensory inputs, a process we call generative predicate invention, to facilitate downstream abstraction learning. However, it remains unclear which formal properties the learned representations must satisfy, and how they can be learned to guarantee these properties. In this paper, we address both questions by presenting a formal theory of generative predicate invention for skill abstraction, resulting in symbolic operators that can be used for provably sound and complete planning. Within this framework, we propose SkillWrapper, a method that leverages foundation models to actively collect robot data and learn human-interpretable, plannable representations of black-box skills, using only RGB image observations. Our extensive empirical evaluation in simulation and on real robots shows that SkillWrapper learns abstract representations that enable solving unseen, long-horizon tasks in the real world with black-box skills. 
