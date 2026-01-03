
# Memory & Human-Centered Conversational AI Agent

## Overview
This project explores the design of a conversational AI system that emphasizes human-centered interaction over pure task completion. The system focuses on explicit memory and forgetting mechanisms, emotional awareness, and contextual continuity to support users while preserving human judgment.

## System Design
At the core of the system is a Conversation Manager responsible for coordinating memory usage, emotional assessment, and response generation. Memory is treated as a deliberate design choice, with clear distinctions between short-term context and long-term user information.

## Memory
- Short-term memory stores recent conversational context to maintain coherence.
- Long-term memory stores confirmed preferences and stable information.
- Forgetting is explicitly designed to avoid retaining sensitive or irrelevant data.

## Emotion Awareness
A lightweight emotion or sentiment analysis component assesses the tone of user input and modulates response style without altering factual content.

## Limitations
- The system does not claim true understanding or empathy.
- Emotional analysis is approximate and context-dependent.
- Memory policies require careful tuning to avoid overreach.

## Future Work
- Evaluation of user trust over longer interactions.
- Refinement of memory retention and forgetting policies.
- Exploration of human-in-the-loop controls.
