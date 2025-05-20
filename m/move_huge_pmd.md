# Function: <code>move_huge_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int move_huge_pmd(struct vm_area_struct *vma, struct vm_area_struct *new_vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f6ae0)
Location: mm/huge_memory.c:1496
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff811f6ae0-ffffffff811f6c7a: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812159d0)
Location: mm/huge_memory.c:1367
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812159d0-ffffffff81215b4a: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd, bool *need_flush);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81227f80)
Location: mm/huge_memory.c:1486
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81227f80-ffffffff81228161: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd, bool *need_flush);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81234170)
Location: mm/huge_memory.c:1698
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81234170-ffffffff81234325: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd, bool *need_flush);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81251d60)
Location: mm/huge_memory.c:1782
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81251d60-ffffffff81252084: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd, bool *need_flush);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812762f0)
Location: mm/huge_memory.c:1780
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812762f0-ffffffff81276588: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128b170)
Location: mm/huge_memory.c:1802
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff8128b170-ffffffff8128b463: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/huge_memory.c (0)
Location: mm/huge_memory.c:1860
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812a8b78-ffffffff812a8b8d: move_huge_pmd.cold (STB_LOCAL)
ffffffff812a5d70-ffffffff812a606f: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b7230)
Location: mm/huge_memory.c:1865
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812b7230-ffffffff812b7531: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ec3d0)
Location: mm/huge_memory.c:1724
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812ec3d0-ffffffff812ec6d1: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f7480)
Location: mm/huge_memory.c:1745
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812f7480-ffffffff812f7765: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fd940)
Location: mm/huge_memory.c:1750
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812fd940-ffffffff812fdc5b: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813474e0)
Location: mm/huge_memory.c:1668
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff813474e0-ffffffff813477fb: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bd7e0)
Location: mm/huge_memory.c:1673
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff813bd7e0-ffffffff813bdaa6: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143fff0)
Location: mm/huge_memory.c:1768
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff8143fff0-ffffffff814402b5: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81475840)
Location: mm/huge_memory.c:1752
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff81475840-ffffffff81475af2: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a5210)
Location: mm/huge_memory.c:1968
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff814a5210-ffffffff814a54c2: move_huge_pmd (STB_GLOBAL)
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
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff800010357ea8)
Location: mm/huge_memory.c:1865
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffff800010357ea8-ffff800010358164: move_huge_pmd (STB_GLOBAL)
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
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c0000000004404f0)
Location: mm/huge_memory.c:1865
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
c0000000004404f0-c0000000004408a0: move_huge_pmd (STB_GLOBAL)
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
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812af810)
Location: mm/huge_memory.c:1865
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812af810-ffffffff812afb11: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a0d30)
Location: mm/huge_memory.c:1865
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812a0d30-ffffffff812a0ff7: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ad620)
Location: mm/huge_memory.c:1865
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812ad620-ffffffff812ad921: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool move_huge_pmd(struct vm_area_struct *vma, long unsigned int old_addr, long unsigned int new_addr, long unsigned int old_end, pmd_t *old_pmd, pmd_t *new_pmd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bd9a0)
Location: mm/huge_memory.c:1865
Inline: False
Direct callers:
  - mm/mremap.c:move_page_tables
  - mm/mremap.c:move_page_tables
```
**Symbols:**

```
ffffffff812bd9a0-ffffffff812bdc9d: move_huge_pmd (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *new_vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, new_vma, old_addr, new_addr, old_end, old_pmd, new_pmd</code> ➡️ <code>vma, old_addr, new_addr, old_end, old_pmd, new_pmd</code>
</li>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool *need_flush</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool *need_flush</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int old_end</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, old_addr, new_addr, old_end, old_pmd, new_pmd</code> ➡️ <code>vma, old_addr, new_addr, old_pmd, new_pmd</code>
</li>
</ul>
</details>
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
