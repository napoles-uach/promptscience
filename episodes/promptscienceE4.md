Welcome to *Prompt Science*, where artificial intelligence meets discovery.
In this episode, we explore six stories that show how AI is transforming — and sometimes unsettling — the scientific world: the GPT-5 mathematics controversy, AI control of fusion plasmas, a neural network uncovering hidden faults beneath a volcano, new theory on calibrating generative models, the open-source transition of TorchSim, and finally, the first open conference dedicated to AI agents for science.

Let’s start with the story that set the internet on fire.
In mid-October 2025, OpenAI manager **Kevin Weil** posted on X that *“GPT-5 just found solutions to ten previously unsolved Erdős problems, and made progress on eleven others — problems that have been open for decades.”*
His excitement was amplified by mathematician **Mark Sellke**, who listed the specific Erdős problem numbers, implying that GPT-5 had produced new mathematical proofs.
At first glance, it sounded like a milestone — a sign that generative AI might finally be contributing original reasoning to mathematics.

But within hours, mathematicians and AI researchers pushed back hard.
**Thomas Bloom**, who maintains the site *erdosproblems.com*, clarified that “open” on his site only means *he personally hasn’t checked for solutions*, not that the problems remain unsolved.
In other words, GPT-5 had not discovered anything new; it had simply surfaced existing results buried in the literature.

The misunderstanding quickly escalated.
**Demis Hassabis**, CEO of DeepMind, commented: *“this is embarrassing.”*
**Yann LeCun**, Meta’s Chief AI Scientist, added that OpenAI had essentially fallen for its own hype — *“Hoisted by their own GPTards.”*
The original tweets were deleted, and the researchers admitted the mistake.

The incident, in the end, was not a failure of the model but of communication.
GPT-5 did exactly what it was designed to do — retrieve, relate, and synthesize existing knowledge across billions of documents.
The mistake was human: announcing those results as original discoveries without verifying their novelty.
As mathematician **Terence Tao** pointed out, the real promise of AI in mathematics lies not in solving unsolved conjectures overnight, but in accelerating the process of connecting and cross-referencing existing work.
GPT-5, in that sense, performed admirably — acting as a tireless research assistant that can scan literature far beyond the reach of any single human researcher.
The lesson is clear: intelligence, artificial or otherwise, still requires judgment.

Now, from mathematics to plasma physics.
Also in October 2025, DeepMind and Commonwealth Fusion Systems announced *Bringing AI to the Next Generation of Fusion Energy*.
Their project, **TORAX**, merges reinforcement learning with differentiable simulation written in JAX to stabilize fusion plasmas in tokamak reactors.
A tokamak confines plasma hotter than the Sun using magnetic fields, but even small instabilities can collapse the plasma in milliseconds.
TORAX lets reinforcement-learning agents explore control policies in simulation — computing gradients directly through the magnetohydrodynamic equations — before any physical pulse is fired.
These agents learn to tune coil currents dynamically, maximizing confinement and safety.

It’s physics-in-the-loop machine learning: AI interacting with real differential equations rather than just data.
If successful, this could mark a turning point for sustainable fusion energy, where control algorithms evolve as fast as the plasma they manage.

From fusion cores we turn to volcanic depths.
The Campi Flegrei caldera near Naples has long worried scientists with its swelling ground and frequent tremors.
A team from Stanford University, the Italian National Institute of Geophysics and Volcanology, and the University of Naples Federico II used a deep neural network trained for *phase picking* to analyze years of seismic recordings.
The AI detected more than fifty-four thousand micro-earthquakes — five times the manual count — revealing a circular *ring fault* beneath Pozzuoli.
The pattern shows how the crust accommodates inflation without indicating imminent eruption.
By listening to seismic noise with algorithmic precision, AI has become a new kind of seismograph, mapping how volcanoes breathe.

And while AI digs deeper into nature, it’s also learning to correct itself.
A new preprint, *Calibrating Generative Models* (arXiv 2510.10020) by **Henry D. Smith**, **Nathaniel L. Diamant**, and **Brian L. Trippe**, tackles the problem of *miscalibration* in modern generative systems.
These models produce beautiful samples — texts, images, molecules — but their probabilities rarely match reality.
The authors frame calibration as an optimization problem: find a new distribution *q* close to the model’s *p* that satisfies statistical constraints.
They introduce two methods, **CGM-relax** and **CGM-reward**, blending differentiable penalties and reinforcement signals.
Across language, vision, and protein-design benchmarks, both approaches yield models that are not just creative but statistically reliable — a crucial step if we want AI to serve as a quantitative scientific tool.

Another major story this week came from the intersection of machine learning and materials science.
Researchers from the **University of Chicago** and **Argonne National Laboratory** announced that **TorchSim**, a high-performance simulation engine for machine-learned interatomic potentials, is moving to **community ownership and governance**.
The transition is being coordinated with **Radical AI** and the **AI for Science community at Hugging Face**, marking an important step toward open, collaborative computational infrastructure.

Machine-learned interatomic potentials, or **MLIPs**, have become essential for simulating materials with near-quantum accuracy at molecular-dynamics speed.
They predict atomic forces orders of magnitude faster than **Density Functional Theory**, bridging the gap between **first-principles accuracy** and **large-scale dynamics**.
Yet the MLIP landscape has been fragmented: each new model required custom integration code, and most legacy engines were not designed for **GPU-native inference** or **batched model evaluation**.

TorchSim changes this.
Built in **PyTorch**, it provides a **unified interface** for different MLIP architectures, automatic batching for inference, and seamless GPU acceleration.
It allows researchers to swap potentials, integrate new neural architectures, and benchmark performance without rewriting simulation code.
It’s a foundation for what many see as *the “PyTorch of atomistic simulation”* — a modular, open, and scalable engine designed for the AI era.

The move to community governance ensures transparency and sustainability.
As **Ben Blaiszik**, one of the coordinators, put it: the goal is to let scientists focus on discovery instead of infrastructure.
The call is now open for contributors — from molecular-dynamics practitioners to ML engineers — to build examples, add optimizers, and expand documentation.

In a world where AI-driven models are becoming central to physical simulation, TorchSim represents something larger than code:
it’s a shift toward **open scientific infrastructure**, where the tools for discovery evolve under the collective stewardship of the community itself.

Finally, let’s end with a glimpse of the growing ecosystem around AI-for-Science collaboration.
In October 2025, researchers across academia and industry launched the **Open Conference of AI Agents for Science 2025** — a global, openly organized event inviting labs, startups, and independent researchers to share results on autonomous and semi-autonomous agents for scientific discovery.
The conference emphasizes reproducibility, open datasets, and the creation of community benchmarks.
Talks range from robotic chemistry labs driven by reinforcement learning to literature-search agents building real-time knowledge graphs.

What makes this initiative exciting is not just the technology but the structure: an open platform where code, prompts, and models are treated as public infrastructure.
It reflects a maturing recognition that accelerating science with AI must also mean democratizing it.

So, from GPT-5’s misunderstood triumphs to DeepMind’s controlled fusion, from volcano mapping to model calibration, from open-source atomistic simulation to global AI-for-Science collaboration, one theme stands out:
Artificial intelligence is not replacing scientists — it’s multiplying the ways we can ask questions.

That’s all for this episode of *Prompt Science.*
Find transcripts and references at https://promptscience.org, join the conversation on X at prompt_science, and contribute ideas or corrections through Pull Requests on GitHub.
Until next time, keep your reasoning rigorous — and your prompts transparent.
