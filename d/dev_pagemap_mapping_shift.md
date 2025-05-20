# Function: <code>dev_pagemap_mapping_shift</code>

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
In mm/memory-failure.c (ffffffff8128898f)
Location: mm/memory-failure.c:267
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
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
In mm/memory-failure.c (ffffffff8129d68f)
Location: mm/memory-failure.c:268
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812b89c0)
Location: mm/memory-failure.c:265
Inline: False
Direct callers:
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff812b89c0-ffffffff812b8c07: dev_pagemap_mapping_shift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812ca8a0)
Location: mm/memory-failure.c:264
Inline: False
Direct callers:
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff812ca8a0-ffffffff812caae7: dev_pagemap_mapping_shift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81300690)
Location: mm/memory-failure.c:265
Inline: False
Direct callers:
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff81300690-ffffffff8130092d: dev_pagemap_mapping_shift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff8130c830)
Location: mm/memory-failure.c:289
Inline: False
Direct callers:
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff8130c830-ffffffff8130cacd: dev_pagemap_mapping_shift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff81312f90)
Location: mm/memory-failure.c:293
Inline: False
Direct callers:
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff81312f90-ffffffff81313224: dev_pagemap_mapping_shift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:305
Inline: False
Direct callers:
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff8135fa50-ffffffff8135fce8: dev_pagemap_mapping_shift (STB_LOCAL)
ffffffff81cc30d0-ffffffff81cc30ec: dev_pagemap_mapping_shift.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:300
Inline: False
Direct callers:
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff813da5c0-ffffffff813da934: dev_pagemap_mapping_shift (STB_LOCAL)
ffffffff81e755ea-ffffffff81e75606: dev_pagemap_mapping_shift.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:322
Inline: True
Direct callers:
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff81460920-ffffffff81460b0e: dev_pagemap_mapping_shift.isra.0 (STB_LOCAL)
ffffffff820683a9-ffffffff820683c2: dev_pagemap_mapping_shift.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:380
Inline: True
Direct callers:
  - mm/memory-failure.c:__add_to_kill
```
**Symbols:**

```
ffffffff814950f0-ffffffff814952b3: dev_pagemap_mapping_shift.isra.0 (STB_LOCAL)
ffffffff820e7c77-ffffffff820e7c90: dev_pagemap_mapping_shift.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory-failure.c (0)
Location: mm/memory-failure.c:376
Inline: True
Direct callers:
  - mm/memory-failure.c:__add_to_kill
```
**Symbols:**

```
ffffffff814c4a50-ffffffff814c4c1c: dev_pagemap_mapping_shift.isra.0 (STB_LOCAL)
ffffffff821c49be-ffffffff821c49d7: dev_pagemap_mapping_shift.isra.0.cold (STB_LOCAL)
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
Location: mm/memory-failure.c:264
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
In mm/memory-failure.c (c00000000045e940)
Location: mm/memory-failure.c:264
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
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
long unsigned int dev_pagemap_mapping_shift(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812c2e80)
Location: mm/memory-failure.c:264
Inline: False
Direct callers:
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff812c2e80-ffffffff812c30c7: dev_pagemap_mapping_shift (STB_LOCAL)
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
In mm/memory-failure.c (ffffffff812b3f85)
Location: mm/memory-failure.c:264
Inline: True
Inline callers:
  - mm/memory-failure.c:add_to_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812c0c90)
Location: mm/memory-failure.c:264
Inline: False
Direct callers:
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff812c0c90-ffffffff812c0ed7: dev_pagemap_mapping_shift (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long unsigned int dev_pagemap_mapping_shift(struct page *page, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory-failure.c (ffffffff812d1750)
Location: mm/memory-failure.c:264
Inline: False
Direct callers:
  - mm/memory-failure.c:add_to_kill
```
**Symbols:**

```
ffffffff812d1750-ffffffff812d1997: dev_pagemap_mapping_shift (STB_LOCAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
