# Function: <code>copy_pte_range</code>

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
In mm/memory.c (ffffffff811c0dda)
Location: mm/memory.c:888
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff811dc7c6)
Location: mm/memory.c:924
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff811ec2d6)
Location: mm/memory.c:926
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
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
In mm/memory.c (ffffffff811f71ea)
Location: mm/memory.c:992
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int copy_pte_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, pmd_t *dst_pmd, pmd_t *src_pmd, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8120a2e0)
Location: mm/memory.c:1059
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff8120a2e0-ffffffff8120aa50: copy_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff8122b130)
Location: mm/memory.c:1073
Inline: True
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff8122b130-ffffffff8122b8dc: copy_pte_range.isra.93 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff8123e4f0)
Location: mm/memory.c:816
Inline: True
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff8123e4f0-ffffffff8123eca4: copy_pte_range.isra.84 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff81250340)
Location: mm/memory.c:784
Inline: True
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff81250340-ffffffff81250a51: copy_pte_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff8125e8f0)
Location: mm/memory.c:784
Inline: True
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff8125e8f0-ffffffff8125f001: copy_pte_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int copy_pte_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, pmd_t *dst_pmd, pmd_t *src_pmd, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128f030)
Location: mm/memory.c:812
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff8128f030-ffffffff8128f41b: copy_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int copy_pte_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pmd_t *dst_pmd, pmd_t *src_pmd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81299790)
Location: mm/memory.c:923
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff81299790-ffffffff81299f2a: copy_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int copy_pte_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pmd_t *dst_pmd, pmd_t *src_pmd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129e9c0)
Location: mm/memory.c:929
Inline: False
Direct callers:
  - mm/memory.c:copy_pmd_range
```
**Symbols:**

```
ffffffff8129e9c0-ffffffff8129f141: copy_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int copy_pte_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pmd_t *dst_pmd, pmd_t *src_pmd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812dfc00)
Location: mm/memory.c:1003
Inline: False
Direct callers:
  - mm/memory.c:copy_pmd_range
```
**Symbols:**

```
ffffffff812dfc00-ffffffff812e03ec: copy_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int copy_pte_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pmd_t *dst_pmd, pmd_t *src_pmd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81340430)
Location: mm/memory.c:1010
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff81340430-ffffffff813409f2: copy_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int copy_pte_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pmd_t *dst_pmd, pmd_t *src_pmd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b83d0)
Location: mm/memory.c:967
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff813b83d0-ffffffff813b898f: copy_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int copy_pte_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pmd_t *dst_pmd, pmd_t *src_pmd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813ed1a0)
Location: mm/memory.c:1001
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff813ed1a0-ffffffff813ed606: copy_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int copy_pte_range(struct vm_area_struct *dst_vma, struct vm_area_struct *src_vma, pmd_t *dst_pmd, pmd_t *src_pmd, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81418770)
Location: mm/memory.c:1021
Inline: False
Direct callers:
  - mm/memory.c:copy_p4d_range
```
**Symbols:**

```
ffffffff81418770-ffffffff81418bdd: copy_pte_range (STB_LOCAL)
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
int copy_pte_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, pmd_t *dst_pmd, pmd_t *src_pmd, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f6308)
Location: mm/memory.c:784
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffff8000102f6308-ffff8000102f6964: copy_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int copy_pte_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, pmd_t *dst_pmd, pmd_t *src_pmd, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c05184bc)
Location: mm/memory.c:784
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
c05184bc-c0518a9c: copy_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int copy_pte_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, pmd_t *dst_pmd, pmd_t *src_pmd, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003bdcf0)
Location: mm/memory.c:784
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
c0000000003bdcf0-c0000000003be764: copy_pte_range (STB_LOCAL)
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
In mm/memory.c (ffffffe000209c8e)
Location: mm/memory.c:784
Inline: True
Inline callers:
  - mm/memory.c:copy_page_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff81256f40)
Location: mm/memory.c:784
Inline: True
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff81256f40-ffffffff81257651: copy_pte_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int copy_pte_range(struct mm_struct *dst_mm, struct mm_struct *src_mm, pmd_t *dst_pmd, pmd_t *src_pmd, struct vm_area_struct *vma, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81249880)
Location: mm/memory.c:784
Inline: False
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff81249880-ffffffff81249f38: copy_pte_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff81254ce0)
Location: mm/memory.c:784
Inline: True
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff81254ce0-ffffffff812553f1: copy_pte_range.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff81264760)
Location: mm/memory.c:784
Inline: True
Direct callers:
  - mm/memory.c:copy_page_range
```
**Symbols:**

```
ffffffff81264760-ffffffff81264ea5: copy_pte_range.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *dst_vma</code>
</li>
<li>
<b>Param added. </b>
<code>struct vm_area_struct *src_vma</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *dst_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mm_struct *src_mm</code>
</li>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param reordered. </b>
<code>dst_mm, src_mm, dst_pmd, src_pmd, vma, addr, end</code> ➡️ <code>dst_vma, src_vma, dst_pmd, src_pmd, addr, end</code>
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
</ul>
<b>Flavor</b>
<ul>
</ul>
