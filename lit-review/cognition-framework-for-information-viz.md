# A human cognition framework for information visualization

The authors see visualization as an "human cognition-augmentation" challenge. They propose that a well-designed visualization induces reasoning and understanding by influencing high-level cognitive functions. In this paper they introduce a formal framework which identifies certain intersections of the visualization and human cognition that designers can specifically tackle.

Two relevant fields that have been looking into this topic are _Human-Computer-Interaction (HCI)_ and _Human Factors and Ergonomics (HFE)_ but attempts to formalise the design process have so far been limited to "Do's and Don'ts" based on performance measures such as reaction time etc. Some other's (e.g., Huang et al., 2009) have been relying on theoretical concepts such as cognitive load theory to achieve the wanted operationalization of visualization design.

@Todo: Tory & Moller (2010): Human Factors in Information Visualization

## Information Visualizations

Over the history of visualization research many models have been introduced, often coming with their respective ways of categorizing and labelling the synthesis process. **The modern visualization process is demarcated by the introduction of human cognition.** But the complexity of the relationship between visualization and the perceiving human was still often reduced to the _User_ at the end of the pipeline.

Etling et al. produced fascinating results in a study bringing up questions about the likeability and usefulness of visualizations. **Subjective preference is a bad indicator of objective performance**

Thus, they suggest that a well-designed information visualization will increase the objective performance by taking the human cognition into account (within a certain given context!).

## The framework

Classic visual perception theory often relies on a bottom-up classification. Small, basic units are registered by biological units (receptor fields) and then continuously combined into more complex, high-level objects. The focus on this aspect will lead to the understanding of information visualizations as mere layouts of visual data that needs to be facilitated for perception.

This framework emphasizes the top-down perspective:

> Top-down processing _guides the way in which in which the bottom-up information is processed in order to activate organised knowledge structures represented in long-term memory, which is why we emphasize top-down processing in our framework_.

E.g. for top-down processing: participants could easier identify line-segments if these were arranged as part of a meaningful constellation rather than a unstructured one. Several studies also looked into reaction times for object recognition in and outside of contextual situations and the evidence seems to support the _interplay of top-down and bottom-up processes_.

**Dual-systems theory** in cognitive psychology and science fundamentally argues that human cognition consists of an analytical reasoning system and a rapid-firing more intuitive system. (thinking fast and slow)

Analytical system
: responsible for certain kinds of reasoning. e.g. ,analogical (reasoning from one domain into another) or deductive reasoning (from the genereal to the specific)

Intuitive system
: Solely based on pattern recognition based on learning of statistical regularities.

### Encoding

### Attention

### Working Memory

Chunking
: Units of to be processed content of similar meaning maintained in the working memory. Number of chunks was assumed to be around 7, but now more around 4

### Pattern Recognition



### Long-term Memory

Very important for OKMaps users:

We have to create visualizations that appeal to users without an established long-term memory yet, while at the same time not driving away users with long-term information to work with.

Declarative memory
: asd

Non-declarative memory
: asd

### Decision Making


## The leverage points of human cognition as a framework

Stimulus is the presentation of a visualization while a decision or action can be any next interaction (e.g., zooming into a subset of the data) and will then trigger a new iteration.

@Todo: Look into Ware (2004) as an alternative framework. A bottom-up heavy three stage framework that would seemingly work very well to understand OKMaps basic interaction model

The **leverage points** that Patterson et al. introduce are access mechanisms in the design process that are derived from the previously presented layout of the human cognitive system.

### Capture exogeneous attention

> utilize salient cues to drive exogenous attention, alerting users to changes in or important attributes of a visualization

### Guide endogenous attention

>  provide appropriate organization of material or interaction options to assist endogenous attention and minimize distracting information

### Facilitate chunking

> choose visualization parameters that provide strong grouping cues to facilitate the chunking of information, which will minimize the effects of working-memory capacity limitations

verbal methods to assess chunking: Ericsson and Simon (1984)

### Aid reasoning with mental models

> organize information based on mental models so as to provide strong retrieval cues for knowledge structures in long-.term memory to aid reasoning

Cognitive Task Analysis (CTA) can be used to capture expert mental models. Think-aloud protocols and interviews during decision making processes

@Idea: use of colors within bubbles to represent interbubble similarities

@Todo: Plaisant et al (2002) - semantic tree browser

Assessing mental models: measure the overlap of the user's self reported mental model with the visualization OR (!!!) measure the amount of queries before the finishing of a certain task & reaction times

### Aid analogical reasoning

> structure information so as to provide strong retrieval cues for knowledge structures (mental models) to aid ain analogical reasoning

This whole passage is basically the generalization of my metaphoric language, maps ramblings.

**Metaphors** can be considered analogies if primarily share relational informatoin (?!).

### Encourage implicit learning

> develop training regimes for implicitly learning about statistical regularities within a visualization

Implicit learning
: learning without being able to verbalize what has been learned

## The Cognitively Enhanced Information Visualization Design Process

Top-down design processes
: informed by knowledge about cognitive functions and cognitive science

bottom-up design processes:
: empirically oriented; systematically varies parameters and runs tests to find optima

A hybric model may be the most useful and pragmatic mode of operation: top-down design decisions point out potentially fruitful future directions while bottom-up tasks evaluate results

## Conclusion

Very close to the mode of operation (and development) at Open Knowledge Maps. Need to compare to other visualizations and see if these leverage points are easily fulfilled... Seems to be a great fit for the goals and aims of OKMaps.

Especially interesting to consider the framework in the context of future directions (bootstrapping user maps etc)

Also, the inclusion of this framework is interestingly a top-down intervention in itself, representing a very first important future direction itself.