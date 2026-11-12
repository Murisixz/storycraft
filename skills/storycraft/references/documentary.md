# Documentary: long-form narrated video, true stories and fiction told as documentary

This file covers long-form narrated documentaries for YouTube and similar platforms: video essays and narrated podcasts about history, mysteries, investigations and human tragedies. It also covers **fiction told in the documentary manner**, such as a novel adapted into a documentary-style video. The craft is Storycraft's own: the story engine, the information plan, clarity at turning points, emotion and endings. This file adds what changes when the story is true, or told in a true story's manner, when it is heard rather than read, and when pictures and sound share the work.

The guidance comes from a close reading of twenty-one long-form documentaries from three channels with very different methods (`sources.md`). Where all three channels share a practice, it is given as a default with its conditions. Where they differ, the difference is given as a choice. Where only one channel shows a technique, it is marked as an option. None of it is a template: choose by the effect the story needs, and never copy a creator's wording, catchphrases or recurring structures.

## Contents
1. What changes: the ear, the picture, the record
2. The documentary workflow
3. The truth ledger
4. The central question, the promise and the known outcome
5. Building the sequence: sections, questions and turns
6. Openings
7. Names, places, dates and terms at first need
8. Withholding in a true story
9. Who says so: attribution, doubt and the narrow claim
10. Writing for the ear
11. Narrator, picture, sound and silence
12. Real people, death and room to absorb
13. Unfamiliar worlds and mechanisms
14. Long runtimes: threads, stock-taking and business
15. Fiction told as documentary
16. Narrating in Arabic
17. Revising a documentary script
18. Failure patterns and repairs
19. Checklist
20. Voicing the script with ElevenLabs (Multilingual v2 and Eleven v4)

---

## 1. What changes: the ear, the picture, the record
- **The ear cannot reread.** A listener holds a few new items at a time, and a referent slips the moment it is lost. Orientation, reference and links (`clarity-and-orientation.md`) matter more than on the page. They are carried by role labels, repetition, stable names and the order of information, not by layout.
- **The picture may not be seen.** Many viewers listen with the screen off or in another window, and some channels publish audio versions. Others watch with the sound down and read captions. Decide early which facts must survive audio alone. Usually that means every fact the story stands on. Let the picture add evidence, place, faces and texture.
- **The record sets the limits.** In nonfiction, the story engine's "what really happened" is not invented. It is what the evidence supports, with what someone claimed and what nobody knows kept audible. In fiction told as documentary, the viewer must always be able to tell the story's invention from the real world around it (§15).
- **The engine still runs.** The people in the record wanted things, met opposition and made choices under pressure. The hidden story becomes the truth ledger (§3). The dramatic question becomes the central question (§4). The information plan governs reveals. Turning points must be legible on first hearing (`clarity-and-orientation.md` §6).

## 2. The documentary workflow
Match the depth to the request. A ten-minute explainer needs a question, a sequence and a clean script. A two-hour investigation needs the whole plan. Templates: `assets/templates/documentary-plan.md` and `assets/templates/narration-script.md`.
1. **Brief.**
   - runtime and platform;
   - who the viewers are and what they already know about the period, place and trade;
   - the language or languages of the narration;
   - whether many will listen without watching;
   - **the setting the viewer must hear:** the place and the period (in fiction told as documentary, the story's setting and the real one);
   - for each narration language, what its viewers already know (viewers from the region may know the trade well), and whether that narration gets its own edit or must fit a locked picture;
   - **the frame:** a true story; fiction told as documentary; or a story and the history behind it (§15);
   - what may be spoiled.
2. **Truth ledger** (§3): every statement the narration will make, with its status and source.
3. **Question and promise** (§4): the central question; what the video will and will not settle; where the known outcome sits.
4. **Sequence** (§5, §14): sections with jobs; a ladder of small questions; the turns; minutes per section; where stock is taken.
5. **Schedules:** first need for names, places, terms and figures (§7); the reveal plan (§8); decisive moments and the room after them (§12).
6. **Script for the ear** in three tracks (narration, picture, sound and pause), each narration line tagged with its ledger status (§10–11).
7. **Revision passes and a cold listen** (§17).
8. **Voice it** if the narration will be synthesised (§20): read each scene for its performance, write the spoken text for the chosen model, split at scene boundaries, and keep production notes out of the text the API speaks.

## 3. The truth ledger
Give every statement the narrator will make a status, and decide how the narration will mark it aloud.

| Status | Meaning | How the narration usually marks it |
|---|---|---|
| **H**, established | Supported by a source the script can name and the viewer could check | Plain statement; the source named once where it matters |
| **C**, claimed | One person's or one document's account: a witness, a chronicle, a report, a rumour | A verb of saying and the claimant: "the captain later told the inquiry", "the chronicle says" |
| **U**, uncertain | Sources disagree, the record is silent, or the fact could not be checked | "Accounts differ", "no record survives", "we don't know", with what would settle it |
| **F**, invented | The novel's or story's own fiction (only in fiction told as documentary) | The frame, plus a marker at every seam with real history (§15) |
| **A**, added | Something the adaptation itself invents (a detail, a clue, a bridging moment) that the novel does not contain | Voiced as the video's own ("we can imagine…"), or cut; never "in the novel" |

- **Check before you write.** A documentary borrows its authority from its sources. A fact you could not verify, spoken in a calm narrator's voice, becomes the video's own claim. If a source cannot be reached, mark the fact U or leave it out.
- **Keep the source's own modality.** "Were expected to" is not "did", "frequently" is not "usually", and "about" is not "exactly". Change the word and you have changed the fact.
- **Name a lone source once.** When most H rows rest on one secondary account, name it aloud once, with its kind, outlet or author, and date ("a 1990 magazine feature on the trade"). Then sound no surer than one source allows. A date alone does not tell the listener how far to trust it.
- **One status per sentence.** A sentence that mixes statuses, such as a historical fact and the novel's object in one clause, is a seam and needs its own marker (§15). Do not slip a new story fact inside an inference or a hedge ("if…, it is no surprise that the crew questioned him first"). State the fact in its own sentence, then the inference.
- **Inside the F strand, keep the same distinctions as in the record:**
  - what the novel establishes;
  - what its characters claim;
  - what it leaves open.

  Mark each aloud. A later reveal is fair only if the account was heard as a claim when it was first told.
- **Inference is allowed when it is marked.** "Probably", "would have" and "we can picture" let the narration imagine a scene the record does not show. Keep each such passage short, keep invented numbers out of it, and let a voice from the time carry the feeling where one exists (§9).
- **Keep the ledger beside the script in revision.** Every line of narration should map to a ledger row or to a marked interpretation of the narrator's own.

## 4. The central question, the promise and the known outcome
- **Find the question the viewer will want answered,** and pose it early, aloud or unmistakably implied. A narrow question the evidence can answer ("what does the evidence inside this building show?") lets the ending pay in full. A huge question the record cannot settle needs a stated scope or an honest open end. Before fixing the question, check that the H and C rows can answer it; if they cannot, narrow it or promise an open end.
- **Say what the video will and will not settle.** A stated scope lets every section be measured against a promise you can keep. It gets in the way when viewers came for the big verdict; then add your own marked view late (§9).
- **A subject often holds two questions:** what happened and why (causal), and what it was like to live through (experiential). Promise only what the ending will pay. When an ending gives only an elegy, the causal promise goes unpaid; give one sentence of synthesis before the elegy.
- **When the outcome is known,** from the title, from history or from the opening, move the suspense into the process. Do not be coy about a fact the viewer already holds; that costs trust. Then choose where the decisive event sits by what the suspense is about:

| Where the known event sits | The suspense is about | Works when | Gets in the way when; then |
|---|---|---|---|
| Stated in the opening and never staged as the climax | whether each piece of evidence holds, how near the misses were, and what stays unknown | an investigation or a contested case | nothing is left to discover; keep one answerable question running under the middle |
| Near the middle | how the margin shrank: risks pile up in the first half, each a possible cause, and the second half investigates | a disaster or an accident with a cause to find | the first half is background with no person and no question; bring people in early and tie a human detail to each risk |
| Near the end | how a world worked and how it came apart, and what people inside it did not know | a long history, a decline, a fall | the subject itself is held back too long; give a date, a place and the subject early, and make each early section plant something later sections use |
| Verdict first, then the mechanism | what the verdict means, and one finding held back that changes it | the verdict is public and contested | the ending has nothing left to reveal; keep one finding for the end |

## 5. Building the sequence: sections, questions and turns
- **Give every section a job,** and name it in the plan: orient, context, chronology, escalation, investigation, evidence, reveal, aftermath, reflection. A section with no job is a digression. Keep a digression only when it plants something a later section uses, and tie it to the story's people when you plant it.
- **Link sections by cause or contradiction.** "And then" links are normal in chronicle stretches. Check that each section still opens or closes a question.
- **Keep a ladder of small questions.** Long middles live on questions that open and close within minutes. They also live on outcomes announced in advance (the viewer knows the mistake before the character makes it) and on dramatic irony (the viewer knows the trap). The central question can rest while the small ones work, but it must return before the end.
- **Plan the turns and say them in words.** A short sentence of contrast at the head or the end of a paragraph carries a turn best, with the pause after it.
- **A turn past the middle can reclassify what the viewer has already heard,** as the official version, one witness's version or the novel's version. It then asks a second question of the same material. Tie the new question aloud to the original one, or it sounds like a technicality.
- **Proportion.** Decide the minutes per section against the runtime and the question. A long history can spend a long time on context before its subject's own story only if every part of that context is used later. A twenty-minute video cannot afford that ratio: keep only the context the story will use.
- **Parallel cases** (several victims, messages, theories or suspects) are easier to follow when each follows the same order of slots, because the ear learns what comes next and hears the differences. Break the order at each case's own detail and compress the thin cases, or the people start to sound alike.

## 6. Openings
The opening sets the question, the promise and the frame. In its first minutes the viewer needs a person, a place, a time and a reason to wonder. Choose the opening by subject, not by habit.

| Opening | What it does | Works when | Gets in the way when; then |
|---|---|---|---|
| A recording or document from inside the event | puts the viewer in the moment; the outcome is implied | a primary source exists and can be identified | it is used as a stunt; say what it was as soon as it ends |
| An ordinary moment just before the break | builds the bond and the irony at once | the title or the opening has told the viewer something is coming | the ordinary stretch runs long without a question; cut sooner to the first sign of trouble |
| A later person at the remains, trying to recover the story | their difficulty becomes the viewer's question and admits how thin the evidence is | the subject is old and the record thin | their thoughts must be invented; use what they wrote, mark any imagined thought once, and close the frame within minutes |
| A stamp of place, date and scale, then a paradox | quick orientation, then a question | investigations, puzzles, unexplained events | the paradox is overstated; state it as the record does |
| The outcome first, then the question of how | turns curiosity from what to how | a known outcome | the "how" adds nothing new; find the question the outcome leaves open |
| A whole life compressed into one sentence, then a pause | the arc and a mood together | a ship, a building or a person whose end is known | the sentence overloads; keep one image and one fact |

- **Say the place and the period aloud,** early: the sea, coast or country, and the decades. In fiction told as documentary, give both the story's setting and the real one. If neither the novel nor the record gives a year, say so, and give the widest place and period the ledger supports. Terms of the trade alone leave the listener to guess where and when they are.
- **Name the frame in the opening:** a true story; a story told in the documentary manner; or a novel and the history behind it. Name the novel and its author as you would any source. A title with no author leaves the listener unsure whether the book exists.
- **Name the key source early** when the video's authority rests on it. One sentence will do; bring the other sources in where they matter.
- **Keep business out of the opening** (greetings, sponsors, appeals, channel news). If a channel needs an introduction, put a short one after the cold open.

## 7. Names, places, dates and terms at first need
- **Role before name.** Introduce a person by role, relation or deed, with the name: "the man at the signal lamp, his brother Tomas". After a long absence, reintroduce them by the most vivid thing they did or their relation to the story, not by rank.
- **One name per person, kept stable.** Do not rotate names, titles and epithets for the same person in narration. Flag a reused name at once ("a second man of the same name").
- **Budget the names.** Each new named person costs attention. Name those who return; describe the rest by role, or count them. A chain of relations ("the friend of the neighbour of the man who hired him") can replace a run of names.
- **Places by ear.**
  - Before action moves through a place (a ship, a building, a stretch of coast), tour it briefly in words and reuse its landmark words later.
  - Give modern names beside old ones.
  - Where the geography confuses, give one rule for staying oriented ("upriver, here, means south").
  - A verbal zoom from the widest frame to the spot works when it is short and says why the place matters.
- **Figures and dates.**
  - one figure per breath, rounded, with one comparison the ear can hold;
  - convert into one familiar unit;
  - prefer relative dates ("three weeks later") once the year is set;
  - work the deciding figure aloud;
  - leave spare numbers to the screen.

  A dense run of figures can hold if it moves in one direction, like a clock counting down or a distance shrinking.
- **Figures heard together combine.** A listener multiplies a rate by a duration and subtracts one date from another. "Eight dives in a quarter of an hour" beside "from sunrise to sunset" becomes hundreds of dives a day. Check what the ear will compute from figures in neighbouring sentences. Then separate them, qualify them as the source does, or drop one.
- **The general and the particular.** "A diver" (any diver, in the history) and "he" or "the diver" (the story's man) drift into each other by ear. When the narration moves between the trade in general and one person, say which.
- **Near-homophones.** Check the title and the key nouns for words they can be heard as ("ledger" and "letter"). Gloss once at first use: "the ledger, the book of debts".
- **Terms.** Gloss a term in the same breath as its first use, by what it does in this story, then keep that one word. A term from another language can collide with a word the listener knows (a local name for a job heard as an unrelated title). If it does, keep the plain gloss as the working word and give the local term once. Teach it just before it matters, inside a moment where it already matters, and use it again at the payoff. Do not define terms the story will not use. A term left unexplained is cheap once and costly when they pile up for a viewer new to the period.
- **The basic situation is never a mystery** unless the plan says so: who someone is to whom, what a place is, the year, a job (`clarity-and-orientation.md` §9).

## 8. Withholding in a true story
Withholding should reward attention, never trick it. Hold back meanings, causes and verdicts, not the basic facts.
- **Plant in passing and pay off in the same words.** A small fact mentioned in an ordinary moment, such as a door left open, a loan or a crack, later explains the ending. When it returns, use the same plain words. If the gap is long, admit the viewer may have forgotten it, and bring the object back once in between.
- **Test a clue's logic against everything the viewer will know at the payoff.** A detail already explained by facts the viewer holds proves nothing: a rope still dry on the day a man refused to dive is one. If the adaptation adds a clue the novel lacks, check it against the novel's own chain of causes (`mystery-and-clues.md`).
- **Announced deferrals** ("we will come back to the missing letter") hold a question across a long middle. They work when the stated distance is honest and the promise is paid; restore the setup in a clause when you pay it. Keep no more than two such promises open. An unpaid promise, or "in a moment" that means fifteen minutes, teaches the viewer to discount the next one.
- **Flags** ("this will matter") work when they are rare and always paid. Repeated, they become noise; let placement do the work instead.
- **Hold a person back until their motive reframes the question,** or a source until reliance on it begins. But give a source's stake in one clause at its first use, before it shapes scenes.
- **Return to an earlier moment in its original words,** so that a new meaning falls on the viewer without a retelling. This is fair only if the first telling attributed the account. If it stated one person's version as fact, the later twist cheats.
- **Tell an official or invented version at full strength, then take it apart** with the evidence, so the viewer feels how the deception worked. Signal from the start that it is a version, through an attribution or a touch of irony, so the viewer does not feel deceived by you.
- **Name the record's silence** at the moment the viewer wants the answer: "the report never says what the last message contained." An admitted gap keeps trust, and it can be the most human moment in the film. Raised early and paid at the end, the gap in the record can carry the final loss.
- **A known outcome, a hidden meaning.** Options:
  - tell an earlier event out of order, at the point where it answers a later question;
  - judge a key object alone first, then in its context.

## 9. Who says so: attribution, doubt and the narrow claim
The ear needs a claim's status when the claim is heard, not three sentences later.
- **Mark the distance from the source as you say it,** with a verb ("claimed", "remembered", "the inquiry found"), a tense or a framing clause. Say what a witness could know: where they stood, for how long, and what they could see.
- **Set the rules of evidence early** when the sources are doubtful: who wrote the record, how far from the events, and with what stake. Test one claim in full, so the viewer can weigh the later ones.
- **Legends and doubtful stories.** Say it is a legend before you begin, or in its first sentence. Tell it whole if it carries the drama, rule on it in one plain sentence, then say what it reveals about the people who told it. If the legend's plot later drives events, mark the sentence where the record resumes.
- **Competing accounts.** Give them in order, label each by who told it and why, and end on the narrowest claim the evidence supports.
- **Reconstructions and imagined feeling.** Label them as plainly and as concretely as the scene itself, and name the missing evidence. Keep the conditional through the whole passage and keep invented numbers out. A short disclaimer after a vivid scene leaves the scene in memory and loses the disclaimer.
- **Renew the attribution at the peak.** The line between record and claim blurs most often at the dramatic climax: testimony framed once and then narrated as event, or a reconstruction slipping into the plain past tense. Re-attribute there, in a clause.
- **Close quotations audibly.** The listener must hear where a quoted document ends: a change of voice, a closing attribution, or the narrator resuming with a plain line of consequence.
- **Your own view.** Give each side its strongest form first, then state your view once, late, marked as yours. Do not let jokes, ridicule or an imagined scene of the other side deliver the verdict.
- **Hedge what is uncertain and state plainly what is not.** A hedge in every sentence hides the few real leaps.

## 10. Writing for the ear
- **Sentence length follows the job.** Explanation and context can run long, but testimony, turns, deaths and verdicts run short. The studied narrators averaged anywhere from about thirteen to twenty-eight words a sentence. What served the listener was contrast at the right places: a short sentence after long ones is where attention lands.
- **One idea per sentence at a decisive point.** Keep the subject near its verb, and put the news at the end of the sentence, where the voice falls and a pause can follow.
- **End the paragraph on its strongest line, then pause.** Keep the effect for turns and verdicts. Used at every paragraph end, it becomes audible machinery.
- **Plain, concrete words for narration.** Save heightened language for a few set pieces and the close.
- **Transitions name the relation:** cause ("because", "so"), contrast ("but"), time ("three weeks later"). A section can open on the last word or idea of the one before.
- **Take stock at the end of each movement:** one or two sentences on what is now known and what is still open. Keep the open clue the next section needs in the recap, not just the most vivid details. Bring back a planted fact in a clause just before it pays off.
- **Callbacks.** An image, phrase or fact from the opening returns at the end, changed by what the viewer now knows.
- **What the ear cannot take:**
  - parentheses;
  - "the former" and "the latter";
  - long lists;
  - strings of letters or digits read aloud;
  - a pronoun with two possible owners;
  - words that point at a picture the listener may not see.
- **Humour** relieves density. Place it right after a dense passage and away from deaths, danger, lost evidence and sincere lines.
- **Read every line aloud at the narrator's pace,** and time each section from the reading, not from a word count. The studied narration ran at about 110 to 155 words per minute of runtime. That figure already includes pauses and music, so do not add them again: it is slower with held pauses, faster in dense explanation.
- **When you cannot read the script aloud,** as with a draft written for a narrator:
  - estimate each language separately from words per minute;
  - say that the figure is an estimate;
  - leave the timing to the narrator.

  Check that no single line needs an impossible pace. Arabic and English word counts are not comparable.
- **Your own voice.** Learn the principle, not the phrasing. Strip out any borrowed catchphrase, signature sentence shape or recurring structural move. Watch your own devices too: any device used in every section becomes a tic.

## 11. Narrator, picture, sound and silence
- **Write in three tracks** (`assets/templates/narration-script.md`): what the narrator says; what the picture shows; sound, music and pauses. Tag each narration line with its ledger status.
- **What only the narrator can carry:** the facts the story stands on, who says so, how sure it is, the links between events, and the question. Do not leave these to on-screen text alone when viewers may be listening.
- **What the picture can carry:** place, scale, faces, documents as evidence, maps, and the look of a period. When the picture shows it, the narrator need not describe it, but still says what matters about it.
- **Words that point at the screen** ("as you can see") fail for listeners. Use them only where the picture is the evidence, and say in words what it shows.
- **Where the viewer needs a pause:**
  - after the line that says what a death, betrayal or discovery meant;
  - at section ends;
  - after a primary voice.

  The event itself can run straight through. Mark each pause in the sound track with its length. A pause after a strong line lets it land; a pause after every line flattens everything.
- **Other voices** (archival audio, actors reading sources, interviews). Introduce each by who they are and what they saw or wrote, and take the telling back with a plain line of consequence. A voice that starts in the middle of a paragraph and is never handed back leaves the listener unsure whose words they heard.
- **Music and sound** are planned in the sound track. Never use them to lend false authenticity, such as crackle on invented "archive" audio, without a label (§15).

## 12. Real people, death and room to absorb
- **Give each death a plain sentence of its own,** stated so that a first-time listener knows it happened. Decide when the viewer should understand it: at once, at the end of a reconstruction, or at a later reveal, with the doubt labelled. The lens is the one used for fiction (`clarity-and-orientation.md` §6).
- **Scale the room to the person's weight in the story and the viewer's attachment.** A death that only moves the chronology on can pass in a clause. A person the viewer has followed for an hour needs a sentence of their own and time after it, even if all you can say is that the record falls silent.
- **Let other voices carry the grief:** survivors' testimony, the dead's own words (letters, messages, a last call), witnesses of the time, laments. Keep the narrator's own words plain.
- **Ways to give room** (the options in `emotion.md` §6 apply):
  - a reconstructed last day that ends on a sensory absence;
  - one human detail, placed after the fact;
  - a pause after the line of consequence;
  - the names and ages of the dead at the end, followed by silence and nothing administrative.

  A two-pass telling is an option seen in one channel: the discovery first, told briskly, then the person's last hours, where the feeling lands.
- **What not to put next to a death:** blame in the very next sentence, an explanation, a run of figures, a sponsor or appeal, or a joke. Give a beat, a name or a human detail first.
- **Blame fairly.** Quote verdicts exactly and add the system's share. Read the last decisions of the dead as charitably as the evidence allows, with a hedge, and keep your speculation labelled.
- **Victims are people before they are wounds.** Where the record allows, meet a victim by name and life before, or close to, the injury. Keep graphic detail in the sources' words, and keep it short.
- **Mass death.** Acknowledge the toll once, in specific words, before it becomes a figure in an argument.

## 13. Unfamiliar worlds and mechanisms
For viewers who have never heard of the trade, the period or the place:
- **Teach one mechanism at a time, just before it matters,** step by step and with one image, inside a moment where it already matters.
- **Work a small example from the user's seat** before a real person uses the thing: how a signal lamp spells a word, how a cipher shifts its letters, how a hatch lets water in. The real attempt is then heard as a test of what the viewer now knows.
- **Use one everyday analogy, aimed at one paradox,** and cut its spare parts.
- **Define by consequence:** what the thing does to the people in this story.
- **Give the listener one recurring object or place to track:** a lamp, a logbook, a hatch, one weak leg of a structure.
- **Build the place in words** before anyone moves through it.
- **Where explanation stalls:**
  - a primer on terms the story never uses again;
  - a prelude of figures before any person appears;
  - a lesson that outlasts its question;
  - an explanation inserted while a question hangs unanswered.

  In a braid of story and history (§15), history that arrives while a story question is open is the design, not a stall, provided a sentence ties it to that question or raises its stakes. It stalls when it answers nothing either strand has asked.

## 14. Long runtimes: threads, stock-taking and business
- **Keep one live thread through a long run of episodes:**
  - a clock (a deadline, an arrival, a date coming within reach);
  - an argument that gains a voice each time it returns;
  - an image or short parable that comes back at each fracture.

  Each return must add something.
- **Reintroduce people by their deeds.** Recap through a character's memory where you can, and take stock at the end of each movement (§10). A long account whose landmarks keep people and places clear can still lose the argument. One sentence on which explanations are still standing repairs that.
- **Chapters need a spoken signal:** a date restart, a change of place, a short line that names the new stretch. A title card alone is lost on listeners.
- **Keep business at the seams:** before the story, at a section's end, or after the end. Never put it between a promise and its payoff, in the middle of a figure, straight after a death, or after a memorial.
- **Mention another video only with a recap** a newcomer can follow.

## 15. Fiction told as documentary
The documentary manner borrows nonfiction's authority: a calm narrator, dates, documents, archive-like pictures. Used on invented events, that authority can mislead. The task is to keep the immersion of the manner while the viewer always knows which strand they are in.

**Choose the frame and say it at the start**, in the narration, on screen and in the description:

| Frame | What the viewer is told | What it achieves | When it gets in the way; then |
|---|---|---|---|
| A story and its world, braided | which strand is the novel ("in the novel…") and which is history | teaches real history through a story; history arrives at the story's own moments of need | the switching feels like a lecture; switch at the story's questions, not on a timetable |
| A dramatised story in the documentary manner | at the start: the people and events are invented, and the world around them is real; then a reminder at each seam | immersion close to a true-crime telling | late joiners and clips lose the frame; repeat the label at each chapter and in the description |
| A mock documentary (invented archives, interviews, documents) | that it is fiction, before it begins and in the packaging | the strongest immersion and play | it is the most easily taken as fact; disclose realistic synthetic material, and never place a real person or a real event inside invented evidence |

**Keep the strands apart.**
- **Give the ledger F and A statuses** (§3). Every F line must be recognisable as invention, by the frame the viewer was given and can still recall, or by a marker at that line.
- **"In the novel" promises that the book contains it.** List the adaptation's own additions (A). Voice each one as the video's own, or cut it.
- **A frame that calls the world real vouches for every world detail inside the invented scenes:** the gear, the routines, how debts were kept, how long a season ran. Enter those details in the ledger like H rows. Then verify them, mark them as the novel's, or leave them out.
- **Use three audible registers:**
  - what the record shows;
  - what someone claimed, or what is uncertain;
  - what the story invented.

  Renew the marker where the drama peaks, because that is where the lines blur (§9).
- **Mark the seams.** Where an invented event touches a real one (an invented keeper in a real lighthouse service, an invented diver inside a real system of debt), say which is which in the same sentence: "The storm is on record; this boat is the novel's."
  - **The riskiest seam is the hand-off sentence,** where a history question is answered with the novel's object, or a scene from the novel is explained by a general claim about the trade. Give that sentence its own marker.
  - **The habitual past is heard as how the trade worked** ("captains kept…"). Keep the novel's objects out of it.
  - **The unverified seam.** When the novel's object might also have been real and your sources do not say, say that too ("whether real captains kept such books, the source does not say"). Otherwise the viewer assumes one or the other.
- **No invented evidence for real claims, and no real evidence for invented events.**
  - Never put invented words or deeds in the mouth of a real person or institution as if documented.
  - Never caption a real archival photograph as an invented character.
  - Present an invented document as the story's document.
- **Label pictures and sound:** reconstructions, paintings, generated images and dramatised audio. YouTube asks creators to disclose realistic altered or AI-generated content: a real person shown saying or doing what they did not, altered footage of a real event or place, or a realistic scene that did not occur. It may add a label itself (YouTube Help, "Disclosing use of GenAI content", checked November 2026). An "illustration" label says the image is not a photograph, not which strand it belongs to. Give each strand its own look: one visual treatment for the novel's scenes, another for the history.
- **History at the story's first need.** Give the real context exactly when the story needs it: the quarantine law when a ship is refused a harbour, not a lecture before the story starts. Mark uncertain history as uncertain; a novel's setting does not make a disputed date firm.
- **Departures from history.** Where the novel compresses, invents or departs from the record in a way a viewer could carry away as fact, say so once.
- **Spoilers are a promise.** Decide whether the video retells the whole novel or stops before its solution, and say which in the opening or the description.
  - State the promise as the questions the video will not answer.
  - Check the history strand and the narrator's inferences against the withheld chapter: history that explains the novel's secret gives it away.

**Adapting a novel's design.**
- Design the information plan for a viewer who has not read the book. The novel's secrets may need a different order by ear.
- Keep the novel's decisive moments legible on first hearing. A death that a reader could reread is gone for a listener in one breath (§12).
- **Choose what the video keeps of the novel's mystery:**
  - tease it and stop before the solution;
  - retell it whole;
  - or tell it as the novel's version, then step out into what the history can and cannot confirm.
- **Run the story engine on both strands:**
  - the novel's protagonist wants something against an obstacle;
  - the historical strand has its own question (what was this world, and what did it cost the people in it?).

  Braid them so each answers a question the other has raised.

**Phrases that mark the strand** (patterns to adapt, not to repeat in every sentence):
- In English: "In the novel…"; "The story imagines…"; "No record tells us…, and the novel fills that silence with…"; "Historically…"; "The records show…"; "Accounts differ on…".
- In Arabic: «في الرواية…»، «تتخيّل الرواية…»، «لا تذكر السجلّات… وتملأ الرواية هذا الصمت بـ…»، «تاريخيًّا…»، «تقول السجلّات…»، «تختلف الروايات في…».

## 16. Narrating in Arabic
Write and revise Arabic narration with `arabic-writing.md` §12. It covers:
- register for the ear;
- verb-first event sentences;
- short construct chains and relative clauses one deep;
- connectives that name the relation;
- role before name;
- numbers written out for the narrator;
- vowelling for the performer;
- where the pause falls;
- formulae at a death;
- timing the Arabic aloud.

For an Arabic version of a script written in another language, add `translation.md` §6.9. Compose the Arabic narration for the Arabic ear, and do not carry English sentence order into it.

When two narrations share one picture:
- keep the order of the cue points, and rebuild the order of words inside each row;
- re-cut the picture to the Arabic, or, if the picture is locked, shorten the Arabic lines that run long;
- brief each language's audience separately, since viewers in the region may already know the trade.

## 17. Revising a documentary script
Run the passes from big to small. They test effects. They are not a shape every script must take: a quiet portrait may have no reveal, and a puzzle may have no deaths.
1. **Question and promise.** Does the opening set a question that the ending answers, or honestly leaves open? Is every promise kept, the causal one included?
2. **Sequence.**
   - every section has a job;
   - small questions open and close;
   - the turns are said in words;
   - the proportions suit the runtime;
   - stock is taken at the end of each movement.
3. **Truth.**
   - every line maps to the ledger;
   - attribution is renewed at the peaks;
   - quotations end audibly;
   - fiction is marked at every seam, the hand-off sentences included;
   - the adaptation's own additions are voiced as its own;
   - every source keeps its modality;
   - no evidence is invented.
4. **First need.** Names, terms, places and figures arrive when needed. Cut the overloaded minutes.
5. **Weight.**
   - each decisive moment is legible on first hearing;
   - each death has its own sentence and room scaled to the person;
   - nothing administrative or flippant sits beside a death.
6. **The ear.**
   - read aloud and time it;
   - short sentences at turns;
   - the news at the end of the sentence;
   - no pronoun with two owners;
   - no near-homophone left unglossed;
   - no adjacent figures that the ear will combine into a false one;
   - no pointing words without a description.
7. **Picture and sound.** What does the picture carry, and does the script survive audio alone? Is each pause marked where the viewer needs it?
8. **Payoff.** The ending answers the opening, changed. The strongest earned line comes last, and business comes after.
9. **Signatures.** Strip borrowed catchphrases and recurring structures, and vary your own repeated devices.

**The cold listen.** Someone who knows nothing of the plan hears, or reads, only the narration track, in order. A fresh pass of your own can stand in. At the end of each section they say:
- what they believe happened;
- who is who;
- what is established, what is claimed and what is invented;
- what is still open.

Log every stumble (`assets/templates/comprehension-log.md`) and fix the script, not the listener.

## 18. Failure patterns and repairs
| Failure | Symptom | Repair |
|---|---|---|
| The overloaded minute | names, dates and figures stacked faster than the ear can hold | one figure with one comparison; count the rest; leave spare numbers to the screen |
| The silent prelude | a quarter of the runtime goes by before a person or a question | put a person and a question in the first minutes; move context to first need |
| The unpaid flag | "this will matter", and it never does | pay it or cut it |
| The blurred peak | testimony, a legend or the novel's invention narrated as plain fact at the climax | re-attribute in a clause at the peak |
| The open quotation | the listener cannot tell where a document's words end | close it with a voice change, an attribution or a plain line of consequence |
| The death in a clause | a person the viewer followed dies in a subordinate clause or a list | give the death its own sentence, then room |
| Blame after the toll | the next sentence after the deaths turns to fault | give a beat, a name or a detail first |
| The joke beside the loss | humour next to a death, danger or lost evidence | move it to the end of a dense passage elsewhere |
| The picture-only argument | the evidence is on screen and the words give only the verdict | say in words what the picture shows |
| The elegy instead of the answer | the ending mourns but never says why | one sentence of synthesis, then the elegy |
| The claim that outruns the evidence | the closing verdict is stronger than the sources just quoted | make the claim only as strong as the evidence |
| Business inside the story | an appeal between a promise and its payoff, or after a death | move it to a seam |
| The device turned tic | the same opener, closer, flag or name-last sentence in every section | vary it, or keep it for the one moment that earns it |
| Fiction that sounds like history | an invented event told in the same voice as the record | mark the strand at the seam; renew the frame at chapters |
| Invented evidence | a fake quotation from a real person or a fake archive citation | remove it; present invented documents as the story's own |
| The hand-off seam | a history question answered with the novel's object, in the habitual past | mark the strand inside that sentence |
| The addition sold as the novel's | "in the novel" before a detail the book does not contain | voice it as the video's own, or cut it |
| The clue that proves nothing | a planted detail already explained by what the viewer knows | test the clue's logic at the payoff; replace it |
| Figures that multiply | a rate beside a duration, or two dates in neighbouring sentences | separate them, qualify them as the source does, or drop one |
| The anonymous source | "an account", with a date but no kind or author | name its kind and outlet once |
| The missing setting | no place or period said aloud; the listener guesses from the terms | say both early, the story's and the real one |

## 19. Checklist
- [ ] The brief is fixed: runtime, audience knowledge for each language, the audio-only share, the setting, the frame, spoilers.
- [ ] The place and the period are said aloud early (in fiction told as documentary, the story's and the real one).
- [ ] The truth ledger covers every narration line (H / C / U / F / A), one status per sentence, with sources for H and C; unverified facts are marked U or cut; sources keep their modality; a lone source is named once with its kind.
- [ ] The central question and the promise are set early; the scope is stated; the ending pays what was promised.
- [ ] The known outcome sits where the suspense needs it (opening, middle, end or verdict first), and no known fact is withheld coyly.
- [ ] Every section has a job; small questions open and close; turns are said in words; stock is taken at the end of each movement.
- [ ] Each name comes with a role and stays stable; terms are glossed by function at first need; figures come one at a time, with a comparison.
- [ ] Withholding is fair: plants are paid in the same words, deferrals are honest and kept, and the record's silences are named.
- [ ] Attribution is heard with each claim, renewed at the peaks, and every quotation closes audibly.
- [ ] Each decisive moment is legible on first hearing; each death has its own sentence and room scaled to the person; nothing administrative or flippant sits beside it.
- [ ] The script survives audio alone; pointing words are backed by a description; pauses are marked.
- [ ] Fiction told as documentary:
  - the frame is stated at the start;
  - seams are marked, the hand-off sentences included;
  - "in the novel" is used only for what the book contains;
  - world details inside invented scenes are verified or marked;
  - no evidence is invented;
  - each strand has its own look, and synthetic or reconstructed pictures are labelled.
- [ ] Adjacent figures were checked for what the listener will compute; near-homophones are glossed.
- [ ] Arabic narration has been checked with `arabic-writing.md` §12 and read aloud.
- [ ] The script was read aloud and timed; the cold listen is logged and its stumbles fixed.
- [ ] No borrowed catchphrases or signature structures remain, and no device of your own repeats in every section.
- [ ] If the narration will be synthesised (§20):
  - each scene was read for feeling, emphasis, slowing and silence before any control was added;
  - the spoken text holds only what the chosen model should speak, plus the controls it supports;
  - clips split at scene boundaries, with the same settings throughout and stitched;
  - long or exact pauses left to the edit.

## 20. Voicing the script with ElevenLabs (Multilingual v2 and Eleven v4)
This section prepares a finished narration script for two ElevenLabs text-to-speech models: **Eleven Multilingual v2** and **Eleven v4**. The facts about the models come from ElevenLabs' documentation, read on 12 November 2026:
- the models overview;
- "What is Eleven v4?" and the Eleven v4 guide;
- text-to-speech best practices;
- the Create speech API reference;
- the request-stitching and pronunciation-dictionary guides.

The platform changes often. Check a model's page before relying on a control, and never invent one.

### 20.1 Read the scene before directing the voice
Direct the voice from the script, not from the model's menu. For each section, write in the production notes:
- **what the listener should feel,** in a word or two (unease, curiosity, grief, a dry smile);
- **the one word in each key sentence that carries the news.** Usually it is the word the sentence ends on (§10).
- **where the narrator should slow down or drop the voice:** a turn, a death, a discovery, an admission of what the record does not know. Most lines need neither.
- **where silence should fall:** after the line that says what a reveal or loss means, not after the event itself (§11–12), and for how long.

Turn each choice into the plainest means that works, in this order:
1. **The words.** Shorter sentences slow the delivery and put a beat between facts. Ending a sentence on the key word gives it weight. A plain line read evenly usually carries a loss better than any direction.
2. **Punctuation.**
   - a full stop for a beat, a comma for a breath;
   - a dash for a turn or an interruption;
   - a question mark where the line really is a question.

   Ellipses add hesitation, so use them only where hesitation is meant.
3. **A supported control in the model** (§20.2, §20.3): a short break tag in Multilingual v2, or a rare audio tag in Eleven v4.
4. **The edit.** Any silence longer than a breath, and any pause that must be exact, is added in the edit, at the clip boundary. The script's sound track gives its length.

**Keep the performance restrained and varied,** so it sounds like a person telling the story.
- Give one direction to a moment, not one to every line.
- Let most lines run without any control.
- Never whisper or sigh twice in a row.
- If several sections carry the same direction, the voice becomes a mannerism, the same tic problem as in writing (§10).

### 20.2 Eleven Multilingual v2 (`eleven_multilingual_v2`)
**What the model is.** The documentation calls it the most stable model on long-form generations. It covers 29 languages, including Arabic (Saudi Arabia, UAE). It is the API's default `model_id`, and it takes up to 10,000 characters a request (about ten minutes of audio).

**Pauses.**
- Use `<break time="1.5s" />` for pauses of up to 3 seconds.
- The documentation warns that many break tags in one generation can cause instability: the speech speeds up, or noise and artifacts creep in. Use a few at the moments that matter, and make anything longer in the edit.
- A dash often gives a short natural pause. An ellipsis tends to add hesitation or nervousness.

**Audio tags.** The documentation lists audio tags only for the v4 and v3 families, not for Multilingual v2, and warns that descriptive text is spoken. Carry emotion through the text itself, which this model reads for emotional context.

**Pronunciation.**
- Multilingual v2 does not support phoneme tags. Respell the word in the spoken text, or attach a pronunciation dictionary with **alias** rules, at most three dictionaries a request.
- Dictionary **phoneme** rules are skipped by this model.

**Numbers.** Normalization is on by default, and this model handles numbers well. Still write numbers and symbols out in the spoken text: the documentation advises it for multilingual models, and so does `arabic-writing.md` §12 for Arabic narrators.

**Voice settings** (API defaults):
- `stability` 0.5;
- `similarity_boost` 0.75;
- `style` 0, which the documentation recommends keeping at 0;
- `use_speaker_boost` true;
- `speed` 1.0 (the best-practices page gives 0.7 to 1.2, and warns that extremes cost quality).

The documentation's common starting point is stability about 0.5 and similarity about 0.75. A steadier documentary read usually wants stability a little higher. Fix the settings once and keep them for every clip.

**Language.** The API reference says `language_code` is not supported for Multilingual v2 models; leave it out.

**Continuity.** Send `previous_text` and `next_text`, or `previous_request_ids` and `next_request_ids` (§20.4).

```bash
curl -X POST "https://api.elevenlabs.io/v1/text-to-speech/YOUR_VOICE_ID?output_format=mp3_44100_128" \
  -H "xi-api-key: YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "text": "At midnight, the lamp went out. <break time=\"1.5s\" /> By morning, the keeper was gone.",
    "model_id": "eleven_multilingual_v2",
    "voice_settings": {"stability": 0.6, "similarity_boost": 0.75, "style": 0, "use_speaker_boost": true, "speed": 1.0},
    "previous_text": "For eleven years, he had never once let the light fail.",
    "next_text": "His logbook lay open on the table, the last line unfinished.",
    "seed": 1234
  }' \
  --output 04-the-lamp.mp3
```

### 20.3 Eleven v4 (`eleven_v4`)
**What the model is.** The documentation calls it the most emotionally rich, expressive model. It suits audiobooks and long narration with complex emotional delivery. It supports 90+ languages, including Arabic (`ar`), and takes up to 10,000 characters a request.

**No SSML.**
- Eleven v4 supports neither SSML nor break tags.
- Pauses come from punctuation (ellipses add pause and weight), from the structure of the text, and from audio tags.
- Exact silences are added in the edit.

**Audio tags.**
- Audio tags go in square brackets, just before the words they shape.
- The documented tags include delivery and breath: `[whispers]`, `[sighs]`, `[exhales]`, `[pauses]`.
- They also include emotion: `[curious]`, `[sarcastic]`, `[excited]`, `[crying]`.
- And they include sound effects such as `[applause]`, which a documentary narration should not use.
- Tags can be combined.
- Name the voice quality you want plainly, since a vague tag can be performed as a sound.

For a narrator, use a tag only where the words and punctuation cannot carry the moment, and no more than once in a passage. A tag on every line is the audio form of a tic.

**Pronunciation.**
- Write IPA between forward slashes in the text, with stress marks: the documentation's example is `/ˌbaɪoʊˈkemɪstri/`.
- Pronunciation dictionaries with phoneme rules work with `eleven_v4`, and so do alias rules.
- For IPA or CMU pronunciation in languages other than English, the documentation points to v4.

**Voice settings.**
- Use `stability` and `similarity_boost`. The v4 pages say the Style and Speed sliders are not available. Another page lists speed for all models, so the documentation disagrees with itself; follow the model's own page and do not send `style` or `speed`.
- Lower stability gives more varied, expressive delivery, and higher stability gives more consistency across generations. For narration split into many clips, keep it moderate to high and identical in every clip.
- `clone_strength` applies only to professional voice clones fine-tuned for v4 (start at 0).
- Speaker boost is not mentioned for v4; leave it out.

**Language.** Send `language_code` (ISO 639-1, e.g. `"ar"` or `"en"`), which sets the normalization rules.

**Continuity.** Request stitching works with `eleven_v4`; the documentation's own example uses it (§20.4).

```bash
curl -X POST "https://api.elevenlabs.io/v1/text-to-speech/YOUR_VOICE_ID?output_format=mp3_44100_128" \
  -H "xi-api-key: YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{
    "text": "At midnight, the lamp went out... [exhales] By morning, the keeper was gone.",
    "model_id": "eleven_v4",
    "language_code": "en",
    "voice_settings": {"stability": 0.6, "similarity_boost": 0.75},
    "previous_request_ids": ["REQUEST_ID_OF_CLIP_03"],
    "seed": 1234
  }' \
  --output 04-the-lamp.mp3
```

### 20.4 Into the YouTube workflow: clips, consistency and retakes
- **Split at scene boundaries.** One clip is one section or one scene, ending where the script's sound track has a pause, a music change or a cut.
  - Never split inside a sentence, or between a reveal and the line that says what it means.
  - Each clip stays far under the 10,000-character limit, so a bad take costs one scene.
  - Number the clips in script order (`03-the-empty-mat.mp3`).
- **Keep the voice consistent.**
  - Use the same `voice_id`, `model_id`, voice settings, `seed` and `output_format` for every clip, recorded once in the production notes.
  - Stitch each clip to its neighbours. Read the `request-id` response header of each finished clip, and send up to three of the most recent IDs in `previous_request_ids`, the closest last. Use `next_request_ids` when regenerating a clip that already has a successor.
  - The documentation says the IDs should be no older than two hours, and that stitching works best with the same model throughout. When the IDs have expired, send the neighbouring text in `previous_text` and `next_text` instead.
  - Stitching does not work with `enable_logging=false`.
- **Regenerate a single section** when its delivery or a pronunciation is wrong:
  - change only that clip's spoken text (or its seed);
  - keep every other setting;
  - send the neighbours' request IDs, or their text, so its prosody matches theirs;
  - fix pronunciation in the text: a respelling or a dictionary alias in Multilingual v2, IPA in slashes or a dictionary phoneme rule in Eleven v4. Do not change the voice settings to fix one word.
- **Keep production notes out of the text the API speaks.**
  - Every clip has a *spoken text* field holding exactly what is sent: the narration, plus only the controls the chosen model supports (break tags for Multilingual v2; audio tags and IPA for Eleven v4).
  - Everything else stays in separate fields of the clip sheet: the feeling, the emphasis, pause lengths for the editor, picture cues, ledger tags.
  - The model speaks descriptive text aloud. In Eleven v4, any square bracket in the text is read as an audio tag, so the script's own production marks must never travel inside the spoken text.

| Clip | Spoken text (exactly what is sent) | Model and controls used | Production notes (never sent) | Request ID | Take and status |
|---|---|---|---|---|---|

- **Check before sending, without calling the API:**
  - the JSON parses;
  - `model_id` is one of the two IDs above;
  - no control appears that the chosen model does not support (`language_code` or audio tags in Multilingual v2; `style`, `speed` or break tags in Eleven v4);
  - every break is 3 seconds or less;
  - every square-bracketed tag in an Eleven v4 text is a tag you meant;
  - the spoken text contains no production notes, digits or symbols you did not intend to have read out.
