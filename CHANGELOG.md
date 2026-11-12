# Changelog

## 4.2.0 (2026-11-12)
Version 4.2 gives Storycraft a workflow for **long-form YouTube documentaries**: historical stories, mysteries,
investigations and human tragedies. It also covers **fiction told in the documentary manner**, such as a novel adapted
into a documentary-style video. It stays one skill: the story engine, the information plan, the turning-point lens and
the Arabic layer all carry over, and a new reference adds what changes when a story is true, heard rather than read,
and shared with pictures and sound.

**Transcripts studied.** Caption tracks of twenty-one documentaries on three channels were read in full, in order and in
chunks, with verified notes and a map of each video (`references/sources.md` lists them, with their gaps):
- Brick Immortar, six videos;
- Fall of Civilizations, five episodes (one supplied twice, and its automatic-caption copy compared word for word, not
  used for wording);
- LEMMiNO, seven documentaries, two Q&A videos and a promo.

Each channel was analysed on its own, counting each video once, before the three were compared, so the channel with
the most files does not dominate. Recurring findings are given as defaults with their conditions, differences between
channels as choices, and one-channel techniques as options.

**New: `references/documentary.md`.**
- **A truth ledger:** every narration line is marked established, claimed, uncertain or invented, and the narration
  marks each status aloud.
- **The question and the known outcome:** how to choose where a known event sits (stated at the start, at the middle,
  at the end, or verdict first) by what the suspense is about.
- **The sequence:** sections with jobs, a ladder of small questions, turns said in words, and stock-taking at the end
  of each movement.
- **Openings:** a table of options and their costs.
- **First need for the ear:** names, places, dates, figures and terms at the moment a listener needs them.
- **Fair withholding:** plants paid off in the same words, honest deferrals, and the record's silence named.
- **Attribution heard with each claim,** renewed at the dramatic peak, where all three channels let the line blur.
- **Writing for the ear,** and a three-track script for narrator, picture and sound and pause.
- **Room for real deaths,** scaled to the person, with what must not sit beside them.
- **Teaching an unfamiliar trade or period** one mechanism at a time.
- **Long runtimes and where business belongs.**
- **Fiction told as documentary:** three frames, the seams marked, no invented evidence, and labels for reconstructed
  or generated pictures, following YouTube's disclosure rules for realistic AI-generated content.
- **Revision passes and a cold listen,** a failure table and a checklist.

**Arabic narration** (`references/arabic-writing.md` §12, new). Register for the ear; event sentences verb-first;
short construct chains and relative clauses one deep; connectives that name the relation (no all-purpose «حيث»); role
before name; numbers written out and vowelled for the narrator; where the pause falls; formulae at a death; and timing
the Arabic aloud. No Arabic documentary transcripts were supplied, so the section transfers the findings through the
Arabic layer and was checked on an original sample. `translation.md` §6.9 adds narration scripts.

**Elsewhere:**
- `SKILL.md` gains a Documentary mode and workflow, documentary lines in the quality gate, a technique row, reads and
  templates.
- New templates: `documentary-plan.md` and `narration-script.md`.
- `comprehension-log.md` gains a cold-listen table, and `revision-checklist.md` a documentary pass.
- `forms.md` §11 covers the long-form documentary as a medium: runtime from speech at about 110–155 words per minute in
  the studied videos, spoken chapter signals, where business goes, and honest packaging.
- Pointers were added to `clarity-and-orientation.md`, `information-design.md` and `emotion.md`.

**Validation, and what it changed.** The workflow was tested on a short original sample: an invented novel adapted into
a documentary-style opening, in English and in Arabic. The sample is not part of the skill. Three checks were run:
- a cold listen in each language, by readers who saw only the narration;
- an independent audit against the guidance and the verified sources;
- the writer's own audit.

Their findings changed the guidance:
- **The hand-off seam.** A history question was answered with the novel's own object, in the habitual past, so the
  invention was heard as history. Now covered in §15, and in `arabic-writing.md` §12 for «كان يفعل».
- **The adaptation's additions.** Details the adaptation invented were voiced as "in the novel". There is now an A
  status, and "in the novel" is kept for what the book contains.
- **A real frame vouches for the world.** A frame that calls the world real vouches for every world detail inside the
  invented scenes. Those details now go in the ledger.
- **The setting.** No place or period was said aloud, and listeners guessed it from trade terms (§6).
- **Sources.** A source's modality drifted ("expected to" became "did"), and a lone source was named only by its date
  (§3, §9).
- **Figures.** Listeners multiplied neighbouring figures: a dive rate heard beside "sunrise to sunset" (§7).
- **A clue that proves nothing.** A planted clue was already explained by facts the viewer held (§8).
- **The ear.** A pronoun in reported speech had two candidates; a title had a near-homophone ("ledger" and "letter");
  "a diver" and "the diver" drifted into each other; a recap dropped the clue the next section needed (§7, §10).
- **Arabic.**
  - The pause silences the case ending that would show which noun a final adjective belongs to.
  - A name that is also a word needs its role noun on later mentions too, above all in a construct phrase.
  - Words such as «صاحب» have a rival meaning by ear.
  - Devices carried over from the English draft sound translated.
  - Terms known only from English transliterations must be checked in Arabic.
- **Two narrations, one picture.** Keep the cue points; rebuild each row in its own language (§16, `translation.md`
  §6.9).
- **Timing.** The writer cannot always read aloud: estimate per language, do not count pauses twice, and leave the
  timing to the narrator (§10).
- **Circular examples.** The examples in the guidance had come from the sample's own world, so they were varied.

A revised sample was then given to fresh cold listeners in both languages. The fixes held. Their smaller findings
added four more refinements:
- a foreign term that collides with a known word gives way to the plain gloss;
- the unverified seam is said aloud;
- no story fact is hidden inside an inference;
- in Arabic, an indefinite noun for the general case, and a title introduced as a title.

**Voicing with ElevenLabs** (`documentary.md` §20, added within 4.2.0). How to prepare narration for Eleven
Multilingual v2 and Eleven v4 separately, from ElevenLabs' documentation as read on 12 November 2026:
- reading each scene for feeling, emphasis, slowing and silence before choosing a control;
- each model's supported pauses, tags, pronunciation methods and voice settings;
- an example request for each model, with placeholders;
- splitting at scene boundaries, stitching clips and retaking a single section;
- keeping production notes out of the text the API speaks.

The examples were checked statically, without calling the API. The narration-script template now marks held pauses
`{pause 2 s}`, because Eleven v4 reads square brackets as audio tags.

## 4.0.0 (2026-11-11)
Version 4 is driven by a reader's report on a story written with the skill: a character's death in a scene went
unnoticed on first reading and was understood only when the burial was mentioned. The guidance on restraint and ritual
had no account of *when* the reader understands a decisive event. Version 4 adds that judgment, without turning it into
a rule that deaths must be stated, shown or followed by a grief scene.

**Books read in full for this version,** each in order and in chunks, with verified notes (12,769 quotations checked,
all found), a ledger of decisive events and a whole-book analysis (`references/sources.md` gives editions and gaps):
- *The Moonstone* (Collins), *Wolf Hall* and *Bring Up the Bodies* (Mantel);
- in Arabic: *Men in the Sun* (Kanafani), *Celestial Bodies* (Alharthi), *Palace Walk* and *Palace of Desire*
  (Mahfouz), with a series analysis of the two Mahfouz volumes and of the two Mantel volumes;
- Edwidge Danticat's *The Art of Death*, a craft book on writing death, tested against the novels.

Partial sources were *Hamnet* (a 28-page sample that stops before any death) and an article about Alrefai's *Al-Najdi*
instead of the novel. Their limits are recorded, and no claims rest on them beyond what they contain.

**Turning points: what the reader understands, and when** (`clarity-and-orientation.md` §6, rewritten from "Hinges
must be literal"):
- choose when the reader should know: at once, by the end of the scene, later by design, in advance, or kept
  uncertain on purpose;
- choose the channel that fits the point of view and the pace: a plain line, an unmistakable act, a ritual that belongs
  to after death, a reaction the reader was prepared to read, a restatement, a report, an announcement, or silence once
  the fact is secure. Each channel comes with what it achieves, when it works and when it gets in the way;
- separate the fact from its manner, agent or identity, and label any doubt that is meant to stay;
- a first-reading test replaces the literal-clause rule.

**Aftermath as a choice** (`emotion.md` §6): the options include responses in the scene, private grief returned to
later, grief deferred to a fitting occasion, aftermath spread across chapters, a lasting habit, the bereaved written
before the death, a cut to routine, and a short report for a minor death. Each has its effect and its risk. The
heartbreak sequence's "aftermath" step now allows distributed and delayed consequences.

**Ritual and restraint reconciled.**
- Rituals of dying are distinguished from rituals of death.
- A formula carries a fact only for readers who can read it, and only where the book does not use formulae in jest.
- `arabic-writing.md` §8 sorts Arabic death formulae and customs by what they tell the reader: «راح» is ambiguous; a
  formal announcement is unmistakable; a death-watch prayer gives near-certainty.

**Elsewhere:**
- novel-studies adds the seven novels, a cross-book table of how each keeps a death's fact secure while the scene stays
  restrained, and §8's old "Rule" rewritten as conditions;
- information design adds announced outcomes, fair false deaths, and fact versus identity;
- mystery adds the *Moonstone* clue model, sincere half-truths, false-lead lifespans and social barriers to
  investigation;
- scene and summary adds late disclosure, report frames, chapter breaks that carry a death, and proportion as a
  statement;
- viewpoint adds tense as witness, narrator hand-overs and labelled uncertainty;
- world and society adds customs as binding rules, history through household channels, and methods for glossing
  period terms in stride;
- character adds durable habits of grief and responses fitted to each relationship;
- series adds staged recaps of the dead, a death log in the bible, sequels that open in settled aftermath, and echoed
  techniques with changed outcomes;
- the Arabic layer adds register as a signal of gravity, labels that mark viewpoint and death, glossing methods,
  dialogue-layout lessons, and the risk of plot facts in concessive clauses;
- templates gain a decisive-events table in the information plan, a turning-points table in the comprehension log,
  and matching revision checks.

**Flexibility pass.** The rules found to be rigid were rewritten as choices with effects and costs:
- the quality gate's hinge line;
- the prose checklist;
- the horror rule on deaths;
- the novel-studies rule on withheld deaths;
- "never and then";
- "recoverable in every paragraph".

## 3.0.0 (2026-11-10)
An overhaul driven by three things:
- an editor's critique of a story written with the skill, tested claim by claim against the manuscript;
- a comprehension audit of that story's Arabic edition, which a native Arabic reader repeatedly could not follow
  although every word was clear;
- a close reading of eight Arabic novels in three series, each read in full from OCR checked against page images,
  with verified chunk notes, a whole-book analysis and a separate analysis of its Arabic prose:
  - Osamah Al Muslim's *Khawf* 1–3;
  - Ahmed Al Hamdan's *Arsis* 1–2;
  - Amr Abdel Hamid's *Ard Zikola*, *Amarita* and *Wadi al-Dhi'ab al-Mansiyya*.

The audit found that the Arabic edition failed on its information plan, not its vocabulary. The causes:
- links left for the reader to build at turning points;
- pronouns resolving to the wrong nearby man;
- English metalanguage ("she wrote *we*") laid over Arabic grammar;
- background never stated;
- English dialogue layout.

Version 3 teaches the skill to keep a scene clear while a secret stays hidden, to write and translate natural,
followable Arabic, and to run investigations, horror and series with the craft the novels show (and to avoid their
common failures).

**One craft, any language.** Storycraft stays one system. Every transferable lesson from the novels, Arabic or
English, went into the shared craft references, filed by function. The Arabic guidance is a language layer added on
top of that craft, never a separate branch. SKILL.md states the loading rule: choose the craft references the story
needs, then add the language layer.

**New references**
- `clarity-and-orientation.md`: the reader's situation model; the intended-uncertainty list; orientation; referents;
  links and the distance rule; literal hinges; mentioned words and mechanisms; background at first need;
  concealment with clarity; the spoiler-safe cold read.
- `arabic-writing.md`: the Arabic language layer, used with the shared craft and never instead of it:
  - choosing a narrative voice and register;
  - dialect strategies;
  - reference in Arabic (the nearest-person rule; morphology that attributes);
  - dialogue attribution and layout (tags before the line, or labels; measured across the corpus);
  - sentence and paragraph construction;
  - Arabic orientation devices;
  - names, homographs and selective vowelling;
  - idiom, formulae and figurative language;
  - punctuation;
  - a composing procedure;
  - before/after repairs (invented examples).
- `translation.md`: a literary translation procedure, English → Arabic in detail: source analysis, glossaries, a
  transfer plan, drafting rules, ordered verification passes, a cold read that classifies each stumble as source,
  translation or an uncompensated source gap, and a before/after failure catalogue.
- `horror.md`: sources of fear; the familiar made wrong; threats with stated, predicted and tested rules; escalation
  without losing dread; darkness and sound; sentence-level fear; horror and belief; horror endings.
- `series.md`: volume and series questions; ending a volume; recaps and re-orientation; continuity claims;
  evolving rules; characters and long mysteries across volumes; repeated devices; voice across volumes; ending a
  series.

**Revised references**
- `novel-studies.md`: now compares all fifteen novels, English and Arabic, by craft problem. New sections cover teaching
  a world's rules, earned and delivered investigation, dread, clarity under concealment, register, and series, with
  Arabic prose measurements beside the English ones.
- Language-general lessons from the Arabic novels added where they belong by function:
  - transitions, re-entry echoes, replays, time skeletons and one countable result per step (`scene-and-summary.md`);
  - exposition kept inside scenes, fair flash-forwards that mislead, and reveals that widen to a witness
    (`information-design.md`);
  - clues hidden in sound, implausibilities as clues, keys kept from the hero, visible threats as misdirection, and the
    founding rule as the key (`mystery-and-clues.md`);
  - teaching a world's rules in stages, quantified economies, and a rule for what a reset keeps
    (`world-and-society.md`);
  - braids that converge (`long-form.md`);
  - witness relays and two minds in one body (`viewpoint-and-narration.md`);
  - hinge and shock sentences (`prose.md`);
  - ritual language, grief as a daily act, the safety device shown before it is removed, and one voice that names a
    transgression (`emotion.md`);
  - registers given a job and labelled from the narration's standpoint, and persuasion (`voice-and-dialogue.md`);
  - sacrifices revealed by others, a refused means of peace, refusing the original sin, and a wish refused
    (`character.md`, `structure-and-scenes.md`, `endings.md`);
  - naming systems, clocks, narrator switches, audible reasoning and concealment (`clarity-and-orientation.md`).
- `mystery-and-clues.md`: new §18 earned discoveries, false-lead lifespan, suspect marking and confessions that carry a
  prosecution; new §19 the mechanism ledger for plot-carrying mechanisms.
- `character.md`: earning a sacrifice before it is made; functionaries with a life of their own.
- `world-and-society.md`: institutional acceptance scenes; dating the world when the stakes depend on law.
- `endings.md`: closure density; giving a rupture a scene.
- `prose.md`: translationese reframed (the information plan matters more than calques); a hinge-clarity check.
- `revision.md`: new Pass 10, clarity (the cold read).
- `diagnostics.md`: new patterns for courier investigations, accidental irony, starved false leads, convenient
  institutions, undated stakes, mechanisms that fail scrutiny, asserted sacrifices, stage-clearing professionals,
  closure pile-ups and ruptures in a line; a new "Clarity and language" group.
- `information-design.md`, `genres.md` (horror), `sources.md` (the Arabic novels, their editions and limits).

**New templates:** `comprehension-log.md`, `translation-brief.md`, `series-bible.md`. **Extended:** `clue-ledger.md`
(discovery audit, suspect marking, mechanism ledger) and `revision-checklist.md`.

**SKILL.md**
- a new **Translate** mode and workflow;
- language and readership in the brief;
- "One craft, any language": the shared craft applies in every language, and a language layer is added on top;
- a clarity check and an Arabic voice and register plan in the Draft workflow;
- a "Clarity and language" group in the quality gate;
- new calibrations ("a clear scene, a hidden secret"; "clarity is not simplicity");
- new rows in the techniques table (fear of a threat, pull across volumes, clarity with mystery);
- the reference map and typical reads updated;
- the description now covers any language, Arabic writing and translation.

**Limits**
- Not tested in generation, by the author's instruction: no test stories were produced, and only structure,
  references and consistency were checked.
- The novels are quoted only briefly, from OCR. One scan (*Khawf* 3) lacks two printed pages, which is recorded in
  `sources.md`.
- The audited manuscript is not quoted anywhere in the skill; its lessons are generalized and every example is
  invented.

## 2.0.0 (2026-11-09)
A rebuild driven by two things:
- an editor's critique of a story written with v1.0, tested claim by claim against the
  manuscript;
- a close reading of seven published novels, each read in full, chunk by chunk, with verified notes, plus the
  openings of two more (see `skills/storycraft/references/sources.md` and `novel-studies.md`).

v1.0 produced well-engineered stories that could feel summarized, over-patterned and too tidy. v2 keeps the causal and
information machinery and adds the parts that make stories feel lived.

**New references**
- `premise.md`: premise development, turning ordinary material into story possibilities, premise tests, scope-to-length fit.
- `scene-and-summary.md`: what must be staged, summary that lives, carrying years and decades, tellings as scenes.
- `long-form.md`: novella and novel architecture, braided lines, viewpoint rotation, chronology, momentum and its costs.
- `voice-and-dialogue.md`: distinct voices, dialogue mechanics, subtext, testimony, the explainer problem.
- `viewpoint-and-narration.md`: viewpoint, distance, retrospective and unreliable narrators, frames and documents.
- `world-and-society.md`: setting as cause, social rules, history and politics, the barrier "channel audit", fable
  versus specific.
- `prose.md`: register, specificity, comparison budgets, rhythm, motif budgets, visible machinery, benchmarks measured
  on published novels, translation.
- `revision.md`: revision passes from big to small, the leak audit, and testing feedback against the text.
- `novel-studies.md`: contrastive case studies showing how the books read solve the same problems differently.

**Revised references**
- `information-design.md`: inference control (leaks, rival explanations, one strategy per secret), explanation load in
  reveals.
- `character.md`: lives beyond the plot, friction and self-interest, secret-keepers, surprising but true behaviour.
- `endings.md`: proportion, residue and tidiness; explanation endings; recontextualizing endings.
- `emotion.md`: restraint ≠ compression; the heartbreak sequence as a check, not a recipe; consequences in the aftermath.
- `mystery-and-clues.md`: new §15 mystery architectures at length, §16 concealment strategies compared (with
  fair-play warnings), §17 delivering the solution.
- `character.md`: restructured; new §14 agency, §16 failure patterns, expanded checklist.
- `worked-example.md`: a v2 audit of the original example (scope, device budget, visible machinery, leak audit, life,
  explanation load, tidiness). No new story material was added.
- `sources.md`: the novels studied, their editions and coverage; the SFWA length bands.
- `diagnostics.md`, `forms.md` (novella), `structure-and-scenes.md`.

**SKILL.md**
- A new Revise mode.
- A scope check.
- "Choosing techniques by effect".
- A quality gate split into machinery, life, and ending and meaning.
- A calibration section that resolves v1's contradictions: economy versus life, restraint versus staging, short
  resolutions versus full consequences, mystery versus irony.

**Templates:**
- new: `scope-budget`, `character-dossier`, `revision-checklist`;
- updated: `story-bible`, `causal-spine`, `information-plan` (inference timeline), `scene-card`, `doctor-report`
  (feedback verdicts).

## 1.0.0 (2026-11-08)
First release.
