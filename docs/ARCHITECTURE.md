# Architecture

Eidolve begins from one architectural requirement: **every representation and every participant must refer to the same Universe.**

The system may use different technologies, stores, indexes, models, and interfaces, but it must not create separate realities for files, knowledge, memory, research, agents, and people.

## The shared world

Everything that enters Eidolve should be able to retain a stable identity and meaningful relationships beyond its current location.

A document is not identical to its path. A project is not identical to its repository. A conversation is not identical to one application. A model is not identical to one checkpoint location. A research result is not identical to the session in which it was produced.

This continuity is what allows the Universe to span systems, servers, versions, users, projects, and sessions without dissolving into disconnected copies.

## Native artifacts and structured meaning

Eidolve must preserve original artifacts in the forms in which they remain useful: files, repositories, datasets, media, model artifacts, experiment outputs, conversations, and other records.

Around those artifacts, the system builds structure: identities, metadata, relations, concepts, claims, evidence, histories, summaries, and interpretations.

Neither side is sufficient alone. Files without structure are difficult to understand and reuse. Structure without original artifacts loses detail, evidence, and reality. Eidolve keeps both connected.

## Graph, Wiki, and Search over one Universe

The graph, Wiki, and search system must not become separate knowledge products.

The graph expresses how things are related. The Wiki turns dispersed material into readable and revisable understanding. Search discovers and ranks relevant parts of the whole. Each operates over the same objects, artifacts, histories, and knowledge.

A relation discovered through research should improve search. A Wiki synthesis should remain linked to its sources and evidence. A search result should expose the objects, context, history, and relations that make it useful. A file should be reachable through names, topics, projects, people, claims, events, and research questions—not only through its directory path.

## History and evolution

Every important part of the Universe can develop: files, code, data, knowledge, interpretations, projects, models, tools, research directions, and shared understanding.

The architecture must therefore preserve change rather than repeatedly overwrite the past. Versions, branches, contributions, decisions, and the lineage of derived work should remain visible. Git provides the central inspiration for this property, while other forms of data and activity may require different storage and synchronization mechanisms.

The result is not only a current state, but an intelligible history of how that state came to exist.

## Intelligence and research

Humans, AI models, LLMs, agents, and research systems are participants in the Universe.

They must be able to:

1. discover what is relevant;
2. inspect original artifacts and prior work;
3. follow relations, evidence, history, and reasoning;
4. form useful working context for the current problem;
5. reason, research, compare, evaluate, and decide;
6. create new artifacts, relations, syntheses, results, and questions;
7. return those results to the shared Universe.

This closes the essential loop: the Universe supports intelligence, and intelligent work develops the Universe.

## Views, not competing truths

Different tasks require different views. The same Universe may appear as a file browser, knowledge graph, Wiki, search engine, timeline, research map, project space, memory, dataset, or agent context.

These views may organize the world differently, but they should not create independent copies of truth. A change made through one view should remain connected to the same underlying objects and history visible through the others.

## Federation and independence

Eidolve should not depend on one machine, one deployment, one model provider, one application, or one organization. Different systems may hold or compute different parts of the Universe while remaining connected through shared identities, relations, histories, and interfaces.

Qiushi Engine is one possible participant and integration. It may read from, research within, and contribute to Eidolve, but Eidolve remains an independent project and a general Universe for other systems, models, agents, people, and research communities.

## Architectural direction

The implementation should evolve from these requirements rather than from a premature technology stack. Databases, object stores, Git repositories, graph systems, search indexes, model services, and agent runtimes are implementation instruments. The architecture is successful only when they behave as one coherent Universe rather than a collection of connected silos.
