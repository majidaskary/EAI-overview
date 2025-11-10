# Hybrid Emotional–Cognitive Agent with LLM Integration

<p align="center">
  <img width="400" height="400" alt="EAI" src="https://github.com/user-attachments/assets/b783191d-583f-43ae-982c-54d2c0e0afb9" />
</p>



## Overview
**Type**:            Personal R&D Project  
**Duration**:        Sep 2025 ‐ Present    
**Team**:            Individual Project




## Mission
### Hybrid Emotional–Cognitive Agent with LLM Integration

This project explores how emotional models, cognitive appraisal mechanisms, reinforcement learning, and large language models can be combined to build an adaptive interactive agent.
The system maintains internal emotional states, learns from user interactions, updates expectations through prediction errors, and generates context-aware responses using an LLM.
Core components include emotion dynamics, appraisal-based modulation, drive-based motivation, RL policy learning, and a lightweight hybrid LLM conditioning pipeline.




## Getting Started
### 1. Clone the repository
```
git clone https://github.com/majidaskary/EAI.git
cd EAI
```
### 2. Create virtual environment (optional)
```
python -m venv eai_env
source eai_env/bin/activate   # or eai_env\Scripts\activate
```
### 3. Install dependencies
```
pip install -r requirements.txt
```
### 4. Run a simple training/test scenario
```
python scenario_train.py --episodes 1 --style generated
```
This will:
- load the agent
- process emotional appraisal
- update internal drives
- apply RL action selection
- generate an LLM-conditioned response



  
## Project Structure
```
EAI/
│
├── agent_core.py              # Main hybrid agent loop
├── agent_emotion_state.py     # Emotion dynamics & decay
├── agent_appraisal.py         # Cognitive appraisal (goal, norm, control)
├── agent_interaction.py       # Cross-emotion interactions
├── agent_personality.py       # Trait modulation (optimism, empathy...)
├── agent_memory.py            # Episodic & long-term memory + profiling
├── agent_drives.py            # Survival/attachment/identity/growth
├── agent_desire.py            # Motivation & desire update rules
│
├── learning_module.py         # Q-learning / Double-Q / SARSA + config
├── learning_fuzzy_engine.py   # Fuzzy smoothing of emotion signals
├── learning_feedback_evaluator.py # Environment reward scoring
│
├── llm_module.py              # LLM integration layer
│
├── scenario_train.py          # Example interactive training loop
├── scenario_test.py           # Minimal test scenario
│
├── q_table.json               # Persistent RL memory
├── reward_config.json         # Reward weights + appraisal modulation
├── drives_config.json         # Homeostatic drive parameters
│
└── README.md
```



## Roadmap (High-Level)

### Phase A — Emotion Model
  - Plutchik-8 mapping
  - Fuzzy smoothing
  - Emotion decay & homeostasis
   
### Phase B — Cognitive Layer
  - Appraisal (goal relevance, prediction error, controllability, norms)
  - Expectation baseline + prediction error (PE) dynamics

### Phase C — Hybrid Policy
  - RL (Double-Q baseline)
  - Affect-biased action selection
  - Persona-aligned reward shaping

### Phase D — Advanced Internal Architecture (current)
  - Drives (survival, attachment, identity, growth)
  - Desire & motivation module
  - Dynamic reward weight adaptation
  - LLM integration with internal emotional state



## Key Features

- Formal emotion modeling (Plutchik-8 + appraisal variables)
- Cognitive appraisal integration
- Double-Q reinforcement learning with composite rewards
- Homeostatic drives and desire-based modulation
- LLM-conditioned responses informed by internal affective state
- Modular and extensible architecture for research use




## License

This project is licensed under the **Apache 2.0 License**.

You are free to use, modify, and distribute the code, including for commercial purposes, as long as you:

- Include the original copyright notice.
- Include a copy of the Apache 2.0 license.
- State any changes you make.
- Do not hold the author liable for any damages.

See the full license in the [![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE) file.




## Contact

Developer: Majid Askary

Email: m.askary84@yahoo.com

LinkedIn: https://www.linkedin.com/in/majidaskary




