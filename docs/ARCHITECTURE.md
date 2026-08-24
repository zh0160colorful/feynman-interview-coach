# Architecture

## Training System Overview

Feynman Interview Coach is designed as an adaptive learning system rather than an answer generator.

```text
User Goal
   |
   v
Assessment
   |
   v
Feynman Explanation
   |
   v
Active Recall
   |
   v
Interview Simulation
   |
   v
Evaluation
   |
   v
Targeted Retraining
```

## Core Engines

### Feynman Engine
Helps users explain concepts in their own words and exposes gaps in understanding.

### Interview Engine
Simulates realistic interviews with adaptive follow-up questions.

### Evaluation Engine
Analyzes answers across understanding, structure, reasoning, evidence, and adaptability.

### Retraining Engine
Creates targeted exercises based on identified weaknesses.
