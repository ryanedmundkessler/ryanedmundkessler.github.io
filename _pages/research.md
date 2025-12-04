---
layout: archive
title: ""
permalink: /research/
author_profile: true
---

### Evaluating A/B Testing Methodologies via Sample Splitting: Theory and Practice
[Draft, December 2025](https://arxiv.org/abs/2512.03366))

We develop a theoretical framework for sample splitting in A/B testing environments, where data for each test are partitioned into two splits to measure methodological performance when the true impacts of tests are unobserved. We show that sample-split estimators are generally biased for full-sample performance but consistently estimate sample-split analogues of it. We derive their asymptotic distributions, construct valid confidence intervals, and characterize the bias-variance trade-offs underlying sample-split design choices. We validate our theoretical results through simulations and provide implementation guidance for A/B testing products seeking to evaluate new estimators and decision rules.

### Statistical Power Calculations Revisited: Incorporating Beliefs About Effect Sizes
Conference on Digital Experimentation (CODE) at MIT (2025) <br/>
[Extended abstract](https://www.amazon.science/publications/statistical-power-calculations-revisited-incorporating-beliefs-about-effect-sizes)

*Abstract:* In A/B testing, statistical power depends on both the variance of estimated impacts and the distribution of true impacts. Traditional power calculations, however, focus solely on the variance of estimated impacts. In this paper, we present two approaches to connecting power calculations to beliefs about the distribution of true impacts. First, we show how frequentists can compute “prior-informed average power” by taking a weighted average of conventional power across different effect sizes, with weights based on how likely that effect size is believed to occur. Second, we show how Bayesians can compute “Bayesian decision power” by taking a weighted average of the probability of meeting a launch or dial down criteria across different effect sizes, with weights again based on how likely that effect size is believed to occur. These approaches enable A/B testing tools to provide more realistic and informative assessments of statistical power. 


### Overcoming the Winner’s Curse: Leveraging Bayesian Inference to Improve Estimates of the Impact of Features Launched via A/B Tests
Conference on Digital Experimentation (CODE) at MIT (2024) <br/>
[Extended abstract](https://www.amazon.science/publications/overcoming-the-winners-curse-leveraging-bayesian-inference-to-improve-estimates-of-the-impact-of-features-launched-via-a-b-tests)

*Abstract:* Many data-driven companies measure the impact of product groups and allocate resources across them based on the estimated impacts of features they launch via A/B tests. In this doc, we show that, when based on a standard frequentist estimator of the impact of features, this practice can significantly overstate the impact of product groups and distort the allocation of resources. When this practice is instead based on a Bayesian estimator of the impact of features, there are no such problems when the underlying prior beliefs regarding the distribution of true impacts are correctly specified. To help assess performance of the estimators in practice, we conduct simulations, allowing for different forms of misspecification in prior beliefs regarding the distribution of true impacts. In these simulations, we find that the Bayesian estimator generally outperforms the frequentist estimator, even under certain forms of misspecification. We use both the frequentist and Bayesian estimators to measure cumulative impacts across A/B tests at Amazon, highlighting differences in their overall magnitude and their distribution across product groups.

### The Effect of SNAP on the Composition of Purchased Foods: Evidence and Implications<br/>
with Justine Hastings and Jesse Shapiro<br/>
American Economic Journal: Economic Policy 13, no. 3 (2021): 277-315 <br/>
[Manuscript](../files/snap_nutrition.pdf); [Appendix](../files/nutr_online.pdf)

*Abstract:* We use detailed data from a large retail panel to study the effect of participation in the Supplemental Nutrition Assistance Program (SNAP) on the composition and nutrient content of foods purchased for at-home consumption. We find that the effect of SNAP participation is small relative to the cross-sectional variation in most of the outcomes we consider. Estimates from a model relating the composition of a household’s food purchases to the household’s current level of food spending imply that closing the gap in food spending between high- and low-SES households would not close the gap in summary measures of food healthfulness.

### Does Punishment Compel Payment? Driver's License Suspensions and Fine Delinquency<br/>
[Draft, March 2020](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3545324)

*Abstract:* Many state and local governments use the threat of driver's license suspension (DLS) to compel the payment of fines and fees. In this paper, I provide the first quasi-experimental evidence on the efficacy of such threats. Using administrative records from the City of Chicago, I estimate the effect of receiving a threat of DLS on the payment of traffic fines. To isolate the causal effect of receiving a threat, I exploit cross-sectional variation in exposure to a change in the enforcement of DLS policy in a fuzzy difference-in-differences research design. Receiving a threat of DLS increases traffic fine payment by $658 on average over the four years following receipt, representing 40 percent of the average traffic fine debt among drivers in my sample. The effect is significantly smaller among drivers with vehicles registered to higher-poverty ZIP Codes. My estimates suggest that eliminating DLS for the non-payment of traffic fines would reduce annual traffic fine revenue in the city by 4.5 percent.  
