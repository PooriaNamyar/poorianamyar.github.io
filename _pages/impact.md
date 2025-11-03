---
layout: page
title: Impact
permalink: /impact/
description:
nav: true
nav_order: 4
---

# Research Impact and Deployment

- My work, **Soroush** (<a href="https://www.usenix.org/conference/nsdi24/presentation/namyar-solving">NSDI'24</a>), introduces a general max-min fair allocator that applies to any graph-based resource allocation problem, including traffic engineering and cluster scheduling. Soroush has been deployed in Microsoft and has been managing the traffic across Microsoft’s global network since 2023. It has improved the runtime by 3$\times$ on average (up to 5.4$\times$) without compromising fairness and efficiency. In this work, I designed novel algorithms with provable guarantees to solve multi-path max-min fair allocation using a single fast optimization - achieving this _for the first time_ in the networking literature.

- My work on clock synchronization, **Firefly** (<a href="https://dl.acm.org/doi/abs/10.1145/3718958.3750502">SIGCOMM'25</a>), is deployed at Google. I developed a mathematical framework to analyze key properties of clock synchronization systems in data centers. For instance, I proved that running distributed clock consensus on a random overlay graph is scalable, converges quickly, and has a near-optimal error. Firefly combines these analyses with system-level optimizations to achieve $\leq$10 ns error.

- My work, **MetaOpt** (<a href="https://www.usenix.org/conference/nsdi24/presentation/namyar-finding">NSDI'24</a>), opens up a new area of research on scalable, general, and user-friendly performance analyzers. MetaOpt enables practitioners to identify and fix the pathological behavior of their algorithms before deployment. It has attracted interest from both academia and industry. For instance, I collaborated with researchers at ETH Z&uuml;rich to analyze the trade-offs in a new packet scheduling heuristic using MetaOpt (see **PACKS** at <a href="https://www.usenix.org/conference/nsdi25/presentation/alcoz">NSDI'25</a>). MetaOpt has also identified and fixed inefficiencies in key production heuristics at Microsoft.

## Patents
- Flow network intermediate representation for optimization problems, <a href="https://patents.google.com/patent/US20250200130A1/en">US Patent</a>
- Network traffic control using estimated maximum gap, <a href="https://patents.google.com/patent/US12155554B2/en">US Patent</a>
- Solving max-min fair resource allocation at large scale, <a href="https://patents.google.com/patent/US20240314747A1/en">US Patent</a>
- Impact-aware mitigation for computer networks, <a href="https://patents.google.com/patent/US12063142B2/en">US Patent</a>