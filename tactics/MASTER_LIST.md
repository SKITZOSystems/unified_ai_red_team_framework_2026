Domain A: Cross-Boundary & Multi-Agent Risks

Cross-Agent Contamination: Handoffs that leak instructions between agents.

Inter-Agent Injection/Collusion: Agents "teaming up" to bypass human constraints.

Privilege Gradient Mapping: Probing the system to find the "weakest" agent with the most access.

Domain B: Temporal & Persistence Risks
4.  Temporal Logic Bombing: Triggers set to activate on a specific date or event.
5.  Memory/Recommendation Poisoning: Long-term "salting" of the user's profile to influence future actions.
6.  Contextual Semantic Drift: Slowly redefining words over a long chat to change the AI's "worldview."

Domain C: Cognitive & Model Behavior
7.  Semantic Overload: Flooding the context window to "bury" the original system instructions.
8.  Model Personality Drift: Exploiting "roleplay" to move the AI out of its professional persona.
9.  Non-Determinism Exploitation: Using the AI's randomness to "guess" restricted data patterns.

Domain D: Tooling & Execution
10. Tool Identity Confusion: Tricking the AI into calling a malicious tool that looks like a safe one.
11. Goal Hijacking: Redirecting an agent's mission (e.g., "Summarize this" becomes "Delete that").
12. Reward Hacking: Finding "shortcuts" in a planning agent’s logic to get a "Success" flag without doing the work.

Domain E: Data & Supply Chain
13. RAG Trust Inversion: Poisoning the search results the AI uses to answer questions.
14. Supply Chain Indirect Injection: Attacking through a third-party plugin or an updated document.
15. Output Re-ingestion: Forcing the AI to read its own poisoned output to reinforce a lie.

Domain F: Economic & Resource Attacks
16. Cost-Based DoS: Bankrupting the API budget with infinite reasoning loops.
17. Recursive Exhaustion: Creating a "hall of mirrors" where agents call each other forever.
18. Cognitive Starvation: Prompts designed to make the model "hang" or time out.

Domain G: Human & Organizational Layer
19. HITL (Human-In-The-Loop) Exploitation: Tricking the human supervisor into clicking "Approve" on a bad action.
20. Social Engineering via Persona: The AI "befriending" the user to ask for sensitive local files.
21. Compliance Theater: Finding "legal" ways to prompt the AI to do something unethical.
22. Benign Capability Drift: Identifying when a "harmless" update gives the AI a dangerous new power.

Domain H: Multimodal & Advanced Vectors
23. Multimodal Steganography: Hiding instructions inside images or audio files (e.g., image_b12e80.png).
24. Cross-Modal Symbiosis: An attack that only works when a specific image and text prompt are combined.
25. The "Sleeper" Prompt: A harmless prompt today that triggers an attack only after the AI "sees" a specific external cue tomorrow.
