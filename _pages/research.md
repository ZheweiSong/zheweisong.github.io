---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

## Working Papers

### 1. Zhewei Song. (2022). "Seller Defensive Actions in Credence Goods Markets – Does Reputation and/or Education Improve Efficiency?" (Job Market Paper)
In credence goods markets such as healthcare service markets, after a buyer encounters a problem that requires treatment, only sellers have the expertise to determine which type of treatment is sufficient to address the buyer’s problem. Although sufficient treatment maximizes buyers’ expected utility, sometimes it cannot guarantee a 100% success rate. When a treatment failure happens, buyers cannot determine whether it is caused by undertreatment or bad luck after sufficient treatment. Buyers may express their dissatisfaction with sellers in costly ways by engaging in “crying behavior” that result in compensation. To avoid the costly aftermath from such “crying behavior”, sellers will “defend” themselves by overtreating to minimize the probability of treatment failure. However, the high cost of overtreatment incurred by both sellers and buyers will result in a Pareto-inefficient outcome, as compared to the situation where buyers do not cry and sellers choose sufficient treatment. To encourage sellers’ sufficient treatment and discourage buyers’ crying behavior, I extend the one-shot game to a repeated game and introduce a reputation system in which the seller’s treatment history and the buyer’s reactions are publicly visible, and I show that there exists a perfect public equilibrium in which the seller and buyer will frequently play the Pareto-efficient strategy profile. I also hypothesize that education, which primes sellers’ and buyers’ knowledge that they can be better-off when playing the Pareto-efficient strategy profile, can also encourage them to play the efficient strategy profile. My laboratory experimental results show that most sellers overtreat while most buyers cry when neither reputation nor education is present. Buyers are significantly less likely to cry when the reputation system is introduced. When both reputation and education are present, sellers are significantly more likely to choose sufficient treatment and significantly less likely to overtreat in the late stage of the game.


### 2. Zhewei Song & Erin Krupka. (2022). "“When Group- and Self-Esteem Lead To ‘We-Thinking’: When Does Social Identity Motivate Group Behavior?" Under review at *Experimental Economics*.
In this paper, we take as given that social identity motivates individuals to make group contributions and focus on examining the determinants of when it motivates these contributions. We test whether “we-thinking”, group-regarding behavior in the presence of an individual-group tradeoff, is predicted by a specific relationship between group- and self-esteem. We define group- and self-esteem as having positive feelings about the relative performance of one’s group and self. By extending Akerlof’s model (2016), we predict that engaging in “we-thinking” is positively correlated with group-esteem and negatively with self-esteem. We proxy for group-esteem and self-esteem using rank-based measures and self-reported measures. Using a laboratory experiment, we manipulate subjects’ group-esteem and self-esteem through intergroup and inter-personal competitions. We measure their engagement in “we-thinking” through a modified dictator game in which they allocate tokens to their group at their expense. Using the self-reported measures our predictions are supported: We find that subjects’ self-reported group-esteem (self-reported self-esteem) is significantly positively (negatively) correlated with engagement in “we-thinking”. Our results using the rank-based measure partially support the model’s predictions: Individual rank is significantly negatively correlated with engagement in “we-thinking” when group rank is high. The findings have implications for when individuals are likely to adopt group-regarding behavior and for how to measure the psychological concept of group/self-esteem.


### 3.	Zhewei Song & Ulrike Vollstaedt. (2022). "How a New Mechanism for Product Quality Testing Organizations Improves Markets with Asymmetric Information in the Long Run"
In markets where the true qualities of products are not visible to buyers, a product quality testing organization has expertise in finding out and revealing the true qualities to buyers. However, the quality testing organization often has limited testing capacity. In this study, we consider markets in the long run so that each seller endogenously determines the quality and price of her product. We propose a quality testing algorithm which makes full use of the testing capacity to only test products that maximizes buyer surplus. We show that with our proposed algorithm, the unique Perfect Bayesian Equilibrium maximizes buyer surplus, and thus our proposed algorithm (weakly) dominates any alternative quality testing algorithm. We conduct a laboratory experiment to test the effectiveness of our proposed algorithm. In addition to the SellersMayApply condition in which our proposed algorithm is applied, we also include a Random condition in which the quality testing organization randomly select products to test and reveal their qualities as a benchmark case. The experimental results show that the buyer surplus in the SellersMayApply condition is significantly higher than that in the Random condition.


## Work in Progress:
### 4. "Can Policy Instruments That Regulate Identity Expression Be Used To Achieve Social Integration?" (With Erin Krupka, Roy Chen and Daphne Chang)

### 5. "Entitlement Effect on Social Groups" (With Erin Krupka, Ro’i Zultan and Sebastian Goerg)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
