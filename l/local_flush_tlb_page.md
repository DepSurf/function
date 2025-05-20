# Function: <code>local_flush_tlb_page</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/smp_tlb.c (c0313c30)
Location: arch/arm/include/asm/tlbflush.h:442
Inline: True
Inline callers:
  - arch/arm/kernel/smp_tlb.c:ipi_flush_tlb_page
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/init.c (ffffffe000003d9a)
Location: arch/riscv/include/asm/tlbflush.h:19
Inline: True
Inline callers:
  - arch/riscv/mm/init.c:paging_init
  - arch/riscv/mm/init.c:paging_init
  - arch/riscv/mm/init.c:get_pmd_virt
  - arch/riscv/mm/init.c:get_pte_virt
```
```
In arch/riscv/mm/fault.c (ffffffe0000b9e32)
Location: arch/riscv/include/asm/tlbflush.h:19
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
```
In arch/riscv/mm/tlbflush.c (ffffffe0000ba4a8)
Location: arch/riscv/include/asm/tlbflush.h:19
Inline: True
```
```
In mm/shmem.c (ffffffe0001ee3fc)
Location: arch/riscv/include/asm/tlbflush.h:19
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/gup.c (ffffffe00020492a)
Location: arch/riscv/include/asm/tlbflush.h:19
Inline: True
```
```
In mm/memory.c (ffffffe00020998a)
Location: arch/riscv/include/asm/tlbflush.h:19
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
```
```
In mm/hugetlb.c (ffffffe00022f60a)
Location: arch/riscv/include/asm/tlbflush.h:19
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffe00023e212)
Location: arch/riscv/include/asm/tlbflush.h:19
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/userfaultfd.c (ffffffe000250594)
Location: arch/riscv/include/asm/tlbflush.h:19
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_zeropage
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
