# Function: <code>pte_mkwrite</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8102298f)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
```
```
In mm/memory.c (ffffffff811c00a9)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
```
```
In mm/mprotect.c (ffffffff811c88d1)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff811dafd1)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
```
```
In mm/migrate.c (ffffffff811f0e9c)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812079e1)
Location: arch/x86/include/asm/pgtable.h:228
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff81021cbf)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
```
```
In mm/memory.c (ffffffff811dbbfd)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mprotect.c (ffffffff811e4b8f)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff811fc16e)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff8121012a)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812163ac)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff8122d2e8)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu.c (ffffffff8102240f)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
```
```
In mm/memory.c (ffffffff811eb456)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mprotect.c (ffffffff811f4bb8)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff8120cc3a)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff81222252)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81228960)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff8123f80a)
Location: arch/x86/include/asm/pgtable.h:242
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff810243df)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
```
```
In mm/shmem.c (ffffffff811dceb0)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In mm/memory.c (ffffffff811f5e74)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mprotect.c (ffffffff811ffa77)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff8121857b)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff8122e09c)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81231fd8)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff8124b3cc)
Location: arch/x86/include/asm/pgtable.h:299
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81024f7f)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
```
```
In mm/shmem.c (ffffffff811eedcd)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8120d8fa)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mprotect.c (ffffffff812181ac)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff8123340f)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff81249e02)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81252d59)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff8126b683)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/xen/mmu_pv.c (ffffffff81025c9f)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
```
```
In mm/shmem.c (ffffffff8120f912)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8122e4f6)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mprotect.c (ffffffff812392e4)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812563d2)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff8126d506)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd
```
```
In mm/userfaultfd.c (ffffffff8128ff33)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In arch/x86/xen/mmu_pv.c (ffffffff8102584f)
Location: arch/x86/include/asm/pgtable.h:326
Inline: True
```
```
In mm/shmem.c (ffffffff812226df)
Location: arch/x86/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8124235a)
Location: arch/x86/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:alloc_set_pte
```
```
In mm/mprotect.c (ffffffff8124d880)
Location: arch/x86/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff8126a8e1)
Location: arch/x86/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff81281bf6)
Location: arch/x86/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81288a03)
Location: arch/x86/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812a4e32)
Location: arch/x86/include/asm/pgtable.h:326
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In arch/x86/xen/mmu_pv.c (ffffffff81027580)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
```
```
In mm/shmem.c (ffffffff81231ce8)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81253503)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
```
```
In mm/mprotect.c (ffffffff8125f885)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81285a67)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff8129dea7)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812a3649)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812c040d)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In arch/x86/xen/mmu_pv.c (ffffffff81027b60)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
```
```
In mm/shmem.c (ffffffff8123fda8)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81261a63)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
```
```
In mm/mprotect.c (ffffffff8126e095)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff81295641)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812ad757)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812b4b49)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812d235d)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In arch/x86/xen/mmu_pv.c (ffffffff81029aa0)
Location: arch/x86/include/asm/pgtable.h:365
Inline: True
```
```
In mm/shmem.c (ffffffff8126e5c7)
Location: arch/x86/include/asm/pgtable.h:365
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8128e455)
Location: arch/x86/include/asm/pgtable.h:365
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
```
```
In mm/mprotect.c (ffffffff8129e6a3)
Location: arch/x86/include/asm/pgtable.h:365
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812c8d53)
Location: arch/x86/include/asm/pgtable.h:365
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812e2b01)
Location: arch/x86/include/asm/pgtable.h:365
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ea0ef)
Location: arch/x86/include/asm/pgtable.h:365
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:365
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8102a480)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
```
```
In mm/shmem.c (ffffffff81278fc5)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8129c586)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
```
```
In mm/mprotect.c (ffffffff812a9a63)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812d48d5)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812edfcd)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f52c5)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8102b120)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
```
```
In mm/shmem.c (ffffffff8127df75)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff812a19de)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
```
```
In mm/mprotect.c (ffffffff812aeeee)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff812db697)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812f4158)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fb80e)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:364
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff8102fa30)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readwrite
```
```
In mm/memory.c (ffffffff812e29ae)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
```
```
In mm/mprotect.c (ffffffff812f06de)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff813228b4)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff8133eb9d)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81345648)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:335
Inline: True
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
In arch/x86/xen/mmu_pv.c (ffffffff81034de6)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:make_lowmem_page_readwrite
```
```
In mm/memory.c (ffffffff81343373)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff81353d3b)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8138faee)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff813b7e59)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
```
```
In mm/huge_memory.c (ffffffff813bb623)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff813e4436)
Location: arch/x86/include/asm/pgtable.h:338
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff83e6f584)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
```
```
In mm/memory.c (ffffffff813bb3a0)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (ffffffff813ce512)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff814107ed)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff81439b30)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143dbce)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff8146be6f)
Location: arch/x86/include/asm/pgtable.h:355
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
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
In arch/x86/xen/mmu_pv.c (ffffffff83690484)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - arch/x86/xen/mmu_pv.c:xen_release_pmd_init
```
```
In mm/memory.c (ffffffff813efd03)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/mprotect.c (0)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
```
```
In mm/hugetlb.c (ffffffff81443b31)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
```
```
In mm/migrate.c (ffffffff81467f71)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/migrate_device.c (ffffffff8146e856)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:356
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
pte_t pte_mkwrite(pte_t pte, struct vm_area_struct *vma);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pgtable.c (ffffffff810d3be0)
Location: arch/x86/mm/pgtable.c:888
Inline: False
Direct callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
  - mm/mprotect.c:change_pte_range
  - mm/migrate.c:remove_migration_pte
  - mm/migrate_device.c:migrate_vma_insert_page
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
**Symbols:**

```
ffffffff810d3be0-ffffffff810d3c2b: pte_mkwrite (STB_GLOBAL)
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
In mm/shmem.c (ffff8000102d3124)
Location: arch/arm64/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffff8000102f8ec0)
Location: arch/arm64/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/mprotect.c (ffff800010305584)
Location: arch/arm64/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffff800010334378)
Location: arch/arm64/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:make_huge_pte
```
```
In mm/migrate.c (0)
Location: arch/arm64/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffff800010357770)
Location: arch/arm64/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:change_huge_pmd
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (ffff800010378064)
Location: arch/arm64/include/asm/pgtable.h:145
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In mm/shmem.c (c04fb06c)
Location: arch/arm/include/asm/pgtable.h:286
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (c051b374)
Location: arch/arm/include/asm/pgtable.h:286
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/mprotect.c (c05233b4)
Location: arch/arm/include/asm/pgtable.h:286
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/migrate.c (c05517c8)
Location: arch/arm/include/asm/pgtable.h:286
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/userfaultfd.c (c0563878)
Location: arch/arm/include/asm/pgtable.h:286
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In mm/shmem.c (c000000000391b4c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:655
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (c0000000003bf6c0)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:655
Inline: True
Inline callers:
  - mm/memory.c:do_numa_page
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:do_wp_page
  - mm/memory.c:finish_mkwrite_fault
  - mm/memory.c:wp_page_copy
  - mm/memory.c:insert_pfn
  - mm/memory.c:insert_pfn
```
```
In mm/mprotect.c (c0000000003d2224)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:655
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (c00000000040d18c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:655
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (c00000000043162c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:655
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (c00000000044456c)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:655
Inline: True
Inline callers:
  - mm/huge_memory.c:remove_migration_pmd
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:do_huge_pmd_numa_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:vmf_insert_pfn_pmd
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/userfaultfd.c (c00000000046a824)
Location: arch/powerpc/include/asm/book3s/64/pgtable.h:655
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In mm/shmem.c (ffffffe0001ee2f4)
Location: arch/riscv/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffe000208f8c)
Location: arch/riscv/include/asm/pgtable.h:254
Inline: True
Inline callers:
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
  - mm/memory.c:insert_pfn
```
```
In mm/mprotect.c (ffffffe000211224)
Location: arch/riscv/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffe00022f5d2)
Location: arch/riscv/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffe00023e34e)
Location: arch/riscv/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/userfaultfd.c (ffffffe00024fc30)
Location: arch/riscv/include/asm/pgtable.h:254
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In arch/x86/xen/mmu_pv.c (ffffffff81027cc0)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
```
```
In mm/shmem.c (ffffffff812383f8)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8125a0b3)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
```
```
In mm/mprotect.c (ffffffff812666e5)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8128dc21)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812a5d37)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ad129)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812ca93d)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In mm/shmem.c (ffffffff8122b433)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff812492aa)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
```
```
In mm/mprotect.c (ffffffff81258de2)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
  - mm/mprotect.c:change_protection_range
```
```
In mm/hugetlb.c (ffffffff8127f9a2)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812977f1)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8129e134)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812bb8ca)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In arch/x86/xen/mmu_pv.c (ffffffff81027b20)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
```
```
In mm/shmem.c (ffffffff81236198)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81257e53)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
```
```
In mm/mprotect.c (ffffffff81264485)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8128ba31)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812a3b47)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812aaf39)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812c874d)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
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
In arch/x86/xen/mmu_pv.c (ffffffff81028760)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
```
```
In mm/shmem.c (ffffffff81246478)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8126783f)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/memory.c:alloc_set_pte
  - mm/memory.c:do_anonymous_page
```
```
In mm/mprotect.c (ffffffff81273e45)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
  - mm/mprotect.c:change_pte_range
```
```
In mm/hugetlb.c (ffffffff8129b827)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/migrate.c (ffffffff812b4357)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812bb289)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff812d9406)
Location: arch/x86/include/asm/pgtable.h:343
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
