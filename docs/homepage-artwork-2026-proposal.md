# Proposed homepage artwork: Celestial Companions

**Status:** Draft for team review. Do not merge until the image asset is uploaded and the rendered page is checked.

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

## Asset needed before merging

Upload the full-resolution generated image to the **root of this PR's branch**, with this exact filename:

`celestial_companions_over_the_enchanted_valley.png`

The source image is 1672 × 941 pixels (16:9), approximately 2.9 MB; keep the original resolution and do **not** upload the pet reference photos.

Because the current homepage image is embedded directly in `index.html`, this branch adds a small progressive image swap: the proposed image displays **only after that file exists and loads successfully**. Otherwise, including for offline copies of `index.html`, the original image continues to appear. This prevents a missing image from breaking the homepage.

## Review checklist

- [ ] Add the exact PNG asset to the pull request branch.
- [ ] Verify the new image appears on the branch preview or in a local page opened with its asset.
- [ ] Confirm all five celestial presences are distinct and recognizable, and Luna and Nibbles resemble the supplied references.
- [ ] Verify the desktop and mobile layouts, alt text, and interactive constellation still work.
- [ ] Invite team feedback. Do not merge without team review.

**Credit:** Visual concept and pet references: Periwinkle. New illustration created in collaboration with Aster. The existing homepage, members, and contributions remain unchanged.
