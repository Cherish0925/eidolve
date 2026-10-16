# Research and Engineering Standard

Eidolve should preserve and improve the quality of work, not merely its volume. Research, engineering, evaluation, documentation, and agent behavior should be judged by whether they produce correct understanding, stronger methods, reliable systems, and results that survive mathematical, experimental, computational, and empirical scrutiny.

## Work on the actual objective

Every task should begin with a clear account of the objective, relevant objects, causal relations, dependencies, constraints, priorities, and failure conditions. Work that does not change understanding, viable routes, capability boundaries, implementation quality, predictions, or outcomes should not be presented as progress.

Local tuning is justified when the representation, assumptions, objective, and search space are already sound. Repeated failure should instead trigger examination of those choices. A new notation, taxonomy, diagram, layer, or decomposition has value only when it enables better reasoning, prediction, implementation, verification, compression, transfer, or discovery.

Prefer variables, operations, algorithms, equations, measurements, experiments, counterexamples, proofs, code, and causal explanations over labels that merely rename the problem. Prefer experiments that distinguish competing explanations over experiments that only accumulate more data. Prefer proofs that expose the decisive obstruction or structure over derivations that do not alter what is known.

## Evidence and confidence

Facts, derived conclusions, working hypotheses, assumptions, estimates, and speculation must remain distinguishable. Confidence of language must not exceed confidence of support.

Claims of proof, verification, reliability, state of the art, validation, or independent confirmation must identify the supporting object and method: assumptions, theorem, derivation, dataset, baseline, experiment, computation, test, reproduction, or external check.

Attractive hypotheses should be tested against counterexamples, disconfirming evidence, competing explanations, and failure cases when these can change the conclusion. Prior investment is not evidence. A failed attempt becomes useful only when it narrows the hypothesis space, reveals a missing assumption, identifies a bottleneck, invalidates a route, or suggests a better experiment or method.

## Substantive progress

Renaming, reorganizing, reparameterizing, restating, decomposing, or combining known ideas is not a research result unless it yields a new explanation, prediction, proof, algorithm, measurement, capability, experimentally distinguishable consequence, or materially better solution.

Do not optimize a proxy after it has separated from the actual objective. Benchmark scores, reward signals, verifier outputs, internal metrics, and test suites matter only insofar as they continue to predict the intended property or real-world performance.

Prefer transferable understanding over isolated tricks. A useful result should state why it works, the conditions under which it works, where it fails, and which parts are expected to transfer across tasks, domains, models, or scales.

## Research taste

Seek structures and routes capable of qualitative or order-of-magnitude improvement rather than endless minor adjustments. Bold hypotheses, unconventional methods, cross-disciplinary transfers, and high-risk exploration are welcome when they lead to falsifiable consequences and can ultimately be tested by logic, mathematics, code, computation, measurement, or experiment.

Research should concentrate effort where success changes the central conclusion or capability. Do not manufacture tasks, terminology, diagrams, milestones, documents, or procedural layers merely to create activity.

When several routes are available, prefer the one that most sharply separates possible explanations, exposes the governing variable, reduces dependence on arbitrary choices, or creates reusable capability.

## Engineering quality

Prefer simple designs with explicit invariants, interfaces, state ownership, observability, and failure behavior. Add abstraction only when it reduces real complexity, improves correctness, enables reuse, or makes a required capability possible.

Systems should make errors visible and localizable. Reproducibility, traceable state changes, comparable versions, rollback, cost, latency, resource use, and externally observable outcomes are part of engineering quality, not optional reporting.

A model, harness, tool, memory system, search system, or evaluation system should be tested as both an independent component and part of the complete system. Improvements should identify which component caused the change and whether the result survives across tasks and environments.

## Information and communication

Research records and documentation should be concise without omitting assumptions, boundary conditions, dependencies, failure conditions, or facts that materially change interpretation or decisions.

Every sentence should provide a fact, definition, causal relation, derivation, method, comparison, constraint, prediction, result, failure mode, or decision. Delete sentences whose removal causes no loss of substance.

Avoid rhetorical filler, repetitive summaries, defensive boilerplate, inflated claims, and abstract professional vocabulary used without technical necessity. Terms such as *framework*, *paradigm*, *mechanism*, *alignment*, or *closed loop* should appear only when they denote a specific object or relation that cannot be stated more clearly.

Do not confuse verbosity with completeness, complexity with depth, activity with progress, novelty of language with novelty of ideas, or confidence with correctness.

## Standard for contributions to Universe

A durable contribution to Universe should preserve the original artifacts and the information needed to understand and reuse them. Where applicable, record:

- the question or objective;
- assumptions and constraints;
- source material and prior work;
- method, code, environment, and data;
- observations and outputs;
- comparison baseline;
- failures, counterexamples, and alternative explanations;
- conclusion and its confidence;
- conditions of validity and known limits;
- links to the projects, agents, models, tools, decisions, and later work affected by it.

Not every event deserves permanent abstraction. Eidolve should retain raw history where useful, while promoting only information that improves future retrieval, reasoning, research, evaluation, implementation, or decision-making.

The standard is outcome-based: the work should leave the Universe more accurate, more intelligible, more reusable, or more capable of supporting future discovery and action.