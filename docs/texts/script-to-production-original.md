# From Script to Production

At this point, the actual script was basically there.

The next problem was different:

**How do I turn this into something I can actually use for generation?**

The full script was too large and contained a lot of information that only mattered to certain shots, so the next step was to connect the script to the actual visual references and break it into manageable production sections.

---

## 13. Attach the real character and environment references

I already had the character and environment images I wanted to use.

So instead of leaving the script with generic names, we mapped the actual references onto it.

For example:

- Harry → Male 1
- Ron → Male 2
- Hermione → Female 1
- Malfoid → Malfoid
- Voldemort → Evil Lord
- Malfoid's father → Male 3
- Death Eaters → Wizards
- courtyard establishing reference
- courtyard ground-level reference
- courtyard overhead reference

The script could then refer directly to the images the generation model was supposed to use.

This is also where continuity becomes much easier to inspect, because every character in the shot now has an actual reference attached to them.

---

## 14. Split the full script into smaller production sections

Rather than trying to use the entire episode as one massive generation prompt, we broke it into sections.

For Episode 1, that became:

**Shots 1–9**

**Shots 10–18**

**Shots 19–26**

Each section could carry the relevant references and shot instructions without dragging the entire episode into every prompt.

The story itself was already finished.

At this stage we were mainly packaging it for production.

---

## 15. Use the reference pass to catch continuity problems

Once the real references were attached, some problems became easier to see.

A concrete example was Male 3.

He was supposed to stand directly behind Malfoid in the early Death Eater group, with his hands on her shoulders.

At one point he had disappeared from that setup.

So we corrected the production version and restored him there.

Later, when the defeated Death Eaters are revealed, he also needed to be present among them.

This was no longer really a story rewrite.

It was a **continuity and reference pass**:

- Is everyone who should be in the shot actually there?
- Are the correct references being used?
- Does the later shot still match what was established earlier?
- Has a character accidentally disappeared between versions?

That became the bridge between the finished script and the actual image/video generation process.

---

## 16. The workflow had now changed

Up to this point, the process had been mostly about:

**story → scene → shots → camera → dialogue → blocking**

Now it became:

**finished script → references → production sections → continuity check → generation**

That distinction matters.

The creative scene development was mostly done.

The next job was making sure the script could survive contact with the actual generation pipeline.

---

# Next: Generating the Shots

From here, the walkthrough can move into how the individual shot prompts were actually used with the image/video tools and how the generated results fed back into the production process.
