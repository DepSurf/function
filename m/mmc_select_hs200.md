# Function: <code>mmc_select_hs200</code>

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
In drivers/mmc/core/mmc.c (ffffffff816c3bc6)
Location: drivers/mmc/core/mmc.c:1243
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
In drivers/mmc/core/mmc.c (ffffffff81726a56)
Location: drivers/mmc/core/mmc.c:1347
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
In drivers/mmc/core/mmc.c (ffffffff817596d0)
Location: drivers/mmc/core/mmc.c:1374
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
In drivers/mmc/core/mmc.c (ffffffff81778594)
Location: drivers/mmc/core/mmc.c:1401
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
In drivers/mmc/core/mmc.c (ffffffff817ee991)
Location: drivers/mmc/core/mmc.c:1410
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
In drivers/mmc/core/mmc.c (ffffffff8183792c)
Location: drivers/mmc/core/mmc.c:1416
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
In drivers/mmc/core/mmc.c (ffffffff81863900)
Location: drivers/mmc/core/mmc.c:1433
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
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
In drivers/mmc/core/mmc.c (ffffffff818a621a)
Location: drivers/mmc/core/mmc.c:1430
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffff818d866a)
Location: drivers/mmc/core/mmc.c:1430
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_select_hs200(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1435
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff819ab400-ffffffff819ab535: mmc_select_hs200 (STB_LOCAL)
ffffffff819ad67f-ffffffff819ad69e: mmc_select_hs200.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_select_hs200(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1442
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff819adfa0-ffffffff819ae0d5: mmc_select_hs200 (STB_LOCAL)
ffffffff81c2a814-ffffffff81c2a833: mmc_select_hs200.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_select_hs200(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1442
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81992560-ffffffff81992698: mmc_select_hs200 (STB_LOCAL)
ffffffff81c1cbf3-ffffffff81c1cc12: mmc_select_hs200.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_select_hs200(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1445
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81a3df80-ffffffff81a3e0b8: mmc_select_hs200 (STB_LOCAL)
ffffffff81d2d8a7-ffffffff81d2d8c6: mmc_select_hs200.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_select_hs200(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1459
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81bab1f0-ffffffff81bab371: mmc_select_hs200 (STB_LOCAL)
ffffffff81ef9cb1-ffffffff81ef9ccf: mmc_select_hs200.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mmc_select_hs200(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81d4e4f0)
Location: drivers/mmc/core/mmc.c:1459
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81d4e4f0-ffffffff81d4e68d: mmc_select_hs200 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mmc_select_hs200(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81db8e00)
Location: drivers/mmc/core/mmc.c:1459
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81db8e00-ffffffff81db8f9d: mmc_select_hs200 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mmc_select_hs200(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81e71270)
Location: drivers/mmc/core/mmc.c:1469
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81e71270-ffffffff81e7140d: mmc_select_hs200 (STB_LOCAL)
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
In drivers/mmc/core/mmc.c (ffff800010b32c20)
Location: drivers/mmc/core/mmc.c:1430
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (c0c0d6ac)
Location: drivers/mmc/core/mmc.c:1430
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (c000000000c2cee0)
Location: drivers/mmc/core/mmc.c:1430
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffe00070b400)
Location: drivers/mmc/core/mmc.c:1430
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffff8187c02a)
Location: drivers/mmc/core/mmc.c:1430
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffff818cd4ca)
Location: drivers/mmc/core/mmc.c:1430
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
In drivers/mmc/core/mmc.c (ffffffff818e9fea)
Location: drivers/mmc/core/mmc.c:1430
Inline: True
Inline callers:
  - drivers/mmc/core/mmc.c:mmc_select_timing
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
