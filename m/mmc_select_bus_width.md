# Function: <code>mmc_select_bus_width</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff816c33c0)
Location: drivers/mmc/core/mmc.c:889
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff816c33c0-ffffffff816c3717: mmc_select_bus_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff817261d0)
Location: drivers/mmc/core/mmc.c:937
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff817261d0-ffffffff8172652c: mmc_select_bus_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81759130)
Location: drivers/mmc/core/mmc.c:958
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81759130-ffffffff8175948c: mmc_select_bus_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff81776950)
Location: drivers/mmc/core/mmc.c:982
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81776950-ffffffff81776cc2: mmc_select_bus_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffff817ecd60)
Location: drivers/mmc/core/mmc.c:984
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff817ecd60-ffffffff817ed0d2: mmc_select_bus_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:986
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81835ee0-ffffffff81836230: mmc_select_bus_width (STB_LOCAL)
ffffffff81838794-ffffffff818387bd: mmc_select_bus_width.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:986
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_init_card
```
**Symbols:**

```
ffffffff81861ef0-ffffffff81862240: mmc_select_bus_width (STB_LOCAL)
ffffffff81864794-ffffffff818647bd: mmc_select_bus_width.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:983
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff818a5cd0-ffffffff818a5ffb: mmc_select_bus_width (STB_LOCAL)
ffffffff818a864e-ffffffff818a866f: mmc_select_bus_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:983
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff818d8110-ffffffff818d844b: mmc_select_bus_width (STB_LOCAL)
ffffffff818daab5-ffffffff818daaca: mmc_select_bus_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:988
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff819ab150-ffffffff819ab21a: mmc_select_bus_width (STB_LOCAL)
ffffffff819ad569-ffffffff819ad595: mmc_select_bus_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:995
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff819adcf0-ffffffff819addba: mmc_select_bus_width (STB_LOCAL)
ffffffff81c2a6fe-ffffffff81c2a72a: mmc_select_bus_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:995
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff819922b0-ffffffff8199237a: mmc_select_bus_width (STB_LOCAL)
ffffffff81c1cadd-ffffffff81c1cb09: mmc_select_bus_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:998
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff81a3dc70-ffffffff81a3dd93: mmc_select_bus_width (STB_LOCAL)
ffffffff81d2d777-ffffffff81d2d7bd: mmc_select_bus_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1005
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff81baaef0-ffffffff81bab01e: mmc_select_bus_width (STB_LOCAL)
ffffffff81ef9bb8-ffffffff81ef9bfe: mmc_select_bus_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1005
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff81d4e0f0-ffffffff81d4e24d: mmc_select_bus_width (STB_LOCAL)
ffffffff820a9809-ffffffff820a9822: mmc_select_bus_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1005
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff81db8a00-ffffffff81db8b5d: mmc_select_bus_width (STB_LOCAL)
ffffffff8212abeb-ffffffff8212ac04: mmc_select_bus_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:1013
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_hs200
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
  - drivers/mmc/core/mmc.c:mmc_select_hs400es
```
**Symbols:**

```
ffffffff81e70e70-ffffffff81e70fcd: mmc_select_bus_width (STB_LOCAL)
ffffffff8220c993-ffffffff8220c9ac: mmc_select_bus_width.cold (STB_LOCAL)
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
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffff800010b32698)
Location: drivers/mmc/core/mmc.c:983
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffff800010b32698-ffff800010b329e0: mmc_select_bus_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c0c0d17c)
Location: drivers/mmc/core/mmc.c:983
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
c0c0d17c-c0c0d46c: mmc_select_bus_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (c000000000c2c8b0)
Location: drivers/mmc/core/mmc.c:983
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
c000000000c2c8b0-c000000000c2cc38: mmc_select_bus_width (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/mmc.c (ffffffe00070af9e)
Location: drivers/mmc/core/mmc.c:983
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffe00070af9e-ffffffe00070b21a: mmc_select_bus_width (STB_LOCAL)
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
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:983
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff8187bad0-ffffffff8187be0b: mmc_select_bus_width (STB_LOCAL)
ffffffff8187e475-ffffffff8187e48a: mmc_select_bus_width.cold (STB_LOCAL)
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
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:983
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff818ccf70-ffffffff818cd2ab: mmc_select_bus_width (STB_LOCAL)
ffffffff818cf915-ffffffff818cf92a: mmc_select_bus_width.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_select_bus_width(struct mmc_card *card);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/mmc.c (0)
Location: drivers/mmc/core/mmc.c:983
Inline: False
Direct callers:
  - drivers/mmc/core/mmc.c:mmc_init_card
  - drivers/mmc/core/mmc.c:mmc_select_timing
  - drivers/mmc/core/mmc.c:mmc_select_timing
```
**Symbols:**

```
ffffffff818e9a90-ffffffff818e9dcb: mmc_select_bus_width (STB_LOCAL)
ffffffff818ec435-ffffffff818ec44a: mmc_select_bus_width.cold (STB_LOCAL)
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
