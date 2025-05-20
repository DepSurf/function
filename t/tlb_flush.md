# Function: <code>tlb_flush</code>

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
Location: arch/x86/include/asm/tlb.h:13
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8124cf17)
Location: arch/x86/include/asm/tlb.h:13
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
Location: arch/x86/include/asm/tlb.h:14
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8125f200)
Location: arch/x86/include/asm/tlb.h:14
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
Location: arch/x86/include/asm/tlb.h:14
Inline: True
```
```
In mm/mmu_gather.c (ffffffff8126da10)
Location: arch/x86/include/asm/tlb.h:14
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
Location: arch/x86/include/asm/tlb.h:14
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff8129dedb)
Location: arch/x86/include/asm/tlb.h:14
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
Location: arch/x86/include/asm/tlb.h:14
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812a925b)
Location: arch/x86/include/asm/tlb.h:14
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
Location: arch/x86/include/asm/tlb.h:13
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812ae6cb)
Location: arch/x86/include/asm/tlb.h:13
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
Location: arch/x86/include/asm/tlb.h:13
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff812efe6b)
Location: arch/x86/include/asm/tlb.h:13
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/hugetlb.c (ffffffff8132235f)
Location: arch/x86/include/asm/tlb.h:13
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
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff81353359)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81354cd6)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff81375c34)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8138f797)
Location: arch/x86/include/asm/tlb.h:10
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
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff813cd619)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff813cf1d2)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff813f2ec2)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140ff2e)
Location: arch/x86/include/asm/tlb.h:10
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
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff81401f79)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff81403b6f)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff81426902)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
```
```
In mm/hugetlb.c (ffffffff814432ea)
Location: arch/x86/include/asm/tlb.h:10
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
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff8142e5c9)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
  - mm/mmu_gather.c:tlb_remove_table
  - mm/mmu_gather.c:tlb_remove_table
```
```
In mm/mprotect.c (ffffffff814300ef)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/madvise.c (ffffffff81460858)
Location: arch/x86/include/asm/tlb.h:10
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffff8147d536)
Location: arch/x86/include/asm/tlb.h:10
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
In mm/memory.c (ffff8000102f6e40)
Location: arch/arm64/include/asm/tlb.h:24
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (ffff800010304830)
Location: arch/arm64/include/asm/tlb.h:24
Inline: True
```
```
In mm/madvise.c (ffff80001031d954)
Location: arch/arm64/include/asm/tlb.h:24
Inline: True
Inline callers:
  - mm/madvise.c:tlb_flush_mmu_tlbonly
```
```
In mm/hugetlb.c (ffff800010333dac)
Location: arch/arm64/include/asm/tlb.h:24
Inline: True
Inline callers:
  - mm/hugetlb.c:__unmap_hugepage_range
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void tlb_flush(struct mmu_gather *tlb);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0519370)
Location: include/asm-generic/tlb.h:361
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
Direct callers:
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (c0523054)
Location: include/asm-generic/tlb.h:361
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/madvise.c (c05373d0)
Location: include/asm-generic/tlb.h:361
Inline: True
Inline callers:
  - mm/madvise.c:tlb_flush_mmu_tlbonly
```
**Symbols:**

```
c051654c-c0516600: tlb_flush (STB_LOCAL)
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
In mm/memory.c (c0000000003beefc)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:106
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (c0000000003d1a30)
Location: arch/powerpc/include/asm/book3s/64/tlbflush.h:106
Inline: True
Inline callers:
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
In mm/memory.c (ffffffe0002077e2)
Location: arch/riscv/include/asm/tlb.h:16
Inline: True
Inline callers:
  - mm/memory.c:unmap_page_range
  - mm/memory.c:unmap_page_range
```
```
In mm/mmu_gather.c (ffffffe000210fd6)
Location: arch/riscv/include/asm/tlb.h:16
Inline: True
Inline callers:
  - mm/mmu_gather.c:tlb_finish_mmu
```
```
In mm/madvise.c (ffffffe000220f40)
Location: arch/riscv/include/asm/tlb.h:16
Inline: True
Inline callers:
  - mm/madvise.c:madvise_free_single_vma
  - mm/madvise.c:madvise_pageout
  - mm/madvise.c:madvise_cold
```
```
In mm/hugetlb.c (ffffffe00022ff5e)
Location: arch/riscv/include/asm/tlb.h:16
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
In mm/memory.c (ffffffff81257bec)
Location: arch/x86/include/asm/tlb.h:14
Inline: True
```
```
In mm/mmu_gather.c (ffffffff81266060)
Location: arch/x86/include/asm/tlb.h:14
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
Location: arch/x86/include/asm/tlb.h:14
Inline: True
Inline callers:
  - mm/memory.c:zap_pte_range
```
```
In mm/mmu_gather.c (ffffffff81258480)
Location: arch/x86/include/asm/tlb.h:14
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
Location: arch/x86/include/asm/tlb.h:14
Inline: True
```
```
In mm/mmu_gather.c (ffffffff81263e00)
Location: arch/x86/include/asm/tlb.h:14
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
Location: arch/x86/include/asm/tlb.h:14
Inline: True
```
```
In mm/mmu_gather.c (ffffffff812737c0)
Location: arch/x86/include/asm/tlb.h:14
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
<b>Arch</b>
<ul>
</ul>
