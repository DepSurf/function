# Function: <code>__collapse_huge_page_isolate</code>

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
In mm/huge_memory.c (ffffffff811f5165)
Location: mm/huge_memory.c:2197
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
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
In mm/khugepaged.c (ffffffff8121a0d4)
Location: mm/khugepaged.c:497
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff8122e47b)
Location: mm/khugepaged.c:499
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff81238282)
Location: mm/khugepaged.c:500
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff81258d2b)
Location: mm/khugepaged.c:501
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
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
In mm/khugepaged.c (ffffffff8127c145)
Location: mm/khugepaged.c:501
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
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
In mm/khugepaged.c (ffffffff812907c8)
Location: mm/khugepaged.c:520
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a9f20)
Location: mm/khugepaged.c:520
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812a9f20-ffffffff812aa488: __collapse_huge_page_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812bb490)
Location: mm/khugepaged.c:532
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812bb490-ffffffff812bb9f8: __collapse_huge_page_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812f0770)
Location: mm/khugepaged.c:584
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812f0770-ffffffff812f0ce0: __collapse_huge_page_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812fbef0)
Location: mm/khugepaged.c:599
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812fbef0-ffffffff812fc3dd: __collapse_huge_page_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff81302e20)
Location: mm/khugepaged.c:597
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff81302e20-ffffffff8130345f: __collapse_huge_page_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff8134cb90)
Location: mm/khugepaged.c:601
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8134cb90-ffffffff8134d1c9: __collapse_huge_page_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff813c4290)
Location: mm/khugepaged.c:592
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff813c4290-ffffffff813c4a07: __collapse_huge_page_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte, struct collapse_control *cc, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:533
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff814481d0-ffffffff81448a26: __collapse_huge_page_isolate (STB_LOCAL)
ffffffff82067d4f-ffffffff82067db5: __collapse_huge_page_isolate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte, struct collapse_control *cc, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:545
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff8147db90-ffffffff8147e27b: __collapse_huge_page_isolate (STB_LOCAL)
ffffffff820e7676-ffffffff820e76d6: __collapse_huge_page_isolate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte, struct collapse_control *cc, struct list_head *compound_pagelist);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/khugepaged.c (0)
Location: mm/khugepaged.c:535
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff814ace60-ffffffff814ad434: __collapse_huge_page_isolate (STB_LOCAL)
ffffffff821c4332-ffffffff821c4392: __collapse_huge_page_isolate.cold (STB_LOCAL)
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
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffff80001035c800)
Location: mm/khugepaged.c:532
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffff80001035c800-ffff80001035ccc4: __collapse_huge_page_isolate (STB_LOCAL)
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
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (c000000000446730)
Location: mm/khugepaged.c:532
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
c000000000446730-c000000000446e90: __collapse_huge_page_isolate (STB_LOCAL)
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
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b3a70)
Location: mm/khugepaged.c:532
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812b3a70-ffffffff812b3fd8: __collapse_huge_page_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812a4910)
Location: mm/khugepaged.c:532
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812a4910-ffffffff812a4de5: __collapse_huge_page_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812b1880)
Location: mm/khugepaged.c:532
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812b1880-ffffffff812b1de8: __collapse_huge_page_isolate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __collapse_huge_page_isolate(struct vm_area_struct *vma, long unsigned int address, pte_t *pte);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/khugepaged.c (ffffffff812c1c20)
Location: mm/khugepaged.c:532
Inline: False
Direct callers:
  - mm/khugepaged.c:collapse_huge_page
```
**Symbols:**

```
ffffffff812c1c20-ffffffff812c21ac: __collapse_huge_page_isolate (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct list_head *compound_pagelist</code>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct collapse_control *cc</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, address, pte, compound_pagelist</code> ➡️ <code>vma, address, pte, cc, compound_pagelist</code>
</li>
</ul>
</details>
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
