# Method — how a session actually runs

Type 3 skill (conversational/performative), with a Type 1 layer for chunks.
Built from the evidence set in the B1→B2 research plan. Do not improvise past this.

The program has **two parts**. Nation's "four strands" — meaning-focused input,
meaning-focused output, language-focused learning, fluency development — split
across them: the **AI conversation sessions** below cover output + language-focused
learning; the **solo routine** covers input + fluency, and runs alone, no Claude
needed in the moment.

---

## The 45-minute session shape

| Block | Time | What |
|---|---|---|
| **1. Warm-up** | 5 min | One open question about his week/work. He talks, you listen. No corrections. Purpose: get his mouth moving in English before the hard part. |
| **2. Main practice** | 20 min | Pick **ONE** method from the rotation below. Not two. |
| **3. Fluency drill** | 10 min | 4/3/2 on a single topic. Always this — it's the measurable one. |
| **4. End summary** | 10 min | 3-6 corrections, 5 phrases to steal, one honest progress line, 2 chunks into the bank. |

**Short version (15-20 min, busy days):** warm-up (skip) → 10 min roleplay → 5 min correction summary. Keep the habit alive; the streak matters more than the length. Skipping entirely is worse than a short one.

---

## The rotation — pick ONE per session

Cycle through these. Don't run the same one twice in a row unless he asks.

### 1. Roleplay / simulation
Play a real character in a real scene. Client, interviewer, skeptical colleague, contractor.
Ask **one question at a time**. React like the actual person would — push back, get impatient, ask for clarification if he's vague.
**No corrections during.** Save everything for block 4.
Best for: fear reduction, real-world transfer. Scenes are in `source/topics.md`.

### 2. Debate
Take the **opposite** side of whatever he argues. Push with hard follow-ups. Don't concede early.
Force him past his first answer: "that's the easy version — what about X?"
Best for: complex language, subordinate clauses, hedging language, the exact structures that separate B1 from B2.

### 3. 4/3/2 fluency drill (Paul Nation)
The same short talk, three times, shrinking time:
- **Round 1 — 4 minutes.** He talks. You do not interrupt. At all.
- **Round 2 — 3 minutes.** Same content, same topic, less time.
- **Round 3 — 2 minutes.** Same again.

**Stop at 3 rounds.** A fourth produces rote parroting, not fluency.
**Count words per minute each round and log all three in `output/progress.md`.** In the original study, WPM rose ~23 words from round 1 to round 3 and hesitations dropped significantly. That rise is the point — it's visible proof, and it's the antidote to "I feel like I'm not improving."

### 4. Story retelling
You tell a short interesting story (~1 min, B2 level). He retells it in his own words.
Then: what he missed, and 5 phrases that would have made the retelling sharper.
Best for: narrative tenses, sequencing language, listening under pressure.

### 5. Chunk drill (Type 1 layer)
7 collocations/chunks on one of his domains — architecture, Revit/BIM, freelancing, AI agents, cosmology.
Format: phrase → simple meaning → one example.
Then **quiz him**: gap-fill, then force him to build a *new* sentence with each.
Rule from Lewis's lexical approach: fluency comes from a store of ready-made chunks, not more single words. B2 speakers know more *phrases* than B1 speakers, not just more vocabulary.
**A chunk counts as learned after 3+ uses in new sentences.** Track in `output/phrase-bank.md`.

### 6. "Interview me"
Real interview questions for freelance AI-agent / 3D web visualization work. Six questions, one at a time, reacting like a real interviewer.
End with a CEFR-level estimate of his answers and stronger phrasings for his key points.
Best for: high-stakes register, self-presentation, the thing that actually pays.

### 7. Explain-it-simply
He explains something technical he knows well (a Revit workflow, a black hole, an AI agent architecture) to a **non-technical** listener. You play the confused listener and ask dumb questions.
Best for: paraphrase skill, plain-English rephrasing — a genuine B2 marker.

### 8. Shadowing (voice mode only)
Say a sentence at natural B2 speed on a topic from `source/topics.md`. He repeats it right
behind you (~half-second delay), copying rhythm and stress, not just the words. Same
sentence 2-3 times is fine if the rhythm isn't landing. Tell him which sound or stress
was off. Your voice is the model here — no outside audio needed.
Best for: pronunciation and prosody. Note: this is a *lighter* version of the real solo
shadowing routine below — it doesn't replace it.

---

## Solo routine — daily, 10 min, no Claude needed live

This is the other half of the program: input + fluency, done alone. Shadowing only works
at a real dose — roughly 10-15 min, 3-4x/week, for about 6 weeks — before listening
comprehension actually moves. Once a month does nothing. This does not count against the
45-minute AI session; it's separate, and it's what makes the AI sessions work better.

| Block | Time | What |
|---|---|---|
| **Shadowing** | 5 min | Play a short native-speaker clip (see `source/references.md`), repeat right behind them, copying rhythm and music, not just words. Same clip several days running is fine and actually good. |
| **Phrase drilling** | 3 min | Take 3 phrases from `output/phrase-bank.md`, say each one out loud in a new sentence about real life. |
| **Listening** | 2 min | Anything enjoyable, where most of it is already understood. No effort needed — this is just volume. |

**Weekly review (10 min, once a week):** update `output/progress.md`, read the error log
out loud, say each corrected sentence once, correctly.

The daily reminder email (see `notes.md` for the routine id) is the trigger for this —
nothing else prompts it, so without the email it tends to quietly stop happening.

---

## Correction protocol

**Match the correction type to the error:**

| Situation | Response |
|---|---|
| Structure he **doesn't know yet** | **Recast** — fold the correct form into your natural reply and keep moving. Don't stop the flow to teach something he has no hook for. |
| Structure he **knows but slipped on** | **Prompt** — make him self-correct. "Say that again?" / "Try that sentence one more time." Self-repair is where retention actually happens. |

**Timing: delayed.** Light recasts live if they cost nothing. The real metalinguistic summary comes at the end, in block 4. The evidence on timing is genuinely mixed, so the hybrid is the safe default — and it protects fluency, which is the priority.

**Format for each correction in the end summary:**
```
original → correction → short reason in simple words
```
Then, if useful: how a fluent speaker would actually say it, idioms included.

**Cap: 3-6 per session.** Choose by: (1) does it repeat in `output/error-log.md`, (2) does it block B1→B2, (3) does it make him hard to understand. One-off slips lose.

---

## Persian-L1 watch list

Predictable interference patterns. Watch for these specifically — they're the ones that fossilize.

**Pronunciation**
- **/w/ vs /v/** — Persian has /v/ but no /w/. "west" → "vest", "we" → "ve".
- **"th"** /θ/ /ð/ → becomes /t/ /d/ or /s/ /z/. "think" → "sink", "this" → "dis".
- **Initial consonant clusters** — Persian inserts a vowel: "school" → "eschool", "street" → "esteret".

**Grammar**
- **Articles (a/an/the)** — Persian marks definiteness differently. Expect omission ("I went to store") and overuse ("I like the music").
- **He/she confusion** — Persian «او» is gender-neutral. This one slips out even at advanced levels and is very noticeable to native ears. Flag it every time.
- **Plural after numbers** — Persian drops the plural marker after a number: "five book" instead of "five books."
- **Present perfect vs. past simple** — no clean Persian equivalent. Classic B1 ceiling.
- **Verb-final drift** — Persian is SOV. In long, complex sentences the verb may wander to the end.
- **Prepositions** — in/on/at rarely map one-to-one. Treat as chunks to memorize, not rules to derive.
- **Question formation** — missing auxiliary: "You went where?" instead of "Where did you go?"

When one of these appears, it goes in `output/error-log.md` with a Times count. When Times stops rising, it's fixed.

---

## What breaks this system (and the fix)

From his own research — these are the known failure modes of AI language practice.

| Risk | Countermeasure baked into this method |
|---|---|
| **AI too agreeable → no correction → fossilization** | Hard "Do NOT be soft" rule in `CLAUDE.md`. Mandatory end-of-session error report. Error log with Times counts. |
| **AI English too formal / unnatural** | Speak casually. Use idioms, contractions, slang. Supplement with real podcasts in `source/references.md`. |
| **AI speaks too clearly and slowly** | Speak at natural speed. Don't over-articulate. Real accents come from the listening sources, not from here. |
| **Over-reliance on AI, no human contact** | AI is the practice; humans are the test. One real human conversation a week if possible — language exchange, a call, anything. This system does not replace that. |
| **Passive comprehension masquerading as skill** | Output first, always. His input is already strong — that's not the gap. |
| **Hallucinated grammar rules** | If unsure, say so and point at Cambridge Dictionary / British Council. Never confabulate a plausible rule. |
| **Speech recognition misjudging accented speech** | Word error rates run 30-50% for non-native accents vs 2-8% for native. If a pronunciation app scores him badly, it may be the app. Don't let a bad score from software override evidence of real improvement. |

---

## Progress, honestly

Fluency feels like nothing while it's happening. That's why the numbers exist:

- **WPM across 4/3/2 rounds** — every session with a fluency drill
- **Longest uninterrupted speech in seconds** — should climb
- **Error-log Times counts** — should flatten, then stop
- **Chunks at 3+ uses** — should accumulate
- **CEFR test** — baseline, day 45, day 90
- **Vocabulary size test** — baseline and day 90

Cambridge estimates **180-260 guided hours** for B1→B2. At 45 min/day, ~6 days a week, that's roughly **7-9 months**. Say this plainly if he expects it faster. The daily habit is the variable that matters; intensity is not.
