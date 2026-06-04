# Day 4: Core Technical Learnings (Chain-of-Thought)

1. **Reasoning State Allocation:** Standard prompts jump directly to conclusions, which reduces token calculations for logical processing. CoT forces the engine to build a sequential dependency tree before executing output tokens.
2. **Dynamic Context Gathering:** Restricting the model from responding until all 4 targeted questions are answered preserves maximum context space and ensures accurate variable mapping.
3. **Deterministic Structure:** Enforcing strict structural and output guidelines controls formatting output perfectly, reducing chaotic generation behaviors.
