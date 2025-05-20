# Function: <code>pte_mkuffd_wp</code>

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
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
```
```
In mm/mprotect.c (ffffffff8129e6bc)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/migrate.c (0)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812ea12a)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff813081e6)
Location: arch/x86/include/asm/pgtable.h:324
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/mprotect.c (ffffffff812a9a7c)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/migrate.c (ffffffff812edd88)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812f5301)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff81313f88)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In mm/memory.c (0)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
```
```
In mm/mprotect.c (ffffffff812aef07)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/migrate.c (ffffffff812f3f37)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff812fb84b)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff8131a147)
Location: arch/x86/include/asm/pgtable.h:323
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
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
In mm/memory.c (ffffffff812de997)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff812f06f7)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/migrate.c (ffffffff8133e968)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff81345685)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff81366ed1)
Location: arch/x86/include/asm/pgtable.h:294
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
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
In mm/memory.c (ffffffff813432e2)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:wp_page_copy
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff81353d07)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/swapfile.c (ffffffff8137ea90)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81390f77)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff813b1a5f)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff813bb66d)
Location: arch/x86/include/asm/pgtable.h:297
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff813e43ae)
Location: arch/x86/include/asm/pgtable.h:297
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
In mm/memory.c (ffffffff813bb29c)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:wp_page_copy
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff813ce1db)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/swapfile.c (ffffffff813fd443)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff814125c4)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81432506)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff8143dc30)
Location: arch/x86/include/asm/pgtable.h:314
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (ffffffff8146bc52)
Location: arch/x86/include/asm/pgtable.h:314
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
In mm/memory.c (ffffffff813ec942)
Location: arch/x86/include/asm/pgtable.h:320
Inline: True
Inline callers:
  - mm/memory.c:do_set_pte
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff81402a8f)
Location: arch/x86/include/asm/pgtable.h:320
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/swapfile.c (ffffffff81430721)
Location: arch/x86/include/asm/pgtable.h:320
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff81445b97)
Location: arch/x86/include/asm/pgtable.h:320
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff81467c5b)
Location: arch/x86/include/asm/pgtable.h:320
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:320
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
```
```
In mm/userfaultfd.c (0)
Location: arch/x86/include/asm/pgtable.h:320
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
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
In mm/memory.c (ffffffff8141b525)
Location: arch/x86/include/asm/pgtable.h:410
Inline: True
Inline callers:
  - mm/memory.c:set_pte_range
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:do_swap_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
  - mm/memory.c:restore_exclusive_pte
```
```
In mm/mprotect.c (ffffffff8142f0d2)
Location: arch/x86/include/asm/pgtable.h:410
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
```
In mm/swapfile.c (ffffffff814690db)
Location: arch/x86/include/asm/pgtable.h:410
Inline: True
Inline callers:
  - mm/swapfile.c:unuse_pte
```
```
In mm/hugetlb.c (ffffffff8147f59d)
Location: arch/x86/include/asm/pgtable.h:410
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/migrate.c (ffffffff8149792b)
Location: arch/x86/include/asm/pgtable.h:410
Inline: True
Inline callers:
  - mm/migrate.c:remove_migration_pte
```
```
In mm/huge_memory.c (ffffffff814a18ba)
Location: arch/x86/include/asm/pgtable.h:410
Inline: True
Inline callers:
  - mm/huge_memory.c:__split_huge_pmd_locked
  - mm/huge_memory.c:__split_huge_zero_page_pmd
```
```
In mm/userfaultfd.c (ffffffff814d0205)
Location: arch/x86/include/asm/pgtable.h:410
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_install_pte
```
```
In fs/proc/task_mmu.c (ffffffff8159cdd1)
Location: arch/x86/include/asm/pgtable.h:410
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:make_uffd_wp_pte
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
