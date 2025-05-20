# Function: <code>__split_huge_pud</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812346b0)
Location: mm/huge_memory.c:1905
Inline: False
```
**Symbols:**

```
ffffffff812346b0-ffffffff812347c2: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812525b0)
Location: mm/huge_memory.c:2012
Inline: False
```
**Symbols:**

```
ffffffff812525b0-ffffffff812526ca: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812769d0)
Location: mm/huge_memory.c:2000
Inline: False
```
**Symbols:**

```
ffffffff812769d0-ffffffff81276ad4: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128b8e0)
Location: mm/huge_memory.c:2020
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
```
**Symbols:**

```
ffffffff8128b8e0-ffffffff8128ba16: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a64f0)
Location: mm/huge_memory.c:2076
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff812a64f0-ffffffff812a6649: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b79c0)
Location: mm/huge_memory.c:2081
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff812b79c0-ffffffff812b7b1d: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ecb90)
Location: mm/huge_memory.c:1954
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff812ecb90-ffffffff812ecced: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f7c20)
Location: mm/huge_memory.c:1969
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/huge_memory.c:copy_huge_pud
```
**Symbols:**

```
ffffffff812f7c20-ffffffff812f7d7d: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fe1d0)
Location: mm/huge_memory.c:1976
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/huge_memory.c:copy_huge_pud
```
**Symbols:**

```
ffffffff812fe1d0-ffffffff812fe32d: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81347d70)
Location: mm/huge_memory.c:1899
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
  - mm/huge_memory.c:copy_huge_pud
```
**Symbols:**

```
ffffffff81347d70-ffffffff81347ecd: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813be1f0)
Location: mm/huge_memory.c:1925
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff813be1f0-ffffffff813be369: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81440a40)
Location: mm/huge_memory.c:2019
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff81440a40-ffffffff81440bb9: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81476300)
Location: mm/huge_memory.c:2008
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff81476300-ffffffff8147646e: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a5bb0)
Location: mm/huge_memory.c:2347
Inline: False
Direct callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff814a5bb0-ffffffff814a5cfa: __split_huge_pud (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812affa0)
Location: mm/huge_memory.c:2081
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff812affa0-ffffffff812b00fd: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a1470)
Location: mm/huge_memory.c:2081
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff812a1470-ffffffff812a15b5: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812addb0)
Location: mm/huge_memory.c:2081
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff812addb0-ffffffff812adf0d: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __split_huge_pud(struct vm_area_struct *vma, pud_t *pud, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812be110)
Location: mm/huge_memory.c:2081
Inline: False
Direct callers:
  - mm/pagewalk.c:walk_pgd_range
  - mm/hmm.c:hmm_vma_walk_pud
```
**Symbols:**

```
ffffffff812be110-ffffffff812be267: __split_huge_pud (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
