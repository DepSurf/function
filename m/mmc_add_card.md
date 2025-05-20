# Function: <code>mmc_add_card</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff816c1980)
Location: drivers/mmc/core/bus.c:282
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff816c1980-ffffffff816c1ba4: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff817245b0)
Location: drivers/mmc/core/bus.c:282
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff817245b0-ffffffff81724834: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff81757530)
Location: drivers/mmc/core/bus.c:282
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81757530-ffffffff817577b4: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff817753d0)
Location: drivers/mmc/core/bus.c:284
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff817753d0-ffffffff81775650: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffff817eb6b0)
Location: drivers/mmc/core/bus.c:287
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff817eb6b0-ffffffff817eb930: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:287
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81834941-ffffffff81834b4b: mmc_add_card.cold.13 (STB_LOCAL)
ffffffff81834810-ffffffff8183489e: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:287
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818608d1-ffffffff81860b04: mmc_add_card.cold.13 (STB_LOCAL)
ffffffff818607a0-ffffffff8186082e: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:284
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818a45e6-ffffffff818a4847: mmc_add_card.cold (STB_LOCAL)
ffffffff818a44c0-ffffffff818a4531: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:284
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818d6a66-ffffffff818d6cd2: mmc_add_card.cold (STB_LOCAL)
ffffffff818d6940-ffffffff818d69b3: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff819a93c6-ffffffff819a9632: mmc_add_card.cold (STB_LOCAL)
ffffffff819a92a0-ffffffff819a9313: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:310
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81c2a2db-ffffffff81c2a547: mmc_add_card.cold (STB_LOCAL)
ffffffff819ac190-ffffffff819ac203: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:310
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81c1c699-ffffffff81c1c905: mmc_add_card.cold (STB_LOCAL)
ffffffff819905d0-ffffffff81990643: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:308
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81d2d30b-ffffffff81d2d4f6: mmc_add_card.cold (STB_LOCAL)
ffffffff81a3bdf0-ffffffff81a3beff: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff81ef96bf-ffffffff81ef98fe: mmc_add_card.cold (STB_LOCAL)
ffffffff81ba8df0-ffffffff81ba8ed5: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff820a976b-ffffffff820a97aa: mmc_add_card.cold (STB_LOCAL)
ffffffff81d4b7c0-ffffffff81d4bac8: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff8212ab64-ffffffff8212aba3: mmc_add_card.cold (STB_LOCAL)
ffffffff81db6070-ffffffff81db636f: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:298
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff8220c90c-ffffffff8220c94b: mmc_add_card.cold (STB_LOCAL)
ffffffff81e6e4f0-ffffffff81e6e806: mmc_add_card (STB_GLOBAL)
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
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffff800010b30a18)
Location: drivers/mmc/core/bus.c:284
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffff800010b30a18-ffff800010b30cd8: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (c0c0b778)
Location: drivers/mmc/core/bus.c:284
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
c0c0b778-c0c0ba48: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (c000000000c2a4c0)
Location: drivers/mmc/core/bus.c:284
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
c000000000c2a4c0-c000000000c2a7d8: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/bus.c (ffffffe00070950a)
Location: drivers/mmc/core/bus.c:284
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffe00070950a-ffffffe00070978e: mmc_add_card (STB_GLOBAL)
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
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:284
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff8187a426-ffffffff8187a692: mmc_add_card.cold (STB_LOCAL)
ffffffff8187a300-ffffffff8187a373: mmc_add_card (STB_GLOBAL)
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
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:284
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818cb8c6-ffffffff818cbb32: mmc_add_card.cold (STB_LOCAL)
ffffffff818cb7a0-ffffffff818cb813: mmc_add_card (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_add_card(struct mmc_card *card);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/bus.c (0)
Location: drivers/mmc/core/bus.c:284
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/sd.c:mmc_attach_sd
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
  - drivers/mmc/core/sdio.c:mmc_attach_sdio
```
**Symbols:**

```
ffffffff818e83e6-ffffffff818e8652: mmc_add_card.cold (STB_LOCAL)
ffffffff818e82c0-ffffffff818e8333: mmc_add_card (STB_GLOBAL)
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
