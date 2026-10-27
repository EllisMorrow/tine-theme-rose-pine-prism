# Adaptation notes

Dawn and Moon are official Rosé Pine variants documented by the upstream palette project and paired as light/dark options in Codex. The upstream `@rose-pine/palette` package is version 4.0.1 at the pinned commit; its metadata names Rosé Pine as the author, while the retained MIT license notice credits mvllow. Tine roles are mapped independently, with light text and tag adjustments documented for readability on declared surfaces.

## Sources

- palette: https://github.com/rose-pine/rose-pine-palette/blob/92af52b465ab6e47437aca223c9b8d3009a2023b/palette.json
- package metadata: https://github.com/rose-pine/rose-pine-palette/blob/92af52b465ab6e47437aca223c9b8d3009a2023b/package.json
- license: https://github.com/rose-pine/rose-pine-palette/blob/92af52b465ab6e47437aca223c9b8d3009a2023b/LICENSE
- Codex pairing: Rosé Pine Moon (dark) and Rosé Pine Dawn (light).

## Mapping decisions

- The light mode uses official Dawn and the dark mode uses official Rosé Pine Moon.
- Tine's stepped surfaces map from Dawn base/surface/overlay and Moon base/surface/overlay; guide, selection and code roles adapt the official highlight neutrals.
- Light secondary text is deepened from #797593 to #625E7A and the tag role from #B4637A to #98566B; the link uses official pine #286983.
- Dark primary text, iris accent, foam link and rose tag follow official Moon roles; surface variations and amber marks are Tine adaptations.
- The 21-token theme API does not control fonts, task markers, arbitrary hover rules or every syntax color; no exact Codex UI reproduction is claimed.

## Local validation

See the [local check summary](local-check.md) for the exact tested combinations and current manifest digest. User screenshots and full Tine interaction acceptance are pending.

## Codex reference verification

- The dark mode follows Rosé Pine Moon and the light mode follows Dawn, matching the mode variants exposed by the current Codex theme picker.
- Moon base #232136, surface #2a273f, overlay #393552 and rose #ea9a97 are taken from the pinned upstream palette; a darker sidebar and selection are Tine adaptations.
- Dawn text roles are modestly deepened for readability. The 21-token API does not control fonts, task markers, arbitrary hover rules or all syntax colors.


Release 0.1.1 retains the tested 0.1.0 color tokens and adds publication metadata and pinned screenshots.

See the [local check summary](local-check.md) for the exact tested combinations and manifest digest.
