# Quantitative Approaches to Larval Biology\: Selected topics and executable examples

This is an [executable book](https://executablebooks.org/en/latest/) presenting applications of quantitative reasoning to gain insights into important questions in Larval Biology research.
The subjects and model implementations derive from my research and courses I taught. 
In particular, most models in this book are drawn from the Larval Biology course at Friday Harbor Laboratories, where I was very fortunate to learn from the astonishing depth and breadth of knowledge of his my long-term co-instructors, Richard Strathmann and Richard Emlet; numerous other resident and visiting investigators; and, many gifted and hardworking students. 
All these scientists are co-contributors to the (good parts of) this book.

Most topics and examples focus on the larvae of marine invertebrates (a few focus on marine vertebrates, a few are more general).
However, most of the ideas in this book have broader application -- Larval Biology is highly interdisciplinary, centered in organismal biology spanning many aspects of ecology, evolution, functional morphology and biomechanics, physiology, genetics, oceanography, climate science, environmental policy and management, and many other fields.
Key questions in Larval Biology are closely related to questions in other biological subdisciplines.
It is the interdisciplinarity and applicability of Larval Biology that motivates this book, and dictates its emphasis on quantitative tools and executable models.
These motivations and emphases may make the book useful to investigators in other biological disciplines, or provide an example of how to develop tools specific to their interests.

## Why use models in Larval Biology?
Larval Biology is historically a mostly experimental disciplne. 
Larval Biologists have frequently pushed technological boundaries, for example in confocal and other computerized imaging techniques, and in molecular techniques to identify taxa, measure population connectivity and understand patterns of development.
This innovative spirit has not reached similar levels in quantitative approaches like mathematical modeling and computer simulations.
Mathematical models have contributed to discussions in a variety of debates in Larval Biology, for example in Life History Evolution questions concerning the evolution of egg size.
However, the potential of mathematical tools to contribute to Larval Biology is much broader and deeper than the literature reflects.

Disseminating some of the background knowledge and experience for using models, and the understanding of why using models is a productive adjunct to traditional approaches in Larval Biology, is a primary objective of this book. 
A future Larval Biology in which the potential of models to enhance discovery is more fully exploited -- in which quantitative models are freely interdigitated among empirical methods and observations where each approach can best contribute  -- would be a more interesting, productive and impactful discipline.

Some of the reasons Larval Biologists might be interested in quantitative models are:

***Models are tools for inferring the logical consequences of specific assumptions.***

The emphasis here is on the "specific assumptions" as much as on the "logical consequences". 
In a career of modeling biological processes in which I believed I was well versed, and of helping other biologists to formulate models in their own areas of expertise, I have consistently encountered two phenomena:

- Formulating a mathematical model requires *specificity* in details that are easy to overlook in conceptual thinking\: 
Exactly *how* is a process like morphogenesis, synchronized spawning, predator avoidance or gene flow regulated? 
In what way are an egg, an early embryo, a larva and an adult "individuals" in a population model? 
I have been frequently flumoxed (and delighted) to discover basic aspects I had never thought about in organismal systems I thought I knew well.
Writing down a quantitative model, even if results are never calculated, exposes these details and the intriguing new insights and questions that arise from them.

- Different scientists, especially scientists from different disciplines, use the *same word with very different meanings*. 
This means that interdisciplinary collaborations, which are necessary and productive in Larval Biology, are frequently derailed by misunderstandings between two experts who have firm, well-founded (but different) interpretations of the subject at hand.
An example is "memory". 
To a mathematician or statistician, a "memoryless system" is one in which the current state determines the probabilities of future events, without regard to how the current state was brought about. 
Thus, a mathematician could happily formulate a "memoryless" model of the human brain.
Clearly, this would not be a biologist's interpretation.
Confounding vocabulary and other vagueness in terminology is usually clarified when the relevant biological mechanisms are expressed in mathematical form.

***Models are tools for inferring what we want to know from what we can measure.***

Larval Biology is frequently hampered by quantities and characteristics  that we want to know but cannot directly measure. 
What are the fitness implications of variants we observe in morphology, size, behavior, geography, or seasonality?
What are the mechanisms responsible for patterns in speciation and extinction, for species range expansion and contraction, or for the prevalence or rarity of different life history strategies? 
How is recruitment of a larval cohort limited or enhanced by each of the numerous biotic and abiotic environmental variables at a given time and place?
How are environmental signals transduced the sensory and regulatory processes into reproductive, foraging or mortality events?

All of these questions, and many more, involve unknowns that are difficult or impossible to measure.
Modeling provides approaches to infer quantities that cannot be measured. 
For example, it is in most cases impractical to measure the mortality rates of larvae in the plankton or in benthic environments. 
Direct measurements would involve unobtrusive observations following a large sample size of individual larvae, recording whether and how they died.
In most cases, this is not possible to carry out.
An alternative is to track cohorts of larvae, measuring changes in abundance, age- and stage- structure, and geographic distribution.
From cohort data, *combined with a modeling framework that provides quantitative predictions based on alternative mortality regimes*, inferences can be made regarding plausible rates and mechanisms of mortality in the observed larval population (**REF**)).

Another way in which observations are constrained is in considering the consequences of hypothetical alternatives to observed characteristics such as morphology or life history.
Organisms that do not exist cannot be observed, but models that correctly reflect the key underlying mechanisms can give quantitative implications of how those organisms might function.

***Models are tools for communicating biological knowledge across organisational levels.***

Another way in which models can contribute to insights in Larval Biology is by integrating specialized knowledge from different disciplines.
For example, a biologist investigating maternal allocation to reproduction -- how many eggs of what size should mom make each year -- may focus on the physiology of egg production, the energy inputs and outputs of mature females, and coordination of spawning to maximize fertilization success.
However, she would not be able to draw inferences about the costs and benefits of the traits she observes without context: 
What are the functional consequences of smaller or larger larvae in terms of swimming ability, food capture and predator avoidance? 
What are the geographic implications of shorter or longer planktonic durations, and do those have implications for maintaining viable self-sustaining populations?
How do impacts in present environments compared to historical environments, or future environments under ocean change?
Each of these questions draws in the expertise of other scientists, whose understanding can be exploited by an investigator of larval reproduction.
Biomechanical models may provide her with specific estimates of how swimming and sensory performance is likely to differ in smaller or larger larvae.
Demographic models may offer quantitative insight into the consequences of variations in planktonic duration.
Geophysical circulation models may predict the transport of larvae in tides and currents, and environmental characteristics such as temperature, oxygen, chlorophyll and pH that may affect larval recruitment.
Climate models may specify the environmental conditions inrelevant to past and future environments.
In all these cases, quantitative models formulated at one biological or environmental level can be leveraged by investigators at another level.
Leveraging models in this way provides a mechanisms for community level collaborations, in which investigators make their discoveries available in the form of publicly available and easily used toolkits. 
This approach would mark a change for Larval Biology, but would be following the productive pathways of other disciplines such as statistics, geophysical modeling and molecular biology.

Beyond all of these reasons, one additional point which has given me satisfaction is worth mentioning: 
Most larvae are available only at narrowly constrained times and places, commonly a certain interval in spring or early summer, at a field station or offshore location. 
Experimental work in Larval Biology grinds to a halt outside this very limited window in space and time, 
Modeling is portable and extends the productive working season of a Larval Biologist to year-round.
The thrill of a novel insight in Larval Biology, even if obtained on a computer rather than a microscope, is equally thrilling in the dark winter months!

```{tableofcontents}
```
