# Function: <code>mmc_regulator_set_ocr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816be050)
Location: drivers/mmc/core/core.c:1368
Inline: False
```
**Symbols:**

```
ffffffff816be050-ffffffff816be104: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8171fc60)
Location: drivers/mmc/core/core.c:1384
Inline: False
```
**Symbols:**

```
ffffffff8171fc60-ffffffff8171fd14: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817524e0)
Location: drivers/mmc/core/core.c:1456
Inline: False
```
**Symbols:**

```
ffffffff817524e0-ffffffff81752594: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81770cf0)
Location: drivers/mmc/core/core.c:1288
Inline: False
```
**Symbols:**

```
ffffffff81770cf0-ffffffff81770dae: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e6a50)
Location: drivers/mmc/core/core.c:1482
Inline: False
```
**Symbols:**

```
ffffffff817e6a50-ffffffff817e6b0e: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8182fda0)
Location: drivers/mmc/core/core.c:1281
Inline: False
```
**Symbols:**

```
ffffffff8182fda0-ffffffff8182fe5e: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff8185c020)
Location: drivers/mmc/core/core.c:1284
Inline: False
```
**Symbols:**

```
ffffffff8185c020-ffffffff8185c0de: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff818b13dd-ffffffff818b13f9: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff818b0ff0-ffffffff818b1090: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff818e387d-ffffffff818e3899: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff818e3490-ffffffff818e3530: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff819b697e-ffffffff819b699a: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff819b6570-ffffffff819b6610: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff81c2b302-ffffffff81c2b31e: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff819b8ab0-ffffffff819b8b50: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff81c1d693-ffffffff81c1d6af: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff8199d1e0-ffffffff8199d280: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff81d2e897-ffffffff81d2e8dd: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff81a49f60-ffffffff81a4a022: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff81efad07-ffffffff81efad4d: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff81bb83b0-ffffffff81bb8480: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff820a9bec-ffffffff820a9c14: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff81d5d0e0-ffffffff81d5d1c8: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff8212afc5-ffffffff8212afef: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff81dc7ca0-ffffffff81dc7da4: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff8220cd82-ffffffff8220cdac: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff81e80600-ffffffff81e80704: mmc_regulator_set_ocr (STB_GLOBAL)
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
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (ffff800010b3dde0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
Direct callers:
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_set_ios
```
**Symbols:**

```
ffff800010b3dde0-ffff800010b3ded0: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (c0c18364)
Location: drivers/mmc/core/regulator.c:106
Inline: False
Direct callers:
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/mmci.c:mmci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_ios
  - drivers/mmc/host/sdhci.c:sdhci_set_power
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_power
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_set_power
  - drivers/mmc/host/omap_hsmmc.c:omap_hsmmc_disable_supply
```
**Symbols:**

```
c0c18364-c0c18450: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (c000000000c3b5d0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
c000000000c3b5d0-c000000000c3b738: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/regulator.c (ffffffe000714dc4)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffe000714dc4-ffffffe000714e9a: mmc_regulator_set_ocr (STB_GLOBAL)
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
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff8188723d-ffffffff81887259: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff81886e50-ffffffff81886ef0: mmc_regulator_set_ocr (STB_GLOBAL)
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
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff818d86dd-ffffffff818d86f9: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff818d82f0-ffffffff818d8390: mmc_regulator_set_ocr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_regulator_set_ocr(struct mmc_host *mmc, struct regulator *supply, short unsigned int vdd_bit);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/regulator.c (0)
Location: drivers/mmc/core/regulator.c:106
Inline: False
```
**Symbols:**

```
ffffffff818f51fd-ffffffff818f5219: mmc_regulator_set_ocr.cold (STB_LOCAL)
ffffffff818f4e10-ffffffff818f4eb0: mmc_regulator_set_ocr (STB_GLOBAL)
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
