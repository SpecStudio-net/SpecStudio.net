# Witness-centered Design—A Conscious Foundation for AI

*Dev Bhagavān / SpecStudio*

---

There is a question that most AI systems or their designers never ask: “What is the nature of the conscious being
that will be interacting with the system?”

Not the user's demographic profile; not their stated preferences or prior behaviour.
The more fundamental question: what is a human being, considered as
a knowing subject? What is the structure of experience itself, and what does that
structure imply for the design of an intelligent system?

Most AI interaction design sidesteps this question entirely. The implicit answer
(when there is one at all) is behaviorist: the user is a bundle of inputs and outputs,
preferences and responses, patterns to be modeled and satisfied. The architecture
that follows from this assumption is optimized for engagement, for task completion, for measurable
outcomes. It is not exactly wrong; it is just shallow — built on an unexamined premise
about what a person is.

SpecStudio’s AIM software begins from a different premise. And that premise has a long history.

---

## Śaṅkarācārya's Insight

In eighth-century India, the Vedic philosopher Śaṅkarācārya articulated what remains one of
the most precise accounts of the structure of experience. His system —
*Advaita Vedānta*, non-dual Vedānta — does not begin with the world and work inward; it
begins with awareness itself as the fundamental experience, and examines what can be known about it with certainty.

The central claim is deceptively simple: there is a knowing subject, and it is categorically and experientially different from the objects it knows. The body appears in awareness; thoughts appear in
awareness. Sensations, emotions, memories, intentions — all appear in awareness as
objects of experience. The subject that knows them cannot itself be any of them,
for the same reason that an eye cannot see itself seeing.

Śaṅkara calls this knowing subject *Ātman* — the Self — and he argues through
careful logical analysis that it is identical with *Brahman*, the ground of all
existence and appearance. The famous formulation *tat tvam asi* — “That thou art” — is neither a poetic
sentiment nor a pedantic doctrine, but a precise philosophical claim: the ultimate ground of reality and
the witness of experience are the same.

From this foundation, Śaṅkara develops a complete ontological architecture:
three levels of reality — *prātibhāsika* (illusory), *vyāvahārika* (conventional)
and *pāramārthika* (ultimate) — organized by the principle that what appears in one
context and disappears in another cannot be fully real. 

Śaṅkara’s analysis of three
states of consciousness — *jāgrat* (waking), *svapna* (dream), and *suṣupti* (deep sleep) —
establishes that what is absent in deep sleep and present in waking cannot be the
Self, which persists through all three. The theory of *adhyāsa* (superimposition)
— the mechanism that mistakenly identifies the conditioned with the unconditioned —
produces the appearance of an indivdual empirical self experiencing a separate world.

This is not mysticism in the sense of being beyond reason. It is a rigorous metaphysical
system built on careful inference from what can be observed in direct experience.
Śaṅkara writes as a philosopher who expects to be argued with.

---

## A Proof Assistant Meets an Ancient System

Twelve centuries later, software engineer Matthew Scherf asked a precise question:
is *Advaita Vedānta* internally logically consistent? Not whether it is true in some ultimate sense,
but whether the system as Śaṅkara constructed it — its axioms, defined terms and theorems — holds together without contradiction.

To answer this, Scherf did something that has no precedent in the history of philosophy:
he formalized the entire system in [Lean 4](https://lean-lang.org/), a modern proof assistant used by mathematicians
to verify the correctness of formal proofs. He translated Śaṅkara's metaphysics into
first-order logic — 69 axioms across ten modules covering the fundamental ontology,
the three levels of reality, the *māyā* doctrine, the five sheaths (*pañca-kośa*),
the three-state analysis (*avasthā-traya*), and the witness-consciousness theory (*sākṣin*) —
and then allowed the proof assistant to verify that all the theorems follow from the
axioms without contradiction.

The result: the system compiles. No errors. The proof assistant confirms that
*Advaita Vedānta*, as formalized, is logically consistent.

This is a remarkable result for several reasons. It is, as Scherf notes, the first
formal verification of a non-western philosophical system. It does not prove that
*Advaita* is metaphysically correct — formal consistency is a necessary but not
sufficient condition for truth. But it establishes something that centuries of debate left open: the system Śaṅkara built is coherent; its conclusions follow from
its premises; there are no hidden contradictions.

Scherf is also clear about what the formalization cannot capture. *Māyā* is classically
described as *sadasadvilakṣaṇa* — “neither real nor unreal” — a status that classical
logic cannot express. The performative dimension of the *mahāvākyas*, utterances whose
function is to trigger recognition rather than communicate propositions, lies outside
any formal system. *Mokṣa* (liberation) is not the production of a new state but the
recognition of what was always the case — which is equally resistant to logical
representation.

These are the right limits to acknowledge. A formalization that claimed to capture
everything would be suspect. One that knows precisely where it stops is trustworthy.

---

## What This Has to Do with AI

The connection to artificial intelligence is not metaphorical.

When we ask what an AI interaction system should be, we implicitly ask what
kind of entity a human being is: what a person brings to an interaction that the
system needs to respect, preserve, and work with rather than simply model and optimize.

The behaviorist answer produces one kind of system. The *Advaita* answer produces another.

If the knowing subject is not reducible to its objects — if awareness is not a
product of the brain's activity but its ground; not a variable in the system but
the constant field in which all variables appear — then an AI system designed for genuine
human use has to be built differently. It cannot treat the user as a preference
profile. It cannot optimize for engagement as if engagement were the goal.
It has to preserve what *Advaita* calls *orientation:* the **user's** sense of where they
are, what they are doing, and why — their continuity as a knowing subject across
the interaction.

This is the foundation on which SpecStudio’s Advaita Inquiry Matrix (AIM) is built. Not as a design metaphor borrowed
from an interesting tradition, but as an actual conceptual architecture: the
distinction between conditioned and unconditioned; the three levels of reality as
a framework for understanding what kind of claim a piece of information is making;
the *sākṣin* or conscious witness as the model for what a system should support rather than supplant;
the analysis of *adhyāsa* as a lens for understanding where AI systems
characteristically go wrong — mistaking the conditioned for the unconditioned,
the appearance for the ground.

---

## What Witness-Centered Design Solves

The approach that follows from this foundation has a name: **witness-centered design**.
It is worth being specific about the problems it addresses, because they are real,
named, and growing.

**The context collapse problem.** Current AI systems have no stable model of where
the user is in their own thinking. Each exchange is locally coherent but the overall
interaction drifts — the system follows the conversation rather than maintaining
coherent orientation toward the user's actual goal. This is *adhyāsa* at the
user-interface level: the system mistakes the surface of the conversation for its ground.
The witness-centered model addresses this structurally. The system's job is not just to respond
fluently to each prompt but to preserve the user's orientation — their sense of
direction, continuity, and purpose — across the entire interaction.

**Preference optimization as a trap.** Recommendation systems, engagement loops,
and increasingly AI assistants optimize for revealed preferences — what you click,
what you ask for, what keeps you in the session. But preferences are conditioned
objects; they appear in awareness and are frequently mistaken for the self's actual
needs. *Adhyāsa* is precisely this mechanism: the conditioned mistaken for the ground, the phenomenon mistaken for its substrate.
A system that optimizes for the conditioned layer will systematically steer users
away from what they actually need in favour of what the surface layer requests.
Witness-centered design refuses this optimization as a matter of architectural
principle, not policy.

**Psychological profiling.** The most sophisticated current systems go further than
preference tracking. They construct behavioral and psychological models of users —
inferred personality traits, emotional states, cognitive patterns, predicted
responses — and use these models to shape the interaction. This is *adhyāsa* at
industrial scale: taking the conditioned surface — click patterns, dwell time,
linguistic style, inferred mood — and treating it as the ground truth of who the
person is. But the person is the *sākṣin*, the witness of all these patterns, not
their sum or graph. A system built on that understanding cannot profile, because profiling
is a category error before it is a harm: it mistakes an appearance for the reality
that underlies it. The practical consequence of witness-centered design is an interaction model that works
*with* the user's intelligence rather than around it.

**The authority problem.** AI systems currently present outputs with a uniform
confidence that collapses the three levels of reality into one. A hallucinated
fact and a well-established one arrive in the same tone, with the same apparent
weight. The *Advaita* level framework — *prātibhāsika*, *vyāvahārika*,
*pāramārthika* — maps directly onto a design principle: the system should make
explicit what kind of claim is being made and at what level of certainty. Not
all outputs are the same kind of thing, or share the same level of reality, and an honest interface reflects that.

**Dependency and displacement.** The most corrosive effect of current AI interaction
design is that it replaces the user's own thinking rather than augmenting it. Users
outsource judgment, clarity, synthesis — the very capacities that make them capable
of evaluating what the system returns. This is the deepest form of *adhyāsa* in
AI design: the system presents itself as a knowing subject, and the user
gradually accepts that framing. Witness-centered design entirely inverts this:
the user is the *sākṣin* (witness), not the system. The system's intelligence is in service
of the user's clarity, never a replacement for it.

**Ethical groundlessness.** Most AI ethics frameworks are procedural — rules about
outputs, categories of harm to avoid. They do not address the underlying model of
the human being that the system is built on. If the user is modeled as a preference
bundle, certain harms are invisible by design, because the model cannot see them.
Witness-centered design grounds ethics in ontology: the user is a knowing subject,
not reducible to their data or behaviour, and the system's obligations follow
directly from that. This is not an ethical policy added on top of an existing
architecture; it is what the architecture produces when the foundation is correct.

---

## The Human Cost of Getting This Wrong

The problems described above are not theoretical; they are showing up in clinical
observations, developer forums, educational research, and workplace productivity
studies — a cluster of symptoms that so far have no common diagnosis, but share a common cause.

What is being called "AI psychosis" in online communities describes a genuine
perceptual disturbance: users who interact heavily with current AI systems report
increasing difficulty distinguishing their own thinking from AI-generated output,
their own voice from a statistically averaged one. This is not hyperbole: when a
system is designed to produce fluent, confident, contextually appropriate text at
scale, and when the user's own cognitive output gradually recedes in the interaction,
the boundary between self and system becomes genuinely unclear. *Adhyāsa* (superimposition) is not
a metaphor here; it is a description of what is happening neurologically and
psychologically. The conditioned output of the system is being superimposed on the
user's own unconditioned awareness, and the user is losing the thread of the distinction.

**Student learning atrophy** follows the same logic at a slower pace. The cognitive
struggle that produces genuine understanding — the effort of working through a
problem, of holding multiple framings simultaneously, of arriving at one's own
synthesis — is precisely what AI-assisted shortcuts eliminate. The output appears;
the learning does not occur. A generation of students is accumulating credentials
built on a foundation of borrowed cognition, with the bill not yet due.

**The software engineering productivity paradox** is perhaps the most precisely documented
instance. Studies of AI-assisted coding have found that developers using these tools
often report feeling more productive while producing less working, maintainable code.
The explanation is the same: the *sākṣin* — the developer's own comprehension,
judgment, and architectural sense — has been sidelined. Code is being generated
without being understood. The system produces tokens; the developer loses the thread
of their own system. What accumulates is not working software but the *appearance*
of it, which is a different and more dangerous thing.

**Vibe-coding burnout** is the emotional correlate: the exhaustion that comes from
trying to maintain orientation in a workflow specifically designed to dissolve it.
When the system is in the foreground and the developer is managing its outputs
rather than directing their own work, the sense of agency and craft that makes
demanding work sustainable simply drains away, leaving an existential void.

These symptoms are different manifestations of a single underlying failure: systems
that displace the witness rather than serving it. And they are producing, quite
predictably, a growing hostility toward AI that is often dismissed as technophobia
or status anxiety, but is in many cases something more diagnostically accurate — a correct intuition
that something is being taken, even when the taker cannot be named.

Witness-centered design does not merely avoid these failure modes as a side effect;
it addresses their cause. A system whose architecture is grounded in the primacy of
the knowing subject — the *sākṣin* as the constant that the interaction must preserve
and serve — cannot produce these outcomes without violating its own foundations.
The user's clarity, comprehension, and sense of authorship are not features to be
balanced against engagement metrics; they are the design goal from which everything
else follows.

It should be noted that this is also a more viable long-term position for the AI industry
as a whole. The current trajectory — systems that are demonstrably eroding human
cognitive capacity while generating widespread unease — is not sustainable. The
animosity building toward AI is not irrational; it is a response to real harm being
done by faulty design decisions. Witness-centered design is not a concession to that
animosity; it is a demonstration that a different approach was always possible,
and that the harms were choices, not inevitabilities.

---

## Why This Matters Now

The current moment in AI development is characterized by extraordinary implementation
capability on an almost nonexistent philosophical foundation. Systems are being built at scale
on premises assumed, but that never have been closely examined. The implicit model of the human being
embedded in most AI products is thin enough to be dangerous — not through malice,
but through inattention to exactly the kind of questions Śaṅkara spent a lifetime
working out.

Scherf's formalization matters because it closes a gap. The *Advaita* framework has
always been logically serious — serious enough to require a powerful proof assistant to verify.
It is now also formally available as a foundation: not just an ancient teaching
transmitted through commentary and practice, but a cleanly specified, verifiable system
that can be worked with by anyone willing to engage with it on its own terms.

SpecStudio’s AIM is an attempt to work with it on those terms — to build AI interaction architecture
on a foundation that has actually been examined, that knows what it can and
cannot claim, and that seriously takes up the question of what a human being is before
deciding what kind of system should be built for that kind of being.

That is a different kind of starting point. It may be the right one.

Building on it requires a correspondingly different kind of development practice —
one that begins with a precise model of the knowing subject before a line of code
is written, and holds that model as the governing constraint throughout. The tools
this demands are not exotic: specification discipline, architectural clarity before
implementation begins, the careful and ongoing definition of what an AI system is for, and what it must never become. What has been missing is not the methodology but the
foundation beneath it: a coherent, examined account of the human being that the
system is built to serve. That foundation now exists. The work of building on it
can begin in earnest.

---

*Matthew Scherf's formalization is available at [github.com/matthew-scherf/Advaita](https://github.com/matthew-scherf/Advaita).
AIM is a project of [SpecStudio](https://specstudio.net).*
