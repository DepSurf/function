# Function: <code>ptep_clear_flush_young</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81071050)
Location: arch/x86/mm/pgtable.c:479
Inline: False
Direct callers:
  - mm/rmap.c:page_referenced_one
  - mm/rmap.c:try_to_unmap_one
```
**Symbols:**

```
ffffffff81071050-ffffffff81071060: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81070f70)
Location: arch/x86/mm/pgtable.c:479
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff81070f70-ffffffff81070f80: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81074af0)
Location: arch/x86/mm/pgtable.c:479
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff81074af0-ffffffff81074b00: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810740c0)
Location: arch/x86/mm/pgtable.c:520
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff810740c0-ffffffff810740d0: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81079b20)
Location: arch/x86/mm/pgtable.c:517
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff81079b20-ffffffff81079b51: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8107c6e0)
Location: arch/x86/mm/pgtable.c:522
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff8107c6e0-ffffffff8107c710: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810830f0)
Location: arch/x86/mm/pgtable.c:588
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff810830f0-ffffffff81083120: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086d60)
Location: arch/x86/mm/pgtable.c:575
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff81086d60-ffffffff81086d8f: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81087a50)
Location: arch/x86/mm/pgtable.c:571
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff81087a50-ffffffff81087a7f: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81089e90)
Location: arch/x86/mm/pgtable.c:578
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff81089e90-ffffffff81089ebf: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108a110)
Location: arch/x86/mm/pgtable.c:578
Inline: False
Direct callers:
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff8108a110-ffffffff8108a13f: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8108ad70)
Location: arch/x86/mm/pgtable.c:578
Inline: False
Direct callers:
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff8108ad70-ffffffff8108ad9f: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff8109a310)
Location: arch/x86/mm/pgtable.c:578
Inline: False
Direct callers:
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff8109a310-ffffffff8109a33f: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810ad460)
Location: arch/x86/mm/pgtable.c:578
Inline: False
Direct callers:
  - mm/rmap.c:folio_referenced_one
```
**Symbols:**

```
ffffffff810ad460-ffffffff810ad495: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810c7590)
Location: arch/x86/mm/pgtable.c:585
Inline: False
Direct callers:
  - mm/rmap.c:folio_referenced_one
```
**Symbols:**

```
ffffffff810c7590-ffffffff810c75c5: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810cace0)
Location: arch/x86/mm/pgtable.c:585
Inline: False
Direct callers:
  - mm/rmap.c:folio_referenced_one
```
**Symbols:**

```
ffffffff810cace0-ffffffff810cad15: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d3230)
Location: arch/x86/mm/pgtable.c:597
Inline: False
Direct callers:
  - mm/rmap.c:folio_referenced_one
```
**Symbols:**

```
ffffffff810d3230-ffffffff810d3265: ptep_clear_flush_young (STB_GLOBAL)
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
In mm/rmap.c (ffff800010309d28)
Location: arch/arm64/include/asm/pgtable.h:726
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c052552c)
Location: mm/pgtable-generic.c:69
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
c052552c-c0525588: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/pgtable-generic.c (c0000000003d7030)
Location: mm/pgtable-generic.c:69
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
c0000000003d7030-c0000000003d71a4: ptep_clear_flush_young (STB_GLOBAL)
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
In mm/rmap.c (ffffffe000213cfe)
Location: arch/riscv/include/asm/pgtable.h:387
Inline: True
Inline callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086a50)
Location: arch/x86/mm/pgtable.c:571
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff81086a50-ffffffff81086a7f: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810756e0)
Location: arch/x86/mm/pgtable.c:571
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff810756e0-ffffffff8107570f: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81086a00)
Location: arch/x86/mm/pgtable.c:571
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff81086a00-ffffffff81086a2f: ptep_clear_flush_young (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptep_clear_flush_young(struct vm_area_struct *vma, long unsigned int address, pte_t *ptep);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff81088b30)
Location: arch/x86/mm/pgtable.c:571
Inline: False
Direct callers:
  - mm/rmap.c:try_to_unmap_one
  - mm/rmap.c:page_referenced_one
```
**Symbols:**

```
ffffffff81088b30-ffffffff81088b5f: ptep_clear_flush_young (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
