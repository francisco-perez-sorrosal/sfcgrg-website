# Session 2: "The neural architecture of language: Integrative modeling converges on predictive processing"

## April 18 2023 @@ Rowzzy Labs

## Attendees: Dylan, Tom, Francesco, Julio, Maddie (remote), Arvind (briefly)

We discussed The neural architecture of language: Integrative modeling converges on predictive processing

### Tom’s notes

* J: What were the datasets?
* T: Read out loud or not?
* M: datasets were presented incrementally, they looked at blood oxygen levels changing in an MRI during reading. FMRI measures blood oxygen levels.
* T: curious about the resolution of this...
* J: mm maybe? It's being picked up outside the skull. But it's amazing the vascular session of the brain is sending blood to parts of the brain that need it.

* J: We have ANNs (ChatGPT) producing beautiful language, no rules of grammar.
* D: They put WordNet into GPT - which has semantic relations
* J: How do children learn grammar? Just like ANNs can learn by prediction - is this how we learn? Rules arise from NWP
* F: Yes, this is why NLP has been upturned by these models.
* T: The primacy of NLP as a task in the paper was interesting.
* T: The architecture without training results were also interesting - echoes of Chomsky's inbuilt grammars?
* General agreement this is crazy

- F: adding layers to ANNs often brings performance

- M: the ones that are untrained without weights seem to have an important architecture. Do the networks have a goal to get to?
- F: When they're trained, yes... this is called self supervised learning.
- M: So there's feedback?
- F: Yes. There's a fwd and backward pass...
- T: but these are untrained networks.
* F: this is a surprising result.

- T: Graph on page 6: how does that work? Some of the results seem better without training?
- F: Is it about random initialization of weights?
- T: WOuldn't that affect all networks (all colors in that diagram)? Here it seems to show one

* J: How are ANNs instantiated?
* D: stacks of Tensor addresses?
* T: ANNs are very high level abstractions of neurons, lots of details left out
* D: Glia cells.
* F: Jeff Hawkin's Numenta team try to mimic Glia.

Digression on Theory of Mind paper by Kosinski
Digression on how many GPUs Bill Gates has

- F: They model experiments with children, verbally stated - e.g. Sammy has a box and puts a ball in it. What can Jane see?
- J: In the GPT demonstrations, you can see the model go back and forth on its beliefs as it reads the story, until it gets it right.

 - T: which parts of the model did they correlate with FMRI or EEG? I didn't get this.

Digression about animal languages
Digression about Wolfram Alpha, GPT4, and languages

* J: will future models learn math as they learn human languages?

- D: Emergence of predictive processing in both humans and neural is beautiful
- J: the phrase that emergences here is reverse engineering

- D: I'm interested in how people get to emotional pathologies - like schizophrenic episodes
- J: One of my favorite papers is animal behavior, the basics of mood. Many animals have moods.
- D: Dr Lisa Barrett goes onto emotions - "How Emotions are Made"
- D: She has people holding concepts - axonal structures that develop over time.
- J: Low mood means the brain is skewed to predict that reward is *not* coming... elevated that the reward is coming. "Stress bees exhibit pessimistic cognitive biases" - there's an extremely low level account of mood.
- D: Cortisol ends up being the pessimistic.
- J: Low mood = times are bad = conserve energy, don't take risks.

- M: an underlying theme here is language based on predictive processing. Reminded me of Being You, and how he was talking about proprioception - is everything in the mind predictions?
- J: Mood is a prediction of reward, are our normal states also predictions? The world will be X way.
- F: Is this System 1 (impulsive) vs System 2 (logical) (Kahneman)?
- D: Where's memory in all of this?
- T: Is it not working memory in the model?
- J: Long term and working memory as two different parts of doing a task?
- F: the ChatGPT API requires you to resubmit the previous parts of the prompt.
- T: so we've spent the evening talking about similarities between biological and artificial networks, this is a clear difference...
