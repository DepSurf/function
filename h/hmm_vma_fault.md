# Function: <code>hmm_vma_fault</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int hmm_vma_fault(struct vm_area_struct *vma, struct hmm_range *range, long unsigned int start, long unsigned int end, hmm_pfn_t *pfns, bool write, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8126d360)
Location: mm/hmm.c:663
Inline: False
```
**Symbols:**

```
ffffffff8126d360-ffffffff8126d5d5: hmm_vma_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hmm_vma_fault(struct hmm_range *range, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff81293880)
Location: mm/hmm.c:828
Inline: False
```
**Symbols:**

```
ffffffff81293880-ffffffff81293b26: hmm_vma_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hmm_vma_fault(struct hmm_range *range, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff812a8550)
Location: mm/hmm.c:874
Inline: False
```
**Symbols:**

```
ffffffff812a8550-ffffffff812a87f6: hmm_vma_fault (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff8130ab30)
Location: mm/hmm.c:61
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_handle_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff8130ab30-ffffffff8130abc3: hmm_vma_fault.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff81316a00)
Location: mm/hmm.c:61
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_handle_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff81316a00-ffffffff81316a95: hmm_vma_fault.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hmm_vma_fault(long unsigned int addr, long unsigned int end, unsigned int required_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff8131cc50)
Location: mm/hmm.c:61
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff8131cc50-ffffffff8131cce9: hmm_vma_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hmm_vma_fault(long unsigned int addr, long unsigned int end, unsigned int required_fault, struct mm_walk *walk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hmm.c (ffffffff81369f90)
Location: mm/hmm.c:63
Inline: False
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff81369f90-ffffffff8136a029: hmm_vma_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/hmm.c (ffffffff813e7d80)
Location: mm/hmm.c:63
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff813e7d80-ffffffff813e7e42: hmm_vma_fault.isra.0 (STB_LOCAL)
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
In mm/hmm.c (ffffffff8146fc50)
Location: mm/hmm.c:63
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff8146fc50-ffffffff8146fd12: hmm_vma_fault.isra.0 (STB_LOCAL)
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
In mm/hmm.c (ffffffff814a4430)
Location: mm/hmm.c:63
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_walk_pmd
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff814a4430-ffffffff814a44f2: hmm_vma_fault.isra.0 (STB_LOCAL)
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
In mm/hmm.c (ffffffff814d5270)
Location: mm/hmm.c:63
Inline: True
Direct callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
  - mm/hmm.c:hmm_vma_walk_pud
  - mm/hmm.c:hmm_vma_handle_pte
  - mm/hmm.c:hmm_vma_handle_pmd
  - mm/hmm.c:hmm_vma_walk_hole
```
**Symbols:**

```
ffffffff814d5270-ffffffff814d5332: hmm_vma_fault.isra.0 (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct vm_area_struct *vma</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int start</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
<li>
<b>Param removed. </b>
<code>hmm_pfn_t *pfns</code>
</li>
<li>
<b>Param removed. </b>
<code>bool write</code>
</li>
<li>
<b>Param reordered. </b>
<code>vma, range, start, end, pfns, write, block</code> ➡️ <code>range, block</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
