# Function: <code>undo_dev_pagemap</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81071380)
Location: arch/x86/mm/gup.c:68
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
**Symbols:**

```
ffffffff81071380-ffffffff81071418: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/gup.c (ffffffff81074f00)
Location: arch/x86/mm/gup.c:68
Inline: False
Direct callers:
  - arch/x86/mm/gup.c:gup_huge_pmd
  - arch/x86/mm/gup.c:gup_pte_range
```
**Symbols:**

```
ffffffff81074f00-ffffffff81074f98: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff811eec80)
Location: mm/gup.c:1268
Inline: False
Direct callers:
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__get_user_pages_fast
  - mm/gup.c:__gup_device_huge
```
**Symbols:**

```
ffffffff811eec80-ffffffff811eece4: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81205160)
Location: mm/gup.c:1357
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
```
**Symbols:**

```
ffffffff81205160-ffffffff812051ee: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812260a0)
Location: mm/gup.c:1361
Inline: False
Direct callers:
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:gup_pgd_range
  - mm/gup.c:__gup_device_huge
```
**Symbols:**

```
ffffffff812260a0-ffffffff81226141: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81239810)
Location: mm/gup.c:1386
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
**Symbols:**

```
ffffffff81239810-ffffffff812398b1: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124a930)
Location: mm/gup.c:1792
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
**Symbols:**

```
ffffffff8124a930-ffffffff8124a9d1: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81258e00)
Location: mm/gup.c:1795
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
**Symbols:**

```
ffffffff81258e00-ffffffff81258ea1: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, unsigned int flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81287b70)
Location: mm/gup.c:2203
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
**Symbols:**

```
ffffffff81287b70-ffffffff81287c28: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, unsigned int flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81291b20)
Location: mm/gup.c:1981
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
**Symbols:**

```
ffffffff81291b20-ffffffff81291bdc: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, unsigned int flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81297410)
Location: mm/gup.c:2047
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
**Symbols:**

```
ffffffff81297410-ffffffff812974cc: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, unsigned int flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff812d7dc0)
Location: mm/gup.c:2135
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
**Symbols:**

```
ffffffff812d7dc0-ffffffff812d7e79: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, unsigned int flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813378e0)
Location: mm/gup.c:2265
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
**Symbols:**

```
ffffffff813378e0-ffffffff81337a77: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, unsigned int flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813aef80)
Location: mm/gup.c:2293
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
**Symbols:**

```
ffffffff813aef80-ffffffff813af117: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, unsigned int flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff813e3560)
Location: mm/gup.c:2514
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
**Symbols:**

```
ffffffff813e3560-ffffffff813e36f1: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, unsigned int flags, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8140dd80)
Location: mm/gup.c:2532
Inline: False
Direct callers:
  - mm/gup.c:gup_huge_pud
  - mm/gup.c:gup_huge_pmd
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:__gup_device_huge
  - mm/gup.c:gup_pte_range
```
**Symbols:**

```
ffffffff8140dd80-ffffffff8140df05: undo_dev_pagemap (STB_LOCAL)
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
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffff8000102f0dd8)
Location: mm/gup.c:1795
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
**Symbols:**

```
ffff8000102f0dd8-ffff8000102f0ea8: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (c0000000003b59e0)
Location: mm/gup.c:1795
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
```
**Symbols:**

```
c0000000003b59e0-c0000000003b5b44: undo_dev_pagemap (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81251450)
Location: mm/gup.c:1795
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
**Symbols:**

```
ffffffff81251450-ffffffff812514f1: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff81244340)
Location: mm/gup.c:1795
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
**Symbols:**

```
ffffffff81244340-ffffffff812443e1: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8124f1f0)
Location: mm/gup.c:1795
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
**Symbols:**

```
ffffffff8124f1f0-ffffffff8124f291: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void undo_dev_pagemap(int *nr, int nr_start, struct page **pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/gup.c (ffffffff8125eb60)
Location: mm/gup.c:1795
Inline: False
Direct callers:
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:gup_pud_range
  - mm/gup.c:__gup_device_huge
```
**Symbols:**

```
ffffffff8125eb60-ffffffff8125ec01: undo_dev_pagemap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>nr, nr_start, pages</code> ➡️ <code>nr, nr_start, flags, pages</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
