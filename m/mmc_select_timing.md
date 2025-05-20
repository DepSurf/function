# Function: <code>mmc_select_timing</code>

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
In drivers/mmc/core/mmc.c (ffffffff816c38bd)
Location: drivers/mmc/core/mmc.c:1302
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff81726a10)
Location: drivers/mmc/core/mmc.c:1407
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff81759627)
Location: drivers/mmc/core/mmc.c:1440
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff81777fcd)
Location: drivers/mmc/core/mmc.c:1467
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff817ee3de)
Location: drivers/mmc/core/mmc.c:1476
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818374d7)
Location: drivers/mmc/core/mmc.c:1482
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818634a7)
Location: drivers/mmc/core/mmc.c:1499
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_select_timing(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1496
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff818a6000-ffffffff818a6387: mmc_select_timing (STB_LOCAL)
ffffffff818a866f-ffffffff818a87ad: mmc_select_timing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_select_timing(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1496
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff818d8450-ffffffff818d87d7: mmc_select_timing (STB_LOCAL)
ffffffff818daaca-ffffffff818dac08: mmc_select_timing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_select_timing(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1501
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff819ab540-ffffffff819ab5ee: mmc_select_timing (STB_LOCAL)
ffffffff819ad69e-ffffffff819ad6c5: mmc_select_timing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_select_timing(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1508
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff819ae0e0-ffffffff819ae18e: mmc_select_timing (STB_LOCAL)
ffffffff81c2a833-ffffffff81c2a85a: mmc_select_timing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81993bf5)
Location: drivers/mmc/core/mmc.c:1508
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81a3f816)
Location: drivers/mmc/core/mmc.c:1511
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81bacaf4)
Location: drivers/mmc/core/mmc.c:1536
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81d4ff5f)
Location: drivers/mmc/core/mmc.c:1536
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81dba8bf)
Location: drivers/mmc/core/mmc.c:1536
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81e72f54)
Location: drivers/mmc/core/mmc.c:1546
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
int mmc_select_timing(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffff800010b329e0)
Location: drivers/mmc/core/mmc.c:1496
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffff800010b329e0-ffff800010b32e3c: mmc_select_timing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_select_timing(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c0c0d46c)
Location: drivers/mmc/core/mmc.c:1496
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
c0c0d46c-c0c0d8b4: mmc_select_timing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_select_timing(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c000000000c2cc40)
Location: drivers/mmc/core/mmc.c:1496
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
c000000000c2cc40-c000000000c2d1a0: mmc_select_timing (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_select_timing(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffe00070b21a)
Location: drivers/mmc/core/mmc.c:1496
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffe00070b21a-ffffffe00070b5cc: mmc_select_timing (STB_LOCAL)
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
int mmc_select_timing(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1496
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff8187be10-ffffffff8187c197: mmc_select_timing (STB_LOCAL)
ffffffff8187e48a-ffffffff8187e5c8: mmc_select_timing.cold (STB_LOCAL)
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
int mmc_select_timing(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1496
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff818cd2b0-ffffffff818cd637: mmc_select_timing (STB_LOCAL)
ffffffff818cf92a-ffffffff818cfa68: mmc_select_timing.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_select_timing(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1496
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff818e9dd0-ffffffff818ea157: mmc_select_timing (STB_LOCAL)
ffffffff818ec44a-ffffffff818ec588: mmc_select_timing.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
