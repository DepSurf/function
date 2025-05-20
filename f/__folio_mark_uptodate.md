# Function: <code>__folio_mark_uptodate</code>

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
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e6a57)
Location: include/linux/page-flags.h:734
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8131c7b5)
Location: include/linux/page-flags.h:734
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff813439e5)
Location: include/linux/page-flags.h:734
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/hugetlb.c (ffffffff8138df84)
Location: include/linux/page-flags.h:734
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff813a333e)
Location: include/linux/page-flags.h:734
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff813b7e0f)
Location: include/linux/page-flags.h:734
Inline: True
```
```
In mm/huge_memory.c (ffffffff813ba0a7)
Location: include/linux/page-flags.h:734
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c6c51)
Location: include/linux/page-flags.h:734
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff813e3a58)
Location: include/linux/page-flags.h:734
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e45b6)
Location: include/linux/page-flags.h:734
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff814678ad)
Location: include/linux/page-flags.h:734
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/hugetlbfs/inode.c (ffffffff81555eb5)
Location: include/linux/page-flags.h:734
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff81350544)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff81390408)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff813bba6c)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/hugetlb.c (ffffffff8140cc38)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81422fdb)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff81439ae6)
Location: include/linux/page-flags.h:731
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143c1f7)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814490a8)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff8146b435)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146c28c)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff814f7f6d)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/hugetlbfs/inode.c (ffffffff815f75ad)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff81381775)
Location: include/linux/page-flags.h:725
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff813c2d55)
Location: include/linux/page-flags.h:725
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff813f0358)
Location: include/linux/page-flags.h:725
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/hugetlb.c (ffffffff8144005b)
Location: include/linux/page-flags.h:725
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81458032)
Location: include/linux/page-flags.h:725
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff8146e80c)
Location: include/linux/page-flags.h:725
Inline: True
```
```
In mm/huge_memory.c (ffffffff814715cb)
Location: include/linux/page-flags.h:725
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8147e889)
Location: include/linux/page-flags.h:725
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff814a021b)
Location: include/linux/page-flags.h:725
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814a1127)
Location: include/linux/page-flags.h:725
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/dax.c (ffffffff8152f16d)
Location: include/linux/page-flags.h:725
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/hugetlbfs/inode.c (ffffffff8162f6c1)
Location: include/linux/page-flags.h:725
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff813aab07)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff813ed9cd)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8141bb93)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/hugetlb.c (ffffffff81479f69)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff814929c7)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff8149d270)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_insert_page
```
```
In mm/huge_memory.c (ffffffff814a1f85)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814af51c)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff814cf8a2)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff814d08b7)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - mm/userfaultfd.c:mfill_atomic_copy
```
```
In fs/dax.c (ffffffff8156404d)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/hugetlbfs/inode.c (ffffffff81668b9d)
Location: include/linux/page-flags.h:746
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
