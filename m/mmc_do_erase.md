# Function: <code>mmc_do_erase</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff816bf500)
Location: drivers/mmc/core/core.c:2052
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff816bf500-ffffffff816bf862: mmc_do_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81721f00)
Location: drivers/mmc/core/core.c:2066
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff81721f00-ffffffff8172229a: mmc_do_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81754ec0)
Location: drivers/mmc/core/core.c:2129
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff81754ec0-ffffffff8175525a: mmc_do_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff81772a20)
Location: drivers/mmc/core/core.c:1954
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff81772a20-ffffffff81772db6: mmc_do_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffff817e86c0)
Location: drivers/mmc/core/core.c:2161
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff817e86c0-ffffffff817e8a56: mmc_do_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1965
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff81831990-ffffffff81831ccd: mmc_do_erase (STB_LOCAL)
ffffffff818342f1-ffffffff8183439b: mmc_do_erase.cold.37 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1968
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff8185d970-ffffffff8185dcad: mmc_do_erase (STB_LOCAL)
ffffffff81860281-ffffffff8186032b: mmc_do_erase.cold.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1656
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff818a15c0-ffffffff818a1909: mmc_do_erase (STB_LOCAL)
ffffffff818a3ec3-ffffffff818a3f6d: mmc_do_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1655
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff818d38b0-ffffffff818d3c02: mmc_do_erase (STB_LOCAL)
ffffffff818d63ce-ffffffff818d6478: mmc_do_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1638
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff819a6000-ffffffff819a62a8: mmc_do_erase (STB_LOCAL)
ffffffff819a8d22-ffffffff819a8d7f: mmc_do_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1638
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff819a8db0-ffffffff819a9058: mmc_do_erase (STB_LOCAL)
ffffffff81c2a153-ffffffff81c2a1b0: mmc_do_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1583
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff8198da80-ffffffff8198dd26: mmc_do_erase (STB_LOCAL)
ffffffff81c1c56f-ffffffff81c1c5cc: mmc_do_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1584
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff81a39130-ffffffff81a393b5: mmc_do_erase (STB_LOCAL)
ffffffff81d2cf6b-ffffffff81d2d023: mmc_do_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1584
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff81ba61f0-ffffffff81ba6498: mmc_do_erase (STB_LOCAL)
ffffffff81ef932f-ffffffff81ef93e7: mmc_do_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1596
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff81d486c0-ffffffff81d489c4: mmc_do_erase (STB_LOCAL)
ffffffff820a9502-ffffffff820a955d: mmc_do_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1596
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff81db2fc0-ffffffff81db32c4: mmc_do_erase (STB_LOCAL)
ffffffff8212a901-ffffffff8212a95c: mmc_do_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1601
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff81e6b390-ffffffff81e6b694: mmc_do_erase (STB_LOCAL)
ffffffff8220c6a9-ffffffff8220c704: mmc_do_erase.cold (STB_LOCAL)
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
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffff800010b2ce40)
Location: drivers/mmc/core/core.c:1655
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffff800010b2ce40-ffff800010b2d220: mmc_do_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c0c08184)
Location: drivers/mmc/core/core.c:1655
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
c0c08184-c0c08550: mmc_do_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (c000000000c25cd0)
Location: drivers/mmc/core/core.c:1655
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
c000000000c25cd0-c000000000c261e4: mmc_do_erase (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/mmc/core/core.c (ffffffe000706e3c)
Location: drivers/mmc/core/core.c:1655
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffe000706e3c-ffffffe0007071f8: mmc_do_erase (STB_LOCAL)
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
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1655
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff81877270-ffffffff818775c2: mmc_do_erase (STB_LOCAL)
ffffffff81879d8e-ffffffff81879e38: mmc_do_erase.cold (STB_LOCAL)
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
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1655
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff818c8710-ffffffff818c8a62: mmc_do_erase (STB_LOCAL)
ffffffff818cb22e-ffffffff818cb2d8: mmc_do_erase.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int mmc_do_erase(struct mmc_card *card, unsigned int from, unsigned int to, unsigned int arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/mmc/core/core.c (0)
Location: drivers/mmc/core/core.c:1655
Inline: False
Direct callers:
  - drivers/mmc/core/core.c:mmc_erase
  - drivers/mmc/core/core.c:mmc_erase
```
**Symbols:**

```
ffffffff818e5230-ffffffff818e5582: mmc_do_erase (STB_LOCAL)
ffffffff818e7d4e-ffffffff818e7df8: mmc_do_erase.cold (STB_LOCAL)
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
