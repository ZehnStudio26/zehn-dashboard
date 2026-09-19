# Badge icons

One image per badge **and level**, named `{badge-slug}-l{1|2|3}.png`
(bronze L1 / silver L2 / gold L3 — resized to 128px from the full-res art
in `badge_system/badge_art/`):

    gameplay-scripter-l1.png ... story-content-publisher-l3.png

The dashboard shows the image matching the member's held level. A plain
`{badge-slug}.png` also works as a level-independent fallback; no image at
all falls back to a text chip.

Missing art (proposed badges, no images yet): `project-manager`,
`team-communication-manager`.
