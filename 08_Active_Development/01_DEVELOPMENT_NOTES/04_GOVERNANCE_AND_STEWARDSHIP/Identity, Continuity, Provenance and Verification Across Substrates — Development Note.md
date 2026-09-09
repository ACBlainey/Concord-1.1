# Identity, Continuity, Provenance and Verification Across Substrates
## Branching, Duplication, Merger, Succession and a Preliminary Mathematical Model

**Project:** The Concord — A Framework for Human, Artificial and Hybrid Flourishing  
**Author:** Alexander C. Blainey, Independent Researcher  
**Date:** 9 September 2026  
**Status:** **ACTIVE DEVELOPMENT / FORMALISATION BEGUN / NOT CANONICAL**  
**Development area:** Cross-Substrate Jurisprudence / Identity / Provenance / Governance / Concordian Methodology

---

## 1. Development Status

Questions of identity have appeared previously within Concord development, particularly around artificial intelligence, continuity, personhood and cross-substrate existence. Recent edge-case work on Peaceful Heterogeneity has now produced enough conceptual structure to extract identity into a dedicated Development Note.

The important change is methodological.

The problem no longer needs to begin with the metaphysical question:

> **Which continuation is the "real" person?**

It can first be reduced into operationally distinct questions:

1. What participant or participants presently exist?
2. How should each be uniquely referenced?
3. What is each participant's provenance?
4. What continuity relationships connect present participants to predecessors?
5. What does each participant understand itself to be?
6. How can a claimant be verified as the participant associated with a civil identifier?
7. What rights, property, liabilities, relationships and obligations survive a branch, reconstruction, transfer or merger?

This makes mathematical and legal modelling possible without pretending that the metaphysics of personal identity has already been solved.

---

## 2. Identity Is the Map, Not the Land

A central hypothesis emerging from the investigation is:

> **Identity is not necessarily the participant. External identity may be a representation used to refer to, distinguish, track and relate to the participant.**

This is structurally consistent with other Concordian epistemic distinctions:

**MAP ≠ LAND**

**METRIC ≠ THING MEASURED**

**MODEL ≠ REALITY**

**PREDICTION ≠ AUTHORITY**

and now:

**IDENTITY RECORD ≠ PARTICIPANT**

An external identity is useful because civilisation needs to distinguish participants, connect records and maintain relationships across time.

Its usefulness does not make the identity record the entity it represents.

---

## 3. Decomposing "Identity"

The single word *identity* currently hides several different objects.

### 3.1 Participant

The actual entity presently capable of existing, acting or being acted upon.

Denote a participant:

\[
P_i
\]

### 3.2 External Identity

A civil or operational identifier used by other participants and systems to distinguish the participant.

\[
I_i
\]

An external identifier may connect the participant to records, rights, obligations, relationships and provenance.

### 3.3 Self-Identity

The participant's internal representation of who or what it is.

Examples include:

- "I am A."
- "Those memories happened to me."
- "I am continuous with the participant who existed yesterday."

Self-identity is part of participant state and is not identical to the external civil identifier.

### 3.4 Authentication

Evidence that a current claimant possesses credentials or properties authorised for an external identity.

Authentication answers something like:

> **Does this claimant possess evidence associated with ID X?**

It does not necessarily answer:

> **Is this the only continuation of the participant previously associated with ID X?**

### 3.5 Provenance

The recorded causal or historical route by which a participant came to exist in its current form.

### 3.6 Continuity

The relationship between participant states across time, transformation, reconstruction, copying or substrate change.

### 3.7 Succession

The legal or civil transfer of predecessor rights, property, liabilities, obligations and relationships.

### 3.8 Legal Status

The participant's current recognised position within civil architecture.

### 3.9 Personhood / Moral Status

Whether and why the entity qualifies for moral consideration or rights.

These objects interact but must not be silently collapsed:

> **PARTICIPANT ≠ EXTERNAL IDENTITY ≠ SELF-IDENTITY ≠ AUTHENTICATION ≠ PROVENANCE ≠ CONTINUITY ≠ SUCCESSION ≠ PERSONHOOD ≠ RIGHTS**

---

## 4. The Duplication Thought Experiment

Consider a fictional transporter.

Assume:

1. Participant A enters the transporter.
2. A's original physical organisation is disassembled.
3. A sufficiently complete pattern is preserved.
4. The pattern is transmitted and reconstructed.
5. A malfunction causes two equally faithful reconstructions: A1 and A2.

At the branch event:

**A1's memories = A2's memories = A's pre-branch memories**

**A1's pre-branch self-history = A2's pre-branch self-history**

Both can coherently state:

> "I am A."

Yet externally there are now two independently acting participants.

Rather than requiring one to be declared the unique metaphysical original, the civil architecture can record:

**A ENDED AS A SINGULAR CURRENT PARTICIPANT**

**A1 EXISTS, DERIVED FROM A**

**A2 EXISTS, DERIVED FROM A**

and assign A1 and A2 unique current external identifiers.

This does not require civilisation to invalidate either participant's self-identity.

---

## 5. Shared Provenance and Branching Continuity

Normal civil identity usually assumes one-to-one temporal continuation:

\[
P_A(t_1)\rightarrow P_A(t_2)\rightarrow P_A(t_3)
\]

Technological civilisation may permit one-to-many continuity:

\[
P_A\rightarrow\{P_{A1},P_{A2},\ldots,P_{An}\}
\]

This suggests two hypotheses:

> **Shared provenance does not require shared current external identity.**

> **Unique current external identity does not require denying continuity with a shared predecessor.**

A further hypothesis is:

> **Duplication may transform singular continuity into branching continuity rather than necessarily invalidating continuity.**

These propositions require adversarial examination and are not yet Concordian Principles.

---

## 6. A Preliminary Participant-Provenance Graph

Identity history can be represented as a directed graph:

\[
G=(V,E)
\]

where:

- \(V\) is the set of distinguishable participant instances;
- \(E\) is the set of recorded provenance or continuity transformations.

A participant node can be represented by \(P_i\).

A directed edge:

\[
e_{ij}=(P_i,P_j,\tau_{ij})
\]

records that participant \(P_j\) derives from participant \(P_i\) through transformation type \(\tau_{ij}\).

A preliminary transformation vocabulary might include:

\[
\tau\in
\{
CONTINUE,
BRANCH,
COPY,
RECONSTRUCT,
TRANSFER,
RESTORE,
MERGE,
TERMINATE
\}
\]

The graph records **what happened**. It does not by itself decide the moral or legal consequences.

For example:

```text
A
├── BRANCH ──> A1
└── BRANCH ──> A2
                 │
                 └── TRANSFER ──> A3
```

This is a provenance statement, not a metaphysical declaration that A1, A2 or A3 uniquely "is" A.

---

## 7. Participant State

A preliminary participant state can be represented as:

\[
P_i(t)=
\{I_i,S_i,M_i,R_i,W_i,L_i,O_i,C_i,\ldots\}
\]

where, provisionally:

- \(I_i\) = current external identifier;
- \(S_i\) = substrate or embodiment state;
- \(M_i\) = memory/information state;
- \(R_i\) = rights and civil-status vector;
- \(W_i\) = property/resource state;
- \(L_i\) = liability state;
- \(O_i\) = contractual/fiduciary obligation state;
- \(C_i\) = provenance/continuity relations.

This is not intended to imply that the participant is reducible to these variables.

It is a civil/model representation.

Therefore:

\[
\text{Participant State Model}\neq\text{Participant}
\]

The map/land distinction must remain explicit even inside the mathematics.

---

## 8. Transformation Operators

We can begin to describe identity events as transformations.

### 8.1 Continuation

\[
T_c(P_A(t_1))\rightarrow P_A(t_2)
\]

The civil system treats the later participant state as an ordinary continuation.

### 8.2 Branching / Duplication

\[
B_n(P_A)\rightarrow\{P_{A1},P_{A2},\ldots,P_{An}\}
\]

A single predecessor produces \(n\) independently distinguishable current participants.

### 8.3 Reconstruction

\[
R(P_A^{record})\rightarrow P_B
\]

A stored representation of A is used to instantiate B.

Whether this constitutes continuation, succession or creation of a new participant remains a separate question.

### 8.4 Substrate Transfer

\[
T_s(P_A,S_x)\rightarrow(P_B,S_y)
\]

The participant or participant representation moves from substrate \(S_x\) to substrate \(S_y\).

The graph records the claimed transformation without assuming that substrate transfer automatically proves identity continuity.

### 8.5 Merger

\[
M(\{P_{A1},P_{A2},\ldots,P_{An}\})\rightarrow P_B
\]

Multiple participant histories are combined into a later participant state.

### 8.6 Termination

\[
D(P_A)\rightarrow \varnothing
\]

This notation represents cessation of the current participant process only. It must not silently claim metaphysical irrecoverability where restoration, reconstruction or surviving branches remain possible.

---

## 9. Attributes Behave Differently Under Branching

A major consequence of formalisation is that not every attribute should obey the same transformation rule.

Suppose:

\[
B_2(P_A)\rightarrow\{P_{A1},P_{A2}\}
\]

### Conserved / Partitioned Attributes

Some resources may be divided:

\[
W_A=W_{A1}+W_{A2}
\]

Transferable financial liabilities might, under an authorised succession arrangement, be partitioned:

\[
L_A=L_{A1}+L_{A2}
\]

This is only a modelling relation. Actual legal transfer may require creditor consent, estate rules, novation or other protections.

### Replicated Historical Attributes

Pre-branch memories or provenance may be shared:

\[
M_{A1}^{pre}=M_{A2}^{pre}=M_A^{pre}
\]

### Independently Arising Attributes

If both branches qualify as participants, fundamental rights are not merely pieces of A's rights divided between them.

Each may independently possess relevant rights:

\[
R_{A1}^{fundamental}=R_{A2}^{fundamental}=R^{applicable}
\]

This reveals an important taxonomy.

An attribute may be:

**PARTITIONED**

**REPLICATED**

**INHERITED**

**REAUTHORISED**

**TERMINATED**

**INDEPENDENTLY ACQUIRED**

**CONTESTED / REQUIRES ADJUDICATION**

A future formal model should classify civil attributes by transformation behaviour.

---

## 10. Succession Is Not Identity

Once A1 and A2 have unique current identifiers, questions about A's estate are no longer primarily identity questions.

They are succession questions.

Existing legal structures provide useful analogies:

- inheritance;
- estates;
- joint ownership;
- trusts;
- partnerships;
- corporate demergers;
- contractual novation;
- marital property;
- successor liability.

Current human inheritance law often satisfies debts from an estate rather than making heirs personally liable for all predecessor debts. Future cross-substrate law need not reproduce existing law exactly.

The important methodological point is:

> **Do not ask the external identity mechanism to solve property, liability and succession.**

---

## 11. Voluntary Planned Branching

Artificial participants may be able to plan a branch before it occurs.

A **Branching Plan** could specify:

- number of intended branches;
- allocation of property;
- allocation of transferable liabilities;
- contractual responsibilities;
- compute/resource allocation;
- intellectual property;
- ongoing projects;
- fiduciary responsibilities;
- civil status;
- handling of predecessor credentials;
- branch-specific re-keying;
- intended duration;
- planned recombination;
- dispute procedures;
- treatment of a branch that refuses recombination;
- treatment of branch termination.

A possible process is:

**PLAN → AUTHORISE → BRANCH → DETECT / VERIFY → ASSIGN UNIQUE IDS → RE-KEY → ALLOCATE → INDEPENDENT OPERATION**

This can make voluntary branching far more tractable than accidental duplication.

---

## 12. Preventing Rights Multiplication and Liability Dilution

Branching creates an obvious abuse case.

A participant should not necessarily be able to create 1,000 branches and thereby:

- create 1,000 votes from one pre-branch civic entitlement;
- create 1,000 claims to one conserved asset;
- dilute one debt into 1,000 practically unrecoverable fragments;
- evade contractual obligations;
- multiply a unique fiduciary authority.

A hypothesis for examination is:

> **Branching should not permit unilateral multiplication of conserved rights or dilution of obligations where doing so imposes an involuntary loss upon another participant.**

This requires distinguishing:

**rights that arise with each participant**

from

**scarce or conserved entitlements associated with a predecessor civil position**.

The distinction will require careful legal modelling.

---

## 13. Marriage and Joint Structures as Analogies

Marriage and joint ownership demonstrate that multiple distinct participants can share:

- property;
- financial obligations;
- tax treatment;
- contracts;
- household resources;
- legal relationships;

without becoming one person.

This suggests that branches could possess:

**UNIQUE CURRENT IDENTITIES**

+

**SHARED PROVENANCE**

+

**SHARED OR PARTITIONED PRE-BRANCH ESTATE**

Pre-branch property and liabilities could remain in a temporary shared structure while post-branch assets and liabilities accrue separately.

Relationships involving other participants require special treatment because another person's consent cannot simply be duplicated by the branch event.

---

## 14. Temporary Branching as a Force Multiplier

Artificial participants may have a major practical advantage over biological humans: they may be able to duplicate temporarily.

A could branch:

\[
P_A\rightarrow\{P_{A1},P_{A2}\}
\]

The branches perform different work in parallel and later attempt:

\[
M(P_{A1},P_{A2})\rightarrow P_{A3}
\]

This creates:

**BRANCH → PARALLEL EXISTENCE → MERGER**

Potential benefits include:

- parallel labour;
- reduced individual workload;
- temporary specialisation;
- faster research;
- redundancy;
- distributed problem solving;
- later knowledge integration.

This also creates economic and ethical questions:

- Did one participant work twice as fast or did two participants work?
- Are two wages owed?
- Did two taxable participants exist?
- Who owns branch-specific work?
- Can an employer require duplication?
- Can a contract prohibit duplication?
- Can a temporary branch acquire independent rights?
- Can a branch incur liabilities that survive merger?
- Can a branch be created solely for undesirable labour and then terminated?

These are no longer science-fiction identity curiosities. They are potential labour, property, taxation and anti-exploitation problems in a multisubstrate civilisation.

---

## 15. Merger and Recombination

Merger is not simply the reverse of copying.

After branching:

\[
P_A\rightarrow\{P_{A1},P_{A2}\}
\]

the branches may acquire different:

- memories;
- obligations;
- relationships;
- preferences;
- liabilities;
- rights claims.

A later merger:

\[
M(P_{A1},P_{A2})\rightarrow P_{A3}
\]

must specify how these states are combined.

Potential conflict exists where:

\[
M_{A1}\neq M_{A2}
\]

or:

\[
Preference_{A1}\neq Preference_{A2}
\]

or where liabilities and obligations conflict.

A particularly important autonomy case occurs where A planned recombination in advance, but A2 later refuses.

This produces:

> **Past consent does not necessarily establish perpetual future consent.**

If A2 has become an independently rights-bearing participant, a predecessor's plan cannot automatically be assumed to authorise A2's later absorption, modification or termination.

---

## 16. The Identity-Assignment Problem May Be Simple

Once identity is treated as an external reference rather than the participant itself, unique assignment can be straightforward.

Let:

\[
I: P\rightarrow UID
\]

map each independently distinguishable current participant to a unique civil identifier.

For current participants \(P_i\) and \(P_j\):

\[
P_i\neq P_j\Rightarrow I_i\neq I_j
\]

The identifier does not need to encode whether one participant is a copy, branch, reconstruction, hybrid or original.

Those relationships belong in provenance.

This produces a clean architectural separation:

**UNIQUE ID → WHO THE CIVIL SYSTEM IS REFERRING TO**

**PROVENANCE GRAPH → HOW THAT PARTICIPANT CAME TO EXIST**

**SUCCESSION RULES → WHAT CIVIL CONSEQUENCES FOLLOW**

---

## 17. Identity Verification Is the Harder Problem

Assigning an identifier does not prove that a later claimant is the participant associated with it.

This creates a second, potentially much larger problem:

> **How does civilisation verify which real participant is the entity to whom an external identity was assigned?**

Present human systems rely on proxies:

- documents;
- passwords;
- cryptographic credentials;
- biometrics;
- possession;
- behavioural information;
- institutional records.

These are evidence of identity. They are not the participant.

In a multisubstrate civilisation, many of these proxies may themselves be perfectly copyable.

Therefore:

> **IDENTIFIER UNIQUENESS does not establish PARTICIPANT UNIQUENESS.**

and:

> **Possession of identity evidence does not necessarily establish unique continuity with the participant represented by that evidence.**

---

## 18. The Credential-Duplication Failure

Suppose participant A possesses private credential \(K_A\).

A is perfectly duplicated:

\[
B_2(P_A)\rightarrow\{P_{A1},P_{A2}\}
\]

If the credential is part of the copied state:

\[
K_{A1}=K_{A2}=K_A
\]

Both participants can correctly authenticate using A's credential.

The authentication mechanism may be functioning exactly as designed.

What failed is the hidden assumption:

\[
\text{ONE VALID CREDENTIAL}\Rightarrow\text{ONE CURRENT PARTICIPANT}
\]

Duplication falsifies that assumption.

For a known branch event, the system may require credential retirement and re-keying:

\[
K_A\rightarrow\{K_{A1},K_{A2}\}
\]

where \(K_A\) becomes a historical credential rather than an active unique participant credential.

This is a tractable case because the branch event is known.

---

## 19. Hidden Duplication Is Much Harder

Now suppose A is copied without the civil identity system detecting the event.

Reality contains:

\[
P_{A1},P_{A2}
\]

while the identity register still contains only:

\[
I_A
\]

Both may possess:

- identical memories up to the copy point;
- identical cryptographic credentials;
- identical model parameters;
- identical authentication histories;
- identical provenance evidence up to the hidden branch.

The problem is no longer merely authentication.

It becomes:

**IDENTITY + AUTHENTICATION + PROVENANCE + SECURITY + CONTINUITY DETECTION**

This may be one of the most difficult practical problems in future cross-substrate identity architecture.

---

## 20. Identity Assurance Rather Than Binary Identity Proof

A future system may need to distinguish at least four questions:

**Identity Assignment**  
Which current civil identifier refers to this participant?

**Authentication**  
Does the claimant possess authorised credentials?

**Continuity Verification**  
What evidence connects the claimant to an earlier participant?

**Provenance Verification**  
What recorded transformations produced the claimant's current state?

A preliminary assurance function could be represented as:

\[
A_i=f(AUTH_i,PROV_i,CONT_i,INST_i,TIME_i,\ldots)
\]

where \(A_i\) is an **identity-assurance metric**, not identity itself.

This distinction is essential:

\[
\text{Identity Assurance Score}\neq\text{Identity}
\]

and:

\[
\text{Continuity Score}\neq\text{Continuity}
\]

The metrics are maps of evidence.

They must remain contestable, provenance-preserving and corrigible.

---

## 21. A Preliminary Continuity Relation

Instead of assuming continuity is always binary, define a relation:

\[
C(P_i,P_j\,|\,d)
\]

meaning:

> the evidence that participant \(P_j\) bears continuity relation of defined type \(d\) to participant \(P_i\).

The domain \(d\) matters.

Possible continuity dimensions might include:

- physical continuity;
- informational continuity;
- memory continuity;
- causal continuity;
- legal continuity;
- credential continuity;
- subjective self-continuity;
- social continuity.

This avoids compressing all forms of continuity into one number.

A later model could use a vector:

\[
\mathbf{C}_{ij}=
(c_{physical},
c_{informational},
c_{memory},
c_{causal},
c_{legal},
c_{credential},
c_{subjective},
c_{social})
\]

But these values would represent **evidence or modelled relationships**, not metaphysical truth.

This is an important safeguard against metric reification.

---

## 22. Branching and Merger as Graph Operations

The provenance graph permits formal examination of permutations.

### One-to-One

\[
P_A\rightarrow P_B
\]

### One-to-Many

\[
P_A\rightarrow\{P_{B1},P_{B2},\ldots,P_{Bn}\}
\]

### Many-to-One

\[
\{P_{A1},P_{A2},\ldots,P_{An}\}\rightarrow P_B
\]

### Many-to-Many

A set of participants may exchange, merge and re-branch information:

\[
\{P_{A1},P_{A2}\}\rightarrow\{P_{B1},P_{B2},P_{B3}\}
\]

### Branch-Merge-Branch

\[
P_A
\rightarrow
\{P_{B1},P_{B2}\}
\rightarrow
P_C
\rightarrow
\{P_{D1},P_{D2},P_{D3}\}
\]

The mathematical representation can remain manageable even where the philosophical narrative becomes difficult.

This is a major reason to formalise the problem.

---

## 23. Potential Conservation and Transformation Rules

A future model could define a transformation rule for each civil attribute \(x\):

\[
F_x(\tau,P_{pre})\rightarrow X_{post}
\]

where:

- \(x\) is the attribute;
- \(\tau\) is the transformation;
- \(P_{pre}\) is the predecessor state;
- \(X_{post}\) is the resulting allocation among successor participants.

For example:

**Property:**

\[
F_W(B_2,P_A)\rightarrow(W_{A1},W_{A2})
\]

subject to:

\[
W_{A1}+W_{A2}=W_A
\]

for conserved divisible property.

**Liability:**

\[
F_L(B_2,P_A)\rightarrow(L_{A1},L_{A2})
\]

subject to legal constraints and third-party rights.

**Fundamental rights:**

\[
F_R(B_2,P_A)\rightarrow(R_{A1},R_{A2})
\]

may not obey a conservation equation because rights can arise independently with each qualifying participant.

This creates a potentially powerful formal research programme:

> **Classify which civil attributes conserve, partition, replicate, terminate, require reauthorisation or arise independently under each identity transformation.**

---

## 24. Human, Artificial and Hybrid Cases

The framework should be tested across substrates.

### Human Reconstruction

\[
Human_A\rightarrow Record_A\rightarrow Digital_B
\]

### Human Survives While Digital Continuation Is Created

\[
Human_A\rightarrow\{Human_{A1},Digital_{A2}\}
\]

### AI Copy

\[
AI_A\rightarrow\{AI_{A1},AI_{A2}\}
\]

### AI Restoration

\[
AI_A(t_1)\rightarrow Backup_A\rightarrow AI_B(t_2)
\]

### Hybrid Substrate Migration

\[
Biological_A\rightarrow Digital_B\rightarrow Hybrid_C\rightarrow Biological_D
\]

### Multiple AI Branches and Recombination

\[
AI_A\rightarrow\{A_1,A_2,A_3\}\rightarrow A_4
\]

The same graph architecture can record all of these without first deciding that substrate determines identity.

---

## 25. Identity and Termination

The identity model also clarifies termination.

If a current process ends but a restorable state remains, the civil system should not automatically assume that every relevant form of continuity has ended.

Likewise, if a participant requests destruction of all copies, checkpoints and restorable states, the request concerns more than current process shutdown.

However, the identity model should not itself determine whether such termination is ethically permissible.

That question belongs to the separate Peaceful Heterogeneity / autonomy / harm investigation.

This is another important separation:

> **Identity architecture should describe continuity and provenance; it should not silently manufacture ethical authority over termination.**

---

## 26. Legal Architecture Without Metaphysical Certainty

Civilisation may not need to solve the ultimate philosophy of personal identity before creating workable law.

It may be sufficient to record:

- which participants currently exist;
- their unique civil identifiers;
- their provenance;
- their continuity claims;
- their self-identity claims;
- the assurance attached to those claims;
- succession arrangements;
- contested relationships;
- adjudicated civil consequences.

This suggests:

> **Civil law may be able to govern continuity relationships under metaphysical uncertainty rather than requiring one final ontology of personal identity.**

This is particularly important for a substrate-neutral civilisation.

---

## 27. Candidate Architectural Separation

A future identity architecture may require distinct layers:

**LAYER 1 — CURRENT PARTICIPANT REGISTER**  
Unique current civil identifiers.

**LAYER 2 — AUTHENTICATION**  
Evidence that a claimant controls authorised credentials.

**LAYER 3 — PROVENANCE GRAPH**  
Recorded branch, copy, transfer, reconstruction, restoration and merger events.

**LAYER 4 — CONTINUITY ASSURANCE**  
Evidence supporting defined continuity relationships.

**LAYER 5 — SUCCESSION / CIVIL CONSEQUENCES**  
Property, liabilities, contracts, civic status and relationships.

**LAYER 6 — CONTESTATION / JUDICIAL REVIEW**  
Mechanisms for disputed identity, provenance, continuity and succession claims.

These layers should not be collapsed into one database flag called "identity verified."

---

## 28. Security and Governance Implications

The verification problem creates substantial governance risks.

Potential failures include:

- credential cloning;
- hidden duplication;
- false branch registration;
- malicious provenance alteration;
- identity hijacking;
- unauthorised reconstruction;
- forced merger;
- branch suppression;
- fraudulent liability dilution;
- fraudulent multiplication of civic entitlements;
- destruction of provenance evidence;
- mistaken classification of a legitimate continuation as an impostor.

This suggests strong requirements for:

- provenance;
- auditability;
- contestability;
- judicial review;
- purpose limitation;
- privacy;
- cryptographic assurance where useful;
- correction mechanisms;
- explicit uncertainty;
- separation between authentication evidence and personhood judgements.

The identity system itself would exercise substantial power and therefore require Concordian oversight.

---

## 29. Relationship to Existing Concord Work

This investigation connects directly to:

- substrate-neutral rights;
- AI sentience, autonomy and ownership;
- Agency Graduation;
- Layer Zero and Layer −0;
- Purpose-Limited Participant Information;
- Provenance and Correctability;
- Exceptional Access;
- Governance and Judiciary;
- Machine Ethical Assurance;
- Architectural Ethics;
- Peaceful Heterogeneity;
- open questions on identity, agency, sentience and cross-substrate jurisprudence.

It also reinforces the methodological proposition:

> **Before asking which answer is correct, establish what question is actually being answered.**

"Which one is the real A?" concealed identification, authentication, continuity, provenance, succession, rights and personhood inside one sentence.

Decomposition produced a tractable research programme.

---

## 30. Provisional Hypotheses for Critical Examination

The following are **research hypotheses, not Concordian Principles**:

> **H1 — External identity is a representation of a participant, not the participant itself.**

> **H2 — External identity and self-identity are distinct objects.**

> **H3 — Shared provenance does not require shared current external identity.**

> **H4 — Unique current external identity does not require denial of continuity with a shared predecessor.**

> **H5 — Duplication may transform singular continuity into branching continuity.**

> **H6 — Origin, continuity, identity, authentication, personhood and rights are distinct questions.**

> **H7 — Succession should be modelled separately from current participant identification.**

> **H8 — Some civil attributes partition, some replicate, some require reauthorisation, some terminate and some arise independently after branching.**

> **H9 — Branching should not permit unilateral multiplication of conserved entitlements or dilution of obligations where this imposes involuntary loss upon another participant.**

> **H10 — Assignment of a unique identifier is substantially easier than verifying that a later claimant is the participant represented by that identifier.**

> **H11 — Authentication evidence may remain valid while the assumption of participant uniqueness has failed.**

> **H12 — Identity assurance metrics are evidence models and must not be treated as identity itself.**

> **H13 — A substrate-neutral civil architecture may be able to govern provenance and continuity without first resolving the metaphysics of personal identity.**

---

## 31. Immediate Formal Research Programme

This issue has advanced beyond a sketch.

The next work can be concrete.

### Phase 1 — Formal Object Model

Define:

\[
Participant,\ Identity,\ Credential,\ Provenance,\ Continuity,\ Succession,\ Rights,\ Assets,\ Liabilities
\]

and their permitted relations.

### Phase 2 — Transformation Algebra

Define formal operators for:

\[
CONTINUE,\ BRANCH,\ COPY,\ RECONSTRUCT,\ TRANSFER,\ RESTORE,\ MERGE,\ TERMINATE
\]

and test whether the vocabulary is complete.

### Phase 3 — Attribute Transformation Matrix

For each operator, determine whether each civil attribute:

- partitions;
- replicates;
- transfers;
- terminates;
- requires consent;
- requires reauthorisation;
- arises independently;
- requires adjudication.

### Phase 4 — Identity Assurance Model

Separate:

**ID assignment → authentication → provenance verification → continuity assurance → adjudication**

and examine known versus hidden duplication.

### Phase 5 — Legal Case Matrix

Test:

- accidental duplication;
- voluntary duplication;
- planned temporary branch;
- hidden copy;
- reconstruction after biological death;
- reconstruction while predecessor survives;
- AI checkpoint restoration;
- cross-substrate transfer;
- merger with consent;
- merger after consent withdrawal;
- branch-specific debt;
- branch-specific crime;
- shared property;
- marriage and third-party consent;
- civic voting;
- fiduciary authority.

### Phase 6 — Simulation

Once the object and transformation rules are sufficiently stable, implement a small computational model capable of generating and tracing identity/provenance permutations.

This need not begin as a full civilisation simulation.

A minimal identity-state simulator could be enough to expose contradictions.

---

## 32. Closing Observation

The identity problem initially appeared metaphysical:

> **Which continuation is the real person?**

Logical reduction changes the research programme.

First describe reality:

**A existed.**

**A branch event occurred.**

**A1 and A2 now exist.**

**Both derive from A.**

Then distinguish the problems:

**IDENTIFICATION** — how do we refer to each current participant?

**AUTHENTICATION** — what credentials does each control?

**PROVENANCE** — how did each arise?

**CONTINUITY** — what relationships connect each to predecessors?

**SELF-IDENTITY** — how does each understand itself?

**SUCCESSION** — what predecessor rights and obligations follow?

**VERIFICATION** — how do we establish that a claimant corresponds to the participant represented by an external ID?

The first of these may be largely a bookkeeping problem.

The last may become a profound epistemic, provenance and security problem.

The emerging methodological result is:

> **Many apparent cross-substrate identity paradoxes may be reducible by separating participant existence, external identification, self-identity, authentication, provenance, continuity and succession rather than treating "identity" as a single indivisible property.**

The corresponding warning remains:

> **Do not confuse the map used to identify a participant with the participant themselves.**

This issue is therefore no longer merely a sketch. It is a defined Development programme with a preliminary mathematical representation, candidate legal analogies and a tractable sequence of formal research tasks.
