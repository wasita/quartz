---
title: "From partners to populations: A hierarchical Bayesian"
tags:
  - literature
citekey: hawkins2023partners
year: "2023"
authors: "Hawkins, Robert D and Franke, Michael and Frank, Michael C and Goldberg, Adele E and Smith, Kenny and Griffiths, Thomas L and Goodman, Noah D"
---

# summary

>[!example] key terms
> coordination, convention formation, hierarchical bayesian inference, common ground, lexical alignment, partner-specific meaning, continual learning

Hawkins and colleagues introduce CHAI (continual hierarchical adaptation through inference), a hierarchical bayesian theory reconciling the tension between stable linguistic conventions and flexible partner-specific meaning-making. meaning is treated as a latent variable jointly inferred across two nested timescales: rapid partner-specific common ground within dyads, and stable community-wide conventions abstracted across many partners.

---

# topic and thesis

> ***briefly, why is the research question important to answer?***

how can language be simultaneously stable enough to function as a shared coordination system across a population and flexible enough to support partner-specific meanings in real conversation? classical accounts treat convention as a static transmission problem, which cannot explain rapid construction of shared meanings with novel partners or how dyadic interactions scale into population-level conventions.

---

# background

> ***what are the main theories in the literature? is there anything missing or problematic?***

game-theoretic accounts (Lewis, 1969) treat conventions as stable equilibria but don't explain dyadic emergence. common ground theory (Clark, 1996) shows convergence on efficient labels but these are often opaque to overhearers. interactive alignment (Pickering & Garrod) explains within-interaction convergence through priming but not generalization. rational speech act (RSA) models treat lexical meanings as fixed. iterated learning addresses population-level convention but abstracts away dyadic dynamics.

> ***what is the empirical evidence? is there anything missing or problematic?***

the repeated reference paradigm (tangram experiments) shows speakers converge on shorter labels across repetitions, but these labels partially reset with new partners. no prior model accounted for both partner-specific and population-level convention in a unified framework.

---

# argument and hypotheses

> ***does the article advance a new theoretical argument? if yes, what is it?***

linguistic meaning is a latent variable inferred hierarchically over two timescales. at the partner level, agents rapidly update beliefs about expression meanings through bayesian inference over shared history. at the community level, agents maintain slower-updating priors over possible partners.

> ***what are the hypotheses to be tested?***

the model should predict: (1) within-pair compression of referring expressions across repetitions, (2) partial reset and slower adaptation with new partners, (3) sensitivity to communicative context in determining which conventions stabilize.

---

# research design

> ***what is the methodological approach?***

computational modeling combined with behavioral experiments using repeated reference games (tangram naming tasks).

> ***what data is used?***

behavioral data from tangram reference games where participants repeatedly name abstract figures for partners, including conditions with partner switches.

> ***what are the specific methods and techniques?***

hierarchical bayesian model (CHAI) extending the rational speech act framework with partner-specific and population-level latent lexicons. model predictions compared against human behavioral data from reference game experiments.

---

# results

> ***what are the key findings?***

the model quantitatively captures within-pair reduction in description length, partial reset when switching to new partners, and the influence of communicative context on convention formation. these patterns emerge naturally from hierarchical inference without special-purpose mechanisms.

> ***what do these findings say about the argument and hypotheses?***

all three predictions were confirmed, supporting the hierarchical bayesian account over flat models that treat conventions as either purely partner-specific or purely population-level.

---

# conclusion

> ***what is the overall conclusion?***

CHAI provides a principled account of coordination and convention at multiple scales. language is reconceptualized not as a fixed shared code but as continuously learned probabilistic expectations that are simultaneously local (shaped by specific partners) and global (constrained by community-level priors).

---

# connections

- related synthesis pages:
	- [[shared-reality]]
- related literature notes:
	- [[2022-murthy-shades-confusion-lexical]]
	- [[2020-gershman-social-structure-learning]]
	- [[2002-stalnaker-common-ground]]
