# Pgs 8-19:

- Nesy systems adopt from "Thinking fast and slow" (system 1/2 thinking).
- The distinction between Nesy systems is still being debated and defined. Some of the concerns are about:

  1. Which component is for learning and/or reasoning?
  2. What degree of coupling is required for these systems to be considered such?
  3. The differentiation between symbolic and neural knowledge.

- A combo of a single component from each system (neural and symbolic) is enough. However, more complex combos have been proven effective.

- A scientific community goals for Nesy is to formalize an empirically accepted theory surrounding it.

  - Challenges exist in the effort to formalize this theory which are centered around: Specification, design, requirements, and verification.

- A major goal of Nesy is to automate symbol creation through Symbol Emergence following the criterion in GRACE2ful.

- In the context of ML a goal for Nesy systems is to allow for a significant reduction in the amount of data required for training (small data) through abstraction from existing symbols.

## Questions

- What are these more complex combos? Are they additional components of Neural and Symbolic systems or separate systems of applications or hardware?

- In figure 2 the XOR symbol is used but that implies a separation of the systems when the paper is about the combinations of Neural and Symbolic systems. So, what is the Figure trying to convey? As the caption is missing.

- The G (Generative) in GRACE2ful given in the paper says "...should be capable of inventing new symbols whose semantics are not pre-specified by humans, thereby avoiding human biases."

  In addition, the C (Communicative) dictates that the "...symbols must be transferable and composable across agents, humans or systems." The "or" implying that only communication is required between one of the items from the list. The E (Explainable) mentions that these symbols should make reasoning transparent, but to whom?

  If human understanding of the newly generated symbols from Nesy systems is not a strict requirement, outside of a computationally efficient system, what benefit would that have for humans? As mentioned in G and C, human understanding is not a strict requirement for symbol emergence from Nesy systems.

# Pgs 19-28:

- Goal of Nesy systems in relation to XAI is to enable useful understanding of Nesy systems based on user desires, depth of explainability, scalability, and relevancy/accuracy.

## Questions

# Pgs 31-40:

- GenAI Pipeline

  1. Data Prep
  2. Training
  3. Fine-tuning
  4. Prompt/Output control
  5. Feedback/Optimization
  6. Deployment

- Most steps in the above pipeline can have symbolic structures and reasoning systems integrated into them to improve generative models.

  - Data Prep: KGs, various graphs,
  - Training: KG Embeddings, joint loss function, concatenation, etc.
  - Fine-tuning: Formal rules, constraints, specs, domain specific knowledge.
  - Prompt/Output control: GraphRAG, Ontological knowledge, KGs
  - Inference: logic-based sampling/decoding, post-filtration, KG, embeddings, text to symbolic artifacts.

- OWL based KGs enable inferencing and consistency checks in Nesy systems. Good for zero and few-shot settings.

  - Can be embedding in training pipelines
  - Can be used to filter invalid outputs at inference time

- Translation - The embedding of logical constraints into the neural loss function and semantic data augmentation.
- Extraction - Transforming learned representations into rules for reasoning tasks.
- Consolidation - Used results from extraction and places them into the existing knowledge structures.

- Enriched Integration systems:

  - Creation
  - Adaptation
  - Translation
  - Generation/Extraction
  - Consolidation
  - Explanation

- Go to enable Learning agent (LLM) Capable of performing KE.
- Human Agent will use existing knowledge and domain expertise to create new knowledge or learn about the systems reasoning process.
- Knowledge-based agents will store KGs, adapting or translating knowledge for human consumption.
- Establishing a procedure to extract and formalize this implicit knowledge, and then integrate it with established ontologies and KGs, is an open challenge

## Questions

- Can you more clearly define what semantic data augmentation is in the context of Knowledge Translation?

# Pgs 41 - 50:

- "When such inference is symbolic, we can achieve generalizable “understanding” rather than situation-specific mimicry." It would be possible to argue that mimicry can still exist with this type of 'generalization' and ability to 'differentiate.'

- Agentic AI frameworks are a common approach for human-machine collaborative systems.

- A desire for a "Cognitive API" exists as requirements for such a system does not exist as there are many design choices that require extensive thought and agreement.
