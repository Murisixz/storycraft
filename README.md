# Storycraft

A storytelling skill for Claude: invent, plot, write and fix stories in any form. It is strongest at mysteries,
suspense, sad and bittersweet stories, and plots whose events follow from one another.

Storycraft teaches Claude the parts that make a story work. Events cause each other; someone wants something badly and
pays for it; the audience always has something to hope for, fear, wonder about, or know before a character does; and
endings feel surprising but inevitable. It gathers the core principles of Robert McKee's *Story*, Howard & Mabley's
*The Tools of Screenwriting* (from Frank Daniel's teaching), and classic and modern craft writing on plot, mystery and
emotion. Version 2 adds findings from a close reading of published novels, each read in full, compared for how they
solve the same problems differently. All of it is rewritten as practical procedures, decision rules, checklists and
templates, in the skill's own words, not as models to imitate.

## What it does

| Mode | Ask for | You get |
|---|---|---|
| **Spark** | ideas, premises, "what if" options | Distinct premises, each with a protagonist and want, obstacle, stakes, emotional core and hidden engine |
| **Architect** | an outline, plot, mystery design or story bible | Story core → ending first → hidden story and information plan → cause-and-effect beat list → clues and plants → emotional and pacing passes → quality gate |
| **Draft** | a scene, chapter, script or short-video beat sheet | A short scene plan, then the pages |
| **Doctor** | "why is my story flat/confusing/predictable?" | A ranked diagnosis with evidence, concrete fixes, and a revised spine |
| **Revise** | a draft plus editorial feedback, or "revise this" | Each feedback claim tested against the text (claim, evidence, verdict, cause, fix), then revision passes from scope down to sentences |

Example prompts:
- "Give me five ideas for a sad, mysterious 60-second Minecraft Short that viewers will theorize about."
- "Design a fair-play whodunit for my novel. I want the killer's motive to be heartbreaking."
- "Write the scene where she visits the man she wrongly convicted. Tense, 1,200 words."
- "Here's my outline. Why does it feel flat? Fix it."
- "Outline a quiet, bittersweet short film with no twist."
- "My editor says this novella feels summarized and too tidy. Is that fair? Revise it."

## What's inside

```
skills/storycraft/
├── SKILL.md                      # the workflow: modes, story engine, scope check, quality gate, calibration
├── references/                   # loaded only when needed
│   ├── premise.md                # premise development, ordinary material into story, premise tests, scope fit
│   ├── structure-and-scenes.md   # cause and effect, inciting incident, acts, scene design, pacing, shapes beyond the arc
│   ├── scene-and-summary.md      # what must be staged, summary that lives, long time spans, tellings as scenes
│   ├── long-form.md              # novella and novel architecture, braided lines, chronology, momentum at length
│   ├── character.md              # want vs need, contradiction, antagonism, lives beyond the plot, friction, secret-keepers, agency
│   ├── voice-and-dialogue.md     # distinct voices, dialogue mechanics, subtext, testimony, the explainer problem
│   ├── viewpoint-and-narration.md # viewpoint, distance, retrospective and unreliable narrators, frames, documents
│   ├── world-and-society.md      # setting as cause, social rules, history, the barrier "channel audit"
│   ├── information-design.md     # suspense, curiosity, irony, surprise, reveals, inference control
│   ├── mystery-and-clues.md      # hidden stories, investigations, clues, red herrings, fair play, solutions
│   ├── emotion.md                # caring, subtext, restraint, meaningful sadness, grief over time
│   ├── endings.md                # crisis, climax, controlling idea, proportion and residue, open endings
│   ├── prose.md                  # register, specificity, comparison and motif budgets, rhythm, translation
│   ├── genres.md                 # genre contracts and conventions
│   ├── forms.md                  # short story, novella, novel, screenplay, short video, games, comics, audio, stage
│   ├── revision.md               # revision passes, leak audit, testing feedback against the text
│   ├── diagnostics.md            # failure catalogue (symptom → cause → fix) and doctor procedure
│   ├── novel-studies.md          # contrastive case studies from published novels read in full
│   ├── worked-example.md         # an annotated Architect pass on an original short film
│   └── sources.md                # where the ideas come from, and how each source was accessed
├── assets/templates/             # story bible, scope budget, causal spine, information plan, clue ledger, character
│                                 # dossier, scene card, revision checklist, doctor report
└── evals/                        # test cases (prompts + graders) for `claude plugin eval`
```

## Install

### Claude Code (plugin)
```
/plugin marketplace add Murisixz/storycraft
/plugin install storycraft@storycraft-marketplace
```
(From a local clone, use `/plugin marketplace add /path/to/storycraft` instead.)

### Claude Code (plain skill)
Copy `skills/storycraft/` to `~/.claude/skills/storycraft/` (for all your projects) or to `.claude/skills/storycraft/`
inside a project.

### Claude apps (claude.ai, desktop)
Download `storycraft.zip` from the [latest release](https://github.com/Murisixz/storycraft/releases/latest) (or zip the
`skills/storycraft` folder yourself so the zip contains `storycraft/SKILL.md`) and upload it
as a custom skill in the app's settings, under Capabilities / Skills. Code execution must be enabled. Menu
names can change between app versions.

### Claude API
Upload the same folder as a custom skill through the Skills API and attach it to requests that use the code execution
tool. See Anthropic's Agent Skills documentation for the current endpoints and beta headers.

## Use
The skill triggers on its own for story work. You can also name it ("use storycraft to…"). Give the form and length,
the genre or tone, and anything that already exists. When an assumption doesn't change the design, Claude states it and
goes ahead; when it would change everything (novel vs 60-second video), Claude asks first.

## Testing
`skills/storycraft/evals/` holds five test cases: a sad mystery Short, a fair-play whodunit, a story doctor case, a
prison-visit scene, and a quiet bittersweet short film. Each has graded assertions. With Claude Code:
```
claude plugin eval /path/to/storycraft
```
This runs every case with and without the skill and reports scores.

## About the sources
The craft guidance is written in Storycraft's own words, with short attributed quotations. `references/sources.md`
says which books were read in full (craft books and novels), which were known only through summaries, and which
essays and studies were consulted. The novels are used for principles, with short attributed quotations only; no plots,
characters or prose are reproduced. Where a book was used only through a third-party summary (Truby's *The Anatomy of Story*, Maass's *The
Emotional Craft of Fiction*, Beinhart's *How to Write a Mystery*), the skill marks it "via outline" or "via a summary".

## License
MIT. See `LICENSE`.
