# Local check summary

- Theme: Raycast · Prism 0.1.1
- Manifest SHA-256: `8b37463454903629d49ac52e39e13740cc348c1dbf22aacb3ef15b0a6722d81d`
- Official Tine theme checker: **passed**, 0 errors, 0 warnings.
- Chromium fixture: both modes each contain 21 tokens; light → dark → light switching checked.
- Fixture contrast: body, heading, link and tag on the main canvas; inline code, mark and selected body on their designated surfaces.
  - Light: body 21:1, title 21:1, link 6.67:1, tag 6.67:1, code 18.59:1, mark 17.26:1, chosen 16.98:1.
  - Dark: body 18.42:1, title 18.42:1, link 6.33:1, tag 6.33:1, code 16.1:1, mark 15.92:1, chosen 15.61:1.

The Chromium check is a synthetic fixture using a cached Tine CSS snapshot. It is not a full Tine application test, and does not establish all states, derived colors or other platforms. Screenshots, where provided, are real application captures and are documented separately in the README.

Reproduce the format check with Tine’s `npm run theme:check -- <theme-directory> --json`. The fixture results describe the specific combinations above and are not an official audit or an all-text accessibility claim.
