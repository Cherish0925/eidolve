# Continuous Evaluation and Evolution

This document defines one capability of Eidolve: using the continuously expanding Universe to evaluate, compare, improve, and replace models and harnesses. It is one part of the larger project, not the definition of Eidolve or Universe.

Knowledge and complexity do not stop growing. New scientific results appear; new experiments reveal previously unseen phenomena; new engineering systems, tools, interfaces, and workflows are built; new requirements emerge; difficult problems are solved; old assumptions fail under new conditions. For any finite model or research system, the world therefore continues to produce tasks that exceed its current competence.

This gives Eidolve a durable source of evaluation material. The limiting resource is not the supply of raw information. It is the quality of the filter that turns new work into clean, difficult, reproducible, uncontaminated, and decision-relevant examinations.

## From new work to high-quality examinations

The Universe should continuously collect and connect new papers, datasets, code, experiments, measurements, observations, engineering releases, workflows, failures, requirements, and research outcomes. Selected material can then be transformed into tasks that test whether a model or harness can understand, reproduce, extend, or use the underlying work.

That transformation should preserve six things:

1. **Substantive novelty.** Keep work that introduces a new result, method, observation, capability, failure, requirement, or environment. Remove duplication, publicity, weak restatements, and low-information variation.
2. **The original difficulty.** Recover what had to be inferred, designed, proved, implemented, measured, or decided before the result was known.
3. **The working environment.** Preserve the repositories, files, data, tools, simulators, interfaces, constraints, and execution conditions needed to attempt the task.
4. **Observable success.** Prefer checked proofs, passing tests, reproduced measurements, correct predictions, functioning systems, verified artifacts, and completed objectives over self-evaluation or verbal similarity.
5. **Freshness and exposure history.** Record publication time, collection time, model cutoff, known training exposure, prior prompts, memory access, and earlier evaluation use.
6. **Provenance and structure.** Connect each task to its sources, assumptions, expected outputs, scoring method, known solutions, baselines, failure cases, and the capabilities it exercises.

A useful examination is not merely a prompt with an answer. It is a versioned scientific or engineering situation with enough preserved structure to test whether a system can do the work.

## A permanent examination supply

Eidolve should maintain several populations of tasks:

- development tasks for rapid iteration and instrumentation;
- frozen suites for stable comparison across versions;
- temporally held-out tasks derived from work published after a declared cutoff;
- hidden tasks and variants that reduce direct optimization against known cases;
- transfer tasks that require using ideas across domains, tools, or representations;
- research tasks whose outputs require proofs, code, experiments, simulations, measurements, or new artifacts;
- live operational tasks drawn from real projects, with quality, cost, latency, and human intervention measured under realistic conditions.

Solved work provides tasks with known outcomes and reconstructable paths. Unsolved work tests exploration, judgment, experiment design, route selection, and measurable progress without a reference answer. The two classes should be scored differently.

Generated variants are useful only when they preserve the original difficulty and have independently checked outcomes. Quantity does not compensate for weak tasks.

## Separate the model from the harness

A deployed research system is the joint result of a model and the harness through which it receives context, remembers, plans, uses tools, executes code, interacts with environments, observes feedback, and revises its actions.

Evaluation should therefore compare:

- the same model under different harnesses;
- different models under the same harness;
- complete model–harness systems under matched conditions.

This separation distinguishes improved reasoning from improved retrieval, memory, tools, prompts, planning, execution control, or environment design. A failure should be attributed to the smallest justified cause: model limitation, context selection, memory, planning, tool use, environment, scoring, task construction, or interaction among them.

### Model capabilities

The relevant capability set depends on the intended work, but a general research system should be evaluated across:

- reasoning, intelligence, and world knowledge;
- agentic research: literature recovery, hypothesis formation, proof or experiment design, persistence, route changes, synthesis, and measurable progress;
- generation and creation of explanations, algorithms, designs, experiments, code, mathematical constructions, and other artifacts;
- in-context and few-shot learning of new rules, examples, conventions, tools, and task distributions;
- long-context use and long-term memory, including conflict handling, compression, recovery, and cross-session reuse;
- multimodal perception and fusion across text, images, diagrams, tables, audio, video, measurements, simulations, and instrument outputs;
- instruction following, role and style control, and compliance with explicit priorities and constraints;
- multi-turn state tracking of goals, assumptions, commitments, intermediate results, and unresolved questions;
- tool selection, argument construction, result interpretation, composition, and error recovery;
- planning, task decomposition, dependency ordering, stopping decisions, and replanning after failure;
- code execution, numerical reasoning, physical simulation, and interpretation of outputs under explicit assumptions;
- efficiency in time, compute, tokens, money, external calls, and human attention;
- safety and alignment with intended authority, constraints, and objectives;
- hallucination suppression, source checking, contradiction recovery, error localization, and self-correction.

### Harness capabilities

The harness should be evaluated across:

- tool integration, routing, composition, interoperability, and failure handling;
- context construction, retrieval, compression, provenance, conflict resolution, and memory management;
- planning reliability over long horizons, including recovery from failed branches and avoidance of repeated dead ends;
- prompt, policy, example, and instruction design, measured by their effect on the intended objective rather than stylistic compliance;
- environment interaction in repositories, terminals, simulators, instruments, services, and external systems;
- execution quality: reproducibility, isolation, rollback, state synchronization, observability, latency, throughput, and cost;
- coordination among model, tools, memory, context, and runtime without duplicated work or contradictory state;
- blue–green release, state migration, comparison, promotion, rollback, and preservation of Universe continuity;
- adversarial and cooperative improvement among systems without leakage of hidden answers or collapse into imitation;
- permission boundaries, traceable changes, data protection, and correct handling of conflicting authority.

## Minimal three-system prototype

The smallest useful implementation contains three AI research systems.

The **examiner** reads the changing Universe. It filters new scientific and engineering work, reconstructs tasks, prepares and maintains environments, defines scoring, creates checked variants, labels capabilities, checks contamination, and publishes versioned examination suites. Its quality is measured by whether its tasks reveal real capability differences and predict performance on future work.

The **blue system** is the current stable model–harness system. It provides the baseline for capability, reliability, cost, and operational behavior.

The **green system** is the candidate system. It may differ in model, prompts, memory, tools, planning, training, data, runtime, or architecture. Blue and green attempt the same frozen and hidden tasks under matched conditions. Their artifacts, traces, costs, failures, and outcomes return to the Universe.

Green is promoted only when it improves the intended objective while preserving critical capabilities. A higher aggregate score is insufficient when it hides severe regressions, higher cost, task leakage, instability, or optimization toward a distorted metric. Blue remains available for comparison and rollback; after promotion, the roles may alternate.

Blue and green may also critique, test, reproduce, challenge, or assist one another. The examiner must prevent this interaction from exposing hidden answers or converting evaluation into mutual self-confirmation.

## The evolution cycle

The operational sequence is:

> observe new work → filter and connect it in the Universe → reconstruct tasks and environments → freeze versioned examinations → compare models, harnesses, and complete systems → localize failures → change the smallest causal component → retest on retained and fresh tasks → promote, reject, or roll back → return outcomes and transferable knowledge to the Universe

Every stage should produce durable objects: sources, tasks, environments, tests, baselines, attempts, artifacts, scores, costs, failures, model and harness versions, explanations, and promotion decisions. Later systems should be able to recover why a version improved, where it failed, which component changed, and whether the result generalized.

## Preventing benchmark and metric collapse

Benchmarks, internal scores, self-evaluations, verifiers, test suites, and reward signals are proxies. They remain useful only while they continue to measure the intended capability.

A task set should be revised or retired when it becomes contaminated, saturated, easy to imitate without the target ability, poorly correlated with real work, or dominated by scoring artifacts. New tasks should enter because the world produced a meaningful new result, demand, environment, or failure—not merely to increase benchmark size.

Training data, development tasks, public tests, hidden tests, temporal holdouts, and live operational measurements must remain distinguishable. Known exposure and reuse paths should be recorded in the Universe. Promotion decisions should include regression tests, capability slices, cost, reliability, and real-project outcomes rather than one aggregate number.

The final question is practical: does the new model–harness system understand more, solve harder problems, conduct stronger research, create better artifacts, operate more reliably, and use resources more effectively on work it could not simply memorize or anticipate?

## The role of Universe

Universe makes this continual process possible because it preserves the changing source world, the tasks derived from it, the environments required to attempt them, the complete history of system versions, and the evidence behind every comparison.

The evaluation system is one participant in Universe. It does not define the whole project. Eidolve also serves knowledge, files, information, research, cognition, memory, search, collaboration, training, humans, agents, models, and systems whose purposes extend far beyond evaluation.