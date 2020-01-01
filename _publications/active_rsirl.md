---
title: "Active Learning for Risk-Sensitive Inverse Reinforcement Learning"
collection: publications
permalink: /publications/active_rsirl
excerpt: 'Risk-sensitive inverse reinforcement learning provides an general model to capture how human assess the distribution of a stochastic outcome when the true distribution is unknown (ambiguous). This work enables an RS-IRL learner to actively query expert demonstrations for faster risk envelope approximation.'
date: 2019-9-10
venue: 'International Conference on Robotics and Automation (ICRA) (In Review)'
paperurl: 'https://arxiv.org/abs/1909.07843'
authors: '**Rui Chen**, Wenshuo Wang, Zirui Zhao, Ding Zhao'
image: 'active_rsirl.gif'
archive_image: 'active_rsirl.gif'
codeurl: 'https://github.com/ruichen-v/active_learning_for_rsirl'
archive_venue: '**Rui Chen**, Wenshuo Wang, Zirui Zhao, Ding Zhao. In *International Conference on Robotics and Automation (ICRA) (In Review)*, 2020'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---
# Abstract
One typical assumption in inverse reinforcement learning (IRL) is that human experts act to optimize the expected utility of a stochastic cost with a fixed distribution. This assumption deviates from actual human behaviors under ambiguity. Risk-sensitive inverse reinforcement learning (RS-IRL) bridges such gap by assuming that humans act according to a random cost with respect to a set of subjectively distorted distributions instead of a fixed one. Such assumption provides the additional flexibility to model human's risk preferences, represented by a risk envelope, in safe-critical tasks. However, like other learning from demonstration techniques, RS-IRL could also suffer inefficient learning due to redundant demonstrations. Inspired by the concept of active learning, this research derives a probabilistic disturbance sampling scheme to enable an RS-IRL agent to query expert support that is likely to expose unrevealed boundaries of the expert's risk envelope. Experimental results confirm that our approach accelerates the convergence of RS-IRL algorithms with lower variance while still guaranteeing unbiased convergence.
 
<!-- [Download paper here](https://arxiv.org/abs/1909.07843) -->
