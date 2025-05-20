# Function: <code>mmc_init_card</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff816c3720)
Location: drivers/mmc/core/mmc.c:1360
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
```
**Symbols:**

```
ffffffff816c3720-ffffffff816c464f: mmc_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81726870)
Location: drivers/mmc/core/mmc.c:1459
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff81726870-ffffffff8172793e: mmc_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81759490)
Location: drivers/mmc/core/mmc.c:1492
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff81759490-ffffffff8175a75e: mmc_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81777df0)
Location: drivers/mmc/core/mmc.c:1519
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff81777df0-ffffffff81778ff0: mmc_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff817ee200)
Location: drivers/mmc/core/mmc.c:1528
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:mmc_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff817ee200-ffffffff817ef439: mmc_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1534
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff81837300-ffffffff81838277: mmc_init_card (STB_LOCAL)
ffffffff81838872-ffffffff81838bef: mmc_init_card.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1551
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff818632d0-ffffffff81864268: mmc_init_card (STB_LOCAL)
ffffffff81864872-ffffffff81864c15: mmc_init_card.cold.24 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1548
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff818a7470-ffffffff818a80e1: mmc_init_card (STB_LOCAL)
ffffffff818a886d-ffffffff818a8ac2: mmc_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1548
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff818d98d0-ffffffff818da544: mmc_init_card (STB_LOCAL)
ffffffff818dacc8-ffffffff818daf16: mmc_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1553
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff819ac6a0-ffffffff819acfa1: mmc_init_card (STB_LOCAL)
ffffffff819ad7cd-ffffffff819ad97c: mmc_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1560
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff819af270-ffffffff819afb85: mmc_init_card (STB_LOCAL)
ffffffff81c2a963-ffffffff81c2ab0e: mmc_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1560
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff819939e0-ffffffff8199435f: mmc_init_card (STB_LOCAL)
ffffffff81c1cd1e-ffffffff81c1cf11: mmc_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1563
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff81a3f5f0-ffffffff81a40090: mmc_init_card (STB_LOCAL)
ffffffff81d2da1b-ffffffff81d2dd12: mmc_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1598
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff81bac8d0-ffffffff81bad43e: mmc_init_card (STB_LOCAL)
ffffffff81ef9e25-ffffffff81efa127: mmc_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1598
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff81d4fd20-ffffffff81d50a6c: mmc_init_card (STB_LOCAL)
ffffffff820a98b0-ffffffff820a9984: mmc_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1598
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff81dba6e0-ffffffff81dbb424: mmc_init_card (STB_LOCAL)
ffffffff8212ac92-ffffffff8212ad66: mmc_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1608
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff81e72b70-ffffffff81e739f3: mmc_init_card (STB_LOCAL)
ffffffff8220ca4f-ffffffff8220cb23: mmc_init_card.cold (STB_LOCAL)
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
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffff800010b33dc0)
Location: drivers/mmc/core/mmc.c:1548
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffff800010b33dc0-ffff800010b34a04: mmc_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c0c0e884)
Location: drivers/mmc/core/mmc.c:1548
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
c0c0e884-c0c0f548: mmc_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c000000000c2e560)
Location: drivers/mmc/core/mmc.c:1548
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
c000000000c2e560-c000000000c2f490: mmc_init_card (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffe00070c474)
Location: drivers/mmc/core/mmc.c:1548
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffe00070c474-ffffffe00070cfb0: mmc_init_card (STB_LOCAL)
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
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1548
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff8187d290-ffffffff8187df04: mmc_init_card (STB_LOCAL)
ffffffff8187e688-ffffffff8187e8d6: mmc_init_card.cold (STB_LOCAL)
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
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1548
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff818ce730-ffffffff818cf3a4: mmc_init_card (STB_LOCAL)
ffffffff818cfb28-ffffffff818cfd76: mmc_init_card.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_init_card(struct mmc_host *host, u32 ocr, struct mmc_card *oldcard);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1548
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_attach_mmc
  - drivers/mmc/core/mmc.c:_mmc_hw_reset
  - drivers/mmc/core/mmc.c:_mmc_resume
```
**Symbols:**

```
ffffffff818eb250-ffffffff818ebec4: mmc_init_card (STB_LOCAL)
ffffffff818ec648-ffffffff818ec896: mmc_init_card.cold (STB_LOCAL)
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
