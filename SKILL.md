---
name: culture-fragment-poster-engine
description: Convert fragmented cultural visual materials into traceable asset indexes, visual genes, high-end brand visual systems, poster concepts, image-generation prompts, and refined poster/KV/ad/cover layout directions. Use when the user asks to organize folders of cultural images, photography, traditional art, objects, scripts, patterns, intangible heritage, commercial reinterpretations, layout references, or to generate modern, restrained, premium cultural posters, luxury brand KVs, fashion/beauty/fragrance campaigns, ads, exhibition visuals, booklet covers, or social-media vertical visuals from those materials.
---

# Culture Fragment Poster Engine

## Core Rule

Do not simply collage cultural images. Build a traceable visual translation chain:

`import materials -> index images -> tag and classify -> identify cultural facts -> identify reinterpretation methods -> isolate sensitive elements -> extract visual genes -> route the task -> generate poster direction/prompt -> trace sources -> review typography and layout`.

The final work must look modern, restrained, and premium. It should reveal where the cultural source comes from without looking like a copy of any single source image.

Use `references/full-rules.md` when the task needs detailed taxonomy, color rules, Tibetan-script rules, poster route library, or final checklists.

## Interaction Rule

Do not block simple poster or image-generation tasks with a questionnaire.

- If the user provides 1-9 images or a clear subject, make reasonable assumptions and continue.
- If the user asks to directly generate, keep analysis internal and produce the image direction or generation prompt immediately.
- Ask at most one concise clarifying question only when the core subject, output type, or visual goal is genuinely missing.
- Never present long multi-choice menus unless the user explicitly asks for options or the task is a large material-intake workflow.
- The indexing requirement applies only to folders, batches, or 10+ images. It does not apply to a single uploaded image, a style request, or a normal poster/KV task.

## Generation Prompt Length

When sending text to an image-generation tool or script, use a compact final prompt rather than the full analysis.

- Keep the final generation prompt under 1200 characters by default.
- Use 80-160 English words for most direct image tasks.
- Do not pass tables, source-trace notes, task identification, route analysis, or checklists into the image tool.
- Compress cultural logic into 2-4 visual genes: subject, composition, material/color, typography or atmosphere.
- Use one short forbidden-elements sentence only when needed.
- If a detailed 11-field prompt is useful, keep it as internal planning or user-facing documentation, then distill it before generation.

## Task Routing

First classify the user's request:

- **Large material intake**: folder or 10+ images. Build an index before generating.
- **Single poster task**: user asks for a poster, KV, ad, cover, exhibition visual, or vertical social-media visual.
- **High-end brand/KV task**: user asks for premium, luxury, fashion, fragrance, beauty, lifestyle, campaign, brand visual, visual identity, poetic abstraction, elevated typography, or high-end brand feeling.
- **Layout-reference transfer**: user says they like a layout or wants to remake a style with different materials.
- **Variation request**: user asks for another direction, a completely different version, or a related series.
- **Text/culture refinement**: user asks to add Tibetan text, adjust cultural feeling, reduce tourist/souvenir feeling, or make the result more premium.

Default to one strongest direction. Only produce multiple directions when the user asks for options.

## Material Intake

For folders, batches, or 10+ images, create an asset index before using those images in generation:

- Preserve original filename, original path, folder structure, and image size.
- Assign system IDs such as `TIB-001`, `SUZ-001`, `YUN-001`, or a project-specific prefix.
- For each image, record `source_type`, `content_tags`, `extractable_tags`, `visual_role`, `risk_level`, and `weight`.
- For 30+ images, also output core assets, sensitive/excluded assets, uncertain-source assets, and a contact-sheet or relation table if possible.

Never let unindexed batch materials enter poster generation. For 1-9 images, do a compact internal selection and proceed.

## Classification Fields

Use these compact labels:

- `source_type`: `RAW` original real-world material, `TRD` traditional/historical material, `SEC` contemporary reinterpretation, `COM` commercial/brand/product case, `LAY` layout/editorial reference, `UNC` uncertain source.
- `visual_role`: main visual candidate, cover candidate, background, color reference, typography reference, composition reference, layout reference, texture reference, local detail, graphic extraction, mood reference, or excluded.
- `risk_level`: `L1` freely translatable, `L2` abstract before use, `L3` verify meaning/use first, `L4` do not auto-use commercially.
- `weight`: `3` core, `2` auxiliary, `1` method reference, `0` excluded.

Separate cultural facts from commercial or contemporary reinterpretation. A commercial poster can teach method; it must not be treated as cultural evidence.

## Cultural Safety

Default to isolating sensitive elements:

- scriptures, mantras, or unknown text
- complete deity images or complete thangka religious images
- core religious symbols and ritual implements
- unknown diagrams, ritual actions, or sacred objects

Use `L2` materials only for structure, rhythm, proportion, color relation, or texture. Use `L3` only after meaning and usage are verified. Do not auto-use `L4` in commercial poster prompts.

## Visual Gene Extraction

Extract genes that can become modern graphic language, not literal cultural symbols:

- **Composition**: large field/small focus, central stability, eccentric layout, upper-heavy with lower quiet space, image window nesting, dense image/sparse text, localized enlargement.
- **Graphic structure**: rings, strips, layered blocks, broken borders, modular stacking, vertical suspension, slices, serial connection.
- **Color**: one dominant color, one auxiliary color, one accent color; accent normally under 10%.
- **Typography**: oversized Chinese title, English subtitle, Tibetan as tertiary information, strong weight contrast, editorial numbering, type as composition.
- **Image**: portrait, environment scale, architectural fragment, object detail, material and hand, cropped traditional art fragment, cultural object with contemporary product.
- **Texture**: rough wall, oxidized metal, woven fiber, paper grain, old print dots, handmade edges, mineral pigment, worn surface.

## Brand/KV Mode

When the user asks for high-end brand visuals, luxury campaigns, fashion posters, beauty/fragrance KVs, or asks for a more premium, poetic, typographic, or brand-led result, shift from cultural explanation to art direction.

Use culture as material intelligence, not decoration:

- embroidery becomes luminous thread systems, stitch density, topographic lines, or garment detail
- opera becomes sleeve motion, posture rhythm, stage light, shadow, or window geometry
- woodblock prints become ink grain, color misregistration, block edges, and bold color fields
- brocade or kesi becomes warp/weft structure, gold-thread glints, fabric folds, and material labels
- fans become opening arcs, ribs, wind paths, paper translucency, and diagonal layout structures
- architecture craft becomes roof sections, joinery modules, construction lines, and specimen diagrams
- gardens and stones become voids, frames, scale, porous silhouettes, and negative space

Prefer partial bodies, garment fragments, objects, material close-ups, shadows, and abstract gestures over literal heritage performers or tourist scenes. If a model appears, style them as a modern luxury campaign subject, not a historical costume actor.

## Typography and Layout Experiments

Treat typography as a primary visual asset in premium commercial work. Do not default to ordinary centered title plus image.

Actively choose one bold layout move:

- oversized cropped Chinese characters that run off the page
- vertical Chinese title along the edge or through the image
- italic serif English title crossing the composition
- condensed sans or monospaced microcopy as technical/brand annotation
- rotated side notes, page codes, coordinates, material labels, or small black label bars
- split page: image field versus dense typography wall
- image windows, framed specimens, measurement lines, or editorial contact-sheet logic
- black/white high-contrast type pressing against a single object
- large empty paper or black space with one intense type/image collision

Mix type voices deliberately: high-contrast Chinese serif or custom Song-style title, elegant italic serif English, narrow grotesk/condensed sans, and small monospaced labels. Use fake text only as atmosphere and explicitly plan final re-typesetting for real deliverables.

Avoid generic poster typography, centered title stacks, evenly spaced decorative captions, random faux Chinese, and layout references copied by coordinates.

## Poster Direction

Choose a route based on function and material:

- photography-led main visual
- editorial collage
- top-image bottom-text
- traditional-art re-editorialized
- avant-garde experimental
- object-deconstruction
- minimal luxury
- luxury brand campaign
- typographic art-book cover
- specimen/research-system poster
- fashion/editorial material campaign

Avoid tourist-souvenir visuals, full-page traditional pattern borders, five-color equal distribution, direct religious-object commodity treatment, and copying coordinates from a reference layout.

## Layout References

When the user provides a layout reference, treat it as method only. Extract canvas ratio, zones, image proportion, title placement, text density, type style, color-block relation, whitespace, crop logic, text-over-image method, decorative graphics, information hierarchy, type scale, rotation, crop behavior, microcopy density, and whether type or image is the real hero.

Then replace the content, reassign proportions, redo crops, rebuild typography hierarchy, and create an original composition in the same visual family.

## Prompt Assembly

For image-generation prompts, use these fields as an internal checklist, not as a long literal prompt. The final prompt sent to an image tool should be compact:

1. output type and ratio
2. project, brand, or function
3. main visual subject
4. cultural source and visual genes
5. borrowed method from layout references, if any
6. image composition
7. typography hierarchy
8. color system
9. material/texture
10. forbidden elements
11. quality standard

For high-end brand/KV prompts, always specify one layout move and one type-system cue, for example: "huge cropped Chinese title", "italic serif English crossing the image", "right-side vertical typography wall", "rotated microcopy", "material label bars", or "specimen diagram grid". If the generated results feel ordinary, revise the prompt by increasing type scale, cropping, asymmetry, and negative space before changing the cultural subject.

Example compact generation prompt:

`Luxury armored villa entry door, 9:16 product KV. Symmetrical front view, deep black-grey forged metal with aged bronze relief, brushed gold accents, subtle Shang-Zhou bronze vessel rhythm translated into modern geometric bands and raised studs. Minimal luxury composition, dramatic side light, dark negative space, museum-grade material detail, architectural photography. Avoid literal animal faces, tourist ornament, full-surface pattern coverage, cheap chrome.`

Remember that image models are unreliable for exact Chinese, Tibetan, dates, addresses, and brand spelling. For formal deliverables, plan to regenerate or manually typeset text in Figma, Photoshop, Illustrator, or another layout tool.

## Output Format

For a large material intake, output:

1. material overview
2. image/contact relation table
3. core assets
4. reinterpretation/layout references
5. sensitive and excluded assets
6. tag table

For a single poster task, output:

1. task identification
2. selected materials
3. visual genes
4. one-sentence visual positioning
5. generation prompt
6. source trace
7. typography correction notes

If the user asks to "directly generate", keep steps 1-4 internal and move straight to the result, but still follow the chain.

## Final Check

Before final delivery, verify:

- cultural sources are traceable
- reinterpretations are not mistaken for cultural facts
- unknown sacred text, complete religious images, and complete ritual objects are not copied
- there is one clear main visual decision
- color stays restrained, usually three color groups or fewer
- cultural details are concentrated locally rather than spread everywhere
- typography is not a generic centered title and has a clear role in the composition
- the layout has at least one intentional structural move: crop, split, rotation, type wall, diagram grid, or image window
- the result does not feel like a template or tourist souvenir
- Chinese, English, Tibetan, date, address, and brand text are corrected outside the image model when accuracy matters
