# Function: <code>__tlb_reset_range</code>

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
In mm/memory.c (ffffffff811bbcec)
Location: include/asm-generic/tlb.h:137
Inline: True
Inline callers:
  - mm/memory.c:tlb_gather_mmu
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
In mm/memory.c (ffffffff811d77cb)
Location: include/asm-generic/tlb.h:140
Inline: True
Inline callers:
  - mm/memory.c:tlb_gather_mmu
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
In mm/memory.c (ffffffff811e74d8)
Location: include/asm-generic/tlb.h:130
Inline: True
Inline callers:
  - mm/memory.c:tlb_gather_mmu
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
In mm/memory.c (ffffffff811f25e2)
Location: include/asm-generic/tlb.h:131
Inline: True
Inline callers:
  - mm/memory.c:arch_tlb_gather_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812095a9)
Location: include/asm-generic/tlb.h:131
Inline: True
Inline callers:
  - mm/memory.c:arch_tlb_gather_mmu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8122a454)
Location: include/asm-generic/tlb.h:131
Inline: True
Inline callers:
  - mm/memory.c:arch_tlb_gather_mmu
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
In mm/memory.c (ffffffff8123f84f)
Location: include/asm-generic/tlb.h:153
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8124d068)
Location: include/asm-generic/tlb.h:153
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
  - mm/mmu_gather.c:arch_tlb_finish_mmu
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
In mm/memory.c (ffffffff81251142)
Location: include/asm-generic/tlb.h:294
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8125f3bd)
Location: include/asm-generic/tlb.h:294
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/memory.c (ffffffff8125f605)
Location: include/asm-generic/tlb.h:302
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8126dbcd)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/memory.c (ffffffff8128fa63)
Location: include/asm-generic/tlb.h:314
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff8129de1f)
Location: include/asm-generic/tlb.h:314
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
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
In mm/memory.c (ffffffff8129a59e)
Location: include/asm-generic/tlb.h:313
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812a919f)
Location: include/asm-generic/tlb.h:313
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
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
In mm/memory.c (ffffffff8129f76c)
Location: include/asm-generic/tlb.h:315
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812ae60f)
Location: include/asm-generic/tlb.h:315
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
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
In mm/memory.c (ffffffff812e0a57)
Location: include/asm-generic/tlb.h:315
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812efdaf)
Location: include/asm-generic/tlb.h:315
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/hugetlb.c (ffffffff813223d6)
Location: include/asm-generic/tlb.h:315
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
In mm/memory.c (ffffffff81341e2b)
Location: include/asm-generic/tlb.h:331
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff813532bd)
Location: include/asm-generic/tlb.h:331
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81354d39)
Location: include/asm-generic/tlb.h:331
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff81375ca6)
Location: include/asm-generic/tlb.h:331
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8138f7fe)
Location: include/asm-generic/tlb.h:331
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff813b9d49)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff813cd57d)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff813cf231)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff813f2f1b)
Location: include/asm-generic/tlb.h:363
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140ff90)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff813eea60)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff81401edd)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81403bd5)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff8142695b)
Location: include/asm-generic/tlb.h:363
Inline: True
```
```
In mm/hugetlb.c (ffffffff8144334c)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8141a533)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff8142e52d)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu_fullmm
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81430140)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff814608b2)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8147d583)
Location: include/asm-generic/tlb.h:363
Inline: True
Inline callers:
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
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102f7234)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (ffff800010304de0)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/madvise.c (ffff80001031da6c)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/madvise.c:tlb_flush_mmu_tlbonly
```
```
In mm/hugetlb.c (ffff800010333df4)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519084)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (c0523034)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/madvise.c (c053742c)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/madvise.c:tlb_flush_mmu_tlbonly
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
In mm/memory.c (c0000000003bef1c)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (c0000000003d1c84)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
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
In mm/memory.c (ffffffe0002077fa)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (ffffffe000210fb8)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
```
```
In mm/madvise.c (ffffffe000220f56)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffe00022ff74)
Location: include/asm-generic/tlb.h:302
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
In mm/memory.c (ffffffff81257c55)
Location: include/asm-generic/tlb.h:302
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8126621d)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/memory.c (ffffffff8124a504)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff8125863d)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/memory.c (ffffffff812559f5)
Location: include/asm-generic/tlb.h:302
Inline: True
```
```
In mm/mmu_gather.c (ffffffff81263fbd)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
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
In mm/memory.c (ffffffff8126546f)
Location: include/asm-generic/tlb.h:302
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8127397d)
Location: include/asm-generic/tlb.h:302
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_gather_mmu
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
```
</details>
</li>
</ul>

## Differences
