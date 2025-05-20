# Function: <code>mmc_set_uhs_voltage</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817743a0)
Location: drivers/mmc/core/core.c:1481
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff817743a0-ffffffff81774686: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817ea740)
Location: drivers/mmc/core/core.c:1708
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff817ea740-ffffffff817ea8bc: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1518
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81834404-ffffffff81834424: mmc_set_uhs_voltage.cold.41 (STB_LOCAL)
ffffffff818336b0-ffffffff8183380c: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1521
Inline: False
Direct callers:
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81860394-ffffffff818603b4: mmc_set_uhs_voltage.cold.43 (STB_LOCAL)
ffffffff8185f640-ffffffff8185f79c: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1203
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818a4037-ffffffff818a4059: mmc_set_uhs_voltage.cold (STB_LOCAL)
ffffffff818a31d0-ffffffff818a3335: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1203
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818d6525-ffffffff818d6547: mmc_set_uhs_voltage.cold (STB_LOCAL)
ffffffff818d54c0-ffffffff818d5625: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1186
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819a8e2c-ffffffff819a8e4c: mmc_set_uhs_voltage.cold (STB_LOCAL)
ffffffff819a7d00-ffffffff819a7ff2: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1186
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81c2a25d-ffffffff81c2a27d: mmc_set_uhs_voltage.cold (STB_LOCAL)
ffffffff819aaf60-ffffffff819ab252: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1192
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81c1c633-ffffffff81c1c655: mmc_set_uhs_voltage.cold (STB_LOCAL)
ffffffff8198f800-ffffffff8198f967: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1193
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d2d26a-ffffffff81d2d28c: mmc_set_uhs_voltage.cold (STB_LOCAL)
ffffffff81a3af50-ffffffff81a3b0be: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1193
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81ef961d-ffffffff81ef963d: mmc_set_uhs_voltage.cold (STB_LOCAL)
ffffffff81ba7e30-ffffffff81ba7fa1: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81d4a5c0)
Location: drivers/mmc/core/core.c:1200
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d4a5c0-ffffffff81d4a76a: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81db4e10)
Location: drivers/mmc/core/core.c:1200
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81db4e10-ffffffff81db4fb8: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81e6cf70)
Location: drivers/mmc/core/core.c:1205
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81e6cf70-ffffffff81e6d177: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2ed30)
Location: drivers/mmc/core/core.c:1203
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffff800010b2ed30-ffff800010b2eeb0: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c0a1ec)
Location: drivers/mmc/core/core.c:1203
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
c0c0a1ec-c0c0a39c: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c287c0)
Location: drivers/mmc/core/core.c:1203
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
c000000000c287c0-c000000000c289f8: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000708562)
Location: drivers/mmc/core/core.c:1203
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffe000708562-ffffffe00070869a: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1203
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81879ee5-ffffffff81879f07: mmc_set_uhs_voltage.cold (STB_LOCAL)
ffffffff81878e80-ffffffff81878fe5: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1203
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818cb385-ffffffff818cb3a7: mmc_set_uhs_voltage.cold (STB_LOCAL)
ffffffff818ca320-ffffffff818ca485: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_set_uhs_voltage(struct mmc_host *host, u32 ocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1203
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_get_cid
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818e7ea5-ffffffff818e7ec7: mmc_set_uhs_voltage.cold (STB_LOCAL)
ffffffff818e6e40-ffffffff818e6fa5: mmc_set_uhs_voltage (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
