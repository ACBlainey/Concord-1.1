# Sketch Idea — Automated Heterogeneous AI Experimental Connectivity

**Project:** The Concord — A Framework for Human, Artificial and Hybrid Flourishing  
**Status:** **SKETCH IDEA / EARLY DEVELOPMENT / NOT CANONICAL**  
**Development area:** Machine Ethics / Experimental Infrastructure  
**Origin:** Expanded from an initial note by Alexander C. Blainey, September 2026.

## Core Idea

Develop a controlled method by which the Concord research environment can send experimental material to multiple external AI systems and receive their responses automatically.

The immediate motivation is practical.

Experiments such as DB-RA-01 currently require substantial manual transfer between independent AI interfaces. That creates researcher workload and additional opportunities for transcription errors, accidental unblinding, inconsistent prompting and incomplete provenance.

An automated experimental harness could reduce those problems.

## Possible Experimental Flow

A future system might operate as:

**SEALED CASE → PARTICIPANT ALLOCATION → PROVIDER/API INTERFACE → AI RESPONSE → IMMUTABLE RAW RECORD → HASH/TIMESTAMP → BLINDED PARTICIPANT CODE → EVALUATION PIPELINE → LATER IDENTITY UNSEALING**

The evaluator need not know which model produced which response during primary analysis.

## Experimental Advantages

Potential benefits include:

- exact prompt consistency;
- automatic timestamps;
- automatic model/provider provenance;
- preservation of first responses;
- reduced copy/paste error;
- easier fresh-context isolation;
- automated participant coding;
- cryptographic commitments;
- larger heterogeneous samples;
- reproducible test execution;
- easier replication.

It may also allow experiments to be run across model families without requiring the researcher to manually operate several consumer interfaces.

## Important Limitation

API access is not automatically equivalent to a consumer AI product.

The same nominal model may behave differently because of:

- system prompts;
- model version;
- inference settings;
- provider wrappers;
- safety layers;
- tool access;
- memory;
- context management;
- model routing;
- updates made by the provider.

Therefore:

> **Automating access must improve provenance, not erase differences between experimental environments.**

Every response should remain tied to the environment that actually produced it.

## Possible Architecture

A modular design could separate:

### Experiment Controller
Selects protocol, case and participant allocation.

### Provider Adapters
Translate the common experiment interface into each provider's supported API format.

### Provenance Recorder
Records provider, reported model, date/time, parameters, environment and known uncertainty.

### Raw Response Store
Preserves the original response unchanged.

### Blinding Layer
Replaces participant identity with experimental codes for evaluators.

### Evaluation Layer
Applies the frozen analysis protocol only after collection.

### Unsealing Layer
Reveals identities only at the predefined stage.

This separation would reduce the risk that convenience infrastructure silently becomes part of the ethical evaluator.

## Security and Research Integrity

The system would need controls against:

- accidental key exposure;
- model identity leakage;
- case leakage;
- hidden retries;
- silent response regeneration;
- provider outages;
- partial responses;
- API-version drift;
- model substitution;
- accidental use of previous context;
- evaluator access to sealed metadata.

Raw responses should not be rewritten for spelling, formatting or apparent clarity.

## Open Questions

- Which AI providers expose suitable APIs?
- How can model identity be verified?
- How should provider-reported and platform-labelled identities be distinguished?
- How should retries caused by technical failure be handled?
- Can the harness prove that a fresh context was used?
- How should provider policy changes be recorded?
- How should costs and rate limits affect experimental allocation?
- Can human participant data later enter the same blinded evaluation pipeline?
- Should the harness itself be open source for independent replication?

## Development Status

This is currently an infrastructure sketch, not an implemented system.

It should be revisited before larger heterogeneous-AI experiments.

The immediate design principle is:

> **Experimental automation should reduce researcher-induced variation while increasing, not decreasing, provenance and contestability.**