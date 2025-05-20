# Function: <code>tlb_flush_mmu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bca80)
Location: mm/memory.c:261
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
Direct callers:
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff811bca80-ffffffff811bca9d: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d786f)
Location: mm/memory.c:265
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
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
ffffffff811d7840-ffffffff811d785d: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e756f)
Location: mm/memory.c:265
Inline: True
Inline callers:
  - mm/memory.c:tlb_finish_mmu
Direct callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff811e7540-ffffffff811e755d: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f26a7)
Location: mm/memory.c:265
Inline: True
Inline callers:
  - mm/memory.c:arch_tlb_finish_mmu
Direct callers:
  - arch/x86/mm/pgtable.c:___pud_free_tlb
  - arch/x86/mm/pgtable.c:___pmd_free_tlb
  - arch/x86/mm/pgtable.c:___pte_free_tlb
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff811f2650-ffffffff811f266d: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81209667)
Location: mm/memory.c:266
Inline: True
Inline callers:
  - mm/memory.c:arch_tlb_finish_mmu
Direct callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81209610-ffffffff8120962d: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a507)
Location: mm/memory.c:265
Inline: True
Inline callers:
  - mm/memory.c:arch_tlb_finish_mmu
Direct callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8122a4b0-ffffffff8122a4cd: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8124ccf0)
Location: mm/mmu_gather.c:80
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/mmu_gather.c:arch_tlb_finish_mmu
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8124ccf0-ffffffff8124cdeb: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8125f1a0)
Location: mm/mmu_gather.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8125f1a0-ffffffff8125f2d7: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8126d9b0)
Location: mm/mmu_gather.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8126d9b0-ffffffff8126dae7: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8129de42)
Location: mm/mmu_gather.c:246
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8129dbb0-ffffffff8129dd2f: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812a91c2)
Location: mm/mmu_gather.c:246
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff812a8f30-ffffffff812a90af: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812ae632)
Location: mm/mmu_gather.c:246
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff812ae3a0-ffffffff812ae4fe: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff812efdd2)
Location: mm/mmu_gather.c:246
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff812efb40-ffffffff812efc9e: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff813532e0)
Location: mm/mmu_gather.c:259
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81353060-ffffffff8135318c: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff813cd5a0)
Location: mm/mmu_gather.c:296
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff813cd300-ffffffff813cd429: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81401f00)
Location: mm/mmu_gather.c:296
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81401c60-ffffffff81401d89: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff8142e550)
Location: mm/mmu_gather.c:297
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
Direct callers:
  - arch/x86/kernel/paravirt.c:native_tlb_remove_table
  - mm/memory.c:zap_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff8142e2d0-ffffffff8142e3dd: tlb_flush_mmu (STB_GLOBAL)
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
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffff800010304c60)
Location: mm/mmu_gather.c:188
Inline: False
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffff800010304c60-ffff800010304cd4: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (c0523054)
Location: mm/mmu_gather.c:188
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:free_pgd_range
```
**Symbols:**

```
c0522e4c-c0522f54: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (c0000000003d18f0)
Location: mm/mmu_gather.c:188
Inline: False
Direct callers:
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:free_pgd_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/madvise.c:madvise_free_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/madvise.c:madvise_cold_or_pageout_pte_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:zap_huge_pmd
  - mm/huge_memory.c:madvise_free_huge_pmd
```
**Symbols:**

```
c0000000003d18f0-c0000000003d1b34: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffe000210fd6)
Location: mm/mmu_gather.c:188
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:free_pgd_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffffffe000210e76-ffffffe000210efe: tlb_flush_mmu (STB_GLOBAL)
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
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81266000)
Location: mm/mmu_gather.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81266000-ffffffff81266137: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81258420)
Location: mm/mmu_gather.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/memory.c:zap_pte_range
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81258420-ffffffff81258557: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81263da0)
Location: mm/mmu_gather.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81263da0-ffffffff81263ed7: tlb_flush_mmu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tlb_flush_mmu(struct mmu_gather *tlb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mmu_gather.c (ffffffff81273760)
Location: mm/mmu_gather.c:188
Inline: False
Direct callers:
  - arch/x86/kernel/paravirt.c:tlb_remove_page
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/huge_memory.c:zap_huge_pmd
```
**Symbols:**

```
ffffffff81273760-ffffffff81273897: tlb_flush_mmu (STB_GLOBAL)
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
