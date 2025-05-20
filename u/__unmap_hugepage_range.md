# Function: <code>__unmap_hugepage_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811dd780)
Location: mm/hugetlb.c:3156
Inline: False
Direct callers:
  - mm/hugetlb.c:__unmap_hugepage_range_final
  - mm/hugetlb.c:unmap_hugepage_range
```
**Symbols:**

```
ffffffff811dd780-ffffffff811ddaf4: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff811fba60)
Location: mm/hugetlb.c:3183
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff811fba60-ffffffff811fbdc6: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8120c560)
Location: mm/hugetlb.c:3289
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff8120c560-ffffffff8120c87d: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81217ee0)
Location: mm/hugetlb.c:3273
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff81217ee0-ffffffff812181ee: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81232d30)
Location: mm/hugetlb.c:3294
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff81232d30-ffffffff81233068: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81255d60)
Location: mm/hugetlb.c:3324
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff81255d60-ffffffff8125607e: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8126a1b0)
Location: mm/hugetlb.c:3333
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff8126a1b0-ffffffff8126a51a: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:3402
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff81288450-ffffffff81288463: __unmap_hugepage_range.cold (STB_LOCAL)
ffffffff812852e0-ffffffff8128564b: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff81294e80)
Location: mm/hugetlb.c:3519
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff81294e80-ffffffff81295204: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812c8430)
Location: mm/hugetlb.c:3941
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff812c8430-ffffffff812c880d: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812d4000)
Location: mm/hugetlb.c:3911
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff812d4000-ffffffff812d43a7: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff812daee0)
Location: mm/hugetlb.c:4139
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff812daee0-ffffffff812db287: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4429
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff81cbfbc8-ffffffff81cbfc9a: __unmap_hugepage_range.cold (STB_LOCAL)
ffffffff81321f20-ffffffff81322494: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page, zap_flags_t zap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:4993
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff8138f160-ffffffff8138f95a: __unmap_hugepage_range (STB_LOCAL)
ffffffff81e71f45-ffffffff81e72013: __unmap_hugepage_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page, zap_flags_t zap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5235
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff8140f930-ffffffff814100e0: __unmap_hugepage_range (STB_LOCAL)
ffffffff82066b5e-ffffffff82066c3a: __unmap_hugepage_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page, zap_flags_t zap_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5321
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff81442cf0-ffffffff814434a6: __unmap_hugepage_range (STB_LOCAL)
ffffffff820e635a-ffffffff820e6446: __unmap_hugepage_range.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page, zap_flags_t zap_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/hugetlb.c (0)
Location: mm/hugetlb.c:5576
Inline: False
Direct callers:
  - mm/memory.c:unmap_single_vma
  - mm/hugetlb.c:unmap_hugepage_range
```
**Symbols:**

```
ffffffff821c34ea-ffffffff821c35ee: __unmap_hugepage_range.cold (STB_LOCAL)
ffffffff8147cef0-ffffffff8147d6b5: __unmap_hugepage_range (STB_GLOBAL)
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
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffff800010333a58)
Location: mm/hugetlb.c:3519
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffff800010333a58-ffff800010333ecc: __unmap_hugepage_range (STB_GLOBAL)
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
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (c00000000040c3f0)
Location: mm/hugetlb.c:3519
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
c00000000040c3f0-c00000000040cb50: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffe00022fc4a)
Location: mm/hugetlb.c:3519
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffe00022fc4a-ffffffe00023000c: __unmap_hugepage_range (STB_GLOBAL)
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
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128d460)
Location: mm/hugetlb.c:3519
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff8128d460-ffffffff8128d7e4: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8127f210)
Location: mm/hugetlb.c:3519
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff8127f210-ffffffff8127f57b: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8128b270)
Location: mm/hugetlb.c:3519
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff8128b270-ffffffff8128b5f4: __unmap_hugepage_range (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __unmap_hugepage_range(struct mmu_gather *tlb, struct vm_area_struct *vma, long unsigned int start, long unsigned int end, struct page *ref_page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/hugetlb.c (ffffffff8129b090)
Location: mm/hugetlb.c:3519
Inline: False
Direct callers:
  - mm/hugetlb.c:unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range_final
```
**Symbols:**

```
ffffffff8129b090-ffffffff8129b404: __unmap_hugepage_range (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>zap_flags_t zap_flags</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
