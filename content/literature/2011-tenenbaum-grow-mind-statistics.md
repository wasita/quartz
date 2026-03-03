---
title: "How to grow a mind: Statistics, structure, and abstraction"
tags:
  - literature
citekey: tenenbaum2011grow
year: "2011"
authors: "Tenenbaum, Joshua B and Kemp, Charles and Griffiths, Thomas L and Goodman, Noah D"
---

# summary

>[!example] key terms
> hierarchical bayesian models, probabilistic generative models, structured representations, inductive learning, cognitive development, abstract knowledge

Tenenbaum and colleagues propose that human cognition achieves rich, generalizable knowledge from sparse data by performing probabilistic inference over hierarchies of flexibly structured representations. the paper positions hierarchical bayesian models as a unifying account of learning, cognitive development, and a path toward more humanlike machine learning.

---

# topic and thesis

> ***briefly, why is the research question important to answer?***

how do humans learn so much from so little? children and adults routinely generalize concepts, causal relations, and language structure from only a handful of examples — a capacity that simple statistical or associative learning cannot explain.

---

# background

> ***what are the main theories in the literature? is there anything missing or problematic?***

nativism (Chomsky, Fodor) correctly emphasized rich mental representations but provided no account of how knowledge is learned. empiricism/connectionism provided learning mechanisms but relied on unstructured representations incapable of capturing symbolic, compositional structure.

> ***what is the empirical evidence? is there anything missing or problematic?***

prior bayesian models addressed specific cognitive domains in isolation (e.g., word learning, causal reasoning) but no unified framework existed for domain-general learning of structure itself.

---

# argument and hypotheses

> ***does the article advance a new theoretical argument? if yes, what is it?***

the mind performs approximate probabilistic inference over hierarchies of structured representations. abstract knowledge is encoded as probabilistic generative models. hierarchical bayesian models resolve where priors come from by positing multiple levels of inference (priors on priors), so abstract knowledge is itself learned from data.

> ***what are the hypotheses to be tested?***

this framework should simultaneously provide strong inductive constraints (enabling fast learning from few examples) while remaining flexible across domains. demonstrated for word learning, causal reasoning, property induction, and social cognition.

---

# research design

> ***what is the methodological approach?***

review and theoretical synthesis with computational modeling demonstrations across multiple cognitive domains.

> ***what data is used?***

draws on existing empirical data from word learning, causal reasoning, property induction, and theory-of-mind experiments.

> ***what are the specific methods and techniques?***

hierarchical bayesian modeling — comparing model predictions against human behavioral data across domains.

---

# results

> ***what are the key findings?***

hierarchical bayesian models over structured representations (graphs, grammars, causal schemas) quantitatively capture human generalization patterns across word learning, causal induction, and property reasoning tasks.

> ***what do these findings say about the argument and hypotheses?***

neither pure nativism nor pure empiricism is sufficient — the integration of structured representations with statistical inference captures human cognitive abilities.

---

# conclusion

> ***what is the overall conclusion?***

hierarchical bayesian models over structured representations provide a principled account of how humans generalize from sparse data through simultaneous acquisition of structure and statistics at multiple levels of abstraction. open questions remain regarding neural implementation and scaling to full intuitive theories.

---

# connections

- related synthesis pages:
- related literature notes:
	- [[2009-griffiths-theory-based-causal-induction]]
	- [[2009-kemp-structured-statistical-models]]
	- [[2010-griffiths-probabilistic-models-cognition]]
	- [[2017-baker-rational-quantitative-attribution]]
