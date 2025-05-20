# Function: <code>memory_failure_dev_pagemap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812895e3)
Location: mm/memory-failure.c:1153
Inline: True
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
In mm/memory-failure.c (ffffffff8129e433)
Location: mm/memory-failure.c:1155
Inline: True
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
In mm/memory-failure.c (ffffffff812ba16f)
Location: mm/memory-failure.c:1152
Inline: True
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
In mm/memory-failure.c (ffffffff812cc02b)
Location: mm/memory-failure.c:1156
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int memory_failure_dev_pagemap(long unsigned int pfn, int flags, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81300e70)
Location: mm/memory-failure.c:1179
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81300e70-ffffffff81301053: memory_failure_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int memory_failure_dev_pagemap(long unsigned int pfn, int flags, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8130dc60)
Location: mm/memory-failure.c:1293
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff8130dc60-ffffffff8130dee4: memory_failure_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int memory_failure_dev_pagemap(long unsigned int pfn, int flags, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81313fa0)
Location: mm/memory-failure.c:1359
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81313fa0-ffffffff813141e8: memory_failure_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int memory_failure_dev_pagemap(long unsigned int pfn, int flags, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1499
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81360110-ffffffff81360365: memory_failure_dev_pagemap (STB_LOCAL)
ffffffff81cc3123-ffffffff81cc3159: memory_failure_dev_pagemap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int memory_failure_dev_pagemap(long unsigned int pfn, int flags, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1643
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff813dafa0-ffffffff813db384: memory_failure_dev_pagemap (STB_LOCAL)
ffffffff81e7563d-ffffffff81e75677: memory_failure_dev_pagemap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int memory_failure_dev_pagemap(long unsigned int pfn, int flags, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814613e0)
Location: mm/memory-failure.c:1951
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff814613e0-ffffffff81461775: memory_failure_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int memory_failure_dev_pagemap(long unsigned int pfn, int flags, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81498030)
Location: mm/memory-failure.c:2079
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff81498030-ffffffff814983c3: memory_failure_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int memory_failure_dev_pagemap(long unsigned int pfn, int flags, struct dev_pagemap *pgmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff814c76c0)
Location: mm/memory-failure.c:2132
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure
```
**Symbols:**

```
ffffffff814c76c0-ffffffff814c7998: memory_failure_dev_pagemap (STB_LOCAL)
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
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:1156
Inline: False
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (c000000000461240)
Location: mm/memory-failure.c:1156
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/memory-failure.c (ffffffff812c460b)
Location: mm/memory-failure.c:1156
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812b564b)
Location: mm/memory-failure.c:1156
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812c241b)
Location: mm/memory-failure.c:1156
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
In mm/memory-failure.c (ffffffff812d2ea6)
Location: mm/memory-failure.c:1156
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
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
