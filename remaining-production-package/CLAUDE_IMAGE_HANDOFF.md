# Claude Image Handoff — Govardhan Gatha Bhaag 3 + Bhaag 4 Clips 9–14

## Exact project location

You are working inside this Windows folder:

`C:\Users\adbsa\OneDrive\Documents\Pocket Change\gov-gatha\remaining-production-package`

Open this dashboard first:

`C:\Users\adbsa\OneDrive\Documents\Pocket Change\gov-gatha\remaining-production-package\production-dashboard-nepali.html`

The approved Episode 1 reference images are here:

`C:\Users\adbsa\OneDrive\Documents\Pocket Change\gov-gatha\ep01\_MASTER_PROJECT_PACKAGE\10_VIDEO_GENERATION_PACKAGE\03_APPROVED_REFERENCES`

Save your generated images only inside:

- `C:\Users\adbsa\OneDrive\Documents\Pocket Change\gov-gatha\remaining-production-package\03_CANDIDATE_VISUALS\BHAAG_3`
- `C:\Users\adbsa\OneDrive\Documents\Pocket Change\gov-gatha\remaining-production-package\03_CANDIDATE_VISUALS\BHAAG_4`

Save any genuinely new reusable reference candidates inside:

`C:\Users\adbsa\OneDrive\Documents\Pocket Change\gov-gatha\remaining-production-package\04_NEW_REFERENCE_CANDIDATES`

Do not work in Downloads, the old `New projectssa` folder, or a different copy of the project.

## तपाईंको जिम्मेवारी

ठ्याक्कै 23 clip pairs बनाउनुहोस्:

- Bhaag 3: `B3-C01` देखि `B3-C17` सम्म — 17 start frames + 17 four-panel storyboards
- Bhaag 4: `B4-C09` देखि `B4-C14` सम्म — 6 start frames + 6 four-panel storyboards

कुल: **23 start frames + 23 storyboard boards = 46 images**

Codex ले Bhaag 2 सबै र Bhaag 4 clips 1–8 बनाउनेछ। ती clip IDs नबनाउनुहोस्।

## Source dashboard

`production-dashboard-nepali.html` खोल्नुहोस् र माथिको **Claude का २३** filter थिच्नुहोस्। प्रत्येक कार्डमा:

- exact start-frame prompt
- exact four-panel storyboard prompt
- आवश्यक existing references
- missing/new asset warning
- story action र continuity beats

सबै छन्। Prompt पुनर्लेखन नगर्नुहोस्; आवश्यक भए reference attachment स्पष्ट गर्न मात्र सुधार गर्नुहोस्।

## Reference source

Existing approved Episode 1 references:

`../ep01/_MASTER_PROJECT_PACKAGE/10_VIDEO_GENERATION_PACKAGE/03_APPROVED_REFERENCES/`

Dashboard मा देखिएका references मात्र attach गर्नुहोस्। Unrelated reference नदिनुहोस्।

## Output folders and exact filenames

### Bhaag 3

Save to:

`03_CANDIDATE_VISUALS/BHAAG_3/`

For every ID, use:

- `B3-C01_START_FRAME_candidate_v1.png`
- `B3-C01_STORYBOARD_4P_candidate_v1.png`

त्यसैगरी C02–C17।

### Bhaag 4

Save to:

`03_CANDIDATE_VISUALS/BHAAG_4/`

- `B4-C09_START_FRAME_candidate_v1.png`
- `B4-C09_STORYBOARD_4P_candidate_v1.png`

त्यसैगरी C10–C14।

PNG, 16:9. Existing files overwrite नगर्नुहोस्; revision भए `_v2` प्रयोग गर्नुहोस्।

## Non-negotiable visual rules

- Match Episode 1 premium stylized 3D Indian mythological animation.
- Preserve Krishna, Indra, Yashoda and Nanda identities exactly.
- No modern objects, text, labels, panel numbers, arrows, captions, logos or watermarks.
- No costume/face/age drift, duplicated leads, broken anatomy, random gods or horror styling.
- Start frame must show only the initial state before the main movement.
- Storyboard must be one 16:9 board containing **four separate mini 16:9 landscape frames in a 2×2 grid**: two across the top and two across the bottom. Each mini frame must visibly remain landscape 16:9. Use thin neutral gutters only. Do not use four tall vertical panels, labels, or outer black bars.
- Storyboard panels must maintain the same camera axis, identities, costumes, lighting and location.
- Do not create end frames.
- Generated images remain candidates until user visual approval.

## Missing assets

Some Claude cards depend on new assets such as Samvartaka clouds, flooded Vrindavan, the lifted-Govardhan shelter, lathis, or repentant Indra states. If a missing master reference blocks a clip:

1. Create the reusable master asset first.
2. Save it under `04_NEW_REFERENCE_CANDIDATES/` with its code from the dashboard.
3. Do not mark it approved.
4. Use it consistently across the dependent Claude clips.
5. Include the final asset filename in your delivery note.

## Delivery checklist

- 46 expected images delivered
- filenames match exactly
- all images are 16:9 PNG
- no text/watermarks
- character identity checked
- continuity checked between consecutive clips
- missing master references listed
- known defects listed
- no files marked approved

When finished, place a short report at:

`99_REPORTS/CLAUDE_IMAGE_DELIVERY_REPORT.md`
