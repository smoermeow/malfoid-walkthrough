# Prompting Episodes 1 and 2

I started both episodes with a script, character and environment references, and a conversational brief asking Hermes to use **Seedance Prompter V4**. I introduced Narrative later, for specific passages in Episode 2. The scripts supplied the story; the skills helped me turn it into generation instructions.

## Models and tools I used

- **Video:** Seedance 2.5, **480p throughout both episodes**, without upscaling.
- **Video-prompt writing:** Hermes with **Seedance Prompter V4**; I brought in **Seedance Narrative Prompter** later for selected Episode 2 work. These are writing skills, separate from the video-generation model.
- **Original character and environment images:** **Krea 2 Turbo** (`krea/krea-2/medium-turbo`) with my [Retro Anime inspired moodboard](https://www.krea.ai/moodboards/75bb7600-4c66-4dec-8ba7-cde9b9965c81?already_owned=1).
- **Character sheets:** Codex image generation. I used **GPT-image 2** for the sheets; the newer Foideldore requests specify **`gpt-image-2-medium`**. [The character-design walkthrough](../character-design.html) explains that process.
- **Assembly and music:** CapCut; Eleven Music for Episode 1's *Walked Away*. Episode 2 has no added music.

These skills can also work from references and a directed description of the events, style and camera treatment instead of a detailed script. For general use, go straight to the [V4 README](https://github.com/smoermeow/creative-skills/blob/main/video/seedance/seedance-prompter-v4/README.md) or [Narrative README](https://github.com/smoermeow/creative-skills/blob/main/video/seedance/seedance-narrative-prompter-v1/README.md). Here I’m following how I used them for these episodes.

**I’ve cleaned up my conversational instructions below for readability.** They retain the intent and boundaries, but are not verbatim transcripts. Exact generation prompts remain linked separately.

<h2 id="episode-1">Episode 1: working through the three sequences</h2>

### 1. Supply the material and define what can change

I supplied the [three-sequence script](../archive/episode-1/scripts/episode-1-three-sequences-26-shots.md), including shot descriptions, references, durations, dialogue, voice direction, lighting and sound. My opening instruction asked for three V4 prompts and explained what Hermes could develop and what it needed to preserve:

```text
Use Seedance Prompter V4 to create three prompts from the supplied script.

You may optimize camera language and continuity, but do not change the
narrative. If an important narrative change seems necessary, stop and
explain it first.

Shot 11 must remain unchanged. Preserve the ending, except that the final
shot may need more time so we can clearly see Malfoid walk away and
Male 1 watching her leave.
```

I mostly use Wispr Flow to talk these instructions into the microphone. They don’t need to be written like a technical specification, but I still need to say where I want creative development and what must stay intact. Here, camera language and continuity could be optimized; the narrative and the shots I had locked could not be changed silently.

### Why I wanted Shot 11 kept intact

I thought this was one of the coolest shots in the scene, and it was already directed well. I wanted that exact shot, not a version split into several shots or redesigned for extra coverage. Malfoid is behind Voldemort, and the composition needs to retain that relationship.

In the supplied script, her blitz arrival and killing curse are Shot 10. **Shot 11 is the ground-level shot where his wand drops and he collapses while Malfoid remains standing behind him.** That is the shot my opening instruction names. Keeping it intact was a deliberate creative choice, not a general restriction on the prompter’s camera work.

### 2. Translate the script into generation instructions

Hermes read V4’s instructions and master knowledge, then drafted all three prompts in its first response. Each established references, visual style, character states and the setting before a timed shot sequence with camera, action, dialogue, lighting and sound fields.

That initial drafting pass is separate from how I worked through production. **I developed and generated Episode 1 sequence by sequence:** the first section, then the second using the first clip as a continuity reference, then the third using the second clip. Later prompts needed to respond to the actual generated state, not just the original script.

I also needed the references to have clear roles. In the recovered [Threat / Setup prompt](../archive/episode-1/authoring/01_threat_setup_wizards_v3.txt), character images establish identity, clothing and equipment; the courtyard images establish architecture and materials. They do not dictate the staging. For example, its reference block says:

```text
Character references define identity, clothing, colors, and equipment, not staging.
```

I wanted the images to establish the designs, without turning a character sheet or comparison lineup into the scene’s staging. [The reference gallery](../assets.html) shows the original designs and derived sheets; [the Episode 1 recipes](../episode-1.html) give the full ordered inputs for each part.

### 3. Iterate on the performance and ending

I worked through **Threat / Setup**, **Reversal**, and **Farewell** as separate production sections.

1. **Prompt 1:** establish the courtyard, characters and threat. I revised that section before moving on.
2. **Prompt 2:** use the Prompt 1 video as a continuation reference, but start on a new cut immediately after its ending rather than replaying the last shot.
3. **Prompt 3:** carry forward the Prompt 2 result. I later supplied a video tail and selected original-source frame, and revised the farewell’s pacing, audio and visible continuity.

I developed the farewell beyond my opening request through later decisions: a private-grief coda, a composed-to-grief revision, then more time for the final grief shot. [Compare those completed versions](../episode-1.html#part-3). They are later iterations, not instructions silently inserted into the original first message.

The linked recipes retain the exact inputs and version history. For the first two sections, I’ve identified the output clips, but the recovered records do not establish the exact submitted authoring revision. The farewell recipes include recovered submissions.

<h2 id="episode-2">Episode 2: a more explicit acting and reveal brief</h2>

### 1. Start with references, three script sections and exact dialogue

For Episode 2, I supplied the three script-section files together, mapped the character and office references, and included the exact Japanese dialogue. I asked Hermes to create all three prompts in one pass, with a more explicit brief about the acting and the concealed reveal:

```text
Use Seedance Prompter V4 to create three prompts from the supplied script.

Image 1 — Malfoid
Image 2 — Male 1 / Harry
Image 3 — Foideldore
Image 4 — The office

Create a retro-anime drama sequence focused on Japanese anime acting,
emotional arcs and character personality.

You may optimize camera language, continuity and pacing. Preserve the
narrative and use the supplied Japanese dialogue exactly. Raise important
narrative changes before making them.

Shot 16 is locked: the slow zoom and turn are essential. Do not reveal
that Foideldore is a woman before the turn.

Do not make the whole sequence understated. Preserve the contrast between
irritation, attraction, embarrassment and anger. Restraint can serve a
particular beat, such as Foideldore's stillness before the outburst.
```

Hermes saved the three initial section prompts together. I then revised and generated them as the work developed. The batch was a starting point, not three finished prompts I never touched again.

My brief gave the creative work a purpose: develop coverage, continuity, pacing and the intended acting, while preserving the story, dialogue and reveal timing. I was specifying the aspects I wanted developed, rather than giving a general freedom level.

I used the [Office v2 reroll](../assets.html#office-v2-3) as the actual office reference. I also had a tower exterior in the design material; the per-render recipes show which images were actually submitted.

<h3 id="borrow-cuts">2. Borrow Narrative's cutting method while retaining V4</h3>

For Prompt 1, I wanted Harry’s appeal to continue while the picture followed Malfoid’s reactions. I brought in Narrative at this point, first asking Hermes to read and discuss its method before editing:

```text
Read the Narrative Prompter and its knowledge file. Its method of cutting
within one continuous passage may help here.

Keep V4 as the base. Let Harry's dialogue continue across picture cuts.
Describe Malfoid's thinking as part of the action, and use the audio fields
to control the relationship between her thoughts and his continuing voice.
```

This condenses several follow-ups. The division of work is the important part: **V4 kept the overall structure; Narrative supplied a way to connect the action and cuts inside a passage.**

I tried that with Malfoid’s thought audio in revision 4. The later **revision 5 removed her thought audio from Prompt 1**, kept Harry as the only speaking voice, and retained the internal cutting. Its 14.5–23.0-second passage still uses V4 fields:

```text
14.5–23.0 — SHOTS 04–05 / HARRY'S SPEECH AND MALFOID'S REACTIONS:
Camera: Hold Male 1's three-quarter medium close-up; internal cuts follow Malfoid's reactions and eyeline.
Dialogue: MALE 1; 「彼女がヴォルデモートを止めたんです。あそこにいた連中も、全部。」
Delivery: Insistent, stressing the scale of what Malfoid did; one continuous passage across both cuts.
Action: Male 1 begins this line while the camera still holds him. At 15.5s, cut to the existing tight three-quarter frontal close-up on Malfoid: his shoulder is soft at frame-left, her face fills frame-right. She folds her arms, follows his gesturing hand with her eyes, and gives him a visibly annoyed side-glance. His speech continues behind her.
Still listening, she rolls her eyes and tilts her head slightly away. Her gaze returns to him. At 19.0s, while his line continues, cut to a locked medium side-profile of Male 1 from Malfoid's eyeline. His open hand appeals toward Foideldore offscreen; his face and gesture fill the frame. He continues speaking as she watches his face and gesture.
```

[Read the complete submitted v5 prompt](../archive/episode-2/submitted/dreamina-episode02-section01-v5-8aff6a02.txt) · [Open v5's clip and ordered inputs](../episode-2.html#ep02-dreamina-episode02-section01-v5-8aff6a02)

<video controls playsinline preload="none" src="../media/renders/dreamina-episode02-section01-v5-8aff6a02.mp4"></video>

I kept the V4 structure and borrowed this part of Narrative’s method. I wasn’t converting the whole prompt. There also wasn’t a universal V4 ban on cutting during speech; Hermes had applied an example-specific restriction too broadly.

<h3 id="selected-passages">3. Use Narrative prose only for two selected passages</h3>

Prompt 2 needed a different combination. The opening daydream, snapback and pointing outburst needed camera, expression, inner voice, background changes and reactions to occur together. I limited the change to those passages:

```text
Keep the existing V4 prompt as the base.

Use Narrative writing only for:
00.0–06.5 — the daydream and snapback
06.5–13.0 — the pointing outburst

Connect the camera, acting, thoughts, background changes and delivery.
Keep the remaining shots in their V4 fields. Preserve approved dialogue,
timing and continuity outside the requested changes.

Do not convert the whole prompt to Narrative.
```

I kept that arrangement in the later **revision 15**. Its opening two passages are connected prose; from Shot 10 onward, the prompt returns to `Camera:`, `Action:`, `Lighting:`, `Dialogue:` and `Delivery:` fields.

A passage from the submitted prompt shows why the connecting words matter:

```text
The camera cuts to a close OTS from behind Malfoid, framing Malfoid’s pointing hand in the foreground and Male 1 in close-up as Male 1 continues leaning back to avoid the finger, keeping his nervous grimace while Malfoid continues shouting, {特に、かの有名なハリー・ポッターにはね。}, the name landing with biting emphasis. In the backdrop beyond Male 1, Foideldore remains standing behind the desk, close to the windows, with her back to the camera. <Robe and sleeve movement.>
```

“While,” “as” and “continues” specify simultaneous events and carry action across the cut. The foreground hand, Harry's close-up and Foideldore in the backdrop make the depth and blocking explicit. Rewriting these as isolated action and dialogue lists would change the direction.

[Read the complete submitted r15 prompt](../archive/episode-2/submitted/dreamina-episode02-section02-v4-r15-01.txt) · [Open r15's clip and ordered inputs](../episode-2.html#ep02-dreamina-episode02-section02-v4-r15-01)

<video controls playsinline preload="none" src="../media/renders/dreamina-episode02-section02-v4-r15-01.mp4"></video>

### 4. Continue the clips, then assemble the episode

I used Section 1 v5 as the continuation source for Section 2, then Section 2 r15 for Section 3 r7. Each continuation recipe lists its actual video tail, character/environment references and selected source frame. [Follow the continuity inputs](../episode-2.html#continuation).

My saved Studio selections are v5, r15 and r7. The linked records identify those selections; they aren’t a frame-by-frame reconstruction of my finished CapCut edit.

<h2 id="takeaways">What to carry into your own brief</h2>

- **Provide the actual inputs.** A script or event description, ordered reference roles, clip durations and exact dialogue where required.
- **Give creative work a purpose.** Here, camera coverage, pacing and anime performance could be developed. The story and locked reveal could not be changed silently.
- **Keep secondary-method scope explicit.** Borrowing a cutting technique and replacing two selected passages are different instructions. Neither implies rewriting the entire prompt.
- **State audio positively and negatively.** These prompts request dialogue, ambience and SFX, with **no music**. “No music” does not mean silent video.

I assembled the clips with their generated dialogue/SFX in CapCut. For Episode 1, I added [Walked Away on ElevenLabs](https://elevenlabs.io/music/songs/aCCc7Em3kGA5Ubp7iGYH) ([music prompt and lyrics](../music.html)). I didn’t add music to Episode 2.

## Read further, only if you want to

[Standalone skill READMEs](../skills.html) explain setup, invocation and outputs without requiring this project. The [detailed invocation history](../prompting-history.html) retains the fuller account, while the [prompt archive](../prompt-archive.html) keeps the in-scope revisions and submissions. The existing [scripting walkthrough](../script-development.html) explains how the scripts themselves developed.

**Version note:** the downloadable Narrative skill is the actual package routed by the Creative Orchestrator, with its complete knowledge file. Historical prompt records retain their original source/version labels; the current package is not presented as byte-identical to every historical execution.
