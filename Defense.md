---
bibliography: Thesis.bib
author: Daniel Milway
date: 24 April 2019
title:	Explaining the Resultative Parameter
subtitle: Final Oral Examination
documentclass: scrartcl
classoptions: letterpaper
#fontfamily: ebgaramond
fontfamily: Alegreya
#fontsize: 12pt 
geometry: 
- margin=1in
header-includes: |
  \setkomafont{disposition}{\rmfamily}

...

# The problem

**Main Question:** Why are some languages but not all languages able to generate adjectival resultatives?

(@AR) Jackie hammered the metal flat.

**Subquestion 1:** What properties must a grammar have to generate resultatives like (@AR)?

**Subquestion 2:** How can the answer to subquestion 1 be acquired from primary linguistic data?

# Why Resultatives?
- Two of the Main Questions of linguistics: 

	* **How much can languages vary from one another?**

	* **How do children acquire their language?**

- In fact these are two sides of the same coin

	* Universals don't need to be learned,

	* so children only acquire that which varies.

- By definition, we can only learn what we have evidence for.

- Adjectival resultatives are puzzling in light of these considerations.

	* They're parameterized, but not in an obviously learnable way.

- The parameter: 

	* In some languages (@SPTemplate) can be interpreted as depictive or resultative

	* In others (@SPTemplate) can be interpreted only as depictive

(@SPTemplate) [~TP~ DP [~VP~ V NP AP]]

- There's no reliable evidence for interpretations

	* How is this parameter setting learned?

- Snyder's correlation fixes the learnability issue:

	* The resultative parameter is set indirectly on the basis of the compounding parameter.

- This leaves us with the problem of linking compounds to resultatives

	* Compounding is an SM-oriented phenomenon

	* Adjectival resultative construction is a CI-oriented phenomenon.

- So how can we link the two?

- There are three theoretical routes available to us for explaining any variation:


1. Only surface variation

2. Lexical Parameterization Hypothesis (LPH)

3. Parameter theory.

- From a minimalist perspective, 1 is the most attractive.

	* The CI-orientation of resultatives points away from it, though.

- 3 is problematic for a number of reasons.

	* See section 3.1.2.2

- This leaves 2: LPH

## The Lexical Parameterization Hypothesis

(@LPH) **LPH**\
All (syntactic) variation derives from variation in the lexicon.

- This still leaves room for interpretation.

	* **What can and cannot vary in the lexicon?**

	* **How does lexical variation translate to (*e.g.*) the resultative parameter?**

- The answer to the second depends on the answer to the first.

- Three answers have been given to the first:

1. Lexicons vary in the presence/absence of certain heads.\
	(see, Bo\v{s}ković's DP/NP parameter)

2. The Bundling Hypothesis.\
(see @folli2006licensing)

3. Lexicons vary in the featural endowment of their heads.

- 1 doesn't seem to be generally problematic, but not well equipped for the resultative parameter

	* Ascribing the resultative parameter to the presence/absence of $res^\circ$ but it runs into issues:

		- French, for example, has resultative deadjectival verbs (*aplattir*, *blanchir*, etc)

		- It is rather implausible that it could be linked to compounding

- 2 has more general problems

	* It's not clear what "bundling" consists in.

	* It doesn't seem learnable.

	* The link between resultatives and compounding isn't clear.

- 3 is promising

	* It's learnable

		- Languages plainly differ with respect to whether certain categories show inflectional morphology, and how "rich" that morphology is.

	* variation in inflectional morphology has been linked to grammatical variation

		- Rich subject agreement is linked to null-subjects

	* Can it link resultatives and compounding?

		- My thesis demonstrates that, given certain theoretical assumptions, yes it can.

## How can featural endowments vary?

- Lexical Items are bundles of phonetic, semantic, and formal features.

- The variation we're interested in is in the formal features.

- In principle we can expect variation along two "axes":

	* the sort of features (*e.g.* Q, Case, $\varphi$)

	* the "completeness" of the feature bundle.

- The first sort of variation is not important here

	* and might not really be available.

- The second sort is vital for my thesis because it is operative in label theory [@chomsky2013problems].

- The bundle of features of type F can be absent, incomplete, or complete on the lexical item H in language L.

(@FeatureBundle) **The form of the feature bundle parameter**\
For head H, and feature F, one of \{H~$\emptyset$~, H~$F$~, H~$\langle F, F\rangle$~\} is in LEX

- This is undoubtedly wrong, but it will do for my thesis.

- The setting of (@FeatureBundle) affects the grammar according to label theory:

	* H~F~ is too weak to label on its own.

	* It needs to be strengthened by Agree in order to label a phrase.

	* @chomsky2015problems uses this to differentiate between null subject languages and overt subject languages

- The setting is also acquirable insofar as it is reflected in inflectional morphology.

	* French Adjectives must be inflected, German adjectives are only inflected in attributive positions.

	* **Note:** This is consistent with there being a default setting of the parameter that is only overridden in the face of evidence.

### A Note on the strong-weak distinction {-}

- My use, following @chomsky2015problems, of the terms "strong" and "weak" with regards to LIs and their feature bundles is not to be confused with the "strong features" of @chomsky1995minimalist

- In early minimalism, selectional features could be marked with the diacritic STRONG.

	* STRONG features needed to be checked overtly

- This theory collapsed for two related reasons:

	* No corroborating evidence could be found

	* The diacritic STRONG could not be grounded in either of the interfaces.

- In label theory, the terms "strong" and "weak" are merely descriptive.

	* LIs are too weak to label if they have an incomplete set of formal features

- This theory has problems, no doubt, but it doesn't inherit the problems of the previous theories of feature strength.

## Summary

- The big questions that I opened with have been given a number of answers

	* and those answers raise sub-questions which have been given a number of sub-answers.

- Theoretical thinking can help us to answer the question

	* but in the end we want an empirically valid answer.

- The resultative parameter, augmented with Snyder's [-@snyder2001nature] correlation, I think, strongly points to one answer:

	* Syntactic variation might be limited to variation in the lexicon, specifically variation in the formal-featural endowment of functional heads.

# One Implication

- My structural analysis, given in figure 1, involves sideward movement. 

![The VP structure of (@AR)](./ResStruct.png "[~VP~ [~VP~ hammer [~DP~ the metal]][~resP~ <DP> [res [~AP~ flat]]]]"){ width=40% }

- In fact, as (@TwoThemes) shows, that sideward movement must be obligatory

(@TwoThemes) \*Jackie hammered the cutlet the metal flat.

- My proposed derivation for figure 1, however, suggests that in any similar structure, such a sideward movement step should be required.

- This is backed up by depictives and one of the ACC-ing structures proposed by @cinque1996pseudo.

- It seems that specifiers of adjoined phrases **must** be extracted.

(@SpecBan) \* [~$\langle$YP,ZP$\rangle$~ ZP [~YP~ XP [ Y ...]]] unless XP is a lower copy/trace

- I argue in section 8.2, though, that this constraint cannot be derived or expressed in standard syntactic theories
	
	* *i.e.*, those based on feature satisfaction

- Feature-satisfaction theories are inherently monotonic

	* Once a feature is satisfied, it can't then become unsatisfied.

- An interface-based theory like label theory, however, does not face such an issue.

- This, along with the main part of my thesis, provides empirical grounds for taking interface-based theories of syntax seriously.

# References
