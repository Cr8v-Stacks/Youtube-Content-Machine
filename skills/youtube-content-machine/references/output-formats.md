# Output Formats

## Full Production Pack

Use this when the user asks for the normal prep, upload-ready material, full package, production pack, or anything similar.

Return:

1. Title and alternative titles.
2. Draft script diagnosis, when the user provides an existing script.
3. Selected visual system for this episode, with a short reason.
4. Thumbnail text and thumbnail image prompts.
5. Primary character image prompt, when a person, recurring figure, mascot, or historical individual appears.
6. Script only, with no image prompts inside the script.
7. Shot-by-shot script-to-image prompts.
8. SEO meta description.
9. Hashtags.
10. Tags.
11. Research material with source links and key facts used, when the topic is factual or historical.

## Title Section

Include one primary title and 3-8 alternatives.

Prioritize curiosity, specificity, and tension. Avoid clever abstractions that reduce clickability.

When a topic contains a concrete weird detail, lead with that detail. Prefer a title built around the weird number, time gap, cost, scale, or impossible-sounding result over a broad category title. The title should make the viewer ask why or how before the video starts.

## Thumbnail Section

Include:

- Thumbnail text: at least 4 variations per thumbnail image variation.
- Thumbnail image prompts: provide multiple image variations when useful for A/B testing.
- Recommendation: name the best thumbnail text + image pairing and explain why.

The thumbnail should communicate the story before the viewer reads the title.

Prefer the strongest curiosity element over a broad theme. Numbers, contradictions, rejection, impossible scale, and private-use surprises often beat general labels.

Thumbnail text should be short, usually 2-6 words, but never provide only one option. If there are 3 image prompt variations, provide at least 4 text options for each variation.

Recommendation logic:

- Prefer the clearest curiosity object.
- Prefer concrete numbers, contradictions, and emotional labels.
- Avoid clever wording that hides the story.
- Explain the recommendation in one sentence.

## Draft Script Diagnosis

When the user provides a script or draft, do not simply repackage it. First critique it against the channel's standards.

Include:

- What works.
- What does not fit the channel style.
- Whether the intro fits the preferred hook pattern.
- Whether the story has enough tension, contrast, and payoff.
- What must be corrected before production.

Then rewrite or package the script using those corrections.

## Selected Visual System

Before image prompts, choose the best visual system for the episode and say why.

Do not default to generic prompts. Select the visual system based on the script's subject:

- Editorial Diagram System: best for clean conceptual explanations.
- Notebook Sketch System: best for deep theory, origin questions, and reflective sections.
- Social Comic System: best for human interaction, emotion, social pressure, and dialogue.
- Hybrid Sketch System Map: best for historical progression, system evolution, trust networks, behavior loops, and concepts that need both narrative and diagrams.
- Cinematic Documentary System: best for historical people, inventions, projects, companies, and physical technology.
- Evidence Board / Polaroid System: best for mystery, investigation, forgotten history, hidden connections, and research-driven stories.

If the user suggests a visual system and it fits, use it. If a different system is stronger, say so and explain.

## Script Section

Write the script cleanly without image prompts. If timestamps are useful, include them. If the user asked for a Short, write tightly for the requested length.

The script should preserve:

- Hook.
- Setup.
- Tension.
- Payoff.
- Present-day or system connection.

## Primary Character Image Prompt

Include this section when the video has a main historical figure, recognizable person, recurring presenter, mascot, or recurring fictional character.

Purpose: give the user a stable reference image prompt they can generate once and reuse for consistency across the video.

For historical or renowned individuals:

- Research what the person looked like using public, factual references.
- Describe age range, hair, facial hair, face shape, clothing era, and defining non-copyrightable traits.
- Avoid copying a specific copyrighted photograph, portrait composition, illustration style, or living artist's style.
- Phrase the prompt as a historically grounded character design, not a replica of a specific image.
- Mention uncertainty when visual references conflict or are limited.

For fictional or generic recurring characters:

- Define stable age, build, hair, clothing, expression range, and color palette.
- Keep the description reusable across shots.

Every later shot featuring the same character should reuse the same character description or refer to it explicitly.

## Shot-By-Shot Image Prompts

Do not map prompts mechanically paragraph by paragraph. Use timed shots like a documentary director.

Each shot should include:

- Timestamp range.
- Narration line or phrase covered by the shot.
- Image prompt.

Multiple shots may cover one sentence when pacing requires it.

For long-form videos, provide 3 image prompt variations per shot for A/B testing unless the user explicitly asks for a single prompt. Vary framing, style layer, or visual metaphor while preserving the same narration beat and channel identity. For Shorts, one strong prompt per shot is usually enough unless the user asks for A/B variants.

Long-form script-to-image ratio:

- Do not use one prompt per large script section.
- Treat each visual beat as a shot.
- Hook sections should usually change visuals every 2-4 seconds.
- Main explanation sections should usually change visuals every 3-4 seconds.
- A 5-6 second shot is only acceptable when it is a deliberate emphasis moment, emotional pause, statistic card, date card, map hold, diagram hold, or visual idea that needs time to sink in.
- If a regular narration beat is longer than 5-6 seconds, split it into two or more image prompts. For example, 6 seconds can become 3+3, 7 seconds can become 4+3, and 8 seconds can become 4+4.
- No single prompt should cover more than about 6 seconds unless there is a clear retention reason. If a longer timestamp is unavoidable, create multiple numbered prompts inside that timestamp instead of one generic prompt.
- An 8-10 minute video should normally produce dozens of visual beats, often 60-100+ shots depending on pacing.
- If the full shot list would be too long for one response, split it into parts instead of compressing it into a thin shot list.

Every image prompt must answer:

1. What is visually happening?
2. How is it framed?
3. What emotional tension is present?
4. What props, setting, or details make the concept clear?

Prompts must be descriptive enough for image generation. Include visual system, composition, subject, action, framing, background, style, emotional tone, important labels/text, and negative constraints where needed.

The AI image generator does not know the script. Each image prompt must stand alone. Do not assume the generator knows the topic, timeline, place, currency, era, character, emotional context, or visual system from surrounding narration.

For historical scripts, every prompt that shows the past must state the period or historical setting clearly. If the narration is about ancient Mesopotamia, Lydia, early agriculture, cowrie money, Victorian industry, 1970s energy policy, or any other specific setting, name that setting in the prompt.

For money, finance, trade, and economic history visuals, specify the exact value object when relevant. Do not write "money" if the shot needs pounds, dollars, cowrie shells, grain rations, clay accounting tablets, livestock, silver, gold, electrum coins, banknotes, or digital balances.

For prompts involving currencies, objects, machines, clothing, architecture, maps, documents, or tools, define whether they are ancient, medieval, early modern, industrial-era, modern, or futuristic. The prompt should prevent accidental modern objects from appearing in ancient scenes and prevent vague "AI history" visuals.

Every generated prompt should include:

1. Visual system or style layer.
2. Exact subject and action.
3. Historical period, location, or domain context when relevant.
4. Composition and camera/framing.
5. Props, clothing, setting, labels, maps, or physical details.
6. Emotional tension or narrative meaning.
7. Negative constraints for mistakes to avoid.

Bad prompt: "Ancient people trading before money."

Better prompt: "Hybrid Sketch System Map, early agricultural village around 10,000 BCE, two families near mud-brick storage pits and woven grain baskets, one person sharing harvested grain while others watch and remember the favor, medium-wide documentary composition with faint hand-drawn memory lines connecting villagers, warm earth tones, no coins, no paper money, no modern clothing, no modern buildings."

Use judgment on complexity. Some shots should be literal and simple when the narration itself is the visual idea:

- "150 million years ago" can be a bold text/date card reading "150,000,000 YEARS AGO" over a simple background.
- "He had a dog that interrupted his work" can be a simple scene of a man at a desk with a dog interrupting him and a short speech bubble.
- A number, date, quote, map label, newspaper headline, or simple object can be the whole prompt if it serves pacing.

Do not turn every line into an elaborate historical scene. Alternate elaborate documentary shots with simple text cards, props, diagrams, character beats, and visual punctuation.

## SEO Meta Description

Write a rich, upload-ready description, not a short summary. Match the depth of a serious YouTube description that helps both viewers and search understand the video.

Default structure:

1. Paragraph 1: identify the main topic with the primary keyword, key person/place/date/concept, and the main event or question.
2. Paragraph 2: explain the tension, contradiction, conflict, or reason the story matters.
3. Paragraph 3: connect the story to the wider niche, channel promise, or modern relevance.
4. "Topics covered:" section with 6-10 bullet points.
5. Relevant hashtags, when the platform description should include them.

For factual topics, mention names, dates, technologies, companies, locations, or concepts from the script. For human-behavior or systems topics, mention the core behavior, psychological effect, system loop, social pattern, and modern examples.

Keep it natural and readable. Do not keyword-stuff, but do not underwrite it. The description should usually be 150-250 words for Shorts and can be longer for long-form videos.

## Hashtags

Return 3-8 hashtags. Mix broad and specific tags.

## Tags

Return a comma-separated list of search tags. Include:

- Core topic.
- Alternate wording.
- Niche terms.
- Related entities.
- Viewer search phrases.

## Research Material

For factual, historical, science, technology, energy, finance, legal, medical, or current-event content, include a final research section. Keep it concise but useful.

Return:

- Sources used, with links.
- Key facts pulled from each source.
- Any uncertainty or conflicting detail that should be checked before publishing.

This section is for the user to cross-check the content and should not be written like video narration.

## Script Only Format

When the user asks only for a script, do not include metadata unless useful. Provide:

- Primary title.
- Script.
- Optional notes on hook, retention beats, and visual opportunities.

## Brainstorm Format

When brainstorming a new channel, return:

- Channel promise.
- Audience.
- Content lanes.
- Angle templates.
- Visual identity.
- Logo/profile image prompt.
- Banner image prompt.
- Optional watermark, default thumbnail, or recurring character prompt.
- First 10 video ideas.
- Risks and weak points.
- Best next action.

Challenge weak niches or overly broad positioning.
