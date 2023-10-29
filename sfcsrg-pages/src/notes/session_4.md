# Session 4: "Building Machines That Learn and Think Like People"

## June 20 2023 @ Hotel Emblem
## Attendees: Julio, Shan, Francesco, Dylan (remote), Tom

We discussed Building Machines That Learn and Think Like People (Lake, Ullman, Tenenbaum and Gershman)

### Tom’s notes

J: nice, coherent paper. A few years old, also dated.
… Defensive of neural networks while acknowledging their limitations - not resilient to perception or goal changes. Inefficient learning.
… What’s secret sauce? Causal models; intuitive physics/psychology (infants understanding entities can be agents, are efficient), compositionality

T: are intuitive physics/psychology an example of a causal model

J: Can a neural network emulate a simulator? This blew my mind
F: Does this connect to hw elements, substituting for a physics model in cars?
S: I interpreted them as calling not for the neural network to emulate physics systems, but rather explicitly simulate physics and let the network operate on the output of the engine.
… We know neural networks aren’t great at consistency. Analogy: give ChatGPT tools, they need grounding.
… Not claiming we have a physics simulator in the brain, but rather you can access types of computation in the brain
F: Refenrece to A Path Towards Autonomosu Machine Intelligence?
… They have a perceptual model, world model

S: Their answer for bridging from neural to symbolic is “simulate the physics”, skip the symbolic (but I claim that’s easy)
J: We tend to think our psychology is based on grammar, models

F: Many times they contrast neural models and humans

J: How do self driving cars work - do they have an intuitive physics?
D: They have that in there, yes. But not learned, or build from scratch.
J: So we know how to make physics simulators
D: We should consider this a solved problem
J: Car knows where it is…
D: Pet beaver videos of it piling 

F: When talking about intuitive psychology (p19) how do you adapt roles of agents, goals?
.. Classic critique of 2016 reinforcement algorithm ?
… Needs (p42) creativity
S: Dylan defines creativity as entropy. But diffusion models are removal of entropy!
… It’s more about removal of entropy than 

J: Definitions of creativity: generation, novelty, coherence
S: Broad question: relationship between creativity and intelligence. Is it necessary - what do we know about more or less creative people?
J: Hard to know who is creative
T: Can see extreme artists?
D: Artists often get hooked on e.g. dopamine things like heroin
J: Is creativity about loosened constraints? Drug use etc
… Punishment or reward during childhood has an effect.
T: so we don’t know about the relationship
D: Relationship to metaphor, analogy?

J: Autonomous driving systems
S: Yes, theory of mind can explain patterns of data

[ GPT models and Theory of Mind ]

Can cultural factors affect cognition
T: relayed the noise-listening experiments from the Andy Clark book
S: Experiments over noise-audio: would be interesting to see if the introduction of language allows hearing the whole transcript
https://arxiv.org/pdf/2202.05262.pdf
S: Saw him do a reading, but I think they got lucky

F: Universal capacity for grammar?
T: Chomksy’s universal grammar?
S: Disproven.


F: Can ChatGPT create a new language?
T: https://maximumeffort.substack.com/p/i-taught-chatgpt-to-invent-a-language
S: Attention and doing this via prompting seems straightforward.

S: Do we need discretized bottlenecks inside networks? 
