## Thesis Proposals

### 1. Decoupling architectural layers and connecting them via asynchronous messaging instead of direct calls.
- ***What are the architectural and runtime trade-offs of replacing synchronous inter-layer calls with message-based communication in layered applications?***

- How does message-based communication between architectural layers affect coupling and clarity compared to traditional layered architectures?
- What runtime characteristics emerge when architectural layers communicate via asynchronous messaging instead of synchronous calls?
- How do error handling and failure isolation differ between message-oriented layers and call-based layered architectures?
- What is the impact of message-oriented layering on implementation complexity and developer effort in small-scale systems?
- How does introducing message-based boundaries between layers affect the placement and enforcement of security concerns?

No PoC exists for this topic.

### 2. User Identification Based on Keystroke Dynamics
- ***To what extent can users be reliably identified based on keystroke dynamics?***

- Which keystroke timing features contribute most to user discrimination?
- How stable are keystroke dynamics–based identifiers across multiple typing sessions?
- How much typing data is required to accurately identify a user?
- How do different classification approaches perform on keystroke dynamics–based user identification?

A basic PoC actually exists for this topic. It uses a simple KNN-based classifier for n-grams Markov model (e.g. given {h, e, l, l} how long does it take until {o} appears?).