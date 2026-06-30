# Robotics and Cross-Disciplinary Research

Robotics ideas are constrained by more than algorithms. Evaluate the full research system.

## Robotics-Specific Checks

- Platform: real robot, simulator, dataset-only, teleoperation, human study, or hybrid.
- Embodiment: what physical constraints matter, and which are abstracted away.
- Perception-action loop: whether the method closes the loop or only predicts offline labels.
- Control interface: low-level control, high-level planning, policy learning, shared autonomy, or decision support.
- Environment: lab, home, hospital, warehouse, field, road, or synthetic world.
- Data: logging quality, sensor calibration, annotation burden, distribution shift, and privacy.
- Evaluation: success rate, safety, robustness, sample efficiency, latency, recovery, generalization, and human factors.
- Transfer: sim-to-real gap, domain randomization, hardware variation, and deployment assumptions.
- Safety and ethics: human subjects, clinical use, failure modes, risk controls, and consent.

## Cross-Disciplinary Fit

For interdisciplinary ideas, ask:

- Which field owns the core question?
- Which community will review it?
- What evidence standard does that community expect?
- Is the novelty technical, empirical, clinical, behavioral, or methodological?
- Does the work need a collaborator, dataset, platform, or domain expert to be credible?

## Direction Generation

Do not generate generic hot-topic lists. First infer or ask about:

- user's subfield and technical strengths
- available hardware, simulator, datasets, compute, and collaborators
- target timeline and publication ambition
- tolerance for high-risk/high-reward work
- whether the user needs a thesis direction, one paper, or a pilot project

Then propose a small number of directions with opportunity, risk, decisive experiment, and why the direction fits the user.

## Review Risks in Robotics

- Evaluation is too toy-like for the claimed real-world setting.
- Method improves perception but not task success.
- Simulation results are presented as deployment evidence.
- Hardware study is too small to support broad claims.
- Human factors are claimed but not measured.
- Safety, latency, or failure recovery is ignored.
