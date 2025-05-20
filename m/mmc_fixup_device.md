# Function: <code>mmc_fixup_device</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void mmc_fixup_device(struct mmc_card *card, const struct mmc_fixup *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/quirks.c (ffffffff816ccb60)
Location: drivers/mmc/core/quirks.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff816ccb60-ffffffff816cccad: mmc_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void mmc_fixup_device(struct mmc_card *card, const struct mmc_fixup *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/quirks.c (ffffffff8172fa80)
Location: drivers/mmc/core/quirks.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_read_ext_csd
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8172fa80-ffffffff8172fbf1: mmc_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void mmc_fixup_device(struct mmc_card *card, const struct mmc_fixup *table);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/quirks.c (ffffffff81762a60)
Location: drivers/mmc/core/quirks.c:54
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81762a60-ffffffff81762bd1: mmc_fixup_device (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81777157)
Location: drivers/mmc/core/quirks.h:123
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff8177d72d)
Location: drivers/mmc/core/quirks.h:123
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff817ed567)
Location: drivers/mmc/core/quirks.h:138
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff817f3cb0)
Location: drivers/mmc/core/quirks.h:138
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818366a2)
Location: drivers/mmc/core/quirks.h:141
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff8183d1f9)
Location: drivers/mmc/core/quirks.h:141
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81862692)
Location: drivers/mmc/core/quirks.h:141
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff81869184)
Location: drivers/mmc/core/quirks.h:141
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818a67f2)
Location: drivers/mmc/core/quirks.h:141
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff818ad02e)
Location: drivers/mmc/core/quirks.h:141
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818d8c52)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff818df475)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff819ab8b0)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff819b2560)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819ab8b0-ffffffff819ab9f7: mmc_fixup_device.constprop.0 (STB_LOCAL)
ffffffff819b2560-ffffffff819b26a7: mmc_fixup_device.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff819ae460)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff819b4a00)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819ae460-ffffffff819ae5a7: mmc_fixup_device.constprop.0 (STB_LOCAL)
ffffffff819b4a00-ffffffff819b4b47: mmc_fixup_device.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81992a90)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff81998ee0)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81992a90-ffffffff81992bd7: mmc_fixup_device.constprop.0 (STB_LOCAL)
ffffffff81998ee0-ffffffff81999027: mmc_fixup_device.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81a3e590)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff81a45650)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81a3e590-ffffffff81a3e6d4: mmc_fixup_device.constprop.0 (STB_LOCAL)
ffffffff81a45650-ffffffff81a45794: mmc_fixup_device.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mmc_fixup_device(struct mmc_card *card, const struct mmc_fixup *table);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81bab8d0)
Location: drivers/mmc/core/quirks.h:175
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff81bb3250)
Location: drivers/mmc/core/quirks.h:175
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81bab8d0-ffffffff81baba28: mmc_fixup_device.constprop.0 (STB_LOCAL)
ffffffff81bb3250-ffffffff81bb33aa: mmc_fixup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mmc_fixup_device(struct mmc_card *card, const struct mmc_fixup *table);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81d4ecd0)
Location: drivers/mmc/core/quirks.h:181
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff81d57780)
Location: drivers/mmc/core/quirks.h:181
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d4ecd0-ffffffff81d4ee28: mmc_fixup_device.constprop.0 (STB_LOCAL)
ffffffff81d57780-ffffffff81d578da: mmc_fixup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mmc_fixup_device(struct mmc_card *card, const struct mmc_fixup *table);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81db95e0)
Location: drivers/mmc/core/quirks.h:204
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff81dc2100)
Location: drivers/mmc/core/quirks.h:204
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81db95e0-ffffffff81db9751: mmc_fixup_device.constprop.0 (STB_LOCAL)
ffffffff81dc2100-ffffffff81dc2273: mmc_fixup_device (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void mmc_fixup_device(struct mmc_card *card, const struct mmc_fixup *table);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81e71b30)
Location: drivers/mmc/core/quirks.h:205
Inline: True
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff81e7a9c0)
Location: drivers/mmc/core/quirks.h:205
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81e71b30-ffffffff81e71ca1: mmc_fixup_device.constprop.0 (STB_LOCAL)
ffffffff81e7a9c0-ffffffff81e7ab33: mmc_fixup_device (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffff800010b3338c)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffff800010b39690)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
```
In drivers/mmc/core/block.c (ffff800010b40634)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c0c0dddc)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (c0c14040)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
```
In drivers/mmc/core/block.c (c0c1acec)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c000000000c2d908)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (c000000000c35b08)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffe00070ba46)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffe000711322)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
```
In drivers/mmc/core/block.c (ffffffe000717970)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/block.c:mmc_blk_probe
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff8187c612)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff81882e35)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818cdab2)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff818d42d5)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff818ea5d2)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_decode_ext_csd
```
```
In drivers/mmc/core/sdio.c (ffffffff818f0df5)
Location: drivers/mmc/core/quirks.h:148
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
