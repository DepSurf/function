# Function: <code>tlb_get_unmap_shift</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8123f7df)
Location: include/asm-generic/tlb.h:215
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8124cf17)
Location: include/asm-generic/tlb.h:215
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
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
In mm/memory.c (ffffffff812510dd)
Location: include/asm-generic/tlb.h:439
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8125f200)
Location: include/asm-generic/tlb.h:439
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8125f59c)
Location: include/asm-generic/tlb.h:447
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8126da10)
Location: include/asm-generic/tlb.h:447
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8128f9f7)
Location: include/asm-generic/tlb.h:464
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff8129dedb)
Location: include/asm-generic/tlb.h:464
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/memory.c (ffffffff8129a53a)
Location: include/asm-generic/tlb.h:463
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812a925b)
Location: include/asm-generic/tlb.h:463
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/memory.c (ffffffff8129f708)
Location: include/asm-generic/tlb.h:465
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812ae6cb)
Location: include/asm-generic/tlb.h:465
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
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
In mm/memory.c (ffffffff812e09f3)
Location: include/asm-generic/tlb.h:465
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812efe6b)
Location: include/asm-generic/tlb.h:465
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/hugetlb.c (ffffffff8132235f)
Location: include/asm-generic/tlb.h:465
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
In mm/memory.c (ffffffff81341dd0)
Location: include/asm-generic/tlb.h:465
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff81353359)
Location: include/asm-generic/tlb.h:465
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81354cd6)
Location: include/asm-generic/tlb.h:465
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff81375c34)
Location: include/asm-generic/tlb.h:465
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8138f797)
Location: include/asm-generic/tlb.h:465
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
In mm/memory.c (ffffffff813b9cf2)
Location: include/asm-generic/tlb.h:497
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff813cd619)
Location: include/asm-generic/tlb.h:497
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff813cf1d2)
Location: include/asm-generic/tlb.h:497
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff813f2ec2)
Location: include/asm-generic/tlb.h:497
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140ff2e)
Location: include/asm-generic/tlb.h:497
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
In mm/memory.c (ffffffff813eea09)
Location: include/asm-generic/tlb.h:497
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff81401f79)
Location: include/asm-generic/tlb.h:497
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81403b6f)
Location: include/asm-generic/tlb.h:497
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff81426902)
Location: include/asm-generic/tlb.h:497
Inline: True
```
```
In mm/hugetlb.c (ffffffff814432ea)
Location: include/asm-generic/tlb.h:497
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
In mm/memory.c (ffffffff8141a4e9)
Location: include/asm-generic/tlb.h:507
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff8142e5c9)
Location: include/asm-generic/tlb.h:507
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff814300ef)
Location: include/asm-generic/tlb.h:507
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff81460858)
Location: include/asm-generic/tlb.h:507
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8147d536)
Location: include/asm-generic/tlb.h:507
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
In mm/memory.c (ffff8000102f6e48)
Location: include/asm-generic/tlb.h:447
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (ffff800010304848)
Location: include/asm-generic/tlb.h:447
Inline: True
```
```
In mm/madvise.c (ffff80001031d96c)
Location: include/asm-generic/tlb.h:447
Inline: True
Inline callers:
  - mm/madvise.c:tlb_flush_mmu_tlbonly
```
```
In mm/hugetlb.c (ffff800010333db8)
Location: include/asm-generic/tlb.h:447
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81257bec)
Location: include/asm-generic/tlb.h:447
Inline: True
```
```
In mm/mmu_gather.c (ffffffff81266060)
Location: include/asm-generic/tlb.h:447
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8124a49f)
Location: include/asm-generic/tlb.h:447
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff81258480)
Location: include/asm-generic/tlb.h:447
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8125598c)
Location: include/asm-generic/tlb.h:447
Inline: True
```
```
In mm/mmu_gather.c (ffffffff81263e00)
Location: include/asm-generic/tlb.h:447
Inline: True
Inline callers:
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
In mm/memory.c (ffffffff8126540a)
Location: include/asm-generic/tlb.h:447
Inline: True
```
```
In mm/mmu_gather.c (ffffffff812737c0)
Location: include/asm-generic/tlb.h:447
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_flush_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_table_flush
```
</details>
</li>
</ul>

## Differences
