---
title: Resources
nav_order: 3
layout: home
---

## Resources

This course pulls heavily from [**BlueDot Impact's AI Alignment course**](https://aisafetyfundamentals.com/alignment/), an updated version of *AGI Safety Fundamentals*, originally curated by OpenAI researcher Richard Ngo.

### Overview / Introductory Resources

*All optional — pick whatever suits your level.*

- [Intro to AI Safety, Remastered](https://www.youtube.com/watch?v=pYXy-A4siMw) — 18 min video
- [What happens when our computers get smarter than we are?](https://www.ted.com/talks/nick_bostrom_what_happens_when_our_computers_get_smarter_than_we_are) — Nick Bostrom TED talk, 16 min
- [80,000 Hours — Preventing an AI-related catastrophe](https://80000hours.org/problem-profiles/artificial-intelligence/) — ~60 min, quite thorough
- [AGI Safety from First Principles](https://www.alignmentforum.org/s/mzgtmmTKKn5MuCzFJ) — long, the best technical introduction

### Recommended Books
- *The Alignment Problem* — Brian Christian
- *Superintelligence* — Nick Bostrom
- *Human Compatible* — Stuart Russell (UC Berkeley professor)

---

### Week 1: Overview of AI Safety

- [Agentic Misalignment, LLMs as Insider Threats](https://arxiv.org/pdf/2510.05179)
- [The Alignment Problem from a DL Perspective](https://arxiv.org/abs/2209.00626)
- [How we could stumble into AI catastrophe](https://www.cold-takes.com/how-we-could-stumble-into-ai-catastrophe/)
- [Anthropic — Core Views on AI Safety](https://www.anthropic.com/news/core-views-on-ai-safety)
- [Bengio — Reasoning through arguments against taking AI safety seriously](https://yoshuabengio.org/2024/07/09/reasoning-through-arguments-against-taking-ai-safety-seriously/)

### Week 2: ML Review

**Before class:**
- [Visualizing the Deep Learning Revolution](https://www.alignmentforum.org/posts/Yc5QSSZCQ9qdyxZF6/visualizing-the-deep-learning-revolution) (Ngo 2023, ~20 min)
- [Dive Into Deep Learning — Introduction](https://d2l.ai/chapter_introduction/index.html) (everything before §1.4 "Roots"; skip Tagging, Search, Recommender Systems, Sequence Learning)
- 3blue1brown: [But What Is a Neural Network?](https://www.youtube.com/watch?v=aircAruvnKk) + [Gradient Descent, How NNs Learn](https://www.youtube.com/watch?v=IHZwWFHWa-w)
- Prefer text? [Intro to neural networks](http://neuralnetworksanddeeplearning.com/chap1.html) and [backpropagation](http://neuralnetworksanddeeplearning.com/chap2.html)

**In-class (pick one):**
- [GPT-3](https://arxiv.org/abs/2005.14165)
- [Understanding Reasoning LLMs](https://magazine.sebastianraschka.com/p/understanding-reasoning-llms)
- [Chinchilla scaling laws](https://arxiv.org/abs/2203.15556)
- [InstructGPT](https://proceedings.neurips.cc/paper_files/paper/2022/file/b1efde53be364a73914f58805a001731-Paper-Conference.pdf)
- [A Visual Guide to Mixture of Experts](https://newsletter.maartengrootendorst.com/p/a-visual-guide-to-mixture-of-experts)

**Optional:**
- [BERT](https://arxiv.org/pdf/1810.04805)
- [The Bitter Lesson](http://www.incompleteideas.net/IncIdeas/BitterLesson.html)
- [Multi-Head Latent Attention](https://arxiv.org/pdf/2502.07864)
- [QLoRA](https://arxiv.org/pdf/2305.14314)

### Week 3: AGI Timelines, Takeoff, and Imagining the Future

**Before class:**
- [AI 2027](https://ai-2027.com/) (Kokotajlo et al. 2025; header + main timeline, skim the rest; ~60 min)

**In-class (pick one):**
- [More Is Different for AI](https://bounded-regret.ghost.io/more-is-different-for-ai/), [Future ML Systems Will Be Qualitatively Different](https://bounded-regret.ghost.io/future-ml-systems-will-be-qualitatively-different/), [Thought Experiments Provide a Third Anchor](https://bounded-regret.ghost.io/thought-experiments-provide-a-third-anchor/) — Steinhardt sequence
- [Situational Awareness](https://situational-awareness.ai/) (Aschenbrenner 2024; first two sections + overview)
- [Why transformative AI is really, really hard to achieve](https://www.exponentialview.co/p/why-transformative-ai-is-really-really)
- [On Recent AI Model Progress](https://www.thezvi.com/p/on-recent-ai-model-progress)
- [METR: Measuring AI Ability to Complete Long Tasks](https://metr.org/blog/2025-03-19-measuring-ai-ability-to-complete-long-tasks/) (2025)

**Optional:**
- Dario Amodei, [Machines of Loving Grace](https://www.darioamodei.com/essay/machines-of-loving-grace)
- Eliezer Yudkowsky, [The Only Way to Deal With the Threat From AI? Shut It Down](https://time.com/6266923/ai-eliezer-yudkowsky-open-letter-not-enough/)
- Anthropic [Responsible Scaling Policy](https://www.anthropic.com/news/anthropics-responsible-scaling-policy)

### Week 4: RLHF and Preference Training

**Before class (pick one):**
- [DPO — Direct Preference Optimization](https://arxiv.org/pdf/2305.18290)
- [RLHF — Reinforcement Learning from Human Feedback (InstructGPT / PPO)](https://arxiv.org/pdf/2203.02155)
- [DPO vs PPO](https://arxiv.org/pdf/2404.10719)

**In-class (pick one):**
- [Scaling Laws for Reward Model Overoptimization](https://arxiv.org/abs/2210.10760)
- [Deliberative Alignment: Reasoning Enables Safer Language Models](https://openai.com/index/deliberative-alignment/)
- [Rule Based Rewards for Language Model Safety](https://openai.com/index/improving-model-safety-behavior-with-rule-based-rewards/)
- [Open Problems and Fundamental Limitations of RLHF](https://arxiv.org/abs/2307.15217) (Casper et al. 2023)

**Optional:**
- [RLHF: Supervising strong learners by amplifying weak experts](https://arxiv.org/abs/1810.08575) (Christiano et al. 2018)
- [Training a Helpful and Harmless Assistant with RLHF](https://arxiv.org/abs/2204.05862)

### Week 5: Adversarial Robustness

**Before class:**
- [Towards Evaluating the Robustness of Neural Networks](https://arxiv.org/abs/1608.04644) (C&W; Carlini et al. 2016; ~30 min)

**In-class (pick one):**
- [Universal and Transferable Adversarial Attacks (GCG)](https://arxiv.org/abs/2307.15043) (Zou et al. 2023)
- [Improving Alignment and Robustness with Circuit Breakers](https://arxiv.org/abs/2406.04313) (Zou et al. 2024)
- [Safety Alignment Should Be Made More Than Just a Few Tokens Deep](https://arxiv.org/abs/2406.05946) (Qi et al. 2024)
- [AutoDAN: Generating Stealthy Jailbreak Prompts](https://arxiv.org/abs/2310.04451) (Liu et al. 2023)
- [Poisoning Attacks on LLMs Require a Near-constant Number of Poison Samples](https://arxiv.org/abs/2408.07089)
- [Trading Inference-Time Compute for Adversarial Robustness](https://arxiv.org/abs/2501.18841)

### Week 6: LLM Agent Safety and Security

**Before class:**
- [AgentHarm: A Benchmark for Measuring Harmfulness of LLM Agents](https://arxiv.org/abs/2410.09024) (Andriushchenko et al. 2024)

**In-class (pick one):**
- [StruQ: Defending Against Prompt Injection with Structured Queries](https://arxiv.org/abs/2402.06363)
- [SecAlign: Defending Against Prompt Injection with Preference Optimization](https://arxiv.org/abs/2410.05451)
- [AGENTPOISON: Red-teaming LLM Agents](https://arxiv.org/abs/2407.12784)
- [Security Challenges in AI Agent Deployment](https://arxiv.org/abs/2507.20526)
- [Agent Security Bench (ASB)](https://arxiv.org/abs/2410.02644)
- [The Instruction Hierarchy](https://arxiv.org/abs/2404.13208)

**Optional:** [corca-ai/awesome-llm-security](https://github.com/corca-ai/awesome-llm-security) — up-to-date list of agent attacks/defenses.

### Week 7: Alignment, Oversight, and Control

**Before class:**
- [Detecting misbehavior in frontier reasoning models](https://openai.com/index/chain-of-thought-monitoring/) (Baker et al. 2025; read article + linked paper; ~45 min)

**In-class (pick one):**
- [METR — Recent Frontier Models Are Reward Hacking](https://metr.org/blog/2025-06-05-recent-reward-hacking/) (2025)
- [MONA: Myopic Optimization with Non-myopic Approval](https://arxiv.org/abs/2501.13011) (Shah et al. 2025)
- [Debating with More Persuasive LLMs Leads to More Truthful Answers](https://arxiv.org/abs/2402.06782) (Khan et al. 2024)
- [Weak-to-strong generalization](https://openai.com/index/weak-to-strong-generalization/) (Burns et al. 2023)

**Optional:**
- [Superalignment Anti-Literature Review](https://arxiv.org/abs/2506.16685) (Cohen et al. 2025)
- [An alignment safety case sketch based on debate](https://arxiv.org/abs/2505.03989) (Buhl et al. 2025)
- [Scalable AI Safety via Doubly-Efficient Debate](https://arxiv.org/abs/2311.14125) (Brown-Cohen et al. 2023)
- [Specification gaming: the flip side of AI ingenuity](https://deepmind.google/discover/blog/specification-gaming-the-flip-side-of-ai-ingenuity/) (Krakovna et al. 2020)
- [Debate update: Obfuscated arguments problem](https://www.lesswrong.com/posts/PJLABqQ962hZEqhdB/debate-update-obfuscated-arguments-problem) (Barnes et al. 2020)
- [The Effects of Reward Misspecification](https://arxiv.org/abs/2201.03544) (Pan et al. 2022)
- [Defining and Characterizing Reward Gaming](https://arxiv.org/abs/2209.13085) (Skalse et al. 2022)

### Week 8: Inner Misalignment, Deception, and Alignment Faking

**Before class:**
- [Deceptive alignment: ML systems will have weird failure modes](https://bounded-regret.ghost.io/deceptive-alignment/) (Steinhardt 2022)
- [Alignment Faking in Large Language Models](https://www.anthropic.com/research/alignment-faking) (Anthropic 2024)

**In-class (pick one):**
- [Frontier Models are Capable of In-context Scheming](https://arxiv.org/abs/2412.04984) (Meinke et al. 2025)
- [Scheming AIs: Will AIs Fake Alignment During Training In Order to Get Power?](https://arxiv.org/abs/2311.08379) (Carlsmith 2023, §1)
- [AI Control: Improving Safety Despite Intentional Subversion](https://arxiv.org/abs/2312.06942) (Greenblatt et al. 2024)

**Optional:**
- [Goal Misgeneralization in Deep RL](https://arxiv.org/abs/2105.14111) (Langosco et al. 2023) — or [Rob Miles' summary video](https://www.youtube.com/watch?v=zkbPdEHEyEI)
- [Parametrically Retargetable Decision-Makers Tend To Seek Power](https://arxiv.org/abs/2206.13477) (Turner et al. 2022)
- [Risks from Learned Optimization](https://arxiv.org/abs/1906.01820) (Hubinger et al. 2019) — or Rob Miles' [video summary](https://www.youtube.com/watch?v=IeWljQw3UgQ)
- [AI Sandbagging: Language Models Can Strategically Underperform on Evaluations](https://arxiv.org/abs/2406.07358) (van der Weij 2024)

### Week 9: Interpretability, Unlearning, and Representation Engineering

**Before class:**
- [Zoom In: An Introduction to Circuits](https://distill.pub/2020/circuits/zoom-in/) (~30 min)
- [Representation Engineering](https://arxiv.org/abs/2310.01405) (Zou et al. 2023; ~45 min)

**In-class (pick one):**
- [Distillation Robustifies Unlearning](https://arxiv.org/abs/2506.06278)
- [Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet](https://transformer-circuits.pub/2024/scaling-monosemanticity/) (Anthropic 2024; SAEs)
- [The WMDP Benchmark: Measuring and Reducing Malicious Use With Unlearning](https://arxiv.org/abs/2403.03218) (Li et al. 2024 — written by a former BASIS president!)
- [Steering GPT-2-XL by adding an activation vector](https://www.lesswrong.com/posts/5spBue2z2tw4JuDCx/steering-gpt-2-xl-by-adding-an-activation-vector) (Turner et al. 2023; [paper version](https://arxiv.org/abs/2308.10248))

**Optional:**
- [A Longlist of Theories of Impact for Interpretability](https://www.alignmentforum.org/posts/uK6sQCNMw8WKzJeCQ/a-longlist-of-theories-of-impact-for-interpretability) (Nanda 2022)
- [80,000 Hours #107 — Chris Olah on what the hell is going on inside neural networks](https://80000hours.org/podcast/episodes/chris-olah-interpretability-research/)
- [Toy Models of Superposition](https://transformer-circuits.pub/2022/toy_model/index.html) (Elhage et al. 2022)
- [Against Almost Every Theory of Impact of Interpretability](https://www.alignmentforum.org/posts/LNA8mubrByG7SFacm/against-almost-every-theory-of-impact-of-interpretability)

### Week 10: Additional Research Agendas & Miscellaneous Topics

**Before class (pick one):**
- [Auditing language models for hidden objectives](https://arxiv.org/abs/2503.10965) (Anthropic 2025)
- [Embedded Agents, Part 1](https://www.alignmentforum.org/s/Rm6oQRJJmhGCcLvxh/p/i3BTagvt3HbPMx6PN) (Demski and Garrabrant 2018)
- [Alignment Careers Guide](https://aisafetyfundamentals.com/blog/alignment-careers-guide/) (Rogers-Smith 2024)
- [Neural networks generalize because of this one weird trick](https://www.lesswrong.com/posts/fovfuFdpuEwQzJu2w/neural-networks-generalize-because-of-this-one-weird-trick) (Hoogland 2023; singular learning theory)
- [Nobody's on the ball on AGI alignment](https://www.forourposterity.com/nobodys-on-the-ball-on-agi-alignment/) (Aschenbrenner 2023)
- [Formal verification, heuristic explanations and surprise accounting](https://www.alignment.org/blog/formal-verification-heuristic-explanations-and-surprise-accounting/) (Hilton 2024)
- [Sabotage Evaluations for Frontier Models](https://arxiv.org/abs/2410.21514) (Benton et al. 2024)

**In-class:** read **another** article from the above list that you have not read before.

**Optional:**
- [An introduction to the infra-Bayesianism sequence](https://www.alignmentforum.org/posts/zB4f7QqKhBHa5b37a/introduction-to-the-infra-bayesianism-sequence) (Kosoy and Diffractor 2020)
- [Progress on causal influence diagrams](https://www.alignmentforum.org/posts/Cd7Hw492RqooYgQAS/progress-on-causal-influence-diagrams) (Everitt et al. 2021)

---

### Other Recommended Readings

- [Request for Proposals: Technical AI Safety Research](https://www.openphilanthropy.org/request-for-proposals-technical-ai-safety-research/) — Open Philanthropy
- [What failure looks like](https://www.alignmentforum.org/posts/HBxe6wdjxK239zajf/what-failure-looks-like) (Christiano 2019)
- [Clarifying "What failure looks like" (part 1)](https://www.alignmentforum.org/posts/v6Q7T335KCMxujhZu/clarifying-what-failure-looks-like-part-1) (Clarke 2020)
- [Takeoff speeds](https://sideways-view.com/2018/02/24/takeoff-speeds/) (Christiano 2018)
- [What multipolar failure looks like](https://www.alignmentforum.org/posts/LpM3EAakwYdS6aRKf/what-multipolar-failure-looks-like-and-robust-agent-agnostic) (Critch 2021)
- [Another outer alignment failure story](https://www.alignmentforum.org/posts/AyNHoTWWAJ5eb99ji/another-outer-alignment-failure-story) (Christiano 2021)
- [Value is fragile](https://www.lesswrong.com/posts/GNnHHmm8EzePmKzPk/value-is-fragile) (Yudkowsky 2009)
- [Interpretability in Parameter Space (APD)](https://arxiv.org/abs/2501.14926) (Sharkey et al. 2025)
- [hari-sikchi/awesome-ai-safety](https://github.com/hari-sikchi/awesome-ai-safety) — compilation of AI safety papers
- [AI Safety Papers](https://www.aisafetypapers.org/) — another compilation

### Course Logistics
- [Final Project guidelines](#) — *EDIT ME: add link*
- [Reflection submission portal](#) — *EDIT ME: add link*
