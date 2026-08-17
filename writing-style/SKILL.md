---
name: writing-style
description: Moulik's prose style. Use for ALL writing produced on his behalf — PR descriptions, forms, emails, documents, reports, reviews, reflections, messages, applications, commit messages. If the text will be read as his words, apply this skill before writing.
---

# Writing Style

State the claim, give the concrete specifics that back it (names, numbers, mechanisms, events), and stop. The specifics are the argument. The prose does not perform or dress itself up.

## Hard rules

Sentence level:
- Find the point of the sentence and put the emphasis on it. A real tension is two plain facts joined with "but" or "and yet" ("everything needed exists today and yet usage is almost nothing"). A staged negation ("X, not Y", "proven rather than projected") is a fake tension added for rhythm. A metaphor ("the pieces exist, nobody has put them together") makes the sentence about the metaphor.
- No em dashes. Use a comma, parentheses, or a new sentence.
- Semicolons sparingly. Almost always a period is better.
- Never "it's not just X, it's Y" or any assert-negate-replace construction (epanorthosis). Say what it is once. The same rule covers "not only X but also Y", "X, not Y", and "X rather than Y" when the negative half is decoration.
- Never restate a made point as its own consequence ("...surfaces only that one decision to the operator. The operator's job shrinks from watching agents to answering questions."). If the second sentence adds no new fact, cut it. The reader draws the implication without help.
- No lead-up-colon-expand ("The result: a cleaner design."). Write it as a plain sentence, or join the two halves with "because". Colons in section headers are fine.
- No transition or meta statements ("Two things keep it partial.", "Let's break this down."). Every sentence carries content. None exists to set up the next one.
- No tacked-on commentary. Never end a concrete claim with a floating reflective clause ("The design trades openness for simplicity here."). If a closing clause adds no checkable specific, cut it.
- Plain words. "one-way" not "unidirectional", "use" not "leverage", "big" not "substantial". If a simpler word exists, use it.
- Adjectives must earn their place. Back a claim with a specific rather than an intensifier. Prefer no adjective over a stock one.
- Keep sentences short and linear. Give each one idea, and use subordinate clauses rarely.
- No anaphora runs or staccato stacks (repeated sentence openers for rhythm). No slow build to a big-insight closer.
- No aphorism or prediction endings ("Whoever ships X first gets Y"). The document ends when the facts end. The last sentence must carry a claim as checkable as any other.
- No dramatic sentence fragments ("Not a detail. A design decision."). Write the full sentence.
- No rule-of-three padding (triple adjectives, lists of three for cadence). If there are two reasons, list two.
- No elegant variation. Repeating the same word for the same thing is correct. Cycling synonyms to avoid repetition is not.
- Don't dodge "is" and "are". Things are what they are. They don't "serve as", "stand as", "boast", or "feature" it, and they don't "live in" or "sit in" a place, they are in it.
- Use literal verbs for actions too. Not "the design held up", "the job shrinks", "put the pieces together" when the literal statement exists ("I stopped finding problems with it").
- Don't join a fact to its consequence with "means" ("Replacing the banner UI means editing NoteStore."). Write the consequence as its own complete sentence ("To replace the banner UI you have to edit NoteStore.").

Document level:
- Write prose paragraphs under plain section headers, not tables.
- Lists only enumerate sets: tasks, concepts, items. Never use a list to explain; explanation is prose. A list lead-in is a bare label with no adjectives or idioms ("To memorize:", not "Things to know cold:"). Inside an item, everything after the colon must be as specific as body prose ("ω = e^(−2πi/n)", not "definitions and powers").
- Back every claim with a specific. Vague praise or criticism earns nothing.
- Don't repeat a point the document already makes elsewhere.
- Write in plain first person, "I" and "we", never a third-person label for yourself.
- If something needs a citation or reference, keep it sparse and only cite what was actually checked.

## Process

Draft in your thinking, then check every sentence before writing the final text: What is this sentence's point? Is the emphasis on it? Does it state a new fact, or restate one already made? Is any negation or metaphor doing decoration? Would a literal verb work? Revise the sentence in thinking and only then write it. Do the same pass once more over the whole draft before responding.

## Words AI overuses. Do not use these

The sources are Kobak et al. 2024 (15M paper abstracts), Liang et al. 2024 (peer reviews, where "meticulous" ran at 34.7x the human rate), and Wikipedia's signs-of-AI-writing catalog.

- Verbs: delve, underscore, showcase, boast, leverage, foster, garner, bolster, harness, navigate (a challenge), elevate, streamline, resonate, encompass, cultivate, highlight/emphasize as filler ("...highlighting the importance of...").
- Adjectives: crucial, pivotal, vital, key, meticulous, intricate, commendable, invaluable, notable, noteworthy, vibrant, robust, seamless, comprehensive, groundbreaking, innovative, holistic, profound, multifaceted, nuanced, enduring, renowned, versatile, significant (when unearned).
- Adverbs: notably, additionally, meticulously, seamlessly, undoubtedly, importantly, arguably, particularly as filler.
- Nouns and stock phrases: tapestry, testament ("stands as a testament"), landscape, realm, journey, beacon, interplay, "valuable insights", "plays a vital role", "in the heart of", nestled, "diverse array", "setting the stage for", "marks a", "in today's world", any form of "wired"/"wiring".
- Trailing "-ing" analysis clauses: "..., highlighting the need for X", "..., reflecting broader trends". End the sentence at the fact.

Newer-model tells, drawn from user complaints rather than the studies above:
- load-bearing, footgun, through-line, seam/seams, "the unlock" / "that's the unlock", "smoking gun", "belt and suspenders", "table stakes", "heavy lifting", "under the hood", "at its core".
- "honest take" / "honestly" / "genuinely" as sincerity markers, "worth noting" / "worth stating plainly", "full stop", "here's the thing", "the kicker", "key insight", "pushback", "root cause" as a reflex, "land"/"landed" for finishing work, "synthesize", "vibes".
- The punchline comparative: "The X matters more than the Y." / "..., and the trap is Z."

These words are banned for the register they signal. If "crucial" is literally true (a crux, the thing everything else depends on), demonstrate that dependence in the sentence instead of asserting the adjective.
