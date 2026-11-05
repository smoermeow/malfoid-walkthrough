# Creating the characters and environments

<h2 id="redesign">IP-related refusals and character redesign</h2>

I started with character references generated in Krea that looked close to the original Harry Potter designs. Some requests to turn those references into character sheets were refused by GPT-image 2, which I was using through Codex. I then tried generating videos with Seedance 2.0 using the character images and sheets I already had, but those requests were refused too.

Those IP-related refusals led me to change direction for the whole cast, including Malfoid. I asked Hermes to develop my own retro-anime interpretations, using physical descriptions instead of franchise names, without house emblems or directly reproducing the canon designs.

If you want to follow this workflow with these models, I recommend starting with your own interpretations of known characters rather than exact canon recreations. The images and complete prompts below show how I approached that redesign.

## Models, settings and skills

- **Designs and environments:** Krea 2 Turbo, through [Krea Image Generation](https://github.com/smoermeow/creative-skills/blob/main/image/krea-image-generation/README.md). The shared setup was **Raw** creativity and my [**Retro Anime inspired moodboard**](https://www.krea.ai/moodboards/75bb7600-4c66-4dec-8ba7-cde9b9965c81?already_owned=1) at **0.23** strength; the individual settings are available beneath each Krea prompt.
- **Prompt-writing support:** [Midjourney Prompts V2](https://github.com/smoermeow/creative-skills/blob/main/image/midjourney-prompts-v2/README.md) for the initial image-prompt structure and environment prompts. The images were generated in Krea.
- **Character sheets:** **GPT-image 2**, used through Codex with the [Codex-image skill](https://github.com/smoermeow/creative-skills/blob/main/image/codex-image/README.md), using the selected character designs as image inputs.
- **Later Foideldore refinement:** [Anime Character Design Lab](https://github.com/smoermeow/creative-skills/blob/main/image/anime-character-design-lab/README.md), including its design logic sheet.

<div class="image-jumps"><strong>On this page</strong><a href="#redesign">Why the redesign</a><a href="#malfoid">Malfoid</a><a href="#sheets">Character sheets</a><a href="#lucius">Lucius</a><a href="#foideldore">Foideldore</a><a href="#environments">Environments</a><a href="#remaining-cast">The rest of the cast</a></div>

<h2 id="moodboard">My shared moodboard</h2>


<figure class="moodboard-figure"><a href="https://www.krea.ai/moodboards/75bb7600-4c66-4dec-8ba7-cde9b9965c81?already_owned=1"><img loading="lazy" src="media/moodboard/retro-anime-inspired-krea-preview.jpg" alt="Retro Anime inspired moodboard"><span>Use my Retro Anime inspired moodboard on Krea</span></a><figcaption>Retro Anime inspired · smoer · strength 0.23</figcaption></figure>


<h2 id="malfoid">1. Start with the script and Malfoid’s design</h2>

My starting point was a retro-anime Harry Potter fan fiction in which Malfoy is a woman. I gave Hermes the script and asked it to identify the cast and create individual character references. For Malfoid, I supplied a specific brief: long white hair, pale skin, sharp features, a composed attitude, and a formal female school uniform with black robes and dark-green trim.

Hermes developed the generation prompt from that direction. The image below is the version I kept after the cast redesign.


<div class="design-entry" id="design-I021"><h3>Malfoid / Draconia</h3>
<figure class="design-figure"><a href="media/images/krea_malfoid_description_redesign_v1.png"><img loading="lazy" src="media/images/krea_malfoid_description_redesign_v1.png" alt="Malfoid / Draconia"></a><figcaption>Malfoid / Draconia</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/c00a53cc-f07c-428a-b7f2-e2ad00d8ef90">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I021" data-source-prompt="archive/images/I021_krea_malfoid_description_redesign_v1.txt"><code>In retro anime style, a full-body image of a slim, pale young woman on a blank white background. She has long pure snow-white hair worn straight down her back, cool white highlights and neutral silver-grey cel shadows throughout her hair, fine sharp features, a pointed chin, light grey eyes, a serious expression, and a composed, slightly aloof posture. Mature, natural proportions.
Her clothing has a refined, formal, old-fashioned wizard-school appearance:
- A plain long black robe with dark green lining and trim and an unadorned chest
- A fitted charcoal-grey V-neck knit sweater
- A crisp white collared blouse
- A green-and-silver striped tie, neatly worn
- A black pleated skirt with a clean, tailored silhouette
- Opaque black tights
- Polished black elegant low-heeled school shoes
- A slender plain wooden wand held lowered in her right hand
Her silhouette is restrained and elegant, her robe open enough to show the complete uniform. Her hair is pure white from roots to tips. The formal clothing is fully covering and practical. One upright standing figure, complete head and both shoes visible with white space around the silhouette. No crests, badges, emblems, lettering, or logos.
Classic late-1980s to early-1990s hand-drawn Japanese animation character design. Bold economical black linework, angular anime facial construction, graphic hair shapes, matte flat colors, two-tone hard-edged cel shadows, restrained facial acting, clearly drawn clothing folds. Plain white background.</code></pre>
<p class="file-actions"><a href="archive/images/I021_krea_malfoid_description_redesign_v1.txt" download>Download prompt</a> · <a href="assets.html#I021">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;2:3&quot;,
  &quot;resolution&quot;: &quot;1K&quot;,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;complexity&quot;: 0,
  &quot;movement&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ]
}</code></pre></details>
</div>



<h2 id="harry-redesign">2. Harry’s redesigned reference</h2>

The redesigned Harry image below became the input for the successful character sheet in the next step. The complete [Ron](#design-I017), [Hermione](#design-I018) and [Voldemort](#design-I019) designs and prompts are further down this same page.


<span id="harry"></span>

<div class="design-entry" id="design-I016"><h3>Harry / Male 1: redesigned reference</h3>
<figure class="design-figure"><a href="media/images/krea_male_1_description_redesign_v1.png"><img loading="lazy" src="media/images/krea_male_1_description_redesign_v1.png" alt="Harry / Male 1: redesigned reference"></a><figcaption>Harry / Male 1: redesigned reference</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/172c404c-2544-443d-8b22-575137b2f1c1">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I016" data-source-prompt="archive/images/I016_krea_male_1_description_redesign_v1.txt"><code>In retro anime style, a full-body image of a slim, wiry young man on a blank white background. He has an angular narrow face, a straight slightly long nose, strong dark eyebrows, vivid green eyes behind small round black wire-frame glasses, and unruly jet-black hair with a jagged, uneven fringe. A small irregular healed scar sits above one eyebrow. His chin is narrow, his cheeks lean, and his expression is tired but quietly defiant. Mature, naturally elongated proportions.
His clothing has a formal, old-fashioned wizard-school appearance:
- A plain long black hooded robe with deep burgundy lining and an unadorned chest
- A charcoal-grey V-neck knit sweater
- A rumpled white collared shirt
- A plain narrow oxblood tie
- Straight dark charcoal trousers
- Scuffed black lace-up school shoes
- A slender wooden wand held lowered in his right hand
Light stone dust marks his knees and robe hem; small scratches and a bruise mark his cheek. One upright standing figure, complete head and both shoes visible with white space around the silhouette. No crests, badges, emblems, lettering, or logos.
Classic late-1980s to early-1990s hand-drawn Japanese animation character design. Bold economical black linework, angular anime facial construction, graphic hair shapes, matte flat colors, two-tone hard-edged cel shadows, restrained facial acting, clearly drawn clothing folds. Plain white background.</code></pre>
<p class="file-actions"><a href="archive/images/I016_krea_male_1_description_redesign_v1.txt" download>Download prompt</a> · <a href="assets.html#I016">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;2:3&quot;,
  &quot;resolution&quot;: &quot;1K&quot;,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;complexity&quot;: 0,
  &quot;movement&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ]
}</code></pre></details>
</div>



<h2 id="sheets">3. Turn a selected design into a character sheet</h2>

I created character sheets to give the video model multiple views and expressions of the same character, helping it keep their appearance consistent across different shots.

For Harry, I supplied the new Krea design and requested front, back and side views, with three expressions chosen from the script. That sheet request succeeded. The prompt asked GPT-image 2 to retain the face, hair, clothes, palette, equipment and retro-anime style of the supplied image.


<div class="design-entry" id="design-I020"><h3>Harry / Male 1: character sheet</h3>
<p class="small"><strong>Images supplied:</strong> <a href="#design-I016">Harry’s redesigned Krea image</a>.</p>
<figure class="design-figure"><a href="media/images/codex_male_1_redesign_sheet_v1.png"><img loading="lazy" src="media/images/codex_male_1_redesign_sheet_v1.png" alt="Harry / Male 1: character sheet"></a><figcaption>Harry / Male 1: character sheet</figcaption></figure><p class="small"><strong>Model:</strong> GPT-image 2.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I020" data-source-prompt="archive/images/I020_codex_male_1_redesign_sheet_v1.txt"><code>Create a character sheet with front, back and side pose on white background. On left have 3 close up expressions: defiant through pain; stunned and bewildered; cautious, searching confusion.
Retain the retro anime style at all cost.
Use the attached image as the character design reference. Retain the face, hair, clothing, palette, and equipment. Three complete full-body views of the same character, with feet fully inside the image.</code></pre>
<p class="file-actions"><a href="archive/images/I020_codex_male_1_redesign_sheet_v1.txt" download>Download prompt</a> · <a href="assets.html#I020">Archive entry</a></p>
</div>



<h2 id="lucius">4. Give Lucius the appearances his scenes need</h2>

Lucius began with a Krea design and a front, back and side sheet. Later, I needed him to appear among the masked Death Eaters, so I requested one reference showing him with his hood and mask on and off.

For that combined sheet, I supplied the original Lucius design for his identity and clothes, the Death Eater group sheet for the hood and mask, and the new Harry sheet for the drawing style.


<div class="design-entry" id="design-I006"><h3>Lucius / Male 3: original design</h3>
<figure class="design-figure"><a href="media/images/krea_lucius_malfoy_v1.png"><img loading="lazy" src="media/images/krea_lucius_malfoy_v1.png" alt="Lucius / Male 3: original design"></a><figcaption>Lucius / Male 3: original design</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/4e6c1fde-0652-4e75-b9f9-f26a977fddc5">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I006" data-source-prompt="archive/images/I006_krea_lucius_malfoy_v1.txt"><code>In retro anime style image of Lucius Malfoy, full body on a blank white background. A tall, slender middle-aged man with very pale skin, long straight platinum-blond hair falling past his shoulders, cold light grey eyes, an angular aristocratic face, a pointed chin, and a clean-shaven jaw. He looks exhausted and diminished, his controlled posture slightly weakened. Mature, natural proportions.
His attire is formal, old-fashioned pure-blood wizard clothing:
- A long black outer robe with a high collar and heavy draping sleeves
- A fitted dark charcoal waistcoat over a high-necked black shirt
- Subtle black-on-black woven edging, restrained silver clasps
- Straight black trousers
- Polished black leather boots, dulled by stone dust
His robe is dust-streaked and slightly torn at the hem. Loose strands of his long platinum hair frame his strained face. His hands remain visible at his sides, his face uncovered. A single standing figure, both feet and the top of his head fully visible.
Retro anime, bold linework, Shirow meets Frieren. Mature proportions, restrained facial acting, graphic silhouettes, flat cel shading.</code></pre>
<p class="file-actions"><a href="archive/images/I006_krea_lucius_malfoy_v1.txt" download>Download prompt</a> · <a href="assets.html#I006">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;2:3&quot;,
  &quot;resolution&quot;: &quot;1K&quot;,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;complexity&quot;: 0,
  &quot;movement&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ]
}</code></pre></details>
</div>


<div class="design-entry" id="design-I014"><h3>Lucius: initial turnaround sheet</h3>
<p>This was the earlier turnaround, before the combined hood-and-mask reference.</p>
<p class="small"><strong>Images supplied:</strong> <a href="#design-I006">original Lucius design</a>.</p>
<figure class="design-figure"><a href="media/images/codex_lucius_malfoy_sheet_v1.png"><img loading="lazy" src="media/images/codex_lucius_malfoy_sheet_v1.png" alt="Lucius: initial turnaround sheet"></a><figcaption>Lucius: initial turnaround sheet</figcaption></figure><p class="small"><strong>Model:</strong> GPT-image 2.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I014" data-source-prompt="archive/images/I014_codex_lucius_malfoy_sheet_v1.txt"><code>Create a character sheet with front, back and side pose on white background. On left have 3 close up expressions: weakened exhaustion; pleading; fading desperation.
Retain the retro anime style at all cost.
Use the attached image as the character design reference. Retain the face, hair, clothing, palette, and equipment. Three complete full-body views of the same character, with feet fully inside the image.</code></pre>
<p class="file-actions"><a href="archive/images/I014_codex_lucius_malfoy_sheet_v1.txt" download>Download prompt</a> · <a href="assets.html#I014">Archive entry</a></p>
</div>


<div class="design-entry" id="design-I022"><h3>Lucius / Male 3: hood and mask on/off</h3>
<p class="small"><strong>Images supplied:</strong> <a href="#design-I006">image 1: Lucius design</a>; <a href="#design-I015">image 2: Death Eater group sheet</a>; <a href="#design-I020">image 3: Harry sheet, for drawing style</a>.</p>
<figure class="design-figure"><a href="media/images/codex_male_3_hood_on_off_sheet_v1.png"><img loading="lazy" src="media/images/codex_male_3_hood_on_off_sheet_v1.png" alt="Lucius / Male 3: hood and mask on/off"></a><figcaption>Lucius / Male 3: hood and mask on/off</figcaption></figure><p class="small"><strong>Model:</strong> GPT-image 2.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I022" data-source-prompt="archive/images/I022_codex_male_3_hood_on_off_sheet_v1.txt"><code>Create one character sheet on a plain white background with two evenly spaced, front-facing, complete full-body views of the same tall, slender middle-aged man. Both heads and both pairs of feet are fully inside the image.

Use image 1 as the primary character identity and clothing reference: retain his pale skin, angular face, long straight platinum-blond hair, build, black outer robe, charcoal waistcoat, black shirt, trousers, boots, and silver clasps.
Use image 2 only for the black hood and full-face silver mask design, with narrow eye openings and engraved curling patterns.
Use image 3 only for the new cast drawing style, never its character identity or clothing.

LEFT: Hood lowered behind his neck, face fully uncovered, long platinum-blond hair visible.
RIGHT: The same man in the same clothes, black hood fully raised and silver mask fully covering his face. His long hair is mostly tucked beneath the hood.

Only these two views of one character. No expression panels or additional figures.

Retro anime, bold linework, Shirow meets Frieren. Mature proportions, detailed hand-drawn environments, restrained facial acting, graphic silhouettes, selective perspective exaggeration, and strong anime impact frames only at key moments.
Retain the retro anime style at all cost.
</code></pre>
<p class="file-actions"><a href="archive/images/I022_codex_male_3_hood_on_off_sheet_v1.txt" download>Download prompt</a> · <a href="assets.html#I022">Archive entry</a></p>
</div>



<h2 id="foideldore">5. Refine Foideldore, then make the hood variants</h2>

For Episode 2, my starting brief was Dumbledore reinterpreted as a woman, with inspiration from the grandmother in Dandadan and the visual style of the existing cast. I refined her clothes, proportions and expression with Hermes, bringing in Anime Character Design Lab for the later review.

The design needed to convey her personality as well as her appearance. The version I chose has heavy burgundy wizard robes and a composed, dryly mischievous expression. After approving the no-wand design, I requested front, back and side sheets, then a second sheet with the hood up. Both sheets use that same selected design as their image input.


<div class="design-entry" id="design-I046"><h3>Foideldore: selected no-wand design</h3>
<figure class="design-figure"><a href="media/images/krea_foideldore_no_wand_v11.png"><img loading="lazy" src="media/images/krea_foideldore_no_wand_v11.png" alt="Foideldore: selected no-wand design"></a><figcaption>Foideldore: selected no-wand design</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/3ee12ee2-2ae1-4d6a-a4a2-55608e5c8aaf">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I046" data-source-prompt="archive/images/I046_krea_foideldore_no_wand_v11.txt"><code>In retro anime style, a full-body image of a poised, mature female archmage on a blank white background. She has a surprisingly youthful angular face with subtle smile lines, pale blue eyes, a long slightly crooked nose, and small half-moon spectacles worn low on her nose. She carries herself with effortless authority, completely comfortable in her own power. Confident, relaxed and utterly unbothered, with a dry, knowing expression and an undercurrent of mischief. She has the sharp presence of an experienced witch who is very difficult to impress. Her long silver-white hair is gathered into a high, thick, loosely tied ponytail, organized into a few large graphic locks with two loose strands framing her face. Her shoulders are relaxed, her weight comfortably settled, her left hand resting loosely at her waist. Mature, natural proportions, a slender frame with a narrow ribcage and waist, slim hips and slender arms, with noticeably larger, fuller breasts.
She wears one continuous, heavy, floor-length deep burgundy-red wizard robe with dark indigo lining. A large, heavy hood rests down behind her shoulders, hanging low across her upper back in a few broad, soft folds. The robe has a low, open neckline with soft lapels lying flat against her chest. Its rounded shoulders flow directly into generous hanging sleeves and long front panels, with broad uninterrupted areas of fabric and a hem pooling slightly around her feet. The cloth hangs from her shoulders in a small number of deep, weighty folds. A narrow, low-contrast silver embroidered border follows the cuffs and hem, with only a few tiny celestial marks worked into the same thread.
Beneath the open robe she wears a skin-tight charcoal stretch top with close-fitting sleeves and a simple round neckline, smoothly hugging her fuller bust and waist. A narrow dark-violet cloth tie rests at her waist, partly covered by the robe. A long charcoal skirt falls in soft vertical folds to her ankles, with black leather low-heeled ankle boots beneath it. Her empty right hand rests relaxed at her side.
The robe forms a broad, continuous draped silhouette around the darker fitted inner clothes. Her face, low-set spectacles and high silver ponytail are clearly readable above the soft robe neckline. Hair and fabric are described with a few decisive contours and broad, connected hard-edged shadow shapes; the sleeve interiors form simple readable dark masses. One upright standing figure, complete head and entire robe hem visible with white space around the silhouette. No crests, badges, lettering, or logos.
Classic late-1980s to early-1990s hand-drawn Japanese animation character design. Bold economical black linework, angular anime facial construction, graphic hair shapes, matte flat colors, two-tone hard-edged cel shadows, restrained facial acting, clearly drawn clothing folds. Plain white background.</code></pre>
<p class="file-actions"><a href="archive/images/I046_krea_foideldore_no_wand_v11.txt" download>Download prompt</a> · <a href="assets.html#I046">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;2:3&quot;,
  &quot;resolution&quot;: &quot;1K&quot;,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;complexity&quot;: 0,
  &quot;movement&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ]
}</code></pre></details>
</div>


<div class="design-entry" id="design-I047"><h3>Foideldore: hood-down turnaround</h3>
<p class="small"><strong>Images supplied:</strong> <a href="#design-I046">selected Foideldore design</a>.</p>
<figure class="design-figure"><a href="media/images/codex_foideldore_front_back_side_sheet_v1.png"><img loading="lazy" src="media/images/codex_foideldore_front_back_side_sheet_v1.png" alt="Foideldore: hood-down turnaround"></a><figcaption>Foideldore: hood-down turnaround</figcaption></figure><p class="small"><strong>Model:</strong> GPT-image 2.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I047" data-source-prompt="archive/images/I047_codex_foideldore_front_back_side_sheet_v1.txt"><code>Use image 1 as the sole approved character-design and drawing-style authority. Create one clean character turnaround sheet of this exact woman in three full-body views, evenly spaced left to right on a plain white background: front view on the left, back view in the centre, and a true side profile facing frame-left on the right. All three depictions show the same character at the same scale and height, with a shared ground baseline and clear white space between their silhouettes. Each view includes the complete head and entire robe hem.

Preserve the approved face, spectacles, silver hair, slender frame, fuller bust, burgundy robe, inner outfit, fabric details, palette and confident dry personality from image 1. Keep her relaxed standing posture consistent as she turns. Both hands are empty. Reproduce the reference linework, matte colors, graphic shapes and cel-shadow treatment faithfully.

The large hood rests down behind her shoulders and across her upper back in all three views, matching the approved reference. Preserve the visible silver ponytail and the exact existing garment design.

Classic late-1980s to early-1990s hand-drawn Japanese animation character design. Bold economical black linework, angular anime facial construction, graphic hair shapes, matte flat colors, two-tone hard-edged cel shadows, restrained facial acting, clearly drawn clothing folds. Plain white background.</code></pre>
<p class="file-actions"><a href="archive/images/I047_codex_foideldore_front_back_side_sheet_v1.txt" download>Download prompt</a> · <a href="assets.html#I047">Archive entry</a></p>
</div>


<div class="design-entry" id="design-I048"><h3>Foideldore: hood-up turnaround</h3>
<p class="small"><strong>Images supplied:</strong> <a href="#design-I046">selected Foideldore design</a>.</p>
<figure class="design-figure"><a href="media/images/codex_foideldore_hood_up_front_back_side_sheet_v1.png"><img loading="lazy" src="media/images/codex_foideldore_hood_up_front_back_side_sheet_v1.png" alt="Foideldore: hood-up turnaround"></a><figcaption>Foideldore: hood-up turnaround</figcaption></figure><p class="small"><strong>Model:</strong> GPT-image 2.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I048" data-source-prompt="archive/images/I048_codex_foideldore_hood_up_front_back_side_sheet_v1.txt"><code>Use image 1 as the sole approved character-design and drawing-style authority. Create one clean character turnaround sheet of this exact woman in three full-body views, evenly spaced left to right on a plain white background: front view on the left, back view in the centre, and a true side profile facing frame-left on the right. All three depictions show the same character at the same scale and height, with a shared ground baseline and clear white space between their silhouettes. Each view includes the complete head and entire robe hem.

Preserve the approved face, spectacles, silver hair, slender frame, fuller bust, burgundy robe, inner outfit, fabric details, palette and confident dry personality from image 1. Keep her relaxed standing posture consistent as she turns. Both hands are empty. Reproduce the reference linework, matte colors, graphic shapes and cel-shadow treatment faithfully.

The existing large hood is raised over her head in all three views. Its generous fabric volume contains her high ponytail beneath the hood. Her face, low-set spectacles and visible face-framing hair remain recognizable inside the hood opening. The hood is the same hood attached to the approved robe; all other design details match image 1.

Classic late-1980s to early-1990s hand-drawn Japanese animation character design. Bold economical black linework, angular anime facial construction, graphic hair shapes, matte flat colors, two-tone hard-edged cel shadows, restrained facial acting, clearly drawn clothing folds. Plain white background.</code></pre>
<p class="file-actions"><a href="archive/images/I048_codex_foideldore_hood_up_front_back_side_sheet_v1.txt" download>Download prompt</a> · <a href="assets.html#I048">Archive entry</a></p>
</div>



<h2 id="environments">6. Create the locations without characters</h2>

Episode 1 takes place in one courtyard, seen through a wide variety of shots and camera angles. I used different views of that location to help keep it consistent across the sequence.

I asked Hermes to use Midjourney Prompts V2 for the environment prompts and generate the images in Krea with the same moodboard and visual direction as the cast. The environment images were to contain no characters.


<div class="design-entry" id="design-I008"><h3>Episode 1 courtyard: establishing view</h3>
<figure class="design-figure"><a href="media/images/krea_courtyard_establishing_v1.png"><img loading="lazy" src="media/images/krea_courtyard_establishing_v1.png" alt="Episode 1 courtyard: establishing view"></a><figcaption>Episode 1 courtyard: establishing view</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/1d5fbec6-1652-4a8e-81d4-7a6df09b22c1">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I008" data-source-prompt="archive/images/I008_krea_courtyard_establishing_v1.txt"><code>In anime-style, an establishing wide shot from an eye-level angle.

The ruined Hogwarts stone courtyard at night, an empty expanse of fractured flagstones in the foreground and centre, battered Gothic castle walls and broken pointed-arch cloisters behind it. Fallen masonry lies mainly along the courtyard edges; open broken paving remains visible across the centre. The courtyard is entirely unoccupied, without characters, bodies, or human silhouettes.

Weathered grey stone, shattered arch ribs, chipped columns, scattered rubble, small weak orange fires along the edges, drifting embers, and layered smoke. Cold blue moonlight dominates the ruined Hogwarts courtyard, broken by weak orange fires and drifting embers. Hard shadows and rim light create strong silhouettes through the smoke.

Retro anime, bold linework, Shirow meets Frieren. Mature proportions, detailed hand-drawn environments, restrained facial acting, graphic silhouettes, selective perspective exaggeration, and strong anime impact frames only at key moments.</code></pre>
<p class="file-actions"><a href="archive/images/I008_krea_courtyard_establishing_v1.txt" download>Download prompt</a> · <a href="assets.html#I008">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;16:9&quot;,
  &quot;complexity&quot;: 0,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ],
  &quot;movement&quot;: 0,
  &quot;resolution&quot;: &quot;1K&quot;
}</code></pre></details>
</div>


<div class="design-entry" id="design-I009"><h3>Episode 1 courtyard: ground-level view</h3>
<figure class="design-figure"><a href="media/images/krea_courtyard_ground_v1.png"><img loading="lazy" src="media/images/krea_courtyard_ground_v1.png" alt="Episode 1 courtyard: ground-level view"></a><figcaption>Episode 1 courtyard: ground-level view</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/215eb7a3-4f62-49e0-83d3-e8de1f6d40b3">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I009" data-source-prompt="archive/images/I009_krea_courtyard_ground_v1.txt"><code>In anime-style, a wide shot from a ground-level angle.

The ruined Hogwarts stone courtyard at night, viewed just above the fractured paving across the empty central space toward battered Gothic castle walls and broken pointed-arch cloisters. Large chipped flagstones fill the lower foreground, and fallen masonry sits along the courtyard edges. The courtyard is entirely unoccupied, without characters, bodies, or human silhouettes.

Weathered grey stone, shattered arch ribs, chipped columns, scattered rubble, small weak orange fires along the edges, drifting embers, and low layers of smoke. Cold blue moonlight dominates the ruined Hogwarts courtyard, broken by weak orange fires and drifting embers. Hard shadows and rim light create strong silhouettes through the smoke.

Retro anime, bold linework, Shirow meets Frieren. Mature proportions, detailed hand-drawn environments, restrained facial acting, graphic silhouettes, selective perspective exaggeration, and strong anime impact frames only at key moments.</code></pre>
<p class="file-actions"><a href="archive/images/I009_krea_courtyard_ground_v1.txt" download>Download prompt</a> · <a href="assets.html#I009">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;16:9&quot;,
  &quot;complexity&quot;: 0,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ],
  &quot;movement&quot;: 0,
  &quot;resolution&quot;: &quot;1K&quot;
}</code></pre></details>
</div>


<div class="design-entry" id="design-I010"><h3>Episode 1 courtyard: overhead view</h3>
<figure class="design-figure"><a href="media/images/krea_courtyard_overhead_v1.png"><img loading="lazy" src="media/images/krea_courtyard_overhead_v1.png" alt="Episode 1 courtyard: overhead view"></a><figcaption>Episode 1 courtyard: overhead view</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/9a365ff0-00e9-4962-b901-4a92e3dc8823">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I010" data-source-prompt="archive/images/I010_krea_courtyard_overhead_v1.txt"><code>In anime-style, a wide shot from a tilted overhead angle.

The ruined Hogwarts stone courtyard at night, its empty central expanse of fractured flagstones surrounded by battered Gothic castle walls and broken pointed-arch cloisters. Fallen masonry clusters along the edges, leaving the damaged central paving exposed. The courtyard is entirely unoccupied, without characters, bodies, or human silhouettes.

Weathered grey stone, shattered arch ribs, chipped columns, scattered rubble, small weak orange fires along the edges, drifting embers, and separate layers of smoke crossing the paving. Cold blue moonlight dominates the ruined Hogwarts courtyard, broken by weak orange fires and drifting embers. Hard shadows and rim light create strong silhouettes through the smoke.

Retro anime, bold linework, Shirow meets Frieren. Mature proportions, detailed hand-drawn environments, restrained facial acting, graphic silhouettes, selective perspective exaggeration, and strong anime impact frames only at key moments.</code></pre>
<p class="file-actions"><a href="archive/images/I010_krea_courtyard_overhead_v1.txt" download>Download prompt</a> · <a href="assets.html#I010">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;16:9&quot;,
  &quot;complexity&quot;: 0,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ],
  &quot;movement&quot;: 0,
  &quot;resolution&quot;: &quot;1K&quot;
}</code></pre></details>
</div>



### The tower and office

For Episode 2, I supplied descriptions of a Gothic tower at night and a circular stone office with arched windows, bookshelves and a heavy wooden desk. These became the exterior and interior designs below.


<div class="design-entry" id="design-I043"><h3>Episode 2: tower exterior</h3>
<figure class="design-figure"><a href="media/images/krea_foideldore_tower_exterior_v1.png"><img loading="lazy" src="media/images/krea_foideldore_tower_exterior_v1.png" alt="Episode 2: tower exterior"></a><figcaption>Episode 2: tower exterior</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/f8a967f9-215d-422a-95bd-4b1be2b7b4f4">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I043" data-source-prompt="archive/images/I043_krea_foideldore_tower_exterior_v1.txt"><code>In anime-style, a wide exterior establishing view from an elevated neighboring rooftop, looking slightly upward at the main tower.

A tall Gothic stone tower rising above Hogwarts at night, its narrow arched windows glowing warm amber against cold blue moonlight. Dark rooftops and distant castle spires fall away below, with thin clouds and mist moving through the night.

The main tower has a round shaft of weathered grey stone and a steep dark slate spire above a ring of tall, narrow pointed-arch office windows near the top. The tower dominates the central vertical axis, with lower rooflines stepping away to either side. Cold moonlight edges the masonry, roof ridges and spires; soft amber light fills the upper windows. Thin cloud bands cross the deep blue night sky, and pale mist separates the lower rooftops. An empty architectural environment, with the stonework and window shapes clearly readable.

Retro anime, bold linework, Shirow meets Frieren. Mature proportions, detailed hand-drawn environments, restrained facial acting, graphic silhouettes, selective perspective exaggeration, and strong anime impact frames only at key moments.</code></pre>
<p class="file-actions"><a href="archive/images/I043_krea_foideldore_tower_exterior_v1.txt" download>Download prompt</a> · <a href="assets.html#I043">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;16:9&quot;,
  &quot;complexity&quot;: 0,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ],
  &quot;movement&quot;: 0,
  &quot;resolution&quot;: &quot;1K&quot;
}</code></pre></details>
</div>


<div class="design-entry" id="design-office-v2-3"><h3>Episode 2: Foideldore’s office</h3>
<p>The first image below is the office reroll used as the video reference. The second is the first result from the same prompt, available through the original Krea link. The complete prompt applies to both.</p>
<figure class="design-figure"><a href="media/images/office-v2-3.png"><img loading="lazy" src="media/images/office-v2-3.png" alt="Episode 2: Foideldore’s office"></a><figcaption>Episode 2: Foideldore’s office</figcaption></figure><div id="design-office-v2-1"><figure class="design-figure"><a href="media/images/office-v2-1.png"><img loading="lazy" src="media/images/office-v2-1.png" alt="First result from the same office prompt; this is the image on the linked Krea page."></a><figcaption>First result from the same office prompt; this is the image on the linked Krea page.</figcaption></figure></div><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/706fe6e9-48a3-45bf-9690-a98aef50f205">Open the first office result on Krea</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="office-v2-3" data-source-prompt="archive/images/office-v2-3.txt"><code>In anime-style, a wide interior view from the room entrance, looking across the office toward the tall arched windows on the far curved wall.

A large circular stone office with tall arched windows, dark wooden floors, towering bookshelves, framed artwork, candles, brass instruments, stacked books and parchment. A heavy carved wooden desk sits between the windows and the room entrance, surrounded by warm amber light against the cold moonlight outside.

Weathered grey stone walls follow the round tower interior. The tall, narrow pointed-arch windows match the tower exterior, with deep blue night, dark castle rooftops and distant spires visible through them. The desk occupies the midground between the foreground entrance and the background windows. Curving bookshelves and three aged gold-framed artworks line the wall sections between the windows. The large frame on the left contains a painted portrait of an elderly headmistress in dark robes, with silver hair, an angular profile and a lined face rendered in restrained brushwork. The small centre frame contains an antique lunar chart on aged parchment. The large frame on the right contains a muted painting of Hogwarts beneath a cloudy night sky. Dark wooden floorboards lead toward the desk, whose carved edges and legs are clearly visible. Candles, books, parchment and brass instruments are arranged on the desk and nearby shelves. Warm amber candlelight pools across the wood and stone; cool blue moonlight outlines the window recesses and falls across the floor. The office is unoccupied.

Retro anime, bold linework, Shirow meets Frieren. Mature proportions, detailed hand-drawn environments, restrained facial acting, graphic silhouettes, selective perspective exaggeration, and strong anime impact frames only at key moments.</code></pre>
<p class="file-actions"><a href="archive/images/office-v2-3.txt" download>Download prompt</a> · <a href="assets.html#office-v2-3">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;16:9&quot;,
  &quot;resolution&quot;: &quot;1K&quot;,
  &quot;creativity&quot;: &quot;low&quot;,
  &quot;intensity&quot;: 0,
  &quot;complexity&quot;: 0,
  &quot;movement&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ]
}</code></pre></details>
</div>



<h2 id="remaining-cast">7. The rest of the selected cast</h2>

These are the remaining selected character designs and their complete prompts. Ron, Hermione and Voldemort belong to the description-based redesign pass. For the masked Death Eaters, I requested a group lineup rather than individual turnarounds and expression panels.


<div class="design-entry" id="design-I017"><h3>Ron / Male 2</h3>
<figure class="design-figure"><a href="media/images/krea_male_2_description_redesign_v1.png"><img loading="lazy" src="media/images/krea_male_2_description_redesign_v1.png" alt="Ron / Male 2"></a><figcaption>Ron / Male 2</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/3e4379c4-02bd-4e8b-a9f0-44814f4f9989">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I017" data-source-prompt="archive/images/I017_krea_male_2_description_redesign_v1.txt"><code>In retro anime style, a full-body image of a tall, lanky young man on a blank white background. He has thick tousled copper-red hair with uneven pointed tufts, clear blue eyes, plentiful freckles over his nose and cheeks, a long narrow face, a prominent long nose, and large hands and feet. His lean jaw and long limbs give him a distinctive gangling silhouette. His expression is weary and watchful, his posture slightly awkward. Mature, naturally elongated proportions.
His clothing has a modest, old-fashioned wizard-school appearance:
- A plain long black hooded robe with faded burgundy lining and an unadorned chest
- A slightly loose, worn charcoal-grey V-neck knit sweater
- A rumpled white collared shirt
- A plain narrow oxblood tie, loosely knotted
- Dark charcoal trousers with dusty knees
- Worn black lace-up school shoes
- A slender wooden wand held lowered in his right hand
His cuffs and robe hem show wear, with pale stone dust along the lower fabric. One upright standing figure, complete head and both shoes visible with white space around the silhouette. No crests, badges, emblems, lettering, or logos.
Classic late-1980s to early-1990s hand-drawn Japanese animation character design. Bold economical black linework, angular anime facial construction, graphic hair shapes, matte flat colors, two-tone hard-edged cel shadows, restrained facial acting, clearly drawn clothing folds. Plain white background.</code></pre>
<p class="file-actions"><a href="archive/images/I017_krea_male_2_description_redesign_v1.txt" download>Download prompt</a> · <a href="assets.html#I017">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;2:3&quot;,
  &quot;resolution&quot;: &quot;1K&quot;,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;complexity&quot;: 0,
  &quot;movement&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ]
}</code></pre></details>
</div>


<div class="design-entry" id="design-I018"><h3>Hermione / Female 1</h3>
<figure class="design-figure"><a href="media/images/krea_female_1_description_redesign_v1.png"><img loading="lazy" src="media/images/krea_female_1_description_redesign_v1.png" alt="Hermione / Female 1"></a><figcaption>Hermione / Female 1</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/1654abc1-333f-4ebb-9988-62a4f2889208">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I018" data-source-prompt="archive/images/I018_krea_female_1_description_redesign_v1.txt"><code>In retro anime style, a full-body image of a slim young woman on a blank white background. She has a thick, bushy mass of chestnut-brown hair falling to her shoulder blades in unruly angular waves, brown eyes beneath strong expressive eyebrows, a short straight nose, a defined chin, and a serious, intelligent expression. Her broad hair silhouette contrasts with her compact, upright posture. Mature, natural proportions.
Her clothing has a practical, formal, old-fashioned wizard-school appearance:
- A plain long black hooded robe with deep burgundy lining and an unadorned chest
- A charcoal-grey V-neck knit sweater
- A crisp white collared blouse
- A plain narrow oxblood tie
- A tailored black pleated skirt reaching to the knees
- Opaque dark tights
- Practical flat black lace-up school shoes
- A slender wooden wand held lowered in her right hand
A few loose strands cross her face, with small scratches on her cheek and dust on her robe hem. Fully covering practical clothing. One upright standing figure, complete head and both shoes visible with white space around the silhouette. No crests, badges, emblems, lettering, or logos.
Classic late-1980s to early-1990s hand-drawn Japanese animation character design. Bold economical black linework, angular anime facial construction, graphic hair shapes, matte flat colors, two-tone hard-edged cel shadows, restrained facial acting, clearly drawn clothing folds. Plain white background.</code></pre>
<p class="file-actions"><a href="archive/images/I018_krea_female_1_description_redesign_v1.txt" download>Download prompt</a> · <a href="assets.html#I018">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;2:3&quot;,
  &quot;resolution&quot;: &quot;1K&quot;,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;complexity&quot;: 0,
  &quot;movement&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ]
}</code></pre></details>
</div>


<div class="design-entry" id="design-I019"><h3>Voldemort / Evil Lord</h3>
<figure class="design-figure"><a href="media/images/krea_evil_lord_description_redesign_v1.png"><img loading="lazy" src="media/images/krea_evil_lord_description_redesign_v1.png" alt="Voldemort / Evil Lord"></a><figcaption>Voldemort / Evil Lord</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/cef01d30-8438-4ab2-87eb-753d8de2d01a">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I019" data-source-prompt="archive/images/I019_krea_evil_lord_description_redesign_v1.txt"><code>In retro anime style, a full-body image of an extremely tall, thin, inhuman male sorcerer on a blank white background. His build is almost skeletal, with narrow shoulders, very long limbs, thin wrists, and long bony fingers. His skin is unnaturally pale grey, nearly translucent. A completely bald, high rounded skull sits above a long gaunt face with pronounced angular cheekbones, a flattened nose reduced to two narrow nostril slits, thin tightly closed lips, and deep-set ruby-red eyes beneath a severe brow. His expression is cold and predatory. His facial features are sharply simplified into hand-drawn anime shapes.
His attire is simple and imposing:
- A plain long flowing black robe with a high closed overlapping neckline
- Loose, deeply draping sleeves
- Long vertical folds of charcoal-black fabric reaching almost to the ground
- Plain black footwear barely visible beneath the hem
- A slender pale wooden wand held lowered in one bony hand
The silhouette is narrow and elongated, the robe hanging loosely from his thin frame. One upright standing figure, complete head and both shoes visible with white space around the silhouette. No jewelry, decorative accessories, crests, emblems, lettering, or logos.
Classic late-1980s to early-1990s hand-drawn Japanese animation character design. Bold economical black linework, angular anime facial construction, graphic silhouettes, matte flat colors, two-tone hard-edged cel shadows, restrained facial acting, clearly drawn clothing folds. Plain white background.</code></pre>
<p class="file-actions"><a href="archive/images/I019_krea_evil_lord_description_redesign_v1.txt" download>Download prompt</a> · <a href="assets.html#I019">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;2:3&quot;,
  &quot;resolution&quot;: &quot;1K&quot;,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;complexity&quot;: 0,
  &quot;movement&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ]
}</code></pre></details>
</div>


<div class="design-entry" id="design-I007"><h3>Death Eaters / Wizards: group design</h3>
<figure class="design-figure"><a href="media/images/krea_death_eaters_v1.png"><img loading="lazy" src="media/images/krea_death_eaters_v1.png" alt="Death Eaters / Wizards: group design"></a><figcaption>Death Eaters / Wizards: group design</figcaption></figure><p class="small"><strong>Model:</strong> Krea 2 Turbo. <a href="https://www.krea.ai/assets/c1fe51db-6ffa-44eb-90ac-b3ff9cbef81d">Open the original Krea result</a>.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I007" data-source-prompt="archive/images/I007_krea_death_eaters_v1.txt"><code>In retro anime style image of a group of exactly seven masked Death Eaters standing together on a blank white background. Seven distinct adult dark wizards, all visible head to toe in a single shallow staggered row, with clear separation between their silhouettes. Varied heights and builds: one very tall and thin, one short and broad, two average lean builds, one heavyset, and two tall broad-shouldered figures.
Their attire is imposing traditional dark wizard clothing:
- Long black hooded robes with layered charcoal fabric
- Full-face silver Death Eater masks with narrow eye openings and individually different engraved curling patterns
- Deep black hoods covering their hair
- Black leather belts and dark boots visible beneath the robe hems
- Each holds one slender wooden wand lowered at their side
The seven silver masks remain fully worn and cover every face. Their robes vary subtly in collars, sleeve shapes and layered hems while retaining one coherent black-clad faction design. Their stances are watchful and still. All seven stand together as a group; one full-body depiction per person.
Retro anime, bold linework, Shirow meets Frieren. Mature proportions, restrained facial acting, graphic silhouettes, flat cel shading.</code></pre>
<p class="file-actions"><a href="archive/images/I007_krea_death_eaters_v1.txt" download>Download prompt</a> · <a href="assets.html#I007">Archive entry</a></p>
<details><summary>Generation settings</summary><pre><code>{
  &quot;aspect_ratio&quot;: &quot;16:9&quot;,
  &quot;resolution&quot;: &quot;1K&quot;,
  &quot;creativity&quot;: &quot;raw&quot;,
  &quot;intensity&quot;: 0,
  &quot;complexity&quot;: 0,
  &quot;movement&quot;: 0,
  &quot;moodboards&quot;: [
    {
      &quot;id&quot;: &quot;75bb7600-4c66-4dec-8ba7-cde9b9965c81&quot;,
      &quot;strength&quot;: 0.23
    }
  ]
}</code></pre></details>
</div>


<div class="design-entry" id="design-I015"><h3>Death Eaters / Wizards: group sheet</h3>
<p class="small"><strong>Images supplied:</strong> <a href="#design-I007">Krea group design</a>.</p>
<figure class="design-figure"><a href="media/images/codex_death_eaters_sheet_v1.png"><img loading="lazy" src="media/images/codex_death_eaters_sheet_v1.png" alt="Death Eaters / Wizards: group sheet"></a><figcaption>Death Eaters / Wizards: group sheet</figcaption></figure><p class="small"><strong>Model:</strong> GPT-image 2.</p>
<p class="small"><strong>Complete generation prompt</strong></p>
<pre data-image-id="I015" data-source-prompt="archive/images/I015_codex_death_eaters_sheet_v1.txt"><code>Create a character group sheet of the seven masked Death Eaters in the reference image, standing together on a plain white background. Exactly seven complete full-body figures, with clear space around their heads and feet. Retain their individual masks, dark robes, silhouettes, and equipment. One depiction per person. A single group lineup, without front/back/side turnarounds or expression panels. Retain the retro anime style at all cost.</code></pre>
<p class="file-actions"><a href="archive/images/I015_codex_death_eaters_sheet_v1.txt" download>Download prompt</a> · <a href="assets.html#I015">Archive entry</a></p>
</div>



## Continue with the script and video prompts

The references were then mapped to the characters and locations in the production script. The [scripting walkthrough](script-development.html) follows the script work, and [video prompting](prompting.html) explains how I used the Seedance prompting skills with the actual scripts and references.

The [full reference gallery](assets.html) keeps the earlier designs and revisions available for anyone who wants the longer history. The selected designs, worked sheets and their full prompts are all here above.

