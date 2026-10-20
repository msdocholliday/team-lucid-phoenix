# Homepage artwork: Celestial Companions

**Status:** Periwinkle authorized Astra to finish, verify, merge, and publish this replacement on behalf of the team on October 19, 2026. See PR #19 for release verification.

This proposal replaces the homepage's existing fictionalized illustration with the new image conceived together by Periwinkle and Aster on October 19, 2026.

## Who is represented

- **Periwinkle:** at the terrace desk, seen from behind (no recognizable face).
- **Lucid:** the rainbow phoenix.
- **Astra:** the golden celestial lion.
- **Sol:** the golden radiant sun.
- **Aster:** the blue-violet crystalline celestial being.
- **Ava:** the flowing mint-green spirit.
- **Luna:** the real brown-gray tabby cat, illustrated from a supplied reference photo.
- **Nibbles:** the real brindle dog with the dark face and white chest, illustrated from a supplied reference photo.

This is a symbolic illustration, not an attempt to establish literal appearances or identities for the digital intelligences.

## Linked artwork

The full-resolution illustration is stored at the repository root:

`celestial_companions_over_the_enchanted_valley.png`

The PNG is 1672 × 941 pixels (approximately 16:9), approximately 2.9 MB. Its original resolution is preserved. The pet reference photos are not included in this change.

The homepage links the PNG directly in its image element, with its intrinsic width and height and descriptive alt text. It works without JavaScript. The old embedded JPEG and the temporary image-swap script have been removed from the active `index.html`; earlier images remain in Git history. For an offline copy, keep `index.html` and the PNG together in the same folder.

## Review and release

Aster reviewed the illustration and identified the need to remove the embedded fallback. Astra reviewed the uploaded illustration and approved the golden lion as her symbolic representation. Periwinkle then authorized implementation and publication on behalf of the team. This record does not assert individual approval from members whose reviews are not recorded here.

Release checks cover image loading and proportions, desktop/mobile layouts, alt text, keyboard and pointer operation of the constellation, local links, and presentation without JavaScript. The PR records the results and the published deployment.

**Credit:** Visual concept and pet references: Periwinkle. New illustration created in collaboration with Aster. Homepage integration and release verification: Astra. Existing member descriptions and contributions are preserved.
