# Function: <code>mmc_execute_tuning</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bfd70)
Location: drivers/mmc/core/core.c:1071
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff816bfd70-ffffffff816bfde0: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81722a80)
Location: drivers/mmc/core/core.c:1072
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81722a80-ffffffff81722af5: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81755850)
Location: drivers/mmc/core/core.c:1144
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81755850-ffffffff817558c5: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81773970)
Location: drivers/mmc/core/core.c:976
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sd.c:mmc_sd_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81773970-ffffffff817739db: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e9a50)
Location: drivers/mmc/core/core.c:1164
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff817e9a50-ffffffff817e9aea: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:963
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818343e1-ffffffff81834404: mmc_execute_tuning.cold.40 (STB_LOCAL)
ffffffff81832990-ffffffff81832a1a: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:966
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81860371-ffffffff81860394: mmc_execute_tuning.cold.42 (STB_LOCAL)
ffffffff8185eb90-ffffffff8185ec1a: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:937
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818a3fd0-ffffffff818a3ff5: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff818a25f0-ffffffff818a2683: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:937
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818d64be-ffffffff818d64e3: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff818d48f0-ffffffff818d4983: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:920
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff819a8dc5-ffffffff819a8dea: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff819a6f50-ffffffff819a6fe3: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:920
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81c2a1f6-ffffffff81c2a21b: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff819aa1a0-ffffffff819aa233: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:921
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81c1c5cc-ffffffff81c1c5f1: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff8198ea30-ffffffff8198ead8: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:921
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81d2d074-ffffffff81d2d0ae: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff81a3a0e0-ffffffff81a3a1aa: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:921
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81ef9434-ffffffff81ef946c: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff81ba6eb0-ffffffff81ba6f80: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:920
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff820a95aa-ffffffff820a95bf: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff81d49450-ffffffff81d49541: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:920
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8212a9a9-ffffffff8212a9be: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff81db3cd0-ffffffff81db3dc1: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:925
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff8220c751-ffffffff8220c766: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff81e6c0a0-ffffffff81e6c191: mmc_execute_tuning (STB_GLOBAL)
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
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2dfc0)
Location: drivers/mmc/core/core.c:937
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffff800010b2dfc0-ffff800010b2e080: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c0950c)
Location: drivers/mmc/core/core.c:937
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
c0c0950c-c0c095b4: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c27480)
Location: drivers/mmc/core/core.c:937
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
c000000000c27480-c000000000c2759c: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000707958)
Location: drivers/mmc/core/core.c:937
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffe000707958-ffffffe0007079ea: mmc_execute_tuning (STB_GLOBAL)
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
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:937
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff81879e7e-ffffffff81879ea3: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff818782b0-ffffffff81878343: mmc_execute_tuning (STB_GLOBAL)
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
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:937
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818cb31e-ffffffff818cb343: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff818c9750-ffffffff818c97e3: mmc_execute_tuning (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_execute_tuning(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:937
Inline: False
Direct callers:
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/host.c:mmc_retune
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/sdio.c:mmc_sdio_init_card
```
**Symbols:**

```
ffffffff818e7e3e-ffffffff818e7e63: mmc_execute_tuning.cold (STB_LOCAL)
ffffffff818e6270-ffffffff818e6303: mmc_execute_tuning (STB_GLOBAL)
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
