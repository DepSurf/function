# Function: <code>tlb_flush_mmu_tlbonly</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu_tlbonly(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bbcb0)
Location: mm/memory.c:237
Inline: True
Direct callers:
  - mm/memory.c:tlb_finish_mmu
  - mm/memory.c:unmap_page_range
```
**Symbols:**

```
ffffffff811bbcb0-ffffffff811bbd78: tlb_flush_mmu_tlbonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu_tlbonly(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d64f0)
Location: mm/memory.c:241
Inline: True
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff811d64f0-ffffffff811d65b7: tlb_flush_mmu_tlbonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu_tlbonly(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811e6500)
Location: mm/memory.c:241
Inline: True
Direct callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:tlb_finish_mmu
```
**Symbols:**

```
ffffffff811e6500-ffffffff811e65b7: tlb_flush_mmu_tlbonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu_tlbonly(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f1580)
Location: mm/memory.c:241
Inline: True
Direct callers:
  - mm/memory.c:arch_tlb_finish_mmu
```
**Symbols:**

```
ffffffff811f1580-ffffffff811f1634: tlb_flush_mmu_tlbonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu_tlbonly(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81208250)
Location: mm/memory.c:242
Inline: True
Direct callers:
  - mm/memory.c:arch_tlb_finish_mmu
```
**Symbols:**

```
ffffffff81208250-ffffffff81208328: tlb_flush_mmu_tlbonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu_tlbonly(struct mmu_gather *tlb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81228fb0)
Location: mm/memory.c:241
Inline: True
Direct callers:
  - mm/memory.c:tlb_remove_table
  - mm/memory.c:arch_tlb_finish_mmu
```
**Symbols:**

```
ffffffff81228fb0-ffffffff81229061: tlb_flush_mmu_tlbonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123f7d6)
Location: include/asm-generic/tlb.h:168
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8124cf0a)
Location: include/asm-generic/tlb.h:168
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812510d0)
Location: include/asm-generic/tlb.h:395
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8125f1a5)
Location: include/asm-generic/tlb.h:395
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mmu_gather.c:tlb_table_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125f58e)
Location: include/asm-generic/tlb.h:403
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8126d9b5)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mmu_gather.c:tlb_table_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8128f9e4)
Location: include/asm-generic/tlb.h:415
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff8129de42)
Location: include/asm-generic/tlb.h:415
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129a52b)
Location: include/asm-generic/tlb.h:414
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812a91c2)
Location: include/asm-generic/tlb.h:414
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8129f6f9)
Location: include/asm-generic/tlb.h:416
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812ae632)
Location: include/asm-generic/tlb.h:416
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e09e4)
Location: include/asm-generic/tlb.h:416
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812efdd2)
Location: include/asm-generic/tlb.h:416
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/hugetlb.c (ffffffff81322350)
Location: include/asm-generic/tlb.h:416
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81341dcc)
Location: include/asm-generic/tlb.h:416
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff813532e0)
Location: include/asm-generic/tlb.h:416
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81354cce)
Location: include/asm-generic/tlb.h:416
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff81375c2e)
Location: include/asm-generic/tlb.h:416
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8138f78d)
Location: include/asm-generic/tlb.h:416
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813b9cee)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff813cd5a0)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff813cf1ca)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff813f2ea5)
Location: include/asm-generic/tlb.h:448
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140ff24)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813eea01)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff81401f00)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81403b69)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff814268e5)
Location: include/asm-generic/tlb.h:448
Inline: True
```
```
In mm/hugetlb.c (ffffffff814432e0)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8141a4e1)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff8142e550)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff814300e9)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff81460852)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8147d52c)
Location: include/asm-generic/tlb.h:448
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void tlb_flush_mmu_tlbonly(struct mmu_gather *tlb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/memory.c (ffff8000102f6e38)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
Direct callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (ffff800010304c7c)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
Direct callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
```
```
In mm/madvise.c (ffff80001031d948)
Location: include/asm-generic/tlb.h:403
Inline: False
Direct callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffff800010333da4)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
**Symbols:**

```
ffff8000102f40d8-ffff8000102f4338: tlb_flush_mmu_tlbonly.part.0 (STB_LOCAL)
ffff800010304830-ffff800010304a90: tlb_flush_mmu_tlbonly.part.0 (STB_LOCAL)
ffff80001031d948-ffff80001031dbc4: tlb_flush_mmu_tlbonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void tlb_flush_mmu_tlbonly(struct mmu_gather *tlb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519060)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (c0523054)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/madvise.c (c053737c)
Location: include/asm-generic/tlb.h:403
Inline: False
Direct callers:
  - mm/madvise.c:__se_sys_madvise
  - mm/madvise.c:madvise_free_single_vma
```
**Symbols:**

```
c053737c-c0537474: tlb_flush_mmu_tlbonly (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003beef0)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (c0000000003d191c)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe0002077dc)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (ffffffe000210fd6)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/madvise.c (ffffffe000220f3a)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffe00022ff58)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81257bde)
Location: include/asm-generic/tlb.h:403
Inline: True
```
```
In mm/mmu_gather.c (ffffffff81266005)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mmu_gather.c:tlb_table_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124a492)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff81258425)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mmu_gather.c:tlb_table_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125597e)
Location: include/asm-generic/tlb.h:403
Inline: True
```
```
In mm/mmu_gather.c (ffffffff81263da5)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mmu_gather.c:tlb_table_flush
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812653fd)
Location: include/asm-generic/tlb.h:403
Inline: True
```
```
In mm/mmu_gather.c (ffffffff81273765)
Location: include/asm-generic/tlb.h:403
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mmu_gather.c:tlb_table_flush
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
</ul>
<b>Arch</b>
<ul>
</ul>
