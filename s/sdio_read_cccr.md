# Function: <code>sdio_read_cccr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff816c8f8c)
Location: drivers/mmc/core/sdio.c:101
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8172bf5c)
Location: drivers/mmc/core/sdio.c:101
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8175f111)
Location: drivers/mmc/core/sdio.c:102
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8177d659)
Location: drivers/mmc/core/sdio.c:105
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff817f3bdc)
Location: drivers/mmc/core/sdio.c:105
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff8183d0f6)
Location: drivers/mmc/core/sdio.c:105
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81869081)
Location: drivers/mmc/core/sdio.c:105
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818acf26)
Location: drivers/mmc/core/sdio.c:101
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818df36d)
Location: drivers/mmc/core/sdio.c:101
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sdio_read_cccr(struct mmc_card *card, u32 ocr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:119
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b1bd0-ffffffff819b1e0f: sdio_read_cccr (STB_LOCAL)
ffffffff819b360b-ffffffff819b3637: sdio_read_cccr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sdio_read_cccr(struct mmc_card *card, u32 ocr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:143
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b3fa0-ffffffff819b41df: sdio_read_cccr (STB_LOCAL)
ffffffff81c2b140-ffffffff81c2b16c: sdio_read_cccr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sdio_read_cccr(struct mmc_card *card, u32 ocr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:143
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81998700-ffffffff8199893f: sdio_read_cccr (STB_LOCAL)
ffffffff81c1d4ba-ffffffff81c1d4e6: sdio_read_cccr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sdio_read_cccr(struct mmc_card *card, u32 ocr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:143
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81a44e10-ffffffff81a45051: sdio_read_cccr (STB_LOCAL)
ffffffff81d2e59f-ffffffff81d2e5cb: sdio_read_cccr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sdio_read_cccr(struct mmc_card *card, u32 ocr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sdio.c (0)
Location: drivers/mmc/core/sdio.c:144
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81bb2a20-ffffffff81bb2ca0: sdio_read_cccr (STB_LOCAL)
ffffffff81efa9c0-ffffffff81efa9ec: sdio_read_cccr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sdio_read_cccr(struct mmc_card *card, u32 ocr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81d56d90)
Location: drivers/mmc/core/sdio.c:144
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d56d90-ffffffff81d57091: sdio_read_cccr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sdio_read_cccr(struct mmc_card *card, u32 ocr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81dc1710)
Location: drivers/mmc/core/sdio.c:144
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81dc1710-ffffffff81dc1a11: sdio_read_cccr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sdio_read_cccr(struct mmc_card *card, u32 ocr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81e79fd0)
Location: drivers/mmc/core/sdio.c:144
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81e79fd0-ffffffff81e7a2d1: sdio_read_cccr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffff800010b39588)
Location: drivers/mmc/core/sdio.c:101
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (c0c13ef4)
Location: drivers/mmc/core/sdio.c:101
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (c000000000c359f8)
Location: drivers/mmc/core/sdio.c:101
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffe000711262)
Location: drivers/mmc/core/sdio.c:101
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff81882d2d)
Location: drivers/mmc/core/sdio.c:101
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
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818d41cd)
Location: drivers/mmc/core/sdio.c:101
Inline: True
Inline callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sdio.c (ffffffff818f0ced)
Location: drivers/mmc/core/sdio.c:101
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
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
