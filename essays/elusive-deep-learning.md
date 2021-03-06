![Neural GIF](../media/neural.gif)

# Elusive Deep Learning: A Narrative Approach

### Manifolds and Topology

> A manifold is a connected region. Mathematically, it is a set of points associated with a neighborhood around each point. […] In everyday life, we experience the surface of the world as a 2-D plane, but it is in fact a spherical manifold in 3-D space. The concept of a neighborhood surrounding each point implies the existence of transformations that can be applied to move on the manifold from one position to a neighboring one. In the example of the world’s surface as a manifold, one can walk north, south, east, or west.
> (Goodfellow, Bengio & Courville, 2016, p. 156)

![tanh(Wx + b)](../media/tanh.png)
###### **Figure 1:** A visualisation of the neural network layer *tanh(Wx + b)* as a continuous transformation (reproduced from Olah, 2014): a linear transformation by the weight matrix; a translation by the bias vector; and pointwise application of tanh (activation function).

### The Stars Down to Earth

In his book *The Stars Down to Earth* the late philosopher Adorno (1957/1994) writes about the pseudo-rationality of astrological forecasting and the ‘abstract authority’ of reasoning based on the ‘abstract, unapproachable and anonymous’. James (2015, para. 9, in the essay *Cloudy Logic*, draws an analogy between this logic and the phenomenon of big data, paraphrasing Adorno: ‘astrology rearticulates unfashionable superstitions in the occult, in mysticism, and so on, by presenting them in empirical rather than supernatural terms — star charts and tables, for example’. Mackenzie (2017) on the other hand identifies a connection between the transformation of knowledge by ‘machine learners’, mediated by computational and mathematical operations such as vectorisation, and the theoretical legacy of Foucault: the inherent perplexity of knowledge representation practices and power. This essay explores representation learning and the construction of artificial neural networks from a philosophical perspective; and the research questions underlying this work are concerned with the material-semiotic instrumentation through which deep learning systems operate. In other words: what are the key narratives in the field, how are they implemented, and what are the epistemological implications of their application to data practices?

These ideas are as relevant as ever: the perception and understanding of our environments and interactions with them ‘is increasingly mediated by algorithms’ and, alas, modifying our social and political organisation (Mittelstadt, Allo, Taddeo, Wachter & Floridi, 2016). Floridi (2015) argues that the distinction between reality and virtuality is blurred; the two concepts confluence to form a new paradigm of (hyper)connectivity: the ‘Onlife experience’. Mittelstadt et al. (2016, p. 5) identify epistemic concerns in a world constituted by opaque algorithmic activities that ‘reontologise the world by understanding it in new, unexpected ways, and triggering and motivating actions based on the insight it generates’, and postulate that ‘actions taken on the basis of inductive correlations have real impact on human interests independent of their validity’ alluding to decision-making exclusive of evidence to support genuine causal connections.

To complicate matters, the data pipeline consists of abstraction throughout, disconnecting measurement from its original context. This is evident in, but not limited to, the practices of their acquisition, manipulation and representation: Edwards (2019) writes that data is homogenised in order to be useful for most purposes, and posits that the continual revision and reinterpretation of what he calls ‘shimmering data’ is a prerequisite for long-term integrity, instrumental in the production of robust knowledge commons; however, Steyerl (2016) notes a fundamental problem in combining multiple datasets to produce a single ‘superpattern’, a process obfuscating the identification and verification of input parameters; Farocki suggests that significant operational aspects of algorithmic systems are imperceptible to humans as ‘[operational] images [are] made by machines for other machines’ (Paglen, 2014, para. 5); and Dourish (2017) contributes to the discourse with a comprehensive demystification of the virtual, observing that issues arise from the more general dematerialisation of our ‘informated’ world. A wider array of interdisciplinary literature echoes the emergent canon: ‘to think about data, we have to think beyond data’, proposes Berry (2019, p. 43), referring to the wider context in which data are created, maintained and used; and I believe that a significant contribution can be made to the field by considering the epistemic apparatuses with which these activities are performed, that enable ‘the production and reconfiguring of difference’ (Barad, 2007, p. 232) through, namely, the assumptions and belief systems that we impose on the learners.

Adorno’s book is a useful frame of reference in this context, as the widespread adoption of neural networks appears to follow the path once laid out for astrology, in large parts due to social validation and mainstream success: AI-powered technologies are applied across industry with palpably impressive results (e.g. Evans & Gao, 2016), so why question them? This logic ignores the importance of legibility and of due process in a wider social context, and the issues that arise are often addressed in retrospect (e.g. deepfakes; see. Deepfake Detection Challenge, 2019). New memes of spiritualism have descended upon Earth, materialising in the form of GitHub repositories and of other open-source libraries. As blind faith is placed in this dense fog of abstract authority, we are left to hover in ‘the twilight zone between reason and unconscious urges’ (Adorno, p. 53): the phenomenon empowers anyone with rudimentary programming skills to deploy their narratives into the real world and, as seen already, used manipulatively this may have serious and far-reaching consequences.

### Learning Representations

Deep neural networks are described as highly expressive models with intriguing properties (Szegedy et al., 2013). Whilst they have achieved phenomenal real-world performance across a range of domains (e.g. Vinyals et al., 2019), their internal workings remain elusive. Recent research suggests that these networks exhibit ‘nonintuitive characteristics and intrinsic blind spots, whose structure is connected to the data distribution in a non-obvious way’ (Szegedy et al., 2013, p. 2). Further difficulties emerge when considering the mythos of model interpretability: ‘to be meaningful, any assertion regarding interpretability should fix a specific definition’ (Lipton, 2016). In this context, it seems that the leading-edge work is happening across academia and industry (e.g. Olah et al., 2018; see also. Ramos et al., 2019); but as demonstrated by academics in the field, the vast majority of published deep learning research consists of work proposing new models as opposed to studying existing ones (Epstein et al., 2018). This approach is inherently problematic; especially, due to an increase in model size and in complexity and a growing tendency to transfer knowledge across domains. Attention is being directed toward meta-learning, that allows for higher-level generalisation: algorithms that control algorithms. However, if the concerns underlying ‘system 1 deep learning’ (Bengio, 2019) are not fully addressed, there is no doubt that the problems will resurface in some shape or form at a later point in time. In this sense, the urgency of pursuing philosophical research is justified; furthermore, the machine learning community has been explicit about the need for interventions from the social sciences (e.g. Irvin & Askell, 2019). My position is that conversation is needed across a wider range of disciplines.

The significance of representation learning lies in its universality, tying together the many forms of deep learning: ‘feedforward and recurrent networks, autoencoders and deep probabilistic models all learn and exploit representations’ (Goodfellow et al., 2016, p. 554). Learned representations refer to approximated shapes of input distributions, which are achieved through a series of non-linear transformations (i.e. layers in a neural network; see Olah, 2014); and the goal of feature learning is to extract representations, for a given dataset, at increasing levels of abstraction, which can be used for capturing useful information about the underlying explanatory factors ‘hidden in the observed milieu of low-level sensory data’ (Bengio, Courville & Vincent, 2014, p. 1). Learning algorithms are developed to understand the world around us, although as implied earlier, a clear distinction should be made between (possibly spurious) correlations and causal knowledge.

Given the breadth of the field, it will be useful to divide the research into three different categories: data (representations), learners (models to process data), and interfaces (to access representations and judge their validity; also unifies the learner e.g. physical infrastructures, meta-learning systems, and code). Some research questions can be identified that sit at the intersections of all three areas: the first relates to the application of ‘priors’ in representation learning, or more formally known as regularisation strategies that ‘relate to the assumed existence of multiple underlying factors of variation’ (Bengio et al., 2014, p. 25) and, in other words, express initial beliefs about something in terms of probability distribution. Some of these are described by Goodfellow et al. (2016, pp. 552–554) and appear to be generally associated with temporal and spatial aspects of deep learning: the geometric relations and topological properties of input features and their changes over time. For example, it may be assumed that probability mass concentrates and locally connected regions can be approximated by low-dimensional manifolds, each of which clusters naturally and can be assigned to a single class, sparsely populating a higher-dimensional space. That is to say, ‘it doesn’t seem likely that the dog image manifold is completely surrounded by the cat image manifold’ (Olah, 2014). Assumptions give rise to good representations: the public conversation around algorithmic bias is often misfocussed, or otherwise suffers from vagueness, as inductive bias is an intrinsic property of effective deep learning.

The field has innovated rapidly since its inception: in a recent talk, Bengio (2019) characterises the advancement from ‘system 1 deep learning’ to ‘system 2’ as a shift from perception tasks to higher-level operations, such as reasoning, planning, capturing causality, and generalisation. He discusses potential strategies for meta-learning and introduces ‘the consciousness prior’, a term consistent with the nomenclature of machine learning: typified by mimicry, but in this sense oversimplification, of cognitive processes (e.g. attention, memory and imagination). The presentation is speculative and considering that ‘many of our early societal-scale inference-and-decision-making systems are already exposing serious conceptual flaws’ (Jordan, 2018, para 6) talk of such seems premature. A second research question emerges, that expands on the first: what are the key developments that enable such radical propositions? This relates to lower-level building blocks: computational models of learning, such as genetic algorithms, backpropagation, policy and value networks, knowledge transfer, and adversarial training, among others; in a political sense, the material configurations of ideology embodied in algorithmic form (Berry, 2019). These procedures, functions, and systems in place, as well as the emergent knowledge practices that they facilitate, should be explored further from an informational (Floridi, 2014) point of view: as narratives, as storytelling, as information communication, and so on.

There is a relationship between these research questions and the generality of my research aim: bearing in mind that ‘meaning is not self-evident in statistical models’ (Mittelstadt et al., 2016) theorising on representation learning, through an informational lens, may be of use for examining the wider implications of the technology in specific social and cultural contexts. This echoes a post-Kantian axiom for epistemology that ‘reflection, the life of reason, takes place as conscious projection’ (as cited in Crook, 1994, p. 6). To use an analogy: even though we all look at the same thing in the sky a different constellation, or pattern, emerges. Moreover, ‘to benefit genuinely from their freedom, people have to know what actions they can choose from and they have to know what the likely consequences of these various choice options are’ (de Bruin & Floridi, 2016, pp. 28–29); and as the interpretation of deep learning models can be highly nuanced, research into the ways in which their learning and decision-making can be communicated (e.g. Carter, Olah & Satyanarayan, 2019) and, therefore, probed and audited, offers potentially valuable contributions to the development of appropriate interfaces, systems, and policy — for safe practice, implementation, and deployment of real-world AI. Perhaps by prioritising interpretability, in the sense of explainability through a common taxonomy (Doshi-Velez & Kim, 2017), not only can the immediate negative consequences of applied deep learning be mitigated but also the accumulation of hidden technical debt (Sculley et al., 2015) minimised. As Russell (2019, p. 272) writes, ‘one of the most important lessons from the first thirty years of AI research is that a program that knows things, in any useful sense, will need a capacity for representation and reasoning that is at least comparable to that offered by first-order logic’. We may be far off from understanding intelligence; but as the work introduced here implies, something is bubbling beneath the surface.

### The Significance of Storytelling

There are interesting overlaps to explore further between algorithms and narrative theory, between representation and knowledge production, as well as between the act of classification and the ways in which we make sense of the world. The threads that interweave these complex subject matters have been presented here on a speculative level, as they demand much more attention and detail than the scope of this essay allows for; but nevertheless, it has been interesting to highlight some examples. As a starting point for future research I will briefly return to the beginning and expand on *Manifolds and Topology.*

Figure 1 represents the three stages of metamorphosis when data are passed through a neural network layer: a computation of linear transformations followed by a non-linear transformation. The images have been reproduced from a GIF found in *Colah’s Blog*, a collection of online articles in which Olah (e.g. 2014) approaches the mysteries of deep learning networks from various, though mainly visual perspectives, by devising novel methods. There is an important connection between this, and the world-surface-as-manifold analogy introduced by Goodfellow et al. (2016): the process of learning a representation consists of a set of actions following predetermined mathematical principles. The learning in machine learning ‘has few cognitive or symbolic underpinnings’ and is ‘understood as finding, with experience defined purely on the basis of time’ (Walker, 2020). Algorithms understood as instructions, executed over time, take the form of a score performed by an eclectic ensemble of humans and machines. Crawford and Joler (2018) expose the interconnected heap of entities that constitute the backbone of many commercial AI-powered technologies in their comprehensive ‘anatomical map of human labor, data and planetary resources’: socially, politically and historically complex narratives entangled across time and space.

An approach to deep learning from a narrative theory point of view opens up new avenues for critical inquiry into the globally resonant new media landscape; and the recognition of an emergent culture in which technologies, their users and their uses, have shifted from representationalism to a more direct material engagement with the world (Barad, 2016, p. 49) breaks the fourth wall, dropping us into the very core of epistemological discourse as not only observers but also performers: in the vortex of hyper-personalised feeds and alien operational images, a multitude of social forces are at play. To conclude, I cite a (in my mind) poetic description of worldbuilding in stories.

> Meanwhile the cosmos remains a work in progress […]. Space is an assemblage of overlapping perspectives, fragments of old movie stills, comic books, instrumentation, charts, maps and toys. Cosmology is, as a consequence, not so much about creating an integrated whole but of separating out our perceptions into an orderly pattern. Every cosmos we have devised so far begins and ends as a fiction and, as such, can never be rendered entirely coherent. The twelve houses of the Zodiac, literally a circle of animals looking down at us from the night sky, still serve this purpose.
> The Space Oracle (Hollings, 2018, p. 10)

### References

Adorno, T. (1994). *The Stars Down to Earth*. Routledge. (Original work published 1957)

Barad, K. (2007). *Meeting the Universe Halfway: Quantum Physics and the Entanglement of Matter and Meaning*. Duke University Press.

Bengio, Y., Courville, A., & Vincent, P. (2014). Representation Learning: A Review and New Perspectives. Retrieved from https://arxiv.org/abs/1206.5538

Bengio, Y. (2019). *From System 1 Deep Learning to System 2 Deep Learning*. NeurIPS 2019.

Berry, D. (2019). Against Infrasomatization: Towards a Critical Theory of Algorithms. In D. Bigo, E. Isin & E. Ruppert (Eds.), *Data Politics: Worlds, Subjects, Rights* (43–63). Routledge.

de Bruin, B., & Floridi, L. (2016). The Ethics of Cloud Computing. *Science And Engineering Ethics*, 23(1), 21–39.

Carter, S., Olah, C., & Satyanarayan, A. (Eds.). (2019). Distill. Retrieved 28 December 2019, from https://distill.pub

Crawford, K., & Joler, V. (2018). *Anatomy of an AI System: The Amazon Echo as an Anatomical Map of Human Labor, Data and Planetary Resources*. AI Now Institute and Share Lab. Retrieved 20 February 2020, from https://anatomyof.ai

Crook, S. (1994). Introduction. In Adorno, *The Stars Down to Earth*. Routledge.

Deepfake Detection Challenge. (2019). Retrieved 6 January 2020, from https://www.kaggle.com/c/deepfake-detection-challenge

Doshi-Velez, F., & Kim, B. (2017). Towards A Rigorous Science of Interpretable Machine Learning. Retrieved from https://arxiv.org/abs/1702.08608

Dourish, P. (2017). *The Stuff of Bits: An Essay on the Materialities of Information*. MIT Press.

Edwards, P. (2019). Knowledge Infrastructures under Siege: Climate Data as Memory, Truce, and Target. In D. Bigo, E. Isin & E. Ruppert (Eds.), *Data Politics: Worlds, Subjects, Rights* (21–42). Routledge.

Epstein, Z., Payne, B., Shen, J., Dubey, A., Felbo, B., & Groh, M. et al. (2018). Closing the AI Knowledge Gap. Retrieved from https://arxiv.org/abs/1803.07233

Evans, R., & Gao, J. (2016). DeepMind AI Reduces Google Data Centre Cooling Bill by 40%. Retrieved 6 January 2020, from https://deepmind.com/blog/article/deepmind-ai-reduces-google-data-centre-cooling-bill-40

Floridi, L. (2014). *The Fourth Revolution: How the Infosphere is Reshaping Human Reality*. Oxford University Press.

Floridi, L. (Ed.). (2015). *The Onlife Manifesto: Being Human in a Hyperconnected Era*. Springer International Publishing.

Goodfellow, I., Bengio, Y., & Courville, A. (2016). *Deep Learning*. MIT Press.

Hollings, K. (2018). *The Space Oracle: A Guide to Your Stars*. Strange Attractor Press.

Irving, G., & Askell, A. (2019). AI Safety Needs Social Scientists. doi: 10.23915/distill.00014

James, R. (2015). Cloudy Logic. Retrieved 21 December 2019, from https://thenewinquiry.com/cloudy-logic/

Jordan, M. (2018). Artificial Intelligence — The Revolution Hasn’t Happened Yet. Retrieved 30 December 2019, from https://medium.com/@mijordan3/artificial-intelligence-the-revolution-hasnt-happened-yet-5e1d5812e1e7

Lipton, Z. (2016). The Mythos of Model Interpretability. Retrieved from https://arxiv.org/abs/1606.03490

Mackenzie, A. (2017). *Machine Learners: Archaeology of a Data Practice*. MIT Press.

Mittelstadt, B. D., Allo, P., Taddeo, M., Wachter, S., & Floridi, L. (2016). The ethics of algorithms: Mapping the debate. *Big Data & Society*, 3(2), 1–21.

Olah, C. (2014). Neural Networks, Manifolds, and Topology. Retrieved 21 December 2019, from https://colah.github.io/posts/2014-03-NN-Manifolds-Topology/

Olah, C., Satyanarayan, A., Johnson, I., Carter, S., Schubert, L., Ye, K., & Mordvintsev, A. (2018). The Building Blocks of Interpretability. doi: 10.23915/distill.00010

Paglen, T. (2014). Operational Images. *E-Flux Journal*, 59.

Ramos, G., Suh, J., Ghorashi, S., Meek, C., Banks, R., & Amershi, S. et al. (2019). Emerging Perspectives in Human-Centered Machine Learning. In *CHI EA ’19: Extended Abstracts of the 2019 CHI Conference on Human Factors in Computing Systems* (pp. 1–8).

Russell, S. (2019). *Human Compatible: AI and the Problem of Control*. Allen Lane.

Sculley, D., Holt, G., Golovin, D., Davydov, E., Phillips, T., & Ebner, D. et al. (2019). Hidden technical debt in Machine learning systems. In *NIPS’15: Proceedings of the 28th International Conference on Neural Information Processing Systems* (pp. 2503–2511).

Steyerl, H. (2016). A Sea of Data: Apophenia and Pattern (Mis-)Recognition. *E-Flux Journal*, 72.

Szegedy, C., Zaremba, W., Sutskever, I., Bruna, J., Erhan, D., Goodfellow, I., & Fergus, R. (2013). Intriguing properties of neural networks. Retrieved from https://arxiv.org/abs/1312.6199

Vinyals, O., Babuschkin, I., Czarnecki, W., Mathieu, M., Dudzik, A., & Chung, J. et al. (2019). Grandmaster level in StarCraft II using multi-agent reinforcement learning. *Nature*, 575, 350–354.

Walker, K. (2020). Learning from Machines: Conversations with Artists about Machine Learning. Retrieved 18 February 2020, from https://medium.com/@Kevin7_62820/learning-from-machines-conversations-with-artists-about-machine-learning-7db6b34d038c

### Notes

*I have to say that I've only recently begun my adventures in the field of deep learning, so please get in touch should you notice something factually inaccurate, have differing views on the subject, or otherwise wish to chat.*

*URL to article: https://medium.com/@erik.lintunen/elusive-deep-learning-5cd209a1c278*
