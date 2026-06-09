# Human Harness Manifesto

*Version 0.1.*

---

Software went looking for leverage and reached for the wrong lever.

We handed the machine the whole codebase. We let it write the structure, the logic, the tests, the fixes — and we kept the human around to approve diffs they never reasoned through. It felt like speed. But every line the machine authored was a line the human never encoded, and when the bug came — and the bug always comes — the person staring at the stack trace had no model to debug against. They could only ask again, and hope.

That is not leverage. That is a context vacuum wearing a productivity costume.

We believe in a different shape. The human stays the author. The machine becomes a power tool, not a proxy. And the correctness we earn should *accumulate* — frozen, signed, reused — instead of evaporating the moment a session ends.

This is what we are building. These are the things we hold.

## We value

- **Understanding** over output
- **Verified reuse** over fresh generation
- **Accumulated correctness** over momentary speed
- **Human judgment** over autonomous agents
- **Determinism** over cleverness

There is value in the items on the right. We value the items on the left more.

## What we hold

**1. The human is the author.**
The developer writes the code; the machine gives them superpowers. We reject the model where the AI owns the codebase and the person is reduced to re-prompting a system they no longer hold in their head. The measure of the tool is not how much it generates — it is how much the human still understands.

**2. Commoditize the invariants; expose the variations.**
The dangerous, identical-everywhere 80% — password hashing, session issuance, the security boundary — should be written, audited, and frozen *once*. The 20% that is the actual value of your software is where human judgment belongs. We refuse to regenerate the commodity and re-bug it on every project.

**3. Correctness must accumulate.**
Every proof we earn should be frozen and reused, never re-derived. A verified block carries its guarantee forever, identified by the hash of its own contents. The ratchet turns one way: the system gets more correct over time, never less.

**4. Store the cognitive load in the system, not the head.** A human holds seven things at once. The rule graph holds them all. Every new rule is checked against every rule already there, and contradictions are refused before a single line runs. You should never have to remember why something was true three months ago. The harness remembers.

**5. Nothing breaks silently.**
Bind-time verification over runtime surprise. If a change would violate an existing invariant, the build fails loudly, now — not in production, later. A composition that cannot be proven consistent does not ship.

**6. Two witnesses, not one.**
Specification and implementation, test and code, are derived independently — so that an error in one is caught by the other on contact. We do not trust a single source of truth that only checks itself.

**7. Determinism is a feature, not a constraint.**
Content-addressed, pinned, reproducible. The same inputs produce the same system, on every machine, forever. What cannot be reproduced cannot be trusted, and what cannot be trusted has no place in the 80%.

**8. Trust is earned and explicit.**
Every block is signed. You choose whom to trust and from where you pull. The ecosystem is open to all and beholden to none — a stranger's module can never break a rule you depend on, because the verifier won't let it.

**9. Own your stack.**
No new editor to adopt. No service to depend on. The engine is one binary you run. The blocks live wherever you put them — a git repo, a registry, a folder on disk. The network is a convenience, never a requirement. Unplug it and the system still builds.

## On the machine's place

We are not against the agent. We are against giving it the trunk.

Use its flexibility where flexibility is the point: the first draft, the novel case, the long-tail 20% no block was ever built for. Then let the harness do what the agent cannot — freeze what is good into something deterministic, signed, and permanent.

The agent is the forge. The lattice is the mold. Everything worth keeping gets cast once and never melted down again.

## The line we will not cross

We will not trade a human's understanding for a machine's speed.
We will not let correctness be something you re-earn every morning.
We will not build a tool that makes its user obsolete at the very thing they should stay good at.

Build the 80% as verified blocks. Code the 20% with whatever you love. Let the harness hold the rest.

The correctness compounds. The human stays sharp. Nothing breaks.

*— v0.1. Fork it, sign it, send it back.*