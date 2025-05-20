# Function: <code>huge_page_size</code>

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
In arch/x86/mm/hugetlbpage.c (ffffffff81072d9e)
Location: include/linux/hugetlb.h:381
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff811c5a65)
Location: include/linux/hugetlb.h:381
Inline: True
Inline callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
```
```
In mm/rmap.c (0)
Location: include/linux/hugetlb.h:381
Inline: True
```
```
In mm/pagewalk.c (0)
Location: include/linux/hugetlb.h:381
Inline: True
```
```
In mm/hugetlb.c (ffffffff81f8bb61)
Location: include/linux/hugetlb.h:381
Inline: True
Inline callers:
  - mm/hugetlb.c:alloc_bootmem_huge_page
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:381
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:381
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff81f8d922)
Location: include/linux/hugetlb.h:381
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:381
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff812f3c46)
Location: include/linux/hugetlb.h:381
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
```
```
In ipc/shm.c (ffffffff8132a267)
Location: include/linux/hugetlb.h:381
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In arch/x86/mm/hugetlbpage.c (ffffffff8107363b)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff811e1876)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
```
```
In mm/rmap.c (0)
Location: include/linux/hugetlb.h:377
Inline: True
```
```
In mm/pagewalk.c (ffffffff811ed30b)
Location: include/linux/hugetlb.h:377
Inline: True
```
```
In mm/hugetlb.c (ffffffff811fe21f)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:alloc_bootmem_huge_page
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:377
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:377
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff81fb7e12)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In fs/proc/task_mmu.c (ffffffff812a4a95)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff813277b1)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff8135eefb)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In arch/x86/mm/hugetlbpage.c (ffffffff810771c5)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff811f1866)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:377
Inline: True
```
```
In mm/pagewalk.c (ffffffff811f76fb)
Location: include/linux/hugetlb.h:377
Inline: True
```
```
In mm/rmap.c (0)
Location: include/linux/hugetlb.h:377
Inline: True
```
```
In mm/hugetlb.c (ffffffff8120ecef)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:dequeue_hwpoisoned_huge_page
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:dissolve_free_huge_pages
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:alloc_bootmem_huge_page
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:377
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:377
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff81ff47d0)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In fs/proc/task_mmu.c (ffffffff812ba405)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff8133d511)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff813756fb)
Location: include/linux/hugetlb.h:377
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In arch/x86/mm/hugetlbpage.c (ffffffff810759db)
Location: include/linux/hugetlb.h:399
Inline: True
Inline callers:
  - arch/x86/mm/hugetlbpage.c:hugetlb_get_unmapped_area
```
```
In mm/mmap.c (ffffffff811fc575)
Location: include/linux/hugetlb.h:399
Inline: True
Inline callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:399
Inline: True
```
```
In mm/pagewalk.c (ffffffff81202574)
Location: include/linux/hugetlb.h:399
Inline: True
```
```
In mm/hugetlb.c (ffffffff8121a58f)
Location: include/linux/hugetlb.h:399
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:alloc_bootmem_huge_page
  - mm/hugetlb.c:alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:399
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:399
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff820d6fc0)
Location: include/linux/hugetlb.h:399
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/userfaultfd.c (ffffffff8124b79e)
Location: include/linux/hugetlb.h:399
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:399
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81352548)
Location: include/linux/hugetlb.h:399
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff8138929f)
Location: include/linux/hugetlb.h:399
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff81214ab5)
Location: include/linux/hugetlb.h:393
Inline: True
Inline callers:
  - mm/mmap.c:SyS_mmap_pgoff
  - mm/mmap.c:SyS_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:393
Inline: True
```
```
In mm/pagewalk.c (ffffffff8121b1e3)
Location: include/linux/hugetlb.h:393
Inline: True
```
```
In mm/hugetlb.c (ffffffff812356ff)
Location: include/linux/hugetlb.h:393
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:393
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:393
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff826dfc2c)
Location: include/linux/hugetlb.h:393
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/userfaultfd.c (ffffffff8126bac0)
Location: include/linux/hugetlb.h:393
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:393
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff81376dd8)
Location: include/linux/hugetlb.h:393
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff813adfef)
Location: include/linux/hugetlb.h:393
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff81235912)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:406
Inline: True
```
```
In mm/pagewalk.c (ffffffff8123d2c4)
Location: include/linux/hugetlb.h:406
Inline: True
```
```
In mm/hugetlb.c (ffffffff8125875a)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:406
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:406
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff8270a13a)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/memory-failure.c (ffffffff81289aa7)
Location: include/linux/hugetlb.h:406
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812905cc)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:406
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813a5591)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff813de4a2)
Location: include/linux/hugetlb.h:406
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff81249112)
Location: include/linux/hugetlb.h:417
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:417
Inline: True
```
```
In mm/pagewalk.c (ffffffff812518df)
Location: include/linux/hugetlb.h:417
Inline: True
```
```
In mm/hugetlb.c (ffffffff8126ce2c)
Location: include/linux/hugetlb.h:417
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:417
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:417
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff828c131e)
Location: include/linux/hugetlb.h:417
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/memory-failure.c (ffffffff8129e90a)
Location: include/linux/hugetlb.h:417
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812a55a0)
Location: include/linux/hugetlb.h:417
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:417
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813be401)
Location: include/linux/hugetlb.h:417
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff813f8b5c)
Location: include/linux/hugetlb.h:417
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff8125b3ff)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/pagewalk.c (ffffffff81263ba6)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb.c (ffffffff81288274)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff828da6b1)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/memory-failure.c (ffffffff812b9dff)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/userfaultfd.c (ffffffff812c09e3)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813e88ca)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff814250b3)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff81269adf)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/pagewalk.c (ffffffff812723f2)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb.c (ffffffff81297e74)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff828e2b40)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/memory-failure.c (ffffffff812cc30c)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/userfaultfd.c (ffffffff812d2afb)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8140296a)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff8143ee03)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff8129a30f)
Location: include/linux/hugetlb.h:554
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (ffffffff812a1f3a)
Location: include/linux/hugetlb.h:554
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812a23a1)
Location: include/linux/hugetlb.h:554
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_hugetlb_range
  - mm/pagewalk.c:walk_hugetlb_range
```
```
In mm/hugetlb.c (ffffffff812cb546)
Location: include/linux/hugetlb.h:554
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:554
Inline: True
```
```
In mm/migrate.c (ffffffff812e6a15)
Location: include/linux/hugetlb.h:554
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/hugetlb_cgroup.c (ffffffff82cffde9)
Location: include/linux/hugetlb.h:554
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init
```
```
In mm/memory-failure.c (ffffffff81301443)
Location: include/linux/hugetlb.h:554
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:554
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813b7bb3)
Location: include/linux/hugetlb.h:554
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff8145041f)
Location: include/linux/hugetlb.h:554
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff8148fb53)
Location: include/linux/hugetlb.h:554
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff812a551f)
Location: include/linux/hugetlb.h:552
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (ffffffff812ad822)
Location: include/linux/hugetlb.h:552
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812adce1)
Location: include/linux/hugetlb.h:552
Inline: True
Inline callers:
  - mm/pagewalk.c:walk_hugetlb_range
  - mm/pagewalk.c:walk_hugetlb_range
```
```
In mm/hugetlb.c (ffffffff812d7166)
Location: include/linux/hugetlb.h:552
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:552
Inline: True
```
```
In mm/migrate.c (ffffffff812f1d6f)
Location: include/linux/hugetlb.h:552
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/hugetlb_cgroup.c (ffffffff82fec7ae)
Location: include/linux/hugetlb.h:552
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init
```
```
In mm/memory-failure.c (ffffffff8130d4ef)
Location: include/linux/hugetlb.h:552
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:552
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813c9640)
Location: include/linux/hugetlb.h:552
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff8146c92f)
Location: include/linux/hugetlb.h:552
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_punch_hole
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff814ad260)
Location: include/linux/hugetlb.h:552
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff812aacbb)
Location: include/linux/hugetlb.h:665
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (ffffffff812b2c11)
Location: include/linux/hugetlb.h:665
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812b3ca7)
Location: include/linux/hugetlb.h:665
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/hugetlb.c (ffffffff812de845)
Location: include/linux/hugetlb.h:665
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_report_meminfo
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:665
Inline: True
```
```
In mm/migrate.c (ffffffff812f809f)
Location: include/linux/hugetlb.h:665
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/hugetlb_cgroup.c (ffffffff831f6fcc)
Location: include/linux/hugetlb.h:665
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init
```
```
In mm/memory-failure.c (ffffffff813145f8)
Location: include/linux/hugetlb.h:665
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:665
Inline: True
```
```
In fs/proc/task_mmu.c (ffffffff813d0745)
Location: include/linux/hugetlb.h:665
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff831fb40a)
Location: include/linux/hugetlb.h:665
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff814b30e2)
Location: include/linux/hugetlb.h:665
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff812ec348)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (ffffffff812f47ce)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff812f585f)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/hugetlb.c (ffffffff81325d37)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_report_meminfo
  - mm/hugetlb.c:hugetlb_report_meminfo
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81328ba5)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff81342710)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/hugetlb_cgroup.c (ffffffff81cc2cab)
Location: include/linux/hugetlb.h:688
Inline: True
Direct callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init
```
```
In mm/memory-failure.c (ffffffff81360780)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure_hugetlb
```
```
In mm/hmm.c (ffffffff8136a5bf)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff81421b41)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff814c9307)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
Direct callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
```
```
In ipc/shm.c (ffffffff8150b840)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
```
```
In drivers/dma-buf/udmabuf.c (ffffffff818ab5aa)
Location: include/linux/hugetlb.h:688
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81cbf259-ffffffff81cbf285: huge_page_size.isra.0 (STB_LOCAL)
ffffffff81cc2cab-ffffffff81cc2cd7: huge_page_size.isra.0 (STB_LOCAL)
ffffffff81ccf494-ffffffff81ccf4c0: huge_page_size.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff8134f244)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/mremap.c (ffffffff81357613)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/page_vma_mapped.c (ffffffff813585df)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff81359723)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/madvise.c (ffffffff8137547b)
Location: include/linux/hugetlb.h:718
Inline: True
```
```
In mm/hugetlb.c (ffffffff81394aa2)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:hugetlb_unshare_all_pmds
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_show_meminfo
  - mm/hugetlb.c:hugetlb_report_meminfo
  - mm/hugetlb.c:hugetlb_report_meminfo
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
Direct callers:
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff81397de5)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff813b4c40)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/hugetlb_cgroup.c (ffffffff81e75222)
Location: include/linux/hugetlb.h:718
Inline: True
Direct callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init
```
```
In mm/memory-failure.c (ffffffff813dc151)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - mm/memory-failure.c:try_memory_failure_hugetlb
```
```
In mm/hmm.c (ffffffff813e8182)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff8149af52)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff81554d0e)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
Direct callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
```
```
In ipc/shm.c (ffffffff8159daa9)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
```
```
In drivers/dma-buf/udmabuf.c (ffffffff819f5fb4)
Location: include/linux/hugetlb.h:718
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81e715df-ffffffff81e71617: huge_page_size.isra.0 (STB_LOCAL)
ffffffff81e75222-ffffffff81e7525a: huge_page_size.isra.0 (STB_LOCAL)
ffffffff815547c0-ffffffff815547e0: huge_page_size.isra.0 (STB_LOCAL)
ffffffff81e8251a-ffffffff81e8254e: huge_page_size.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int huge_page_size(const struct hstate *h);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff813c8832)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/mremap.c (ffffffff813d1b4f)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/page_vma_mapped.c (ffffffff813d2d3f)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff813d3fc5)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/madvise.c (ffffffff813f33b3)
Location: include/linux/hugetlb.h:757
Inline: True
```
```
In mm/hugetlb.c (ffffffff8140dca4)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:huge_pmd_share
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_show_meminfo_node
  - mm/hugetlb.c:hugetlb_report_meminfo
  - mm/hugetlb.c:hugetlb_report_meminfo
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_free_huge_page
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
Direct callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
```
```
In mm/mempolicy.c (ffffffff81417a67)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (ffffffff81433ddc)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/hugetlb_cgroup.c (ffffffff83ec7215)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init
```
```
In mm/hmm.c (ffffffff8147008c)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff8152f9a7)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff83ecdf29)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
```
In ipc/shm.c (ffffffff8164706d)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
```
```
In drivers/dma-buf/udmabuf.c (ffffffff81b7357e)
Location: include/linux/hugetlb.h:757
Inline: True
Inline callers:
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81405280-ffffffff814052a1: huge_page_size (STB_LOCAL)
ffffffff82065fc5-ffffffff82065ffd: huge_page_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
long unsigned int huge_page_size(const struct hstate *h);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mmap.c (ffffffff813fca32)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/mremap.c (ffffffff814066f8)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/page_vma_mapped.c (ffffffff81407ad7)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff814089a8)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/madvise.c (ffffffff81426e09)
Location: include/linux/hugetlb.h:785
Inline: True
```
```
In mm/hugetlb.c (ffffffff8144106a)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_show_meminfo_node
  - mm/hugetlb.c:hugetlb_report_meminfo
  - mm/hugetlb.c:hugetlb_report_meminfo
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_page
  - mm/hugetlb.c:free_hpage_workfn
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
Direct callers:
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_no_page
```
```
In mm/mempolicy.c (ffffffff8144afe9)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff81469687)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/hugetlb_cgroup.c (ffffffff836ec205)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init
```
```
In mm/hmm.c (ffffffff814a485f)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff815681d2)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff836f2fc9)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
```
In ipc/shm.c (ffffffff8167f5b0)
Location: include/linux/hugetlb.h:785
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
```
**Symbols:**

```
ffffffff81438940-ffffffff81438961: huge_page_size (STB_LOCAL)
ffffffff820e5789-ffffffff820e57c1: huge_page_size.cold (STB_LOCAL)
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
In mm/mmap.c (ffffffff81429402)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/mremap.c (ffffffff81432e07)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
  - mm/mremap.c:__do_sys_mremap
```
```
In mm/page_vma_mapped.c (ffffffff814340e9)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (ffffffff814350c8)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - mm/pagewalk.c:__walk_page_range
  - mm/pagewalk.c:__walk_page_range
```
```
In mm/rmap.c (ffffffff8143aa1c)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - mm/rmap.c:try_to_migrate_one
  - mm/rmap.c:try_to_unmap_one
```
```
In mm/madvise.c (ffffffff814600d9)
Location: include/linux/hugetlb.h:806
Inline: True
```
```
In mm/hugetlb.c (ffffffff8147b19a)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:hugetlb_unshare_pmds
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:folio_putback_active_hugetlb
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_follow_page_mask
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_mfill_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_add_to_page_cache
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:hugetlb_wp
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:move_hugetlb_page_tables
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_vm_op_pagesize
  - mm/hugetlb.c:hugetlb_show_meminfo_node
  - mm/hugetlb.c:hugetlb_report_meminfo
  - mm/hugetlb.c:hugetlb_report_meminfo
  - mm/hugetlb.c:default_hugepagesz_setup
  - mm/hugetlb.c:hugepagesz_setup
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:demote_size_store
  - mm/hugetlb.c:demote_free_hugetlb_folio
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:isolate_or_dissolve_huge_page
  - mm/hugetlb.c:dissolve_free_huge_page
  - mm/hugetlb.c:free_huge_folio
  - mm/hugetlb.c:free_hpage_workfn
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (ffffffff814849e9)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_folios_hugetlb
```
```
In mm/migrate.c (ffffffff814985b7)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
  - mm/migrate.c:remove_migration_pte
```
```
In mm/hugetlb_cgroup.c (ffffffff8391f205)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_legacy_init
  - mm/hugetlb_cgroup.c:__hugetlb_cgroup_file_dfl_init
```
```
In mm/hmm.c (ffffffff814d588f)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (ffffffff8159d499)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - fs/proc/task_mmu.c:pagemap_scan_hugetlb_entry
  - fs/proc/task_mmu.c:smaps_hugetlb_range
  - fs/proc/task_mmu.c:smaps_hugetlb_range
```
```
In fs/hugetlbfs/inode.c (ffffffff83926199)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:mount_one_hugetlbfs
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_zero_partial_page
  - fs/hugetlbfs/inode.c:hugetlb_vma_maps_page
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
  - fs/hugetlbfs/inode.c:generic_hugetlb_get_unmapped_area
```
```
In ipc/shm.c (ffffffff816bb9a0)
Location: include/linux/hugetlb.h:806
Inline: True
Inline callers:
  - ipc/shm.c:newseg
  - ipc/shm.c:newseg
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
In arch/arm64/mm/hugetlbpage.c (ffff8000100b1184)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - arch/arm64/mm/hugetlbpage.c:arch_make_huge_pte
  - arch/arm64/mm/hugetlbpage.c:arch_hugetlb_migration_supported
```
```
In mm/mmap.c (ffff800010300f68)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/pagewalk.c (ffff800010307bc0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb.c (ffff8000103362c4)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffff80001145be34)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/memory-failure.c (ffff80001036f714)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/userfaultfd.c (ffff800010378804)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffff8000104e1130)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area
```
```
In ipc/shm.c (ffff8000105265b4)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (0)
Location: include/linux/hugetlb.h:649
Inline: True
```
```
In ipc/shm.c (0)
Location: include/linux/hugetlb.h:649
Inline: True
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
In arch/powerpc/mm/book3s64/radix_hugetlbpage.c (c00000000009ef44)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - arch/powerpc/mm/book3s64/radix_hugetlbpage.c:radix__hugetlb_get_unmapped_area
```
```
In mm/mmap.c (c0000000003cd28c)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (c0000000003d5c74)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/page_vma_mapped.c:page_vma_mapped_walk
```
```
In mm/pagewalk.c (c0000000003d64c0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb.c (c000000000410b9c)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_mcopy_atomic_pte
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:hugetlb_no_page
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (c000000000411064)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/mempolicy.c:queue_pages_hugetlb
```
```
In mm/migrate.c (c000000000436e40)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/migrate.c:migration_entry_wait_huge
```
```
In mm/hugetlb_cgroup.c (c000000001386910)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/memory-failure.c (c0000000004616f4)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/userfaultfd.c (c00000000046b330)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (c00000000046fac8)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hmm.c:hmm_vma_walk_hugetlb_entry
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/hugetlbfs/inode.c (c00000000061de24)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (c000000000671a0c)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffe00020e496)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/pagewalk.c (ffffffe000212b62)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb.c (ffffffe0002321e4)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffe000019676)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/userfaultfd.c (ffffffe0002501aa)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffe00035528a)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
  - fs/hugetlbfs/inode.c:hugetlb_get_unmapped_area
```
```
In ipc/shm.c (ffffffe00038ae78)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff8126212f)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/pagewalk.c (ffffffff8126aa42)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb.c (ffffffff81290454)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff828cb9f4)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/memory-failure.c (ffffffff812c48ec)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/userfaultfd.c (ffffffff812cb0db)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813faf4a)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff814373e3)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff8125454f)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/pagewalk.c (ffffffff8125cba2)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb.c (ffffffff812820e4)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff828c4119)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/memory-failure.c (ffffffff812b592c)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/userfaultfd.c (ffffffff812bc037)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813eb9ca)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff81427e53)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff8125fecf)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/pagewalk.c (ffffffff812687e2)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb.c (ffffffff8128e264)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff828de774)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/memory-failure.c (ffffffff812c26fc)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/userfaultfd.c (ffffffff812c8eeb)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff813f82ca)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff81433583)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - ipc/shm.c:newseg
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
In mm/mmap.c (ffffffff8126f89f)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/mmap.c:ksys_mmap_pgoff
  - mm/mmap.c:ksys_mmap_pgoff
```
```
In mm/page_vma_mapped.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/pagewalk.c (ffffffff81278172)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb.c (ffffffff8129e004)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb.c:move_hugetlb_state
  - mm/hugetlb.c:putback_active_hugepage
  - mm/hugetlb.c:hugetlb_unreserve_pages
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:hugetlb_change_protection
  - mm/hugetlb.c:follow_hugetlb_page
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:hugetlb_fault
  - mm/hugetlb.c:huge_add_to_page_cache
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:hugetlb_cow
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:__unmap_hugepage_range
  - mm/hugetlb.c:copy_hugetlb_page_range
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_init
  - mm/hugetlb.c:hugetlb_hstate_alloc_pages
  - mm/hugetlb.c:__free_huge_page
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:hugetlb_add_hstate
  - mm/hugetlb.c:__alloc_bootmem_huge_page
  - mm/hugetlb.c:__alloc_bootmem_huge_page
```
```
In mm/mempolicy.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/migrate.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In mm/hugetlb_cgroup.c (ffffffff828e3b8b)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/hugetlb_cgroup.c:hugetlb_cgroup_file_init
```
```
In mm/memory-failure.c (ffffffff812d318c)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/memory-failure.c:memory_failure
```
```
In mm/userfaultfd.c (ffffffff812d9be7)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - mm/userfaultfd.c:mcopy_atomic
```
```
In mm/hmm.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/proc/task_mmu.c (0)
Location: include/linux/hugetlb.h:405
Inline: True
```
```
In fs/hugetlbfs/inode.c (ffffffff8140e01a)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - fs/hugetlbfs/inode.c:hugetlbfs_fill_super
  - fs/hugetlbfs/inode.c:hugetlbfs_statfs
  - fs/hugetlbfs/inode.c:hugetlbfs_show_options
  - fs/hugetlbfs/inode.c:hugetlbfs_fallocate
  - fs/hugetlbfs/inode.c:hugetlbfs_read_iter
```
```
In ipc/shm.c (ffffffff8144a953)
Location: include/linux/hugetlb.h:405
Inline: True
Inline callers:
  - ipc/shm.c:newseg
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
</ul>
