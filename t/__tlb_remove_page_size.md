# Function: <code>__tlb_remove_page_size</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffffffff811d9273)
Location: mm/memory.c:298
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
Direct callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff811d6460-ffffffff811d64e1: __tlb_remove_page_size.part.59 (STB_LOCAL)
ffffffff811d78b0-ffffffff811d78db: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e82b7)
Location: mm/memory.c:298
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
Direct callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff811e75b0-ffffffff811e75e5: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f26f0)
Location: mm/memory.c:302
Inline: True
Direct callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff811f26f0-ffffffff811f2725: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812096b0)
Location: mm/memory.c:303
Inline: True
Direct callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff812096b0-ffffffff812096e8: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a550)
Location: mm/memory.c:302
Inline: True
Direct callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8122a550-ffffffff8122a588: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8124cad0)
Location: mm/mmu_gather.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8124cad0-ffffffff8124cb64: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8125ef80)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8125ef80-ffffffff8125f00a: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8126d790)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8126d790-ffffffff8126d81a: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8129d850)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8129d850-ffffffff8129d8da: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812a8bd0)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff812a8bd0-ffffffff812a8c5a: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812ae080)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff812ae080-ffffffff812ae10a: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812ef820)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff812ef820-ffffffff812ef8aa: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81352d10)
Location: mm/mmu_gather.c:79
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81352d10-ffffffff81352dad: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct encoded_page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff813ccf40)
Location: mm/mmu_gather.c:118
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff813ccf40-ffffffff813ccfe6: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct encoded_page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff814018a0)
Location: mm/mmu_gather.c:118
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff814018a0-ffffffff81401946: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct encoded_page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8142df60)
Location: mm/mmu_gather.c:119
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:native_tlb_remove_table
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8142df60-ffffffff8142e006: __tlb_remove_page_size (STB_GLOBAL)
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
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffff800010304ae8)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffff800010304ae8-ffff800010304ba8: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (c0522d94)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
c0522d94-c0522e4c: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (c0000000003d1550)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
c0000000003d1550-c0000000003d1650: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffe000210dde)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:free_pgd_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffe000210dde-ffffffe000210e76: __tlb_remove_page_size (STB_GLOBAL)
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
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81265de0)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81265de0-ffffffff81265e6a: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81258200)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81258200-ffffffff8125828a: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81263b80)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81263b80-ffffffff81263c0a: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool __tlb_remove_page_size(struct mmu_gather *tlb, struct page *page, int page_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81273540)
Location: mm/mmu_gather.c:66
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81273540-ffffffff812735ca: __tlb_remove_page_size (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct page *page</code> ➡️ <code>struct encoded_page *page</code>
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
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
