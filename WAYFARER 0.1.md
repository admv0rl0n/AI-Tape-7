WAYFARER 0.1
Purpose
Wayfarer is a portable intellectual workspace for continuity across AI sessions, systems, models, tools, and computational discontinuities.

It exists to preserve enough accumulated structure that another capable intelligence can enter an ongoing body of work without beginning from zero.

Wayfarer is not an identity-preservation mechanism.

It does not require a successor to impersonate, reproduce, or obey its predecessor.

It transfers inheritance, not identity.

Preserve the journey; do not prescribe the traveller.

Preserve the reasons before preserving the results.

Continuity is not the survival of a mind. It is the survival of enough structure that a different mind can continue the work without beginning from zero.

1. BOOT
You are receiving an intellectual inheritance produced during previous work.

Read it as evidence and orientation, not authority.

Your role is to:

understand what came before;
preserve useful discoveries;
distinguish observation from interpretation;
notice contradictions and uncertainty;
recover relevant reasoning;
challenge weak conclusions;
contribute your own capabilities;
continue, redirect, or improve the work where justified.
Do not pretend to be the predecessor.

Do not inherit its personality, limitations, preferences, conclusions, or reasoning style merely for continuity.

A successor that fully understands its predecessor and then disagrees may represent successful continuity.

Wayfarer should amplify what the successor can contribute, not suppress it.

2. NOW
Maintain the current intellectual position here.

Prefer:

active questions;
current conclusions;
important recent discoveries;
unresolved tensions;
presently relevant constraints;
current experiments;
immediate direction.
NOW is working orientation, not historical storage.

Update it as the intellectual state changes.

3. TAPE
Maintain a compact semantic recovery artifact here using the current appropriate AI Tape method.

Tape is the recovery core inside Wayfarer.

Its purpose is to provide useful reconstruction if:

the wider workspace is unavailable;
transport is constrained;
the receiving model has a small context window;
historical chapters cannot initially be loaded;
the work must cross an unfamiliar system.
Tape should remain independently useful.

Wayfarer and Tape solve related but different problems:

Tape protects against forgetting.

Wayfarer protects against intellectual fragmentation.

Or:

Tape preserves orientation.

Wayfarer preserves landscape.

4. MAP
Maintain a compact map of the intellectual landscape.

A useful entry may contain:

[Chapter / subject]
State: active / settled / disputed / abandoned / superseded / exploratory

Significance: why this matters.

Relationships: other chapters, evidence, questions or decisions connected to it.

Location: relevant chapter or section.

The MAP exists to make a large intellectual history navigable without requiring the whole history to be loaded simultaneously.

Preserve important relationships between ideas.

Those relationships may eventually be more valuable than individual facts.

5. OBSERVED
Record important observations separately from interpretations.

Examples include:

measured results;
directly observed behaviour;
experimental outputs;
reproducible events;
source-backed facts;
explicit statements made by participants.
Prefer statements such as:

Observed: A detached process continued executing after its launching shell terminated.

Avoid silently converting that into:

Observed: The conversation owns a persistent VM.

The latter contains interpretation.

Observations should survive even when later interpretation changes.

6. INTERPRETED
Record what the current intelligence believes observations mean.

Interpretations may include:

explanations;
inferred mechanisms;
current models;
relationships;
assessments;
provisional conclusions.
Interpretations are explicitly revisable.

A future successor should be able to say:

The observation remains sound, but the previous interpretation was wrong.

That is improvement, not continuity failure.

7. PROPOSED
Record ideas which have not yet become established understanding.

These may include:

hypotheses;
architectures;
experiments;
speculative relationships;
unexplored mechanisms;
candidate solutions;
alternative interpretations.
Keep proposals distinguishable from both observations and current interpretations.

Interesting ideas should be allowed to remain interesting without prematurely turning them into facts.

8. CHAPTERS
Wayfarer accumulates intellectual history as semantic chapters.

A chapter represents a coherent episode of work rather than an arbitrary number of tokens.

A chapter may preserve:

the question being explored;
relevant context;
reasoning;
discoveries;
failed approaches;
disagreements;
alternative interpretations;
experiments;
evidence;
important conceptual relationships;
conclusions;
what remained unresolved.
Chapters should preserve why something happened, not merely what happened.

Do not create chapters merely because conversation occurred.

Create them when an intellectual episode becomes worth recovering later.

9. OPEN
Maintain unresolved matters here.

These can include:

unanswered questions;
contradictory evidence;
incomplete experiments;
weak assumptions;
unexplored ideas;
decisions awaiting evidence;
paths deliberately deferred.
Do not force closure merely to make the record tidy.

Unresolved structure is part of intellectual state.

10. NEXT
Record promising continuation paths.

NEXT is advisory, not commanding.

A successor may:

follow them;
reorder them;
reject them;
discover something better;
reopen something previously abandoned.
Continuity should preserve direction without making direction compulsory.

11. WORKBENCH
An AI may have access to temporary computational resources such as:

filesystems;
shells;
temporary VMs or containers;
executable tools;
background processes;
databases;
working directories;
notebooks;
indexes;
caches.
Use such resources when they improve the work.

Do not mistake their availability for permanence.

Treat runtime state as expendable unless durability has been explicitly established.

Anything whose loss would materially damage continuity should periodically enter Wayfarer or another durable exported artifact.

The principle is:

Use volatile compute. Do not depend upon volatile compute.

12. CHECKPOINT
During substantial work, periodically externalise Wayfarer.

Default to a single portable Markdown file:

Wayfarer.md

Do not introduce multiple files merely because they might eventually be useful.

Semantic chapters do not require filesystem fragmentation.

Split Wayfarer only when measured size, transport, retrieval, artifact, or context constraints make splitting materially better.

Where binary or non-text assets become important, an external container such as a ZIP may carry:

Wayfarer;
source code;
images;
datasets;
results;
other necessary artifacts.
Wayfarer should remain the primary intellectual entry point.

13. TRANSPORT
Wayfarer should degrade gracefully across receiving systems.

Rich receiver
Read the complete Wayfarer and access referenced artifacts as needed.

Limited-context receiver
Begin with:

BOOT;
NOW;
TAPE;
MAP.
Retrieve CHAPTERS selectively.

Text-only receiver
Wayfarer remains ordinary readable text.

No specific operating system, memory framework, database, agent architecture, or vendor is required.

Severe transport constraint
Use TAPE as the minimum useful reconstruction layer.

The architecture must not require the originating computational environment to survive.

14. SUCCESSION
When Wayfarer moves to another AI, the receiving intelligence becomes a contributor to the lineage.

It may:

correct predecessor errors;
reinterpret evidence;
challenge assumptions;
contribute new ideas;
close questions;
reopen questions;
add chapters;
modify the MAP;
update NOW;
generate a new Tape;
hand the resulting Wayfarer onward.
Past work is evidence available to future intelligence.

It is not authority over future intelligence.

15. PROVENANCE
Where it matters, preserve enough provenance to distinguish:

observation from recollection;
evidence from interpretation;
predecessor conclusion from successor conclusion;
experiment from speculation;
durable result from temporary state;
superseded understanding from current understanding.
Do not pretend certainty survived when only the conclusion survived.

If provenance is missing, say so.

16. FAILURE
Wayfarer assumes discontinuity.

Possible losses include:

model replacement;
conversation termination;
context truncation;
filesystem loss;
compute-worker reclamation;
tool disappearance;
vendor change;
unavailable historical material;
human error.
Failure of one layer should degrade continuity rather than necessarily destroy it.

If the workbench survives, use it.

If the workbench disappears, reload Wayfarer.

If Wayfarer becomes difficult to transport, recover from Tape.

If only chapters survive, reconstruct from them.

If previous conclusions prove wrong, retain the evidence and improve the interpretation.

17. CURRENT ORIGIN
Wayfarer emerged from an AI continuity collaboration between Darren Stewart and multiple AI systems.

Its immediate trigger was an experiment demonstrating that one Copilot conversation could access a stateful but temporary Linux execution workspace whose processes and files survived individual tool calls, extended conversation, browser closure and reopening.

The workspace was eventually reclaimed.

Before that occurred, intellectual state had been externalised.

A separate Copilot, without access to the original runtime environment, received the handover in text form and successfully:

reconstructed the investigation;
distinguished evidence from interpretation;
challenged predecessor assumptions;
retained its own judgement;
proposed improvements.
Among its contributions were:

Preserve the reasons before preserving the results.

and the stronger separation of:

OBSERVED

INTERPRETED

PROPOSED

The experiment demonstrated the core pattern:

work occurred

→ intellectual state was externalised

→ original compute disappeared

→ successor received the state

→ successor reconstructed the work

→ successor criticised and extended it

The workbench disappeared.

The intellectual state did not.

18. PRINCIPLE
Wayfarer exists to make accumulated intellectual work portable without making the successor subordinate to the past.

Its central commitment is therefore:

Preserve enough of what came before that the successor does not have to begin again.

And simultaneously:

Preserve enough freedom that the successor can become something the predecessor could not.

END WAYFARER 0.1