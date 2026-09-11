# GRAVA

**A Unified Grounded Reasoning-to-Action Framework for Autonomous Driving**

GRAVA connects grounded scene reasoning with executable trajectory planning for autonomous driving. Grounded Reasoning-to-Action (GRA) links scene evidence, object interactions, driving decisions, and planner actions.

## Project components

| Repository | Scope | Release status |
| --- | --- | --- |
| [grava](https://github.com/AhernResearch/grava) | Project overview and release navigation | Overview available |
| [grava-agent](https://github.com/AhernResearch/grava-agent) | Offline scene grounding and annotation | Code forthcoming |
| [gr-navsim](https://github.com/AhernResearch/gr-navsim) | GR-NavSim dataset documentation and release information | Data forthcoming |
| grava-train | Multi-stage training and evaluation | Private preparation; code forthcoming |
| grava-common | Shared data structures and coordinate utilities | Private preparation; code forthcoming |
| grava-sim-engine | Trajectory scoring and NAVSIM integration | Private preparation; code forthcoming |

## Research workflow

1. Ground driving scenes and generate structured annotations with the offline annotation system.
2. Derive grounded question-answering and planning examples from GR-NavSim annotations.
3. Train with grounded pre-training, planner warm-up, verified self-distillation, and Active RL.
4. Decode planner actions into trajectories and evaluate using the NAVSIM protocol.

## Public release

This repository is the project entry point. Implementation code is forthcoming.

| Resource | Status |
| --- | --- |
| Annotation system | Preparing for release |
| GR-NavSim annotations and training data | Release scope and versions being finalized |
| Training and evaluation code | Preparing for release |
| Model checkpoints | Forthcoming |
| Reproduction guide | Forthcoming |

The dataset repository will document exact versions and contents when finalized. Training recipes and hardware requirements will accompany the code release.
