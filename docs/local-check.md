# Local check summary

- Theme: Rosé Pine · Prism 0.1.1
- Manifest SHA-256: `30131024c83b7f7af2dce8121faf1775453f3e1a104f55288ff33c522812ac5f`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 8.69:1, title 8.69:1, link 5.59:1, tag 4.96:1, code 7.92:1, mark 7.75:1, chosen 8.19:1.
  - Dark: body 11.86:1, title 11.86:1, link 9.19:1, tag 7.13:1, code 10.9:1, mark 7.1:1, chosen 8.82:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
