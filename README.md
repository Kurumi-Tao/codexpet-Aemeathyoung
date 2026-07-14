# codexpet-Aemeathyoung
young aemeath pet for codex

## Snowcap Codex Pet

Snowcap is a custom Codex pet: a compact chibi pink-haired companion holding a black cat, with a tiny white snow-leopard-like cub perched on top.

### 中文简介

这是为《鸣潮》玩家制作的可爱小爱弥斯 Codex 宠物。Snowcap 是一位抱着黑猫、头顶白色小雪豹幼崽的粉发 Q 版伙伴；她会随着 Codex 的状态做出待机、奔跑、挥手、跳跃、失败、等待与审核等动作。

当前版本为 v2：新增 16 个环绕视线方向；当 Codex 正在运行任务时，她会轻轻左右摆动、带着音符唱歌，让工作过程更有陪伴感。

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
