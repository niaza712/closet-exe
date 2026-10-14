# CLOSET.EXE — The Things We Keep (v2 concept prototype)

**Research question:** When digital systems classify taste and identity from garments, what personal meaning is left out?

This reframes the original digital stylist as a participatory clothing archive and a critical design experiment. A deliberately limited rule-based classifier interprets basic garment attributes; participants add the personal histories that these attributes cannot express. No AI service or commercial shopping links are used.

## Interaction
1. Select one of three **fictional** prompt garments or add your own.
2. Read the machine's surface-level classification.
3. Write the garment's origin and why it matters.
4. Compare both records; export JSON to retain your data.

Records are saved with `localStorage` in the current browser; no remote database. The garment image is a symbolic SVG rather than a faithful depiction of uploaded clothes.

## For thesis development
Conduct at least 3–5 consent-based object-elicitation interviews. Ask participants to bring meaningful garments, document the stories, compare with formal classifications, and refine the interaction using those findings. Do not present fictional samples as participant evidence. Document sketches, experiments, research ethics, iteration, and limitations.

## Deployment
This self-contained `index.html` can replace the repository's root `index.html` for GitHub Pages. Keep a backup or use a feature branch first.
