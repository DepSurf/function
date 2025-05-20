# Function: <code>mmc_sd_init_card</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff816c7550)
Location: drivers/mmc/core/sd.c:892
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_reset
  - drivers/mmc/core/sd.c:_mmc_sd_resume
  - drivers/mmc/core/sd.c:mmc_attach_sd
```
**Symbols:**

```
ffffffff816c7550-ffffffff816c7cb7: mmc_sd_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8172a580)
Location: drivers/mmc/core/sd.c:921
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff8172a580-ffffffff8172ad11: mmc_sd_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8175d690)
Location: drivers/mmc/core/sd.c:930
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff8175d690-ffffffff8175de0f: mmc_sd_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8177bdf0)
Location: drivers/mmc/core/sd.c:917
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff8177bdf0-ffffffff8177c54f: mmc_sd_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff817f2720)
Location: drivers/mmc/core/sd.c:929
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff817f2720-ffffffff817f2ac3: mmc_sd_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:923
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff8183b8b0-ffffffff8183bca7: mmc_sd_init_card (STB_LOCAL)
ffffffff8183c138-ffffffff8183c15e: mmc_sd_init_card.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:923
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff81867840-ffffffff81867c32: mmc_sd_init_card (STB_LOCAL)
ffffffff818680c8-ffffffff818680ee: mmc_sd_init_card.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:943
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff818ab6f0-ffffffff818abb1e: mmc_sd_init_card (STB_LOCAL)
ffffffff818abff5-ffffffff818ac02e: mmc_sd_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:943
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff818ddb40-ffffffff818ddf75: mmc_sd_init_card (STB_LOCAL)
ffffffff818de45c-ffffffff818de482: mmc_sd_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:967
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff819b08e0-ffffffff819b0d68: mmc_sd_init_card (STB_LOCAL)
ffffffff819b1244-ffffffff819b1298: mmc_sd_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:997
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff819b2e50-ffffffff819b32d8: mmc_sd_init_card (STB_LOCAL)
ffffffff81c2b094-ffffffff81c2b0e8: mmc_sd_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1005
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff81997630-ffffffff81997ab8: mmc_sd_init_card (STB_LOCAL)
ffffffff81c1d40e-ffffffff81c1d462: mmc_sd_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1389
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff81a43ce0-ffffffff81a44275: mmc_sd_init_card (STB_LOCAL)
ffffffff81d2e46e-ffffffff81d2e502: mmc_sd_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1396
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff81bb17a0-ffffffff81bb1d2d: mmc_sd_init_card (STB_LOCAL)
ffffffff81efa88b-ffffffff81efa927: mmc_sd_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1403
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff81d55970-ffffffff81d55f20: mmc_sd_init_card (STB_LOCAL)
ffffffff820a9a92-ffffffff820a9aa7: mmc_sd_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1403
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff81dc02e0-ffffffff81dc088e: mmc_sd_init_card (STB_LOCAL)
ffffffff8212ae7a-ffffffff8212ae8f: mmc_sd_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:1403
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff81e78ad0-ffffffff81e7911a: mmc_sd_init_card (STB_LOCAL)
ffffffff8220cc37-ffffffff8220cc4c: mmc_sd_init_card.cold (STB_LOCAL)
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
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffff800010b37ed0)
Location: drivers/mmc/core/sd.c:943
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffff800010b37ed0-ffff800010b382b8: mmc_sd_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (c0c1280c)
Location: drivers/mmc/core/sd.c:943
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
c0c1280c-c0c12c58: mmc_sd_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (c000000000c339f0)
Location: drivers/mmc/core/sd.c:943
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
c000000000c339f0-c000000000c33f80: mmc_sd_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffe00070fe00)
Location: drivers/mmc/core/sd.c:943
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffe00070fe00-ffffffe00071018a: mmc_sd_init_card (STB_LOCAL)
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
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:943
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff81881500-ffffffff81881935: mmc_sd_init_card (STB_LOCAL)
ffffffff81881e1c-ffffffff81881e42: mmc_sd_init_card.cold (STB_LOCAL)
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
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:943
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff818d29a0-ffffffff818d2dd5: mmc_sd_init_card (STB_LOCAL)
ffffffff818d32bc-ffffffff818d32e2: mmc_sd_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_sd_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:943
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sd.c:mmc_sd_hw_reset
  - drivers/mmc/core/sd.c:mmc_sd_runtime_resume
```
**Symbols:**

```
ffffffff818ef4c0-ffffffff818ef8f5: mmc_sd_init_card (STB_LOCAL)
ffffffff818efddc-ffffffff818efe02: mmc_sd_init_card.cold (STB_LOCAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
