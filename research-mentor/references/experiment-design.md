# Experiment Design

Design experiments to make a research claim falsifiable. Do not default to implementation details unless asked.

## Minimum Experiment Plan

Cover these elements:

- Research question: the exact question the experiment answers.
- Hypothesis: what should happen if the idea is true.
- Task and setting: environment, dataset, robot platform, simulator, user study, or benchmark.
- Experimental unit: sample, episode, trajectory, task instance, participant, robot run, scene, or trial.
- Baselines and controls: strong current methods, simple heuristics, ablations, and negative controls when applicable.
- Metrics: primary metric, secondary metrics, safety or reliability metrics, and qualitative diagnostics.
- Protocol: train/test split, evaluation episodes, random seeds, statistical testing, and fairness constraints.
- Ablations: components whose removal tests the mechanism, not just performance.
- Failure criteria: what result would convince you the idea is wrong or not worth pursuing.
- Resource budget: data, compute, hardware time, annotation, participant recruitment, and calendar time.
- Expected artifacts: tables, plots, videos, qualitative examples, failure-case gallery, or error taxonomy.
- Risks and fallback experiments: what to do if data, hardware, compute, or performance blocks the plan.

## Good Experiment Taste

- A pilot should kill or strengthen the central hypothesis quickly.
- A baseline should be strong enough that beating it means something.
- An ablation should test a mechanism, not merely decorate the paper.
- A metric should match the claim. If the claim is robustness, average accuracy is insufficient.
- A robotics experiment should separate simulation success from real-world transfer when relevant.
- A publishable study needs both performance evidence and insight into why the method works.

## Common Weaknesses

- Only comparing against weak or outdated baselines.
- Reporting gains without failure cases.
- Treating one dataset or one robot setup as universal evidence.
- Measuring what is easy rather than what supports the claim.
- Hiding negative results that define the method's boundary.
- Adding complexity without proving the added component is necessary.

## Output Guidance

For early-stage ideas, keep the plan small: one decisive pilot, one strong baseline, and one mechanism test.

For mature studies, specify the full evidence ladder: main comparison, ablations, robustness checks, generalization, failure analysis, and claim-to-figure mapping.
