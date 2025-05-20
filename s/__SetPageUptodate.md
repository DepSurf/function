# Function: <code>__SetPageUptodate</code>

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
In kernel/events/uprobes.c (ffffffff8118766e)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811bc582)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
```
```
In mm/hugetlb.c (ffffffff811ddcd3)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_fault
```
```
In mm/ksm.c (ffffffff811e6ddc)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff811f573d)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/huge_memory.c:khugepaged
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
```
```
In mm/userfaultfd.c (ffffffff81207989)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff812f4d48)
Location: include/linux/page-flags.h:359
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff81199c50)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811dbbc5)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff811fd43e)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff81205e40)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff81216c04)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8121a6a6)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8122d28d)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/hugetlbfs/inode.c (ffffffff8132880d)
Location: include/linux/page-flags.h:434
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff811a9321)
Location: include/linux/page-flags.h:450
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff811eb438)
Location: include/linux/page-flags.h:450
Inline: True
Inline callers:
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff8120df0d)
Location: include/linux/page-flags.h:450
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff81217e52)
Location: include/linux/page-flags.h:450
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812291a8)
Location: include/linux/page-flags.h:450
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8122eab7)
Location: include/linux/page-flags.h:450
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/userfaultfd.c (ffffffff8123f7b4)
Location: include/linux/page-flags.h:450
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8129c3db)
Location: include/linux/page-flags.h:450
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/hugetlbfs/inode.c (ffffffff8133e551)
Location: include/linux/page-flags.h:450
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff811b089e)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811dcc31)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mcopy_atomic_pte
```
```
In mm/memory.c (ffffffff811f5e4e)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff81217779)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff81223a31)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812355de)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81238790)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8124b366)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812ab4de)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/hugetlbfs/inode.c (ffffffff81353182)
Location: include/linux/page-flags.h:453
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff811c43a5)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff811eeb23)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8120db2a)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff81232429)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff8123f071)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8124a0e3)
Location: include/linux/page-flags.h:454
Inline: True
```
```
In mm/huge_memory.c (ffffffff81253541)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81259be0)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged
```
```
In mm/userfaultfd.c (ffffffff8126b624)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812cee24)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_fault
```
```
In fs/hugetlbfs/inode.c (ffffffff81377cfb)
Location: include/linux/page-flags.h:454
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff811e48b3)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8120f64d)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8122e24c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:handle_pte_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff81255479)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff8126281d)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8126f04e)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In mm/huge_memory.c (ffffffff81277b47)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8127c53c)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff8128feb1)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff812f9586)
Location: include/linux/page-flags.h:461
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813a6671)
Location: include/linux/page-flags.h:461
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff811f570e)
Location: include/linux/page-flags.h:478
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff81222578)
Location: include/linux/page-flags.h:478
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81242334)
Location: include/linux/page-flags.h:478
Inline: True
Inline callers:
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:__handle_mm_fault
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff81269859)
Location: include/linux/page-flags.h:478
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff8127709d)
Location: include/linux/page-flags.h:478
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812836fe)
Location: include/linux/page-flags.h:478
Inline: True
```
```
In mm/huge_memory.c (ffffffff8128c164)
Location: include/linux/page-flags.h:478
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81290be8)
Location: include/linux/page-flags.h:478
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812a4dbe)
Location: include/linux/page-flags.h:478
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8130d764)
Location: include/linux/page-flags.h:478
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813bf451)
Location: include/linux/page-flags.h:478
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff8120d48a)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff81231b7b)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81253ece)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff81284997)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812928fb)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffffffff812a6d8c)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812ab9e5)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812c038c)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8133597c)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813e9da9)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff8121a914)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8123fc3b)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81262425)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff81294537)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812a267e)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812af180)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b8237)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812bd1f4)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812d22dc)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8134957c)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81403e49)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff8124730b)
Location: include/linux/page-flags.h:527
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8126e4a7)
Location: include/linux/page-flags.h:527
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81291eeb)
Location: include/linux/page-flags.h:527
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff812c7927)
Location: include/linux/page-flags.h:527
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812d6d9a)
Location: include/linux/page-flags.h:527
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812e5206)
Location: include/linux/page-flags.h:527
Inline: True
```
```
In mm/huge_memory.c (ffffffff812e9500)
Location: include/linux/page-flags.h:527
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812f2910)
Location: include/linux/page-flags.h:527
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81307fff)
Location: include/linux/page-flags.h:527
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff8138e8d8)
Location: include/linux/page-flags.h:527
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/hugetlbfs/inode.c (ffffffff81451c99)
Location: include/linux/page-flags.h:527
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff81251987)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff81278ea9)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8129c7ab)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff812d3497)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812e292a)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812f05cb)
Location: include/linux/page-flags.h:531
Inline: True
```
```
In mm/huge_memory.c (ffffffff812f49a0)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812fcf36)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81313d9f)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff813a0037)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/hugetlbfs/inode.c (ffffffff8146e157)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff812557b9)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8127de59)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff812a1fc5)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff812da2de)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff812ea0ba)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812f68e2)
Location: include/linux/page-flags.h:531
Inline: True
```
```
In mm/huge_memory.c (ffffffff812faf30)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff81303cab)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff81319f4f)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff813a75d4)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - fs/dax.c:dax_iomap_pte_fault
```
```
In fs/hugetlbfs/inode.c (ffffffff81473599)
Location: include/linux/page-flags.h:531
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff81291469)
Location: include/linux/page-flags.h:551
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff812bfed3)
Location: include/linux/page-flags.h:551
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff812e308e)
Location: include/linux/page-flags.h:551
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_pte_range
```
```
In mm/hugetlb.c (ffffffff813211a1)
Location: include/linux/page-flags.h:551
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81331fdc)
Location: include/linux/page-flags.h:551
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff81340f2e)
Location: include/linux/page-flags.h:551
Inline: True
```
```
In mm/huge_memory.c (ffffffff81344d99)
Location: include/linux/page-flags.h:551
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff8134d9ee)
Location: include/linux/page-flags.h:551
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff8136674c)
Location: include/linux/page-flags.h:551
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff81367049)
Location: include/linux/page-flags.h:551
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff813f4d2c)
Location: include/linux/page-flags.h:551
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/hugetlbfs/inode.c (ffffffff814ca196)
Location: include/linux/page-flags.h:551
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff812e6a57)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8131c7b5)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff813439e5)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/hugetlb.c (ffffffff8138df84)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff813a333e)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff813b7e0f)
Location: include/linux/page-flags.h:751
Inline: True
```
```
In mm/huge_memory.c (ffffffff813ba0a7)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff813c6c51)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff813e3a58)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff813e45b6)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffffffff814678ad)
Location: include/linux/page-flags.h:751
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/hugetlbfs/inode.c (ffffffff81555eb5)
Location: include/linux/page-flags.h:751
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
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff813bba6c)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
  - mm/memory.c:copy_present_pte
```
```
In mm/hugetlb.c (ffffffff8140cc38)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/ksm.c (ffffffff81422fdb)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff81439ae6)
Location: include/linux/page-flags.h:748
Inline: True
```
```
In mm/huge_memory.c (ffffffff8143c1f7)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff814490a8)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff8146b435)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In mm/userfaultfd.c (ffffffff8146c28c)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff814f7f6d)
Location: include/linux/page-flags.h:748
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
```
```
In fs/hugetlbfs/inode.c (ffffffff815f75ad)
Location: include/linux/page-flags.h:748
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
Location: include/linux/page-flags.h:742
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/memory.c (ffffffff813f0358)
Location: include/linux/page-flags.h:742
Inline: True
Inline callers:
  - mm/memory.c:do_cow_fault
```
```
In mm/ksm.c (ffffffff81458032)
Location: include/linux/page-flags.h:742
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate_device.c (ffffffff8146e80c)
Location: include/linux/page-flags.h:742
Inline: True
```
```
In mm/khugepaged.c (ffffffff8147e889)
Location: include/linux/page-flags.h:742
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/secretmem.c (ffffffff814a021b)
Location: include/linux/page-flags.h:742
Inline: True
Inline callers:
  - mm/secretmem.c:secretmem_fault
```
```
In fs/dax.c (ffffffff8152f16d)
Location: include/linux/page-flags.h:742
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
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
Location: include/linux/page-flags.h:763
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In fs/dax.c (ffffffff8156404d)
Location: include/linux/page-flags.h:763
Inline: True
Inline callers:
  - fs/dax.c:dax_fault_cow_page
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
In kernel/events/uprobes.c (ffff8000102a5cd4)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffff8000102d2f8c)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffff8000102f9654)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffff800010332e3c)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffff800010342070)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/huge_memory.c (ffff800010358868)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:__do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffff80001035e654)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffff800010378010)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic_pte
```
```
In fs/dax.c (ffff80001040a1d4)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffff8000104e25f0)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (c04d50a0)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (c04faec8)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (c051b790)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/ksm.c (c0547dd0)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/userfaultfd.c (c0563800)
Location: include/linux/page-flags.h:511
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
In kernel/events/uprobes.c (c000000000358d24)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (c000000000391950)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (c0000000003c33bc)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (c00000000040ed44)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (c00000000041f8d0)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (c00000000043297c)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In mm/huge_memory.c (c00000000044160c)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (c000000000447a1c)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (c00000000046a7a4)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (c0000000005161dc)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In fs/hugetlbfs/inode.c (c00000000061f6ec)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In mm/shmem.c (ffffffe0001ee1ee)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffe000209626)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffe00022f524)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffe000236328)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/userfaultfd.c (ffffffe00024fbea)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffe0002b3b1e)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffe00035606e)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff81212f64)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8123828b)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8125aa75)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff8128cb17)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff8129ac5e)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812a7760)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In mm/huge_memory.c (ffffffff812b0817)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b57d4)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812ca8bc)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff81341b5c)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813fc429)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff81205cd4)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8122b2c6)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8124ce40)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff8127e937)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff8128c81e)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff8129917a)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In mm/huge_memory.c (ffffffff812a1a95)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812a69d9)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812bb843)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff813324e1)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813ecea9)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff81210d04)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8123602b)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff81258815)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff8128a927)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff81298a6e)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812a5570)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In mm/huge_memory.c (ffffffff812ae627)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812b35e4)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812c86cc)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff8133f62c)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813f97a9)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
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
In kernel/events/uprobes.c (ffffffff8121fc1c)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - kernel/events/uprobes.c:uprobe_write_opcode
```
```
In mm/shmem.c (ffffffff8124630b)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/shmem.c:shmem_mfill_atomic_pte
```
```
In mm/memory.c (ffffffff8126822f)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/memory.c:do_fault
  - mm/memory.c:do_anonymous_page
  - mm/memory.c:wp_page_copy
```
```
In mm/hugetlb.c (ffffffff8129a71d)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_cow
```
```
In mm/ksm.c (ffffffff812a884d)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/ksm.c:ksm_might_need_to_copy
```
```
In mm/migrate.c (ffffffff812b4ca0)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In mm/huge_memory.c (ffffffff812be984)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/huge_memory.c:do_huge_pmd_wp_page
  - mm/huge_memory.c:do_huge_pmd_wp_page_fallback
  - mm/huge_memory.c:do_huge_pmd_anonymous_page
```
```
In mm/khugepaged.c (ffffffff812c3a36)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/khugepaged.c:collapse_huge_page
```
```
In mm/userfaultfd.c (ffffffff812d9370)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/dax.c (ffffffff81352ff3)
Location: include/linux/page-flags.h:511
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8140f404)
Location: include/linux/page-flags.h:511
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
</details>
</li>
</ul>

## Differences
