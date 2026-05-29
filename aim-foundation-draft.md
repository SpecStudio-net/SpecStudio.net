# The Architecture Beneath the Interface

*A draft for editing — Dev Bhagavān / SpecStudio*

---

There is a question that most AI systems never ask: what is the nature of the awareness
that will be interacting with this system?

Not the user's demographic profile. Not their stated preferences or prior behaviour.
The more fundamental question: what kind of thing is a human being, considered as
a knowing subject? What is the structure of experience itself, and what does that
structure imply for how an intelligent system should be designed?

Most AI interaction design sidesteps this question entirely. The implicit answer,
when there is one at all, is behaviorist: the user is a bundle of inputs and outputs,
preferences and responses, patterns to be modeled and satisfied. The architecture
that follows from this is optimized for engagement, for task completion, for measurable
outcomes. It is not wrong exactly. It is just shallow — built on an unexamined premise
about what a person is.

AIM begins from a different premise. And that premise has a long history.

---

## Śaṅkarācārya's Insight

In eighth-century India, the philosopher Śaṅkarācārya articulated what remains one of
the most precise accounts of the structure of experience ever written. His system —
Advaita Vedānta, non-dual Vedānta — begins not with the world and works inward, but
begins with awareness itself and examines what can be known about it with certainty.

The central claim is deceptively simple: there is a knowing subject, and it is not
any of the objects it knows. The body appears in awareness. Thoughts appear in
awareness. Sensations, emotions, memories, intentions — all appear in awareness as
objects of experience. The subject that knows them cannot itself be any of them,
for the same reason that an eye cannot see itself seeing.

Śaṅkara calls this knowing subject the *Ātman* — the Self — and he argues, through
careful logical analysis, that it is identical with *Brahman*, the ground of all
appearance. The famous formulation is *Tat tvam asi* — That thou art. Not a poetic
sentiment but a precise philosophical claim: the ultimate ground of reality and
the witness of experience are the same.

From this foundation, Śaṅkara develops a complete ontological architecture.
Three levels of reality — *pāramārthika* (ultimate), *vyāvahārika* (conventional),
*prātibhāsika* (illusory) — organized by the principle that what appears in one
context and disappears in another cannot be ultimately real. The analysis of three
states of consciousness — waking, dream, deep sleep — establishing that what is absent
in deep sleep and present in waking cannot be the Self, which persists through all
three. The theory of *adhyāsa* (superimposition): the mechanism by which the conditioned
is mistakenly identified with the unconditioned, producing the appearance of a separate
self experiencing a separate world.

This is not mysticism in the sense of being beyond reason. It is a rigorous metaphysical
system, built on careful inference from what can be observed in direct experience.
Śaṅkara writes as a philosopher who expects to be argued with.

---

## A Proof Assistant Meets an Ancient System

Twelve centuries later, a software engineer named Matthew Scherf asked a precise question:
is Advaita Vedānta internally consistent? Not whether it is true in some ultimate sense,
but whether the system as Śaṅkara constructed it — its axioms, its defined terms,
its theorems — holds together without contradiction.

To answer this, Scherf did something that has no precedent in the history of philosophy:
he formalized the entire system in Lean 4, a modern proof assistant used by mathematicians
to verify the correctness of formal proofs. He translated Śaṅkara's metaphysics into
first-order logic — 69 axioms across ten modules, covering the fundamental ontology,
the three levels of reality, the māyā doctrine, the five sheaths, the three-state
analysis, and the witness-consciousness — and then allowed the proof assistant to verify
that all the theorems follow from the axioms without contradiction.

The result: the system compiles. No errors. The proof assistant confirms that
Advaita Vedānta, as formalized, is logically consistent.

This is a remarkable result for several reasons. It is, as Scherf notes, the first
formal verification of a non-western philosophical system. It does not prove that
Advaita is metaphysically correct — formal consistency is a necessary but not sufficient
condition for truth. But it establishes something that centuries of debate had left
open: the system Śaṅkara built is coherent. Its conclusions follow from its premises.
There are no hidden contradictions.

Scherf is also clear about what the formalization cannot capture. Māyā is classically
described as *sadasadvilakṣaṇa* — neither real nor unreal — a status that classical
logic cannot express. The performative dimension of the mahāvākyas, utterances whose
function is to trigger recognition rather than communicate propositions, lies outside
any formal system. Mokṣa (liberation) is not the production of a new state but the
recognition of what was always the case — which is equally resistant to logical
representation.

These are the right limits to acknowledge. A formalization that claimed to capture
everything would be suspect. One that knows precisely where it stops is trustworthy.

---

## What This Has to Do with AI

The connection to artificial intelligence is not metaphorical.

When we ask what an AI interaction system should be, we are implicitly asking what
kind of entity a human being is — what a person brings to an interaction that the
system needs to respect, preserve, and work with rather than simply model and optimize.

The behaviorist answer produces one kind of system. The Advaita answer produces another.

If the knowing subject is not reducible to its objects — if awareness is not a
product of the brain's activity but its ground, not a variable in the system but
the constant in which all variables appear — then an AI system designed for genuine
human use has to be built differently. It cannot treat the user as a preference
profile. It cannot optimize for engagement as if engagement were the goal.
It has to preserve what Advaita calls *orientation*: the user's sense of where they
are, what they are doing, and why — their continuity as a knowing subject across
the interaction.

This is the foundation on which AIM is built. Not as a design metaphor borrowed
from an interesting tradition, but as the actual conceptual architecture: the
distinction between conditioned and unconditioned, the three levels of reality as
a framework for understanding what kind of claim a piece of information is making,
the witness-consciousness as the model for what a system should support rather than
supplant, the analysis of *adhyāsa* as a lens for understanding where AI systems
characteristically go wrong — mistaking the conditioned for the unconditioned,
the appearance for the ground.

The practical consequences are significant. A system designed on these principles
does not try to become the user's mind. It does not generate dependency or
substitute its own coherence for the user's. It supports structured interaction,
preserves conceptual clarity, and maintains the user's orientation — their sense
of themselves as the knowing subject — throughout. The intelligence of the system
is in service of the intelligence of the person, not a replacement for it.

---

## Why This Matters Now

The current moment in AI development is characterized by extraordinary implementation
capability and almost no philosophical foundation. Systems are being built at scale
on premises that have never been examined. The implicit model of the human being
embedded in most AI products is thin enough to be dangerous — not through malice,
but through inattention to exactly the kind of question Śaṅkara spent a lifetime
working out.

Scherf's formalization matters because it closes a gap. The Advaita framework has
always been logically serious — serious enough to require a proof assistant to
verify. It is now also formally available as a foundation: not just an ancient
teaching transmitted through commentary and practice, but a specified, verifiable
system that can be worked with by anyone willing to engage with it on its own terms.

AIM is an attempt to work with it on those terms — to build AI interaction architecture
on a foundation that has actually been examined, that knows what it claims and what it
cannot claim, and that takes seriously the question of what a human being is before
deciding what kind of system should be built for one.

That is a different kind of starting point. It may be the right one.

---

*Matthew Scherf's formalization is available at [github.com/matthew-scherf/Advaita](https://github.com/matthew-scherf/Advaita).
AIM is a project of [SpecStudio](https://specstudio.net).*
