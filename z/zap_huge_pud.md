# Function: <code>zap_huge_pud</code>

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
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81234610)
Location: mm/huge_memory.c:1864
Inline: False
```
**Symbols:**

```
ffffffff81234610-ffffffff812346aa: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81252510)
Location: mm/huge_memory.c:1971
Inline: False
```
**Symbols:**

```
ffffffff81252510-ffffffff812525aa: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81276930)
Location: mm/huge_memory.c:1959
Inline: False
```
**Symbols:**

```
ffffffff81276930-ffffffff812769ca: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff8128b840)
Location: mm/huge_memory.c:1979
Inline: False
```
**Symbols:**

```
ffffffff8128b840-ffffffff8128b8d8: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a6450)
Location: mm/huge_memory.c:2037
Inline: False
```
**Symbols:**

```
ffffffff812a6450-ffffffff812a64e8: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812b7920)
Location: mm/huge_memory.c:2042
Inline: False
```
**Symbols:**

```
ffffffff812b7920-ffffffff812b79b8: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812ecae0)
Location: mm/huge_memory.c:1915
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff812ecae0-ffffffff812ecb84: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812f7b70)
Location: mm/huge_memory.c:1930
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff812f7b70-ffffffff812f7c14: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812fe120)
Location: mm/huge_memory.c:1937
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff812fe120-ffffffff812fe1c5: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81347cc0)
Location: mm/huge_memory.c:1860
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff81347cc0-ffffffff81347d65: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff813be130)
Location: mm/huge_memory.c:1886
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff813be130-ffffffff813be1eb: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81440970)
Location: mm/huge_memory.c:1985
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff81440970-ffffffff81440a28: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff81476230)
Location: mm/huge_memory.c:1974
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff81476230-ffffffff814762eb: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff814a5ae0)
Location: mm/huge_memory.c:2313
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff814a5ae0-ffffffff814a5b9b: zap_huge_pud (STB_GLOBAL)
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
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812aff00)
Location: mm/huge_memory.c:2042
Inline: False
```
**Symbols:**

```
ffffffff812aff00-ffffffff812aff98: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812a13d0)
Location: mm/huge_memory.c:2042
Inline: False
```
**Symbols:**

```
ffffffff812a13d0-ffffffff812a1468: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812add10)
Location: mm/huge_memory.c:2042
Inline: False
```
**Symbols:**

```
ffffffff812add10-ffffffff812adda8: zap_huge_pud (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int zap_huge_pud(struct mmu_gather *tlb, struct vm_area_struct *vma, pud_t *pud, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/huge_memory.c (ffffffff812be070)
Location: mm/huge_memory.c:2042
Inline: False
```
**Symbols:**

```
ffffffff812be070-ffffffff812be106: zap_huge_pud (STB_GLOBAL)
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
