# Abstract Outline

- 1. [ ] background **context** -> **general topic** under study -> **specific topic** of research
- 2. [ ] **central question** or statement of the **problem** your research addresses
- 3. [ ] whats **already known** about this question, what **previous research** has done or shown
- 4. [ ] the main **reason/rationale** for the research, and stated **goals**
- 5. [ ] research and analytical **methods**
- 6. [ ] main **findings/results/arguments**
- 7. [ ] significance or implications of findings/arguments

https://writing.wisc.edu/handbook/assignments/writing-an-abstract-for-your-research-paper/

## Filled out

- 1. [ ] background **context** -> **general topic** under study -> **specific topic** of research
  - complex battlespaces with myriad of air threats
- 2. [ ] **central question** or statement of the **problem** your research addresses
  - between improvements of adversarial deception technology, and shortcoming in glue sensors, or even conflicting readings: "v"?
  - deceptive technology and faulty sensor units: how do we reconcile what we are actually looking at, so that we may engage appropriately?
- 3. [ ] whats **already known** about this question, what **previous research** has done or shown
- 4. [ ] the main **reason/rationale** for the research, and stated **goals**
  - There are things we know about the battlespace
  - We should use those things to improve how we interpret sensor readings
  - AND
    - we should use things that we know about the sensors to improve their collective sensemaking ability
- 5. [ ] research and analytical **methods**
  - in this paper we propose
  - bayesian networks
    - sensor reliability
    - object type
    - intent classification
  - with layer to produce CPDs using heuristics and operator knowledge of battlespace
    - human level domain knowledge
- 6. [ ] main **findings/results/arguments**
  - Through this we find bayesian networks to be
  - favorable tools to perform last-mile reasoning over any number of non-explainable black-box type approaches,
    producing more reliable, trustable, and interpretable results than a stand alone sensor units.
- 7. [ ] significance or implications of findings/arguments

In the absence of empirical data to learn cpd values from, we leveraging heurisitcs of the domain space to computing CPD priors

## Value Adds

- Bayesian network as an explainable systems integrator of sensors, target tracking and identificaiton, and ATR systems
- Using Bayesian networks, we can harmonize the readings of any number of subsystems and condition our confidence in their readings by human level understanding of battlespace conditions and enemy threat class distributions
- Inter-sensor reading consistency

## What I really want to say

- yea, bayesian networks are old
  - but they are explainable
  - and they provide confidence values instead of binary values
- we have tons of different sensor systems, atr systems, etc
  - but none of the systems are perfect and there are failure modes
- the likelihood of all the sensors having the same failure mode at the same time is low
- so we should use them redundantly
- whatever, 90% of the time, the readings should agree
- but if the readings disagree, bayesian networks can help us disambiguate
- AND operators probably know when certain systems have shortcomings (or we have data)
  - so we should encode that and use that information to condition our confidence of sensors
- we happened to pick air defense
  - but really this is applicable to any domain where there are imperfect readings
  - coming from a variety of sources
  - and operators have knowledge not encoded in a computer
- we have tons of different sensors, all reading the same thing
  - but they dont talk to each other
  - even though they have a common unit of communication

### What makes our paper different

- Work in sensor fusion is super low level (I think)
- Bayesian networks have been used in this space, but not as a systems integrator
  - /reading disambiguator

### JADC2

- alright
  - do we mention the mosaic stuff?
  - the term "sensor" and "data fusion" are like very low level
  - this is intent on operating at system-level interfaces

Explainable Multi-system Sensemaking with Bayesian Networks for Air Defense

Wait bro: what if we dont just include sensors

What if we included like social media or ccv cams or something like that

Like something totally off the fucking wall and show: bayesian networks are the equalizer

