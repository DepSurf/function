# Function: <code>mmc_sd_get_cid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff816c6cf0)
Location: drivers/mmc/core/sd.c:694
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff816c6cf0-ffffffff816c6ece: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81729cb0)
Location: drivers/mmc/core/sd.c:723
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81729cb0-ffffffff81729e9e: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8175cdb0)
Location: drivers/mmc/core/sd.c:732
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8175cdb0-ffffffff8175cf9e: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8177b5b0)
Location: drivers/mmc/core/sd.c:724
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8177b5b0-ffffffff8177b74d: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff817f1ff0)
Location: drivers/mmc/core/sd.c:724
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff817f1ff0-ffffffff817f218d: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8183b90a)
Location: drivers/mmc/core/sd.c:718
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8183b130-ffffffff8183b279: mmc_sd_get_cid.part.10 (STB_LOCAL)
ffffffff8183bff2-ffffffff8183c03f: mmc_sd_get_cid.part.10.cold.16 (STB_LOCAL)
ffffffff8183b3d0-ffffffff8183b3e0: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff8186789a)
Location: drivers/mmc/core/sd.c:718
Inline: True
Inline callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818670c0-ffffffff81867209: mmc_sd_get_cid.part.10 (STB_LOCAL)
ffffffff81867f82-ffffffff81867fcf: mmc_sd_get_cid.part.10.cold.16 (STB_LOCAL)
ffffffff81867360-ffffffff81867370: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:738
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818abe8c-ffffffff818abedc: mmc_sd_get_cid.cold (STB_LOCAL)
ffffffff818ab070-ffffffff818ab1c3: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:738
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818de2f3-ffffffff818de343: mmc_sd_get_cid.cold (STB_LOCAL)
ffffffff818dd4c0-ffffffff818dd613: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:762
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819b1182-ffffffff819b11d2: mmc_sd_get_cid.cold (STB_LOCAL)
ffffffff819b05b0-ffffffff819b0703: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:792
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81c2afd2-ffffffff81c2b022: mmc_sd_get_cid.cold (STB_LOCAL)
ffffffff819b2b20-ffffffff819b2c73: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:798
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81c1d34c-ffffffff81c1d39c: mmc_sd_get_cid.cold (STB_LOCAL)
ffffffff81997310-ffffffff81997459: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:808
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d2e395-ffffffff81d2e3e7: mmc_sd_get_cid.cold (STB_LOCAL)
ffffffff81a43a00-ffffffff81a43afc: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:815
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81efa7bf-ffffffff81efa80e: mmc_sd_get_cid.cold (STB_LOCAL)
ffffffff81bb14b0-ffffffff81bb15ad: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81d55440)
Location: drivers/mmc/core/sd.c:815
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d55440-ffffffff81d55595: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81dbfd90)
Location: drivers/mmc/core/sd.c:815
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81dbfd90-ffffffff81dbfee0: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffff81e78550)
Location: drivers/mmc/core/sd.c:815
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81e78550-ffffffff81e786a0: mmc_sd_get_cid (STB_GLOBAL)
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
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffff800010b377a0)
Location: drivers/mmc/core/sd.c:738
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffff800010b377a0-ffff800010b37938: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (c0c12100)
Location: drivers/mmc/core/sd.c:738
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
c0c12100-c0c1228c: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (c000000000c32ff0)
Location: drivers/mmc/core/sd.c:738
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
c000000000c32ff0-c000000000c33270: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/sd.c (ffffffe00070f70c)
Location: drivers/mmc/core/sd.c:738
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffe00070f70c-ffffffe00070f8aa: mmc_sd_get_cid (STB_GLOBAL)
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
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:738
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81881cb3-ffffffff81881d03: mmc_sd_get_cid.cold (STB_LOCAL)
ffffffff81880e80-ffffffff81880fd3: mmc_sd_get_cid (STB_GLOBAL)
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
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:738
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818d3153-ffffffff818d31a3: mmc_sd_get_cid.cold (STB_LOCAL)
ffffffff818d2320-ffffffff818d2473: mmc_sd_get_cid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_sd_get_cid(struct mmc_host *host, u32 ocr, u32 *cid, u32 *rocr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/sd.c (0)
Location: drivers/mmc/core/sd.c:738
Inline: False
Direct callers:
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818efc73-ffffffff818efcc3: mmc_sd_get_cid.cold (STB_LOCAL)
ffffffff818eee40-ffffffff818eef93: mmc_sd_get_cid (STB_GLOBAL)
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
