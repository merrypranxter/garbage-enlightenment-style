# DRIFT FLAGS DRAFT

This file provides draft drift-flag labels for classifying wrong turns in prompts, outputs, or refs.

Useful for:
- internal review
- app integration
- prompt repair
- style QA
- tagging outputs that need correction

## CORE PRINCIPLE

A drift flag should identify the specific wrong turn, not just say “bad.”

## DRIFT FLAG LIST

### `too_polished`
Image is too clean, refined, sleek, or tastefully finished.

### `too_pretty`
Image is attractive in a noble or flattering way that weakens the rude mutant energy.

### `too_spiritual`
Image has drifted into sincere mystical / reverent visionary territory.

### `too_occult_branding`
Image resembles luxury occult merch, tattoo branding, or clean esoteric design.

### `too_cute_pure`
Image is cute but lacks contamination, body weirdness, or symbolic tension.

### `too_horror_grim`
Image is overly dark, joyless, gorey, or realism-heavy in its horror tone.

### `too_generic_trippy`
Image relies on default psychedelic clichés without the repo’s specific engines.

### `too_abstract_empty`
Image is abstract but lacks emergence pressure or body-haunted logic.

### `too_static`
Image feels settled, fixed, and not mid-becoming.

### `too_cool`
Image feels stylish, detached, and emotionally overcontrolled.

### `too_safe`
Image has had too much weirdness or friction removed.

### `too_clean_vector`
Image has drifted into corporate/editorial/flat-design neatness.

### `too_kawaii`
Image is drifting into mascot/sticker sweetness with no contamination.

### `too_symmetrical_sacred`
Image uses symmetry in a way that feels solemn, majestic, or reverential.

### `too_empty_symbolically`
Image has motifs but little symbolic pressure or meaningful interaction.

### `too_random`
Image contains weird elements but no coherent family logic.

### `too_rendered`
Image feels too painted, too airbrushed, or too texturally refined.

### `too_background_wallpaper`
The field/background is decorative but not active.

### `too_glitch_generic`
Digital damage is present but disconnected from body-symbol logic.

### `too_lsd_literal`
The image is trying too hard to imitate hallucinations literally rather than translating the logic into
cartoon-symbolic form.

## SUGGESTED RESPONSE ACTIONS

### For `too_polished`
- roughen linework
- flatten surfaces
- simplify rendering
- reintroduce cheapness

### For `too_cute_pure`
- add a body glyph
- contaminate one sweet motif
- increase symbolic wrongness

### For `too_generic_trippy`
- add motif specificity
- strengthen body logic
- clarify tone friction
- reduce wallpaper-like abstraction

### For `too_static`
- add implied morph pressure

- introduce embedded secondary form
- state “paused mid-mutation”

### For `too_spiritual`
- add parody
- add body humor
- contaminate the sacred icon
- reduce reverent staging

## FLAG CLUSTERS

Common clusters:
- `too_polished` + `too_pretty` + `too_spiritual`
- `too_cute_pure` + `too_safe`
- `too_generic_trippy` + `too_abstract_empty`
- `too_occult_branding` + `too_cool`
- `too_horror_grim` + `too_rendered`

## FINAL RULE

Drift flags should help answer:
**what specifically has become too respectable, too generic, too pure, or too dead?**

That is the right repair question.

PALETTE_PRESETS_DRAFT.json
{
"palette_presets": [
{
"name": "native_acid",
"description": "Core Garbage Enlightenment palette with synthetic acid cartoon pressure.",
"colors": [
"acid_yellow",
"hot_pink",
"weird_peach_flesh",
"toxic_green",
"electric_cyan",
"toy_blue",
"hard_red",
"black_outline",
"dirty_cream"
],
"mood": [
"chemically_vivid",
"rude",
"symbolic",
"unstable"

]
},
{
"name": "sweet_toxin",
"description": "Candy-forward palette contaminated by body and toxic accents.",
"colors": [
"candy_pink",
"bubblegum_coral",
"sweet_sky_blue",
"mint_green",
"sticker_lavender",
"artificial_orange",
"lip_red",
"black_outline"
],
"mood": [
"cute_but_suspicious",
"soft_wrongness",
"toy_like"
]
},
{
"name": "bruise_rainbow",
"description": "Sick-sweet palette with bruised chroma and ominous bodily tension.",

"colors": [
"bruise_mauve",
"sickly_yellow",
"dirty_cyan",
"moldy_green",
"weird_magenta",
"rotted_peach",
"blue_gray",
"black_outline"
],
"mood": [
"eerie",
"sick_sweet",
"body_adjacent"
]
},
{
"name": "plastic_heaven",
"description": "Bright toy-plastic palette with fake innocence and sticker energy.",
"colors": [
"candy_red",
"toy_yellow",
"synthetic_cyan",
"bubble_pink",

"plastic_green",
"white_highlight",
"black_outline"
],
"mood": [
"cheap_toy_ecstasy",
"plastic_revelation",
"fake_innocence"
]
},
{
"name": "thermal_revelation",
"description": "Field-heavy palette for abstract hallucination and contour emergence.",
"colors": [
"thermal_yellow",
"orange_red",
"electric_pink",
"false_cyan",
"contour_blue",
"toxic_green",
"black_cavity"
],
"mood": [
"hallucinatory",

"signal_rich",
"pressure_mapped"
]
},
{
"name": "cute_necrosis",
"description": "Sweet-morbid palette for decorative death and soft eerie symbolism.",
"colors": [
"soft_pink",
"dead_cream",
"bruise_lavender",
"mint_rot_green",
"bone_white",
"black",
"tooth_red"
],
"mood": [
"cute_morbid",
"sweet_eerie",
"decorative_decay"
]
},
{
"name": "dirt_candy",

"description": "Bodily, sticky palette with candy remnants and gross-soft contrast.",
"colors": [
"dirty_coral",
"sour_yellow",
"rot_green",
"body_peach",
"muddy_pink",
"cheap_blue",
"mouth_red",
"cavity_black"
],
"mood": [
"bodily",
"gross_soft",
"low_status_alive"
]
},
{
"name": "glitch_sticker_acid",
"description": "Digitally synthetic palette with screen-bright sticker aggression.",
"colors": [
"neon_cyan",
"hot_magenta",
"hard_yellow",

"low_res_green",
"cheap_white",
"compression_gray",
"black"
],
"mood": [
"digital_cheapness",
"signal_intensity",
"rude_screen_magic"
]
}
]
}
