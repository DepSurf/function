# Function: <code>pgmap_pfn_valid</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool pgmap_pfn_valid(struct dev_pagemap *pgmap, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81316860)
Location: mm/memremap.c:83
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff81316860-ffffffff813168d0: pgmap_pfn_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool pgmap_pfn_valid(struct dev_pagemap *pgmap, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8131cab0)
Location: mm/memremap.c:83
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff8131cab0-ffffffff8131cb19: pgmap_pfn_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool pgmap_pfn_valid(struct dev_pagemap *pgmap, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff81369e00)
Location: mm/memremap.c:83
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff81369e00-ffffffff81369e69: pgmap_pfn_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool pgmap_pfn_valid(struct dev_pagemap *pgmap, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff813e7b10)
Location: mm/memremap.c:82
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff813e7b10-ffffffff813e7b9d: pgmap_pfn_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool pgmap_pfn_valid(struct dev_pagemap *pgmap, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff8146f910)
Location: mm/memremap.c:82
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff8146f910-ffffffff8146f99d: pgmap_pfn_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool pgmap_pfn_valid(struct dev_pagemap *pgmap, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814a40f0)
Location: mm/memremap.c:82
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff814a40f0-ffffffff814a417d: pgmap_pfn_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool pgmap_pfn_valid(struct dev_pagemap *pgmap, long unsigned int pfn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memremap.c (ffffffff814d4fa0)
Location: mm/memremap.c:83
Inline: False
Direct callers:
  - mm/memory-failure.c:memory_failure_dev_pagemap
```
**Symbols:**

```
ffffffff814d4fa0-ffffffff814d502d: pgmap_pfn_valid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
