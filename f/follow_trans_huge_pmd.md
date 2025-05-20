# Function: <code>follow_trans_huge_pmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff811f60d0)
Location: mm/huge_memory.c:1272
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff811f60d0-ffffffff811f6357: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81214e70)
Location: mm/huge_memory.c:1059
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
ffffffff81214e70-ffffffff81215115: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81227480)
Location: mm/huge_memory.c:1147
Inline: False
Direct callers:
  - mm/gup.c:follow_page_mask
```
**Symbols:**

```
ffffffff81227480-ffffffff8122772a: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81233690)
Location: mm/huge_memory.c:1350
Inline: False
```
**Symbols:**

```
ffffffff81233690-ffffffff81233909: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81250f40)
Location: mm/huge_memory.c:1393
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81250f40-ffffffff81251211: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81275410)
Location: mm/huge_memory.c:1391
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff81275410-ffffffff812756e5: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128a370)
Location: mm/huge_memory.c:1403
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8128a370-ffffffff8128a649: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a4f90)
Location: mm/huge_memory.c:1461
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812a4f90-ffffffff812a5269: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b6450)
Location: mm/huge_memory.c:1466
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812b6450-ffffffff812b6729: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812eb570)
Location: mm/huge_memory.c:1323
Inline: False
```
**Symbols:**

```
ffffffff812eb570-ffffffff812eb854: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f6630)
Location: mm/huge_memory.c:1344
Inline: False
```
**Symbols:**

```
ffffffff812f6630-ffffffff812f690e: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fc9e0)
Location: mm/huge_memory.c:1350
Inline: False
```
**Symbols:**

```
ffffffff812fc9e0-ffffffff812fccbb: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81346860)
Location: mm/huge_memory.c:1353
Inline: False
```
**Symbols:**

```
ffffffff81346860-ffffffff81346b3b: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813bcaa0)
Location: mm/huge_memory.c:1385
Inline: False
```
**Symbols:**

```
ffffffff813bcaa0-ffffffff813bce53: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8143f0a0)
Location: mm/huge_memory.c:1463
Inline: False
```
**Symbols:**

```
ffffffff8143f0a0-ffffffff8143f4c8: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81474860)
Location: mm/huge_memory.c:1448
Inline: False
```
**Symbols:**

```
ffffffff81474860-ffffffff81474d05: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a3eb0)
Location: mm/huge_memory.c:1666
Inline: False
```
**Symbols:**

```
ffffffff814a3eb0-ffffffff814a42b4: follow_trans_huge_pmd (STB_GLOBAL)
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
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffff8000103571a8)
Location: mm/huge_memory.c:1466
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffff8000103571a8-ffff8000103573ec: follow_trans_huge_pmd (STB_GLOBAL)
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
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (c00000000043f0d0)
Location: mm/huge_memory.c:1466
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
c00000000043f0d0-c00000000043f440: follow_trans_huge_pmd (STB_GLOBAL)
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
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812aea30)
Location: mm/huge_memory.c:1466
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812aea30-ffffffff812aed09: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8129ff70)
Location: mm/huge_memory.c:1466
Inline: False
Direct callers:
  - mm/gup.c:follow_pmd_mask
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff8129ff70-ffffffff812a0225: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ac840)
Location: mm/huge_memory.c:1466
Inline: False
Direct callers:
  - fs/proc/task_mmu.c:smaps_pte_range
```
**Symbols:**

```
ffffffff812ac840-ffffffff812acb19: follow_trans_huge_pmd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct page *follow_trans_huge_pmd(struct vm_area_struct *vma, long unsigned int addr, pmd_t *pmd, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812bcbc0)
Location: mm/huge_memory.c:1466
Inline: False
```
**Symbols:**

```
ffffffff812bcbc0-ffffffff812bce99: follow_trans_huge_pmd (STB_GLOBAL)
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
