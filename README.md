# codexpet-Aemeathyoung
young aemeath pet for codex

## Snowcap Codex Pet

Snowcap is a custom Codex pet: a compact chibi pink-haired companion holding a black cat, with a tiny white snow-leopard-like cub perched on top.

### Files

- `pets/snowcap/pet.json` - Codex pet manifest.
- `pets/snowcap/spritesheet.webp` - v2 8x11 animated pet atlas, 192x208 per cell, with 16 look directions.
- `qa/contact-sheet.png` - visual QA contact sheet.
- `qa/validation.json` - atlas validation result.
- `qa/review.json` - frame extraction and review result.
- `qa/videos/*.mp4` - animation previews for each state.

### Install Locally

Copy `pets/snowcap` into:

```text
C:\Users\hutao\.codex\pets\snowcap
```

Then restart Codex and select `Snowcap`.

### Animation States

- `idle`
- `running-right`
- `running-left`
- `waving`
- `jumping`
- `failed`
- `waiting`
- `running`
- `review`

### v2 Update

Snowcap now includes 16 clockwise look directions in the final two atlas rows.
The `running` state uses Snowcap's six-frame singing loop, while `waiting`
uses the prior work animation.

`running-left` was generated separately instead of mirrored, preserving side-specific accessory details.
给鸣潮玩家准备的小小可爱爱弥斯codex宠物
