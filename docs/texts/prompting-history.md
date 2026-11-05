# How the skills were invoked and combined

Based on the original conversations and saved prompt versions. Start with [the shorter project Prompting page](../prompting.html) for the main route. This longer account retains source distinctions and the consolidated teaching template.

The opening requests for both episodes named **Seedance Prompter V4**. **Narrative was introduced later**, to solve particular shot-writing and cutting problems. A starter that names both skills from the beginning is therefore a useful consolidation for readers, not a verbatim reconstruction of the original first message.

## 1. What the first message establishes

The first request does more than activate a skill. It establishes the task, the story source, the references, the creative intent and the limits of the assistant’s freedom.

### Episode 1: the original construction brief

The creator supplied a three-sequence script with shot descriptions, references, durations, dialogue, voice direction, lighting and sound. The instruction appended to that material named V4 and defined the preservation boundary.

**Cleaned historical instruction:** spelling and presentation have been edited; this is not a verbatim transcript.

```text
Use Seedance Prompter V4 to create three prompts from the supplied script.

You may optimize camera language and continuity, but do not change the narrative. If an important narrative change seems necessary, stop and explain it first.

Shot 11 must remain unchanged. Preserve the ending, except that the final shot may need more time so we can clearly see Malfoid walk away and Male 1 watching her leave.
```

The attached script was part of that first message. The short instruction on its own is not the whole input. Later changes to the ending belong to later creative decisions; they should not be folded back into this original brief. [S1]

### Episode 2: the more explicit launch brief

The Episode 2 launch identified the image roles, the three script sections, the emotional direction, the exact Japanese dialogue and a locked reveal. It also warned against treating every dramatic beat as restrained acting.

**Cleaned historical launch brief:** the supplied script sections and Japanese dialogue table remain separate attachments/inputs. This is not a new video-generation prompt.

```text
Use Seedance Prompter V4 to create three prompts from the supplied script sections.

Reference order:
Image 1 — Malfoid
Image 2 — Male 1 / Harry
Image 3 — Foideldore
Image 4 — The office

We are creating a retro-anime drama sequence focused on Japanese anime acting, emotional arcs and character personality.

You may optimize camera language, continuity and pacing. Preserve the narrative and use the provided Japanese dialogue exactly. If an important narrative change is needed, stop and raise it first.

Shot 16 is locked: the slow zoom and turn are essential. Do not reveal that Foideldore is a woman before the turn.

Do not apply understated acting to the whole sequence. Preserve the contrast between irritation, attraction, embarrassment and anger. Restraint can serve a particular beat, such as Foideldore’s stillness before the outburst.
```

The actual numbered file list in the launch resolves the image roles explicitly. An earlier attempt listed some attached files in a different order, so a reader should make the identity-to-file mapping unambiguous rather than rely on attachment order alone. [S2]

### Why these starts matter

- **The skill governs the method.** The supplied script governs the narrative; it is not already the finished generation prompt.
- **Creative freedom is bounded.** Camera and pacing can be developed without silently changing dialogue, a reveal or a locked shot.
- **Performance needs a target.** “Retro anime drama” was supplemented with emotional contrasts and character-specific direction.
- **References need roles.** A character sheet supplies identity and costume; it does not automatically supply scene blocking or a camera composition.

## 2. How the skill was made available

In the recorded workflow, the creator named the skill or its source project. The assistant then read the instruction file and supporting knowledge. There is no special activation phrase in these examples beyond making the intended source clear.

For V4, the source pair was:

- `skill.md`
- `seedance-prompter-v4-master-knowledge.md`

For the historical Narrative snapshot, it was:

- `SKILL.md`
- `references/knowledge.md`

The recorded discussion includes reads of both Narrative files before applying its method. Naming a skill is not a substitute for reading the knowledge that its instructions require. [S3]

For a reader using the downloadable packages, retain the complete package. The portable V4 package has a `SKILL.md` loader and renames the original instruction file to `instructions.md`; the loader identifies the required files. A local path is useful only when the assistant can actually read it. Otherwise, provide the file contents through the interface being used.

The walkthrough must distinguish the **historical Narrative snapshot** used in these examples from the **Narrative V1 package currently routed by the orchestrator**. They are not identical source versions. This is a version distinction, not a reason to duplicate the orchestrator.

## 3. Combination A: borrow Narrative’s cutting method inside V4

**Example: Episode 2, Prompt 1.**

The initial problem was how to show Harry’s continuing appeal alongside Malfoid’s reactions and private thoughts. The creator introduced Narrative because its method allows cuts inside one timed passage. The first request was to read and discuss the method, not immediately rewrite the prompt. [S3]

**Cleaned historical follow-up:**

```text
Read the Narrative Prompter and its knowledge file. Its method of cutting within one continuous passage may help here.

Keep V4 as the base. Let Harry’s dialogue continue across the picture cuts rather than requiring the whole line to finish before the camera can cut.

Describe Malfoid thinking to herself as part of the action. Use the SFX/audio-design fields for how Harry’s speech sits underneath her thoughts. Keep the existing lip-movement rule in her character block rather than repeating it throughout the acting.

Discuss the approach before editing. When implementing it, make the relevant character-state, motion-anchor and critical-constraint fields consistent too.
```

This consolidates the read/discuss request, the subsequent clarification and the implementation approval. It was not one original message. [S3]

### What changed in the prompt

V4’s overall structure and per-shot fields remained. Inside the shared passage for source Shots 04–05, the `Action:` description directed internal cuts while Harry’s line continued. The audio fields specified the intended relationship between the voices.

The saved Prompt 1 revision 4 demonstrates the approach:

- One timed range covers **14.5–23.0 seconds**.
- Harry begins the line on camera.
- At **15.5 seconds**, the picture cuts to Malfoid’s close-up while his speech continues.
- At **19.0 seconds**, it cuts to her view of Harry while the spoken/thought passage continues.
- V4’s `Camera:`, `Dialogue:`, `Delivery:`, `Action:`, `Lighting:` and `SFX:` fields are still present. [P1]

**The distinction:** this borrowed a technique for organizing the passage. It did not convert the whole prompt into Narrative’s complete format.

Narrative was not added to override a universal V4 ban on cutting during speech. The later source check identifies that supposed ban as an example-specific constraint the assistant had misapplied. The useful addition was an explicit way to write the connected passage. [S6]

### Keep the outcome honest

Revision 4 was a completed experiment, not the final selected Prompt 1 alternative. The later revision 5 removed Malfoid’s thought audio from the generation prompt, while retaining the internal cutting and Harry’s continuous speech. Its production note identifies Harry as the only speaking voice.

Both authoring versions have recovered submitted/provider payloads. Revision 5 is the saved Studio selection; that selection alone does not establish every frame used in the finished edit. Do not teach the revision 4 thought-audio design as though it were the unchanged final solution. [P1]

## 4. Combination B: use Narrative writing only for selected passages

**Example: Episode 2, Prompt 2.**

Here the creator wanted the selected emotional passages written as connected action: expression, camera, thought, background transformation and delivery occurring together. Separate fields were repeatedly separating events that needed to happen at the same time.

The intended combination was explicit: **V4 governs the overall prompt; Narrative handles only the agreed passages.** A whole-prompt conversion was rejected. [S4]

**Cleaned historical scope instruction:** this condenses several corrections, rather than quoting a single opening message.

```text
Keep the existing V4 prompt as the base.

Use the agreed Narrative method only for the two passages we are working on:
00.0–06.5 — the daydream and snapback
06.5–13.0 — the pointing outburst

These passages cover source beats 07–09. Write their camera, acting, thoughts, visible background changes and delivery as connected action, allowing cuts inside a passage where needed.

Keep the remaining shots in their V4 field structure. Preserve the approved dialogue, camera directions, timing and continuity outside the requested changes. Make only the state/continuity updates we have actually agreed to.

Do not convert the whole prompt to Narrative. Return the revised prompt and a specific summary of what changed.
```

### What the mixed structure actually looks like

This is a schematic of the saved arrangement, not a substitute generation prompt:

```text
[V4 setup: references, style, duration, characters and setting]

[SHOT SEQUENCE]
00.0–06.5 seconds:
[The selected Narrative daydream/snapback passage]

06.5–13.0 seconds:
[The selected Narrative outburst passage, including its internal cut]

13.0–17.5 — SHOT 10:
Camera: ...
Action: ...
Lighting: ...
Dialogue: ...
Delivery: ...

[Remaining V4 shots]
[V4 production notes]
```

The restoration is documented in Prompt 2 revision 10. The later revision 15, associated with completed render r15, retains this arrangement: Narrative in the first two timed passages, V4 fields in the later shots. Its recovered submission matches the authoring payload after removing boundary whitespace; the saved submission and provider readback are exactly equal. [P2]

This was a **local combination of methods**, not two competing templates applied to every part of the prompt.

## 5. The words that must survive cleanup

Removing frustration, repetition and typos must not remove instructions that control timing or meaning.

### “While” and “as” establish simultaneity

The creator explicitly corrected a rewrite that placed the action first and the dialogue afterward. The intended meaning was that Harry reacts **while Malfoid is shouting**, not that his reaction finishes and then she speaks. [S5]

The later Prompt 2 contains both kinds of coupling:

- The camera snap-zooms out **as** Malfoid shakes her head, the office returns, and her private refusal begins.
- Harry continues leaning away from her pointing finger **while** she continues shouting through the internal cut. [P2]

These conjunctions are part of the direction, not filler to polish away.

### “Continues” carries state across the cut

A cut does not reset a character’s blush, crossed or unfolded arms, lean, expression or ongoing speech. A later shot starts from the resulting state unless an action changes it. The same principle applies to room geography and each character’s position.

### Depth labels preserve readable blocking

The creator asked for foreground, background and backdrop language rather than ambiguous chains of “behind.” The approved discussion places Malfoid’s pointing hand in the foreground, Harry in close-up, and Foideldore in the backdrop beyond him, behind the desk near the windows. [S5]

### Keep action and constraints in their intended places

The acting describes what happens. Stable character rules belong in the relevant character block; scene-wide sound direction belongs in audio design. A constraint that is already established does not need to be appended after every action. [S3]

### A script must be translated into a prompt

The creator’s script explains the scene. Preserving its meaning requires preserving simultaneous action, offscreen speech, dramatic emphasis and transitions, not mechanically copying every script field into a disconnected prompt block. [S6]

## 6. A consolidated starter other people can use

**New teaching example, reconstructed from the recorded workflow and later corrections. This was not the creator’s original first message.** Replace bracketed inputs with the reader’s own material.

```text
Read [V4 instructions] and its complete master knowledge file. Use V4 as the governing prompt structure.

Also read [Narrative instructions] and its complete knowledge file. Apply Narrative only as specified below; do not replace V4’s overall format.

Task:
Create [number] video prompt(s) from [script/version/sections].

Clip duration(s):
[Required length for each prompt, or the approved timing source.]

Creative direction:
[Style, genre, intended emotional progression and performance contrast.]

References, in exact order:
[List each file and its role: identity, costume, environment, continuation video, start frame, etc.]

Preserve:
[Exact dialogue, narrative events, locked shots, reveal timing and important continuity.]

Creative freedom:
[What may be developed. Flag any change that would cross the preservation boundary.]

Secondary-skill scope:
Choose and specify one approach:
A. Borrow Narrative’s internal-cut/continuous-action method while retaining V4 fields.
B. Use Narrative paragraphs only for [named passages/time ranges]; retain V4 fields elsewhere.

For overlapping events, connect the camera, physical action, expression and dialogue with explicit timing language. Carry the resulting character state through cuts. Use the appropriate character and audio fields for stable rules and sound direction.

Work from [approved baseline], not an unapproved later rewrite. Return the draft prompt(s) and a concise explanation of the skill combination. Do not start a generation from this drafting request.
```

A real request should choose A or B, identify the exact passage and remove the unused option. It should also supply a duration or establish it before drafting. The template organizes decisions; it does not replace the two skills’ knowledge or the creative brief.

## Source notes for review

These identifiers provide an editor trace without reproducing the raw conversations in the article.

- **[S1]** Episode 1 construction request, 19 October 2026, message **67274**. The script attachment and appended V4 instruction are one input.
- **[S2]** Episode 2 preliminary request/restart, 26 October 2026, messages **70200**, **70260**, **70262**. The last is the explicit numbered launch with Japanese dialogue.
- **[S3]** Narrative read/discuss request and division of responsibilities, messages **70521**, **70536**, **70538**, **70540**, **70542**, **70546**, **70552**. Tool selection **70532** reads both historical Narrative files; the discussion/implementation confirmation is recorded in **70551–70553**.
- **[S4]** Selected-shot method and scope, messages **71195**, **71224**, **71434**, **71436**, **71438**, **71518**. Later whole-prompt conversion was explicitly rejected.
- **[S5]** Blocking, depth and simultaneity, messages **71607**, **71752**, **71757**, **71759**, followed by approval **71761**.
- **[S6]** Script-to-prompt distinction and continuing speech, messages **72745**, **72757**. The source check in response **72756** distinguishes an example-specific complete-line constraint from a universal V4 rule.
- **[P1]** `episode_02_v2_section_01_seedance_v4_v4.prompt.md` and `episode_02_v2_section_01_seedance_v4_v5.prompt.md`, checked against their recovered submissions and provider readbacks.
- **[P2]** `episode_02_section_02_seedance_v4_v10_scoped_shots.prompt.md` and `episode_02_section_02_seedance_v4_v15_camera_thought_overlap.prompt.md`; the latter checked against the r15 submitted/provider payload.
