---
title: "Rational quantitative attribution of beliefs, desires and percepts in human mentalizing"
tags:
  - literature
citekey: baker2017rational
year: "2017"
authors: "Baker, Chris L and Jara-Ettinger, Julian and Saxe, Rebecca and Tenenbaum, Joshua B"
---

# summary

>[!example] key terms
> bayesian theory of mind, mental state attribution, inverse planning, beliefs desires percepts, computational mentalizing, POMDP, quantitative prediction

baker et al. present BToM (bayesian theory of mind), a model that jointly infers an agent's beliefs, desires, and percepts from observed movements by inverting a POMDP-based planning model. BToM accurately captures quantitative human mental-state judgments (rbscv = 0.91) across two experiments.

full citation: [@baker2017rational]

---

# topic and thesis

> ***briefly, why is the research question important to answer?***

attributing mental states to others is central to social cognition. a quantitatively precise computational model is needed to test whether folk-psychological reasoning follows rational inference principles.

---

# background

> ***what are the main theories in the literature? is there anything missing or problematic?***

folk psychology, expected-utility agent models, and prior bayesian social cognition models. earlier BToM work modeled only belief-desire attributions without partial observability.

> ***what is the empirical evidence? is there anything missing or problematic?***

humans rapidly and reliably infer goals and beliefs from action. prior bayesian models fit qualitatively but lacked rigorous quantitative tests with complex scenarios.

---

# argument and hypotheses

> ***does the article advance a new theoretical argument? if yes, what is it?***

human mentalizing is approximate bayesian inference over a generative model of rational agency incorporating POMDP-based planning, enabling simultaneous attribution of beliefs, desires, and percepts.

> ***what are the hypotheses to be tested?***

BToM will quantitatively predict human attributions; simpler motion heuristics will fail.

---

# research design

> ***what is the methodological approach?***

two behavioral experiments with animated spatial scenarios; participants rated agents' desires and beliefs.

> ***what data is used?***

human ratings across many stimuli varying multiple dimensions; model predictions from BToM and heuristic baselines.

> ***what are the specific methods and techniques?***

bayesian inference inverting a POMDP; cross-validated correlation; comparison against motion heuristics.

---

# results

> ***what are the key findings?***

BToM achieved rbscv = 0.91; motion heuristic achieved only 0.61. the model captured graded, multi-attribute attributions.

> ***what do these findings say about the argument and hypotheses?***

high accuracy supports the bayesian inverse planning account. motion heuristics fail, confirming explicit mental-state reasoning is necessary.

---

# conclusion

> ***what is the overall conclusion?***

human mentalizing is well-described as rational bayesian inference about beliefs, desires, and percepts.

---

# connections

- related synthesis pages:
- related literature notes:
	- [[2023-houlihan-emotion-prediction-computation]]
	- [[2011-tenenbaum-grow-mind-statistics]]
	- [[2004-ames-projection-stereotyping]]
